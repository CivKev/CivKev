## Hi, I'm Kevin Silhavy 👋

Founder of **Kemit Security**, a privacy-focused technology company building zero-knowledge and privacy-first tools.

🌐 [kevin.smithis.me](https://kevin.smithis.me) · [kemitsecurity.com](https://kemitsecurity.com)

### What I do
- **Founder, Kemit Security** — I set product strategy, architecture and infrastructure for a lineup of 15+ planned consumer and business privacy products, built on an "AntiBS" philosophy: transparent, privacy-first, low-overhead tools

### Things I've built
- **KemitPass** — deployed a zero-knowledge password manager stack (PostgreSQL + Cloudflare Tunnel) with a custom Stripe billing layer
- **In-house company platforms** — Kemit's HR portal and billing platform, plus a real-time support chat stack (Node.js, Express, Socket.io, PostgreSQL)
- **Inspection report automation** — AI-assisted pipeline that turns handwritten and scanned inspection forms into import-ready spreadsheets, enforcing a 30+ section rulebook of validation and formatting rules
- **Invoice reconciliation tooling** — Python tools that matches what's in the system against PDF invoices and debit notes
- **AmeriBrit Panel** — custom server management portal and Jellyfin plugin (see below)

### What I'm building
- **KemitVPN** — private, no-nonsense VPN for everyday browsing
- **KemitPass** — zero-knowledge password manager
- **Roamveil** — privacy-minded travel eSIM service
- **KemDoc** — e-signature merged with a zero-knowledge vault ("Sign to Vault")
- **Kemit Chat** — our own secure team chat platform, web + iOS
- **Tunnel service** — expose game servers and home networks without port forwarding

### 🏠 Home lab — AmeriBrit
A 20U floor-standing rack I'm building with my best friend in the UK.

- **Media server** — 4U, Ryzen 5 + RTX 3050 for transcoding, running Jellyfin for movies, shows, anime, music and podcasts, published through Cloudflare Tunnel + Caddy
- **AmeriBrit Panel** — my own management portal with a custom Jellyfin plugin. It handles user management, R2 backups, transcode analytics, readable logs, a public status page and UPS-aware shutdowns. A native iOS app with push alerts is in the works.
- **Game server** — off-site on an OVH VPS-3, running Pterodactyl for Minecraft, FiveM and more
- **Cloud server** — Nextcloud + Immich to replace Google Drive and Google Photos
- **Monitoring** — every server runs an agent that dials out to a small off-site VPS, so no ports are open at the house. An ODROID N2+ handles UPS (NUT) monitoring, alerting and Home Assistant.
- **Power & network** — rackmount CyberPower UPS + PDU, 5 Gb fiber, eero mesh with wired backhaul, and an isolated 2.5 Gb storage network

### What I work with
**Self-hosting & infra:** Debian/Ubuntu, Docker, Caddy, Cloudflare Tunnel & Zero Trust, NUT, Home Assistant
**Dev:** Node.js, Express, Socket.io, PostgreSQL, Python, Stripe
**Automation:** Claude / LLM-driven document extraction and workflow automation
