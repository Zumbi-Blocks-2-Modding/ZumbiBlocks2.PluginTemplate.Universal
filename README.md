# Zumbi Blocks 2 Plugin Template (Universal)

A modding template for **Zumbi Blocks 2**, powered by [BepInEx](https://github.com/BepInEx/BepInEx).

## Features

- Compatible with [Steam](https://store.steampowered.com/app/1941780/Zumbi_Blocks_2_Open_Alpha/) and [itch.io](https://adrianks47.itch.io/zumbi-blocks-2) builds of the game
- Automatically installs your plugins
- Validates game and mod loader installation

## Requirements

- Zumbi Blocks 2
- [BepInEx 5](https://github.com/BepInEx/BepInEx/releases)
- [.NET 6.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) or [newer](https://dotnet.microsoft.com/en-us/download)

## Quick Start

**New to modding? Try the [Steam-specific template](https://github.com/Zumbi-Blocks-2-Modding/ZumbiBlocks2.PluginTemplate.Steam). It allows you to build the plugin with a single click.**

This guide assumes you already have Zumbi Blocks 2 installed, complete with the BepInEx mod loader.  
If you have not yet installed BepInEx, follow the [official guide](https://docs.bepinex.dev/articles/user_guide/installation/index.html) and return when done.

1. [Create a new repository based on this template](https://github.com/Zumbi-Blocks-2-Modding/ZumbiBlocks2.PluginTemplate.Universal/generate).
2. Using your IDE, CLI, or Git-oriented desktop program, [clone your repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).
3. Open your local repository with your IDE. If prompted to trust the project, accept.

Next up, you'll need to add Zumbi Blocks 2 as a reference, to be able to access its internals.

1. Right-click the solution in the Explorer and add a Reference.
2. Navigate to your Zumbi Blocks 2 folder, and open `/ZumbiBlocks2_Data/Managed/`.
3. Select `Assembly-CSharp.dll` and confirm the reference. 

You're now free to customize the project!

1. Open the project settings and rename `ExamplePlugin` to your new mod's name.
2. Fill out the plugin fields with your own details.
3. Change the log message to one of your own.
4. [Add a license](https://choosealicense.com/)! This is very important in the open source community.

When done customizing your plugin base, click on Build.  
Your plugin will automatically be installed. Open the game and test it out!

## Community

If you ever get stuck or need assistance getting started, feel free to join the official [Zumbi Blocks 2 Discord Server](https://discord.gg/eCWaHR9).  
There's a modding channel where you can share and discuss everything related to mods.
