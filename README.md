# Tux Mod Manager
TMM is a Linux native mod manager made with the Tauri toolkit, it can, install, load, remove, and deploy mods for both linux native and wine games.

## TMM Roadmap
 - 🟢 Move the current mod manager logic to rust
 - 🔴 Implement a OFS (Overlay File System, similar to VFS from MO2)
 - 🔴 Implement a game launcher for native and wine games (for the OFS)
 - 🔴 Implement a per-game load order

## Installing and running
- Installing Dependencies - Ubuntu/Mint/Debian

`sudo apt install vite npm`

- Running app

`git clone https://github.com/MathiewMay/tux-mod-manager`

`cd tux-mod-manager`

`npm run dev`
