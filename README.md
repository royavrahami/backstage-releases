# Backstage.AI — Releases

Public download mirror for **Backstage.AI**, a real-time interview co-pilot
that runs as a transparent overlay during video calls (Google Meet, Zoom, Teams).

The application's source code lives in a private repository. This repo's only
purpose is to host downloadable installer binaries via
[GitHub Releases](../../releases).

## Download

Latest installer: **[Releases → Latest](../../releases/latest)**

Each release attaches:

- `BackstageAI_Setup_<version>.exe` — Windows 10/11 installer (Inno Setup, ~1.4 GB)
- `BackstageAI_Setup_<version>.exe.sha256` — SHA-256 hash for integrity verification

## Verify your download

```powershell
Get-FileHash BackstageAI_Setup_0.5.2-beta.exe -Algorithm SHA256
# Compare the printed hash with the contents of the .sha256 file
```

## System requirements

- Windows 10 or Windows 11 (64-bit)
- ~5 GB free disk space
- Webcam + microphone
- ~16 GB RAM recommended

## SmartScreen note

The installer is currently **unsigned**, so Windows SmartScreen will show
*"Windows protected your PC"* on first launch. Click **More info** → **Run anyway**.
Code-signing is on the roadmap.

## Links

- Website: <https://backstagecopilot.com>
- Waitlist: <https://backstagecopilot.com/#waitlist>
