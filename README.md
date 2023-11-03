# Fextify purple (very WIP)
<img src='assets\example.png'>
A simple text editor written in Tauri, inspired by Obsidian.

<br>

This is a **prototype**, not a fully polished version.

# How to run?
1. Run the `fextify.exe` included in this folder. (or run `npm run tauri build -- --target x86_64-pc-windows-msvc` to compile)
4. Press `CTRL` + `P` to open the command pallet. It will give you a good idea of what's going on. Otherwise, explore!

# Known bugs
1. Changing the title of any file to a duplicate causes a panic & `config.json` to mess up. For the time being, avoid naming files the same. In case this happens, nuke `config.json` by emptying all arrays & restart the software.
