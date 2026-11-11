# 404 SoundBoard

Minimalist, high-performance native Windows desktop soundboard built with **WPF (.NET 5)**.

## Features
- **Two-tone Minimalist Dark UI** (`#0a0a0a` & `#e11d48`) with native Windows Dark Title Bar
- **Grid View & List View** switcher with GPU-accelerated infinite scroll
- **Play Animations** — pulsing ring on Grid cards & 3-bar animated equalizer on List rows
- **Favorites & Direct MP3 Downloads** with persistent folder selection
- **In-Memory Caching** — instant back/tab navigation
- **Remote Config & Verified Auto-Updater** powered by GitHub `config.json`
- **SHA-256 Anti-Tamper Self-Check** — detects unofficial/modified executables to protect users against bundled malware/RATs

## Official Releases & Integrity Verification

Download **only** from [GitHub Releases](https://github.com/ftubenet/404soundboard/releases).

Verify your executable's SHA-256 hash in PowerShell before running:
```powershell
Get-FileHash ".\404 SoundBoard.exe" -Algorithm SHA256
```

**Latest Official SHA-256 (`v1.0.0`):**
```text
eb327df71d49324b18349af762f34409f494b901562fed1d40af67205bc66a22
```

## Remote Control (`config.json`)
Maintainers can remotely control:
- `latest_version` / `min_supported_version` / `force_update` — Trigger optional or mandatory updates
- `download_url` & `latest_sha256` — Pinned strictly to `github.com/ftubenet/404soundboard/releases/download/...` and SHA-256 verified before swap
- `marquee_text` — Live-update the top announcement ticker without releasing a new `.exe`
- `kill_switch` & `maintenance_msg` — Remotely disable compromised or deprecated builds
- `strict_integrity` & `official_hashes` — Enforce SHA-256 verification against all approved official release binaries

## Contact & Support
- **Facebook Group:** [404 Society](https://www.facebook.com/groups/404society)
- **Telegram:** [@X109110](https://t.me/X109110)
- **Viber / KPay:** `09952666811` (Mg Soe Thu)
