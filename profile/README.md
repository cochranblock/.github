<p align="center">
  <img src="https://raw.githubusercontent.com/cochranblock/cochranblock/main/assets/cochranblock-logo.svg" alt="CochranBlock" width="320">
</p>

<h3 align="center">Your server bill is too high.</h3>

<p align="center">
  This entire company — <a href="https://cochranblock.org">cochranblock.org</a> — runs as a single 15MB Rust binary on bare metal.<br>
  <strong>$10/month. No AWS. No Kubernetes. No DevOps team.</strong><br>
  Veteran-owned. SDVOSB certified (SBA VetCert, 2026-05-12). It's not the Mech — it's the pilot.
</p>

---

### The Trifecta

1. **You can't outprice free** — every line of code is Unlicense, public domain
2. **You can't out-transparent public domain** — source, bugs, IR&D audit, all public
3. **Expertise is inherent** — the code IS the resume

---

### 16 public repos. All Rust. All live.

| Repo | What it does | Size |
|------|-------------|------|
| **[aptnomo](https://github.com/cochranblock/aptnomo)** | Autonomous APT threat hunter. Auto-kills cryptominers. Zero config. | 312 KB |
| **[call-shield](https://github.com/cochranblock/call-shield)** | On-device call screening. Whisper + intent classifier. Zero audio leaves device. | 48 KB |
| **[cochranblock](https://github.com/cochranblock/cochranblock)** | This site. 15MB binary, embedded assets, native search, live analytics. | 8.4 MB |
| **[kova](https://github.com/cochranblock/kova)** | Augment engine. Agent loop, 7 tools, multi-provider LLM, 4-node cluster. | ~51 MB |
| **[pixel-forge](https://github.com/cochranblock/pixel-forge)** | AI sprite generator. 3 on-device diffusion models, MoE cascade, LoRA. | 9.2 MB |
| **[ghost-fabric](https://github.com/cochranblock/ghost-fabric)** | Sovereign edge intelligence. LoRa 915MHz mesh, on-device AI. | 19 MB |
| **[approuter](https://github.com/cochranblock/approuter)** | Reverse proxy + Cloudflare tunnel. All products behind one entry point. | — |
| **[rogue-repo](https://github.com/cochranblock/rogue-repo)** | ISO 8583 payment processing engine. 100% Rust. | — |
| **[oakilydokily](https://github.com/cochranblock/oakilydokily)** | Waiver management, digital intake, ESIGN. First paying partnership. | — |
| **[pocket-server](https://github.com/cochranblock/pocket-server)** | Your website lives on your phone. No hosting bill. Ever. | 1 MB |
| **[illbethejudgeofthat](https://github.com/cochranblock/illbethejudgeofthat)** | Pro se custody case builder. Google Takeout to court-ready exhibit book. | 2.5 MB |
| **[exopack](https://github.com/cochranblock/exopack)** | Test framework. Zero external test deps. | 313 KB |
| **[whyyoulying](https://github.com/cochranblock/whyyoulying)** | Labor category fraud detection for DoD IG. | 505 KB |
| **[wowasticker](https://github.com/cochranblock/wowasticker)** | Offline voice dictation + behavioral scoring. On-device Whisper. | — |
| **[provenance-docs](https://github.com/cochranblock/provenance-docs)** | AI development documentation framework. Timeline of Invention. | 328 KB |
| **[ronin-sites](https://github.com/cochranblock/ronin-sites)** | Multi-tenant shop platform for artists. | 4 MB |

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
