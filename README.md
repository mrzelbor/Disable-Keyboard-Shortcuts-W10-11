# Disable-Keyboard-Shortcuts-W10-11
Information
---
This repository provides two lightweight AutoHotkey-based executables for Windows 10/11.
They are designed to disable selected keyboard shortcuts in order to improve security and prevent misuse of system functions.

Variants
---
- **Disable Keyboard Shortcuts.exe**
  - Standard: Executable that disables specified keyboard shortcuts and **allows** right-click usage.
- **Disable Keyboard Shortcuts - rcB.exe**
  - rcB (Right Click Blocked): Executable that disables the same keyboard shortcuts but **blocks** right-click usage.

Use Cases
---
- Hardening kiosk or shared environments.
- Preventing accidental or unauthorized access to system features.
- Reducing the attack surface in security-sensitive scenarios.

Instructions
---
- You can either run the preferred executable directly, or place it in the following location to have it start automatically at login:
```
C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup
```
- To exit the program, go to Task Manager and end the task.

The following shortcuts are not blocked:
---
- `Windows + L` → Lock Screen
- `Windows Key L` → Windows Left Key
- `Windows Key R` → Windows Right Key
- `Windows + Ctrl + Shift + B` → Reset Graphic Driver
- `Ctrl + C` → Copy
- `Ctrl + F` → Search
- `Ctrl + V` → Paste
- `Ctrl + X` → Cut
- `Ctrl + Y` → Redo
- `Ctrl + Z` → Undo
- `Ctrl + Shift` → Switch Keyboard Layout
- `Ctrl + Alt + Del` → Security Menu
- `Alt + Tab` → Task Switcher
- `Caps Lock` → Toggle Caps
- `Esc` → Escape Key

Updates
---
- Zelbor-AutoHotKey v1.1 - February 18th, 2026
- Zelbor-AutoHotKey v1.0 - August 17th, 2025


I’d be glad to hear any suggestions—please don’t hesitate to reach out.
