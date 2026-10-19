# PPSP5

A PSP emulator for Android with its own light-blue, console-style home screen.

PPSP5 puts a new front end on the open-source PPSSPP engine: a start-up animation, a row of game tiles with each game's own icon and background art, and one-tap play.

## Features

- Light-blue start-up animation and home screen
- Games shown as tiles with their own icon, title and background art
- Supports ISO, CSO and PBP games
- Pick your game folders once; PPSP5 finds the games for you
- Leaving a game returns you straight to the PPSP5 home screen
- PPSP5 Settings: start-up animation, sorting, game folders, and common emulator options (resolution, frame skipping, texture filtering, sound, on-screen button opacity and more)
- Controller support on the home screen
- Light-blue theme for the emulator's own screens

## Install

1. Open the **Releases** page and download the newest `.apk`.
2. Allow installs from your browser or file manager if Android asks.
3. Open PPSP5, go to **Settings → Add folder**, and choose the folder with your games.

Updates install over the top of earlier builds.

## Games

PPSP5 does not include any games or BIOS files. Use only games you own and have legally backed up yourself.

## Build it yourself

This repository holds the PPSP5 overlay. A GitHub Actions workflow downloads the official PPSSPP source, applies the overlay and builds the APK. Go to **Actions → PPSP5 build → Run workflow**. Each release notes the exact PPSSPP version it was built from.

## Status

Early release. Expect rough edges; please open an issue if something breaks.

## Credits and licence

PPSP5 is built on [PPSSPP](https://www.ppsspp.org) by Henrik Rydgård and contributors ([source](https://github.com/hrydgard/ppsspp)). It is free software released under the GNU General Public License, version 2 or later. Any build of PPSP5 you share must keep its source available under the same licence.

PPSP5 is an independent project. It is not affiliated with or endorsed by Sony or the PPSSPP team. PSP and PlayStation are trademarks of Sony Interactive Entertainment.
