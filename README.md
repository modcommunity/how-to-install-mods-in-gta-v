A guide on how to **download** and **install** mods in **Grand Theft Auto V** (focused on singleplayer).

[**View Guide On TMC (Recommended Due To Better Formatting)**](https://blog.moddingcommunity.com/how-to-install-mods-in-gta-v/)

Modding is extremely powerful in Grand Theft Auto V (5) and gaming in general. GTA V mods are community-made modifications that allow you to alter gameplay. Mods can range from allowing you to fly/run incredibly fast to improving the game quality itself via better models, textures, or code.

While GTA V mods are allowed in singleplayer, they are not allowed in GTA V Online. Therefore, please only use these mods in singleplayer. If you are caught modding GTA V Online, it is considered cheating and you'll likely **get banned** unless if you know what you're doing.

Since each mod usually comes with its own installation instructions, I am going to focus on frameworks and libraries that most mods utilize along with Mod Managers. In most cases, you need to copy the mod files to your GTA V's main folder on your computer's file system. On Steam, this is typically in your Steam folder at **steamapps/common/Grand Theft Auto V/**.

## Script Hook V
[Script Hook V](https://www.dev-c.com/gtav/scripthookv/) is a library that allows users to create and use mods via GTA V's native script functions in custom ASI plugins. It is the most popular library from what I've found for GTA V mods. It also automatically closes GTA V if detected in GTA V Online mode to prevent accidentally launching it with mods enabled.

You may use the following steps to install Script Hook V.

1. Download Script Hook V from [here](http://www.dev-c.com/gtav/scripthookv/) and extract it using ZIP.
2. Copy the **ScriptHookV.dll** file to your GTA V's main folder (i.e. where the **GTA5.exe** file is located).
3. In order to load ASI plugins, you need to have ASI loader installed. You may download it separately or use the latest version that comes with Script Hook V (**dinput8.dll**). You must delete previous ASI loader version (**dsound.dll**) if you have it installed.
4. Script Hook V also includes a sample ASI plugin; Native Trainer. This allows you to open a menu in-game which comes with many features and game options such as increasing your walk/run speed, jump height, spawning vehicles/objects, changing weather, and more! If you want to use this trainer, make sure to also copy the **NativeTrainer.asi** file to your GTA V folder!

## Lua Plugin For Script Hook V
Lua is a powerful programming and scripting language and the Lua Plugin for Script Hook V allows users to create mods using Lua.

To install, please perform the following steps.

1. Download Lua Plugin from [here](https://www.gta5-mods.com/tools/lua-plugin-for-script-hook-v).
2. Extract the downloaded file using ZIP.
3. Copy the **LUA.asi** file and **scripts/** folder to your GTA V directory.

You'll notice some Lua plugins in the **scripts/addins/**. This is the folder you'll install other user's mods made with Lua in. You may delete the default Lua plugins in that folder if you don't plan on using them.

## GTA V Mod Manager
[GTA V Mod Manager](https://www.gta5-mods.com/tools/gtav-mod-manager) is the most popular mod manager in GTA V for Windows. You may be able to run this on Linux using something such as Wine, but I haven't tested this personally. Mod managers make it easier for users to install mods. Instead of manually copying files to your GTA V folder, the GTA V Mod Manager will handle this for you.

After downloading and extracting the downloaded file, you should be able to open the Mod manager application since it's an executable. You will need to accept an agreement and also specify your GTA V folder if it doesn't automatically detect the path.

If you have any questions or feedback regarding this guide, please reply to its forum topic [here](https://forum.moddingcommunity.com/t/how-to-install-mods-in-gta-v-2025/510)! This guide will be worked and improved on over time.

Join our [Discord server](https://discord.moddingcommunity.com)!