<p align="center">
  <img src="https://raw.githubusercontent.com/cochranblock/cochranblock/main/assets/cochranblock-logo.svg" alt="CochranBlock" width="320">
</p>

<h3 align="center">Your server bill is too high.</h3>

<p align="center">
  This entire company — <a href="https://cochranblock.org">cochranblock.org</a> — runs as a single Rust binary on a laptop.<br>
  <strong>$10/month. No AWS. No Kubernetes. No DevOps team.</strong><br>
  Edge compute beats cloud. It's not the Mech — it's the pilot.
</p>

---

### What's here

9 Rust repositories. All Unlicense. All production code. Every repo ships with **Proof of Artifacts** and a **Timeline of Invention** proving human-piloted AI development.

| Repo | What it does | Status |
|------|-------------|--------|
| **[cochranblock](https://github.com/cochranblock/cochranblock)** | This site. Single Rust binary, embedded assets, $10/month infrastructure. The live demo. | ![Live](https://img.shields.io/badge/status-live-brightgreen) |
| **[kova](https://github.com/cochranblock/kova)** | Augment engine. Agent loop, 7 tools, multi-provider LLM, 4-node cluster, WASM client. 63K LOC. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[pixel-forge](https://github.com/cochranblock/pixel-forge)** | Free pixel art generator. 3 diffusion models under 30MB. First MoE cascade at this scale. Pure Rust. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[approuter](https://github.com/cochranblock/approuter)** | Reverse proxy + Cloudflare tunnel automation. All products behind one entry point. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[oakilydokily](https://github.com/cochranblock/oakilydokily)** | Hero site with interactive WASM mural, multi-auth, ESIGN waivers. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[exopack](https://github.com/cochranblock/exopack)** | Testing augmentation. TRIPLE SIMS, screenshots, mocks, headless Chrome. Zero-framework CI. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[wowasticker](https://github.com/cochranblock/wowasticker)** | Offline-first mobile app. Voice dictation → on-device Whisper → behavioral sticker scoring. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[whyyoulying](https://github.com/cochranblock/whyyoulying)** | Truth verification engine. | ![Active](https://img.shields.io/badge/status-active-blue) |
| **[ronin-sites](https://github.com/cochranblock/ronin-sites)** | Shop and artist platform. Subdomain routing, mobile-first. | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-yellow) |

---

### The architecture

```
Internet → Cloudflare Tunnel → approuter :8080 → cochranblock :8081
                                              → oakilydokily :3000
                                              → rogue-repo   :3001
                                              → ronin-sites   :8000
```

All of it on one laptop. All of it for $10/month.

---

### Fractional CTO services

I build zero-cloud architectures for startups and SMBs drowning in cloud costs. 11 years defense and enterprise. The code here is the proof.

**[cochranblock.org/deploy](https://cochranblock.org/deploy)** — Zero-Cloud Tech Intake Form

**[Download the binary](https://github.com/cochranblock/cochranblock/releases/latest)** — Run this entire site on your machine. One command.
