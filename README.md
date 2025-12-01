FT-DOS Version 1.10 (Cinematic & Bug-Checked)

   _____ _______    _____   ____   _____
  |  ___|__   __|  |  __ \ / __ \ / ____|
  | |_     | |     | |  | | |  | | (___
  |  _|    | |     | |  | | |  | |\___ \
  | |      | |     | |__| | |__| |____) |
  |_|      |_|     |_____/ \____/|_____/

FT-DOS is a fully simulated DOS-like environment created entirely in a Windows batch file.
It features cinematic boot sequences, fake BIOS/UEFI setup, animations, virtual apps,
hidden easter eggs, BSOD simulations, a virtual filesystem, and more — all completely visual and safe.

============================================================
Table of Contents
============================================================
1. Overview
2. Features
3. Installation
4. Running FT-DOS
5. Command Reference
6. Virtual Apps
7. Retro Mode
8. Themes & Customization
9. Fake BSOD Engine
10. Virtual Filesystem
11. Hidden Commands & Easter Eggs
12. Logging & Debug
13. Screenshots & Animations
14. Changelog
15. Credits
16. License

============================================================
Overview
============================================================
FT-DOS is a safe, visual simulation of a DOS-style OS.
It provides nostalgic computing experiences while staying harmless to your system.

- Cinematic bootloader animations
- BIOS/UEFI setup screens
- Virtual apps & games
- Retro mode
- Hidden commands and easter eggs
- Logging for command usage and errors

============================================================
Features
============================================================
- Cinematic Bootloader
- BIOS/UEFI Setup Utility
- Main Terminal Shell with expanded commands
- Virtual Apps (calculator, ASCII drawer, snake, matrix, DOOM loader)
- Retro Mode emulating DOS 1986
- Themes & Customization
- Fake BSOD Engine (Normal, Advanced, Mega)
- Virtual Filesystem (readme.txt, config.sys, boot.ftd, etc.)
- Hidden Commands & Easter Eggs
- Logging all user actions

============================================================
Installation
============================================================
1. Clone this repository or download the ZIP.
2. Open Command Prompt.
3. Navigate to the folder containing ft-dos.bat.
4. Run the script:

ft-dos.bat

> FT-DOS is safe and visual only.

============================================================
Running FT-DOS
============================================================
1. Enjoy cinematic bootloader sequences.
2. Press any key to enter BIOS/UEFI setup.
3. Explore system info, boot options, and connected devices.
4. Exit to enter FT-DOS main shell.

============================================================
Command Reference
============================================================
Basic Commands:
- help, help -1, help -2
- clear — clear screen
- systeminfo — fake system info
- time — display clock
- credits — view developer credits
- exit — close FT-DOS

Advanced Commands:
- taskkill -system32 — fake BSOD
- ls — list virtual files
- open — open file
- run — launch FT-Apps
- theme — color themes
- diag — run diagnostics
- shutdown, restart — power simulation
- scan — malware scanner
- setup — virtual installer
- hidden — secret commands
- web — open URL
- bootlogo — display splash
- settings — text/animation adjustments

============================================================
Virtual Apps
============================================================
- calc — fake calculator
- ascii — ASCII drawer
- snake — fake snake game
- matrix — matrix screensaver
- doom — fake DOOM loader

============================================================
Retro Mode
============================================================
- Emulates DOS shell (1986)
- Commands: help, dir, ver, spooky, exit
- Green text on black screen for full retro feel

============================================================
Themes & Customization
============================================================
- Classic (default)
- Hacker Green
- Ice Blue
- Warning Yellow
- Ultra Retro
- Dark Mode

============================================================
Fake BSOD Engine
============================================================
- Normal: minor crash simulation
- Advanced: detailed fake system halt
- Mega: kernel meltdown with memory dump

============================================================
Virtual Filesystem
============================================================
Files included:
- readme.txt, config.sys, boot.ftd, manual.ftd, ghost.log, notes.db

============================================================
Hidden Commands & Easter Eggs
============================================================
- secret-memtest
- easter-skeletons
- rick-roll
- Ghost mode entity scan

============================================================
Logging & Debug
============================================================
- Logs all commands & errors to %TEMP%\FTDOS_LOG.txt
- Useful for debugging and development

============================================================
Screenshots & Animations
============================================================
Placeholders — replace with actual GIFs/screenshots if available

Bootloader Animation Example:
[1/30] Memory scan: 3%
[2/30] Memory scan: 6%
...
Boot OK.

Virtual App Example (ASCII Drawer):
>> Hello World
Hello World
>> EXIT

BSOD Example:
A problem has been detected and FT-DOS has been shut down.
*** STOP: 0x0000007E (00000001, 00000002, 00000003, 00000004)
Press any key to reboot...

Retro Mode Example:
MICROSOFT FT-DOS RETRO SHELL [VERSION 1.10]
C:\> dir
Volume in drive C is FAKE-DOS
Directory of C:\RETRO\
KERNEL   SYS   14,336
COMMAND  COM   23,552

> GIFs or terminal screenshots can be placed in /assets and referenced as:
> ![Bootloader](assets/bootloader.gif)

============================================================
Changelog
============================================================
v1.10 — 2025-11-30

- Cinematic bootloader & animations
- Bug-checked mainloop
- Expanded virtual apps & commands
- Enhanced help system
- Retro mode improvements
- Multiple BSOD types
- Hidden commands & easter eggs
- Command logging

============================================================
Credits
============================================================
- Creator: ThatPizzaGod ("@troopergmd" on tiktok.)
- Inspiration: DOS, FT-DOS v1.01, retro computing

============================================================
License
============================================================
This project is licensed under MIT License — see LICENSE.

============================================================
Notes
============================================================
FT-DOS is visual only, harmless, and perfect for:
- Fun & nostalgia
- Education & learning batch scripting
- Experimenting with virtual apps & animations

Enjoy your fake DOS world!
