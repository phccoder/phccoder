<div align="center">

# John David Gulifardo

**Full-Stack Engineer · Enterprise ERP & Edge Systems**

Bridging the gap between physical hardware and legacy systems on one side and modern web architectures on the other — custom desktop daemons, real-time sync engines, and enterprise SaaS.

Hardware meets the web. Legacy meets real-time. Built to ship.

</div>

---

## What I Do

- Designs full systems, not just features
- Bridges proprietary hardware & legacy data to modern platforms
- BIR-compliant finance, payroll & POS tooling
- Ships self-healing agents to real branch offices

---

## Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | PHP 8.3+, Python 3.11+, JavaScript, C++, SQL, Bash / PowerShell |
| **Backend** | Laravel 12/13, Livewire 4 + Volt, Flask, REST APIs, JSON-RPC, Stripe Payment Intents |
| **Frontend** | Blade, Alpine.js, Tailwind CSS 3, Vite, HTML/CSS, Electron, CustomTkinter |
| **Databases** | PostgreSQL 17, MySQL / MariaDB, SQLite, legacy DBF / MySQL migration, AWS S3 |
| **Real-Time** | Laravel Reverb, Pusher, Laravel Echo, Presence Channels, SSE, WebSocket command dispatch |
| **Hardware & Edge** | ZKTeco / NGTeco biometrics, pyzk, OBD-II / ELM327, ADB / Fastboot / EDL / BROM |
| **Packaging** | PyInstaller, Inno Setup 6, NSSM service hosting, PyQt5, tkinter |
| **DevOps** | Docker, GitHub Actions, nginx + PHP-FPM, supervisord, Cloudflare Tunnel, AWS (Ubuntu) |
| **AI & Data** | Whisper (Groq), Gemini, transcription pipelines, automated import / reconciliation |

---

## Flagship Projects

### ⚙️ APCHub (APCInventory)
Enterprise integrated business systems: a TALL-stack ERP (233 migrations, ~119 models, ~93 Livewire components) unified with compiled Python biometric desktop tools and legacy-data reconciliation for a multi-branch financial institution.

- Custom RBAC with recursive manager-subordinate scoping & ~90 permission slugs
- Real-time chat, live biometric telemetry, live passbook-release index (Reverb/Pusher)
- Universal ZKTeco + NGTeco bridge, self-updating single-instance daemon
- Flask delta-sync server mirrored to S3; legacy MySQL/DBF migration with per-row fault isolation

[Repository](https://github.com/phccoder/APCInventory) · [Case Study](https://github.com/phccoder/integrated-business-system-case-study)

### 🛒 M2P POS
Offline-first Point-of-Sale + inventory + financials + BIR-compliance system (Python + CustomTkinter + PostgreSQL 17). One PC or a permission-gated LAN.

- 167 RPC methods, single route map as source of truth
- Integer-centavo money model, immutable stock ledger, full audit log
- BIR-ready: receipts, eJournal/eSales, VAT, X/Z readings, reprint trail
- Three Windows installers incl. bundled PostgreSQL + NSSM services

[Repository](https://github.com/phccoder/m2p-pos) · [Showcase](https://github.com/phccoder/m2p-pos-showcase)

### 💵 Payroll & HR Management SaaS
Multi-tenant Philippine payroll platform with biometric reconciliation — automated weekly payroll, cash-advance ledgers, statutory 13th-month, and immutable locked payslips.

- Payroll as a state machine: draft → reviewed → locked; snapshot-frozen rates
- Law-aware SSS / PhilHealth / Pag-IBIG week-of-month deduction schedule
- Discrepancy gating blocks approve/print/export until attendance is clean
- One-click self-hosting Windows compilers + Cloudflare tunnel support

[Repository](https://github.com/phccoder/philippines-payroll-management-system) · [Showcase](https://github.com/phccoder/payroll-showcase)

### 🖥️ Branch Updater & Biometrics
Centralized branch-office update & data-sync infrastructure — delta-syncs legacy FoxPro databases, pushes app updates, pulls ZKTeco attendance, HQ command center.

- Manifest-diff delta sync mirrored to S3 as durable storage
- Self-updating distribution loop with silent Inno Setup + NSSM services
- Headless biometric agents with WebSocket command dispatch

[Repository](https://github.com/phccoder/branch-updater-and-biometrics)

### 🎧 LEPT Review Hub
Local-first teacher's review app: records class audio, transcribes via Groq Whisper (Tagalog), generates notes/flashcards/quizzes with Gemini.

- Pure-PHP chunking under Groq's 25 MB API limit
- Livewire dashboard with notes/quiz/flashcards/chat/upload
- 100% local — SQLite, no accounts, keys from `.env`

[Repository](https://github.com/phccoder/review-hub)

---

## Other Notable Projects

- **integrated-business-system-case-study** — public case-study mirror of the production APCHub codebase
- **m2p-pos-showcase** · **payroll-showcase** — live screenshots, sample outputs, deep-dive docs, sanitized code
- **Motorcycle-Diag-Tool** — OBD-II/ELM327 real-time diagnostics with DTC lookup & hardware-free simulator
- **arnel-validator** — DBF extractor & Excel validator desktop app
- **android-tools-universal** — bootloader unlocker, ROM dump & ADB toolkit (Fastboot/EDL/BROM) + Electron GUI
- **caption-generator** — 100% offline Whisper subtitle generator (portable .exe)
- **mediafire-bulk-downloader** — IDM-style multi-threaded desktop downloader
- **GD-Check-Writer-Pro** — automated check-printing & cash-flow manager
- **event-ticketing-and-management-system** — case study: QR tickets + on-site validation
- **laravel-payment-gateway** — Apple/Google Pay via Stripe Payment Intents on the TALL stack
- **fintech-gift-card-exchange-platform** — case study: gift-card-to-cash with Paxful API
- **Bus-Ticketing-System** / **BHW Child Health Records** — C++ console projects

---

## Get in Touch

- **Website:** [gulifardo.dev](https://gulifardo.dev)
- **Email:** [gulifardo.dev@gmail.com](mailto:gulifardo.dev@gmail.com)
- **LinkedIn:** [in/gulifardo-dev](https://www.linkedin.com/in/gulifardo-dev/)
- **Telegram:** [@gulifardo_dev](https://t.me/gulifardo_dev)
- **GitHub:** [phccoder](https://github.com/phccoder)

<div align="center">

© 2026 John David Gulifardo

</div>