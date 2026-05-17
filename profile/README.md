<p align="center">
  <img src="https://raw.githubusercontent.com/cochranblock/cochranblock/main/assets/cochranblock-logo.svg" alt="CochranBlock" width="320">
</p>

<h3 align="center">Your server bill is too high.</h3>

<p align="center">
  This entire company — <a href="https://cochranblock.org">cochranblock.org</a> — runs as a single 13 MB Rust binary (8.9 MB on ARM) on bare metal.<br>
  <strong>$10/month. No AWS. No Kubernetes. No DevOps team.</strong><br>
  Veteran-owned. SDVOSB certified (SBA VetCert, 2026-05-12 · expires 2029-05-12). It's not the Mech — it's the pilot.
</p>

---

### The Trifecta

1. **You can't outprice free** — every line of code is Unlicense, public domain
2. **You can't out-transparent public domain** — source, bugs, IR&D audit, all public
3. **Expertise is inherent** — the code IS the resume

---

### 33 public repos. 13 crates published. All live.

| Repo | What it does |
|------|-------------|
| **[any-gpu](https://github.com/cochranblock/any-gpu)** | Bare metal tensor engine. AMD, NVIDIA, Intel, Apple. One codebase, zero vendor lock-in. |
| **[approuter](https://github.com/cochranblock/approuter)** | Reverse proxy + Cloudflare tunnel. All products behind one entry point. Zero-config service registration. |
| **[aptnomo](https://github.com/cochranblock/aptnomo)** | Autonomous APT threat hunter. 312 KB. Auto-kills cryptominers. Zero config. |
| **[atsisbroken](https://github.com/cochranblock/atsisbroken)** | Browser-resident AI form-filling. Beats the ATS black box. Local-first, free forever. |
| **[battle-bros](https://github.com/cochranblock/battle-bros)** | Soldier Board simulation trainer. Offline AI for military regulation training on AR glasses. Public domain. |
| **[call-shield](https://github.com/cochranblock/call-shield)** | On-device call screening. Whisper + intent classifier in 42 MB. Zero audio leaves the device. |
| **[cochranblock](https://github.com/cochranblock/cochranblock)** | This site. 13 MB Rust binary, embedded assets, native search, live analytics. $10/month. |
| **[deglaze](https://github.com/cochranblock/deglaze)** | JS Budget Auditor for WASM. Maps wasm-bindgen glue to the spec proposal that kills each function. |
| **[exopack](https://github.com/cochranblock/exopack)** | Test augmentation: screenshot, video, API mocks, triple sims. Zero external test deps. |
| **[forge-engine](https://github.com/cochranblock/forge-engine)** | 2D-first Rust game engine. Desktop and web on the same code path. NanoSign provenance baked in. |
| **[free-payroll-system](https://github.com/cochranblock/free-payroll-system)** | Local-first payroll. No SaaS. No per-employee pricing. Unlicense. |
| **[ghost-fabric](https://github.com/cochranblock/ghost-fabric)** | Sovereign edge intelligence over Sub-GHz cognitive mesh networks. LoRa 915 MHz, on-device AI. |
| **[header-writer](https://github.com/cochranblock/header-writer)** | Injects Unlicense + contributor headers across every repo in the org. |
| **[illbethejudgeofthat](https://github.com/cochranblock/illbethejudgeofthat)** | Pro se custody case builder. Google Takeout → court-ready exhibit book. |
| **[knoxai](https://github.com/cochranblock/knoxai)** | On-device AI assistant. Sovereign, offline-first. |
| **[kova](https://github.com/cochranblock/kova)** | AI augmentation engine. Agent loop, 7 tools, multi-provider LLM, 4-node cluster. |
| **[kova-ipc](https://github.com/cochranblock/kova-ipc)** | Unix-socket IPC framing for cochranblock daemons. Operator-only, file-mode authenticated. |
| **[nanobyte](https://github.com/cochranblock/nanobyte)** | Million-mote asteroid sensor swarm. 2 mm SiC motes, 24 KB Rust binary per mote, 400 μs LIBS decision. |
| **[oakilydokily](https://github.com/cochranblock/oakilydokily)** | Client site with WASM mural, multi-auth, ESIGN waivers. First paying partnership. |
| **[pixel-forge](https://github.com/cochranblock/pixel-forge)** | Pixel art sprite generator. 3 on-device diffusion models, MoE cascade, LoRA. Metal/CUDA/CPU. |
| **[play-publish](https://github.com/cochranblock/play-publish)** | Play Store publish pipeline — assets, build, sign, upload. One command. |
| **[pocket-server](https://github.com/cochranblock/pocket-server)** | Your website lives on your phone. No hosting bill. Ever. |
| **[provenance-docs](https://github.com/cochranblock/provenance-docs)** | AI development documentation framework. Timeline of Invention + Proof of Artifacts. SBIR-ready. |
| **[r8r](https://github.com/cochranblock/r8r)** | n8n.io reimagined in Rust. One static binary, embedded WASM canvas, codegen pipeline. |
| **[rogue-repo](https://github.com/cochranblock/rogue-repo)** | Sovereign app store + ISO 8583 payment engine. 100% Rust. *(archived)* |
| **[ronin-sites](https://github.com/cochranblock/ronin-sites)** | Multi-tenant SaaS for tattoo shops and independent artists. *(archived)* |
| **[runsible](https://github.com/cochranblock/runsible)** | Ansible reimagined as a TOML-native single-binary Rust tool. |
| **[tmux-harness](https://github.com/cochranblock/tmux-harness)** | AI fleet orchestration via tmux. LangChain is dead. Zero Python. Zero cloud. |
| **[tmuxisfree](https://github.com/cochranblock/tmuxisfree)** | tmux is free. So is this. Sovereign terminal workflow, zero cloud, zero subscriptions. |
| **[whobelooking](https://github.com/cochranblock/whobelooking)** | Visitor presence and analytics. Sovereign, no third-party beacons. |
| **[whyyoulying](https://github.com/cochranblock/whyyoulying)** | Truth verification engine. Labor category fraud detection for DoD IG. |
| **[worldview](https://github.com/cochranblock/worldview)** | Geopolitical signal aggregator. On-device, sovereign, no subscriptions. |
| **[wowasticker](https://github.com/cochranblock/wowasticker)** | Offline voice dictation + behavioral scoring. On-device Whisper. |

---

### The architecture

```
Internet → Cloudflare Tunnel → approuter :8080 → cochranblock  :8081
                                               → oakilydokily  :3000
                                               → rogue-repo    :3001

Edge:    ghost-fabric nodes (LoRa 915MHz mesh)
Cluster: 4 bare metal Debian nodes (lf, gd, bt, st)
GPU:     RTX 3070 8GB + RTX 3050 Ti 4GB (training)
```

All owned hardware. All for $10/month.

---

### Speed

cochranblock.org homepage: **9.5 KB, 0 JavaScript, 240x lighter than Wix**.

The company that sells web hosting ships 116 JavaScript files. We ship zero.

**[See the numbers →](https://cochranblock.org/speed)**

---

### Fractional CTO services

**$3,500** one-time deployment | **$225/hr** consulting | **$3,500/mo** retainer

**[Start a Project](https://cochranblock.org/deploy)** | **[Cost Analysis](https://cochranblock.org/mathskillz)** | **[Book a Call](https://cochranblock.org/book)** | **[Open Books](https://cochranblock.org/openbooks)**

<p align="center"><em>Service-Disabled Veteran-Owned Small Business (SDVOSB) — Certified 2026-05-12 (SBA VetCert, expires 2029-05-12)<br>SAM.gov UEI W7X3HAQL9CF9 · CAGE 1CQ66 · Maryland CSB Approved · eMMA SUP1095449</em></p>
