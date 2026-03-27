<p align="center">
  <img src="https://raw.githubusercontent.com/cochranblock/cochranblock/main/assets/cochranblock-logo.svg" alt="CochranBlock" width="320">
</p>

<h3 align="center">Your server bill is too high.</h3>

<p align="center">
  This entire company — <a href="https://cochranblock.org">cochranblock.org</a> — runs as a single 18MB Rust binary on bare metal.<br>
  <strong>$10/month. No AWS. No Kubernetes. No DevOps team.</strong><br>
  Veteran-owned. SDVOSB pending. It's not the Mech — it's the pilot.
</p>

---

### What's here

14 public Rust repositories. All Unlicense. All production code. Every repo ships with **Proof of Artifacts** and a **Timeline of Invention** proving human-piloted AI development.

| Repo | What it does | Status |
|------|-------------|--------|
| **[cochranblock](https://github.com/cochranblock/cochranblock)** | This site. 18MB binary, embedded assets, $10/month infrastructure. The live demo. | ![Live](https://img.shields.io/badge/status-live-brightgreen) |
| **[ghost-fabric](https://github.com/cochranblock/ghost-fabric)** | Sovereign edge intelligence over sub-GHz cognitive mesh networks. 19MB Rust + LoRa. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[kova](https://github.com/cochranblock/kova)** | Augment engine. Agent loop, 7 tools, multi-provider LLM, 4-node cluster, WASM client. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[pixel-forge](https://github.com/cochranblock/pixel-forge)** | Free pixel art generator. 3 on-device diffusion models, MoE cascade, LoRA fine-tuning. Pure Rust. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[approuter](https://github.com/cochranblock/approuter)** | Reverse proxy + Cloudflare tunnel. All products behind one entry point. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[oakilydokily](https://github.com/cochranblock/oakilydokily)** | Client site with WASM mural, multi-auth, ESIGN waivers. First paying partnership. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[illbethejudgeofthat](https://github.com/cochranblock/illbethejudgeofthat)** | Pro se custody case builder. Google Takeout to court-ready exhibit book in one evening. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[exopack](https://github.com/cochranblock/exopack)** | Testing augmentation. TRIPLE SIMS, screenshots, headless Chrome. Zero-framework CI. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[rogue-repo](https://github.com/cochranblock/rogue-repo)** | Sovereign app store + ISO 8583 payment engine. 100% Rust. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[wowasticker](https://github.com/cochranblock/wowasticker)** | Offline-first mobile app. Voice dictation, on-device Whisper, behavioral scoring. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[whyyoulying](https://github.com/cochranblock/whyyoulying)** | Truth verification engine. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[pocket-server](https://github.com/cochranblock/pocket-server)** | Your website lives on your phone. Rust web server + Android kiosk dashboard. No hosting bill. Ever. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[provenance-docs](https://github.com/cochranblock/provenance-docs)** | AI development documentation framework for federal acquisition. Timeline of Invention + Proof of Artifacts. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[call-shield](https://github.com/cochranblock/call-shield)** | On-device call screening. Whisper + intent classifier in 42MB binary. Zero audio leaves the device. | ![Active](https://img.shields.io/badge/status-active-blue) |

---

### The architecture

```
Internet -> Cloudflare Tunnel -> approuter :8080 -> cochranblock  :8081
                                                 -> oakilydokily  :3000
                                                 -> rogue-repo    :3001

Edge:    ghost-fabric nodes (LoRa 915MHz mesh, 19MB Rust binaries)
Cluster: 4 bare metal Debian nodes (lf, gd, bt, st)
Dev:     Mac Mini ARM (9.9MB binary)
```

All of it on owned hardware. All of it for $10/month.

---

### The math

Your $3,000/month cloud bill should be $10. **[See the numbers.](https://cochranblock.org/mathskillz)**

37signals saved $10M leaving AWS. You don't need to be their size to benefit.

---

### Fractional CTO services

Zero-cloud architecture for startups, SMBs, and government. 13 years defense and enterprise. Army veteran (17C Cyber Operations). USCYBERCOM J38 dev lead.

**$3,500** one-time deployment | **$225/hr** consulting | **$3,500/mo** retainer

**[Start a Project](https://cochranblock.org/deploy)** | **[Cost Analysis](https://cochranblock.org/mathskillz)** | **[Book a Call](https://cochranblock.org/book)**

<p align="center"><em>Service-Disabled Veteran-Owned Small Business (SDVOSB) — Pending</em></p>
