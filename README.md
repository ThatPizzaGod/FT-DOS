FT-DOS Version 1.10 — Cinematic & Bug-Checked
===============================================

        _____ _______    _____   ____   _____
       |  ___|__   __|  |  __ \ / __ \ / ____|
       | |_     | |     | |  | | |  | | (___
       |  _|    | |     | |  | | |  | |\___ \
       | |      | |     | |__| | |__| |____) |
       |_|      |_|     |_____/ \____/|_____/ 

FT-DOS is a fully simulated DOS-like environment created entirely 
in a Windows batch file. It features cinematic boot sequences, fake 
BIOS/UEFI setup, animations, virtual apps, hidden easter eggs, 
BSOD simulations, a virtual filesystem, and logging — all completely 
visual and safe.  

================================================================================
Table of Contents
--------------------------------------------------------------------------------
1. Overview
2. Features
3. Installation
4. Running FT-DOS
5. Main Commands
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
================================================================================

1. Overview
--------------------------------------------------------------------------------
FT-DOS is a safe, visual simulation of a DOS-style OS. 
It provides nostalgic computing experiences without affecting your real system.

Key Highlights:
- Cinematic bootloader sequences
- BIOS/UEFI setup screens
- Terminal shell with expanded commands
- Virtual apps & games
- Retro DOS mode
- Multiple fake BSOD types
- Hidden commands and easter eggs
- Full logging of user actions

================================================================================
2. Features
--------------------------------------------------------------------------------
- Cinematic Bootloader
- BIOS/UEFI Setup Utility
- Main Terminal Shell
- Virtual Apps: calculator, ASCII drawer, snake, matrix, DOOM loader
- Retro Mode: 1986 DOS emulation
- Themes & Customization
- Fake BSOD Engine: Normal, Advanced, Mega
- Virtual Filesystem
- Hidden Commands & Easter Eggs
- Command Logging

================================================================================
3. Installation
--------------------------------------------------------------------------------
1. Clone or download the repository.
2. Open Command Prompt.
3. Navigate to the folder containing ft-dos.bat
4. Run the script:

    ft-dos.bat

> FT-DOS is completely visual and harmless.

================================================================================
4. Running FT-DOS
--------------------------------------------------------------------------------
- Watch the cinematic bootloader load modules and scan virtual memory.
- Press any key to enter BIOS/UEFI setup.
- Explore system info, boot options, and connected devices.
- Exit to enter FT-DOS main shell.

================================================================================
5. Main Commands
--------------------------------------------------------------------------------
Basic Commands:
- help, help -1, help -2 — Show help menu
- clear — Clears the screen
- systeminfo — Displays fake system info
- time — Shows your current system clock
- credits — Shows developer credits
- exit — Close FT-DOS

Advanced Commands:
- taskkill -system32 — Trigger a fake BSOD
- ls — List virtual filesystem
- open — Open a virtual file
- run — Launch virtual apps
- theme — Change text colors and themes
- diag — Run virtual diagnostics
- shutdown, restart — Simulated power commands
- scan — Fake malware scanner
- setup — Virtual installer
- hidden — Secret commands
- web — Open URL
- bootlogo — Display splash screen
- settings — Adjust text speed, animations, ASCII density

================================================================================
6. Virtual Apps
--------------------------------------------------------------------------------
- calc — Fake calculator
- ascii — ASCII drawing application
- snake — Fake Snake game
- matrix — Matrix-style screensaver
- doom — Fake DOOM loader

================================================================================
7. Retro Mode
--------------------------------------------------------------------------------
- DOS 1986 emulation shell
- Commands: help, dir, ver, spooky, exit
- Green text on black for authentic retro look

Example:
MICROSOFT FT-DOS RETRO SHELL [VERSION 1.10]
C:\> dir
Volume in drive C is FAKE-DOS
Directory of C:\RETRO\
KERNEL   SYS   14,336
COMMAND  COM   23,552
BIOS     ROM    8,192

================================================================================
8. Themes & Customization
--------------------------------------------------------------------------------
- Classic (default)
- Hacker Green
- Ice Blue
- Warning Yellow
- Ultra Retro
- Dark Mode

================================================================================
9. Fake BSOD Engine
--------------------------------------------------------------------------------
- Normal: Minor crash simulation
- Advanced: Detailed stop code and driver fault
- Mega: Kernel meltdown with memory dump

Example:
A problem has been detected and FT-DOS has been shut down.
*** STOP: 0x0000007E (00000001, 00000002, 00000003, 00000004)

================================================================================
10. Virtual Filesystem
--------------------------------------------------------------------------------
Included files:
- readme.txt
- config.sys
- boot.ftd
- manual.ftd
- ghost.log
- notes.db

All file operations are simulated.

================================================================================
11. Hidden Commands & Easter Eggs
--------------------------------------------------------------------------------
- secret-memtest
- easter-skeletons
- rick-roll
- Ghost mode entity scan

================================================================================
12. Logging & Debug
--------------------------------------------------------------------------------
- Logs all commands and errors to: %TEMP%\FTDOS_LOG.txt
- Helps with debugging and development

================================================================================
13. Screenshots & Animations
--------------------------------------------------------------------------------
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

================================================================================
14. Changelog
--------------------------------------------------------------------------------
v1.10 — 2025-11-30
- Cinematic bootloader & animations
- Bug-checked mainloop
- Expanded virtual apps & commands
- Enhanced help system
- Retro mode improvements
- Multiple BSOD types
- Hidden commands & easter eggs
- Command logging

================================================================================
15. Credits
--------------------------------------------------------------------------------
- Creator: Mason Mercado
- Development Assistance: ChatGPT
- Inspiration: DOS, FT-DOS v1.01, retro computing

================================================================================
16. License
--------------------------------------------------------------------------------
This project is licensed under the MIT License. See LICENSE.txt for details.

================================================================================
Notes
--------------------------------------------------------------------------------
FT-DOS is visual only and perfect for:
- Fun & nostalgia
- Education & learning batch scripting
- Experimenting with virtual apps, animations, and retro computing

Enjoy your simulated DOS world!
================================================================================
