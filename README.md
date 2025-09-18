## 》IOTHidden Launcher《 ##

A lightweight Android launcher to trigger hidden system activities and shell commands—no terminal needed.  
Import from clipboard or file, search in real time, organize with tags, and run or copy commands with a tap. Includes light/dark theme and adaptive icons.

⚠️ **Warning / Responsibility:** ⚠️ 
Many bundled intents target internal menus (e.g., Samsung "com.sec.hiddenmenu"). Use at your own risk. Changes may affect device stability and could void warranties.

## ❕️IMPORTANT❕️
⚠️ if you don't have allready installed IOTHiddenMenu App, you need to install it first! ➡️ APKMirror.
⚠️ Root access is supported and recommended, since launching certain Activities requires elevated permissions to function correctly.*
A small number of components can also run without root.

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Usage](#usage)
- [`actions.txt` Format](#actionstxt-format)
- [Permissions & Root](#permissions--root)
- [License](#license)

## Features ##

- Actions list >
  with title, optional [tag] (category badge), and the full "am start …" command.

- Run >
  button executes the command.
  
- Copy >
  button places the command on the clipboard.

- Imports Action File >
  Clipboard auto-detects the format.
  File /sdcard/IOTHiddenLauncher/actions.txt (detected on app start).

- Live search across title, tag, and command.
  
- Dark/Light Theme >
  toggle in the app bar (persisted  via SharedPreferences).
  
- Adaptive App Icon >
  plus legacy mipmaps (black background, custom foreground icon).

## Screenshots ##
<img width="1080" height="2115" alt="IOTHidden_AppMainScreenshot" src="https://github.com/user-attachments/assets/70fba1e9-25ab-421d-89b0-df267bb927c4" />

