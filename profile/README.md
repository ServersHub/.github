# ArkServerAPI Information:

<a href="https://gameservershub.com/forums/resources/ark-server-api.12/">ArkServerAPI</a> is open source software you can install directly into windows versions of <a href="https://store.steampowered.com/app/346110/ARK_Survival_Evolved/">Ark Survival Evolved</a> this software allows you to manage and create plugins to enhance your video game servers. <a href="https://gameservershub.com/forums/resources/ark-server-api.12/">ArkServerAPI</a> is currently run and supported by <a href="https://gameservershub.com/forums">GameServersHub</a>.<br><br>

<a href="https://gameservershub.com/forums">GameServersHub</a> intends to keep this project 100% open-sourced and accessible to the public; we fully intend to ensure that the project is maintained and supported for future releases of <a href="https://store.steampowered.com/app/346110/ARK_Survival_Evolved/">Ark Survival Evolved</a> game updates.<br>

## Direct Download:

<b>Website:</b> https://gameservershub.com/forums/resources/ark-server-api.12/<br>
<b>Direct API Files Download:</b> https://github.com/ServersHub/ArkApiUpdater/releases/latest/download/ArkApiUpdater_1.0.zip<br>
<b>Plugins:</b> https://gameservershub.com/forums/resources/categories/ark-survival-evolved.2/<br><br>

## Requirements:

- The API will only work on: Windows 7 and above or Windows Server 2008 and above operating systems.<br>
- You need to install "<b>Microsoft Visual C++ 2019 Redistributable Package</b>" for the API to load correctly.<br><br>

## API Installation Steps:

- Download the resource by clicking the "<b>Download</b>" button.<br>
- Unzip the contents of the "<b>.ZIP</b>" file into "<b>ARK\ShooterGame\Binaries\Win64</b>"<br>
- You can now start your ark survival evolved game server, the ArkApi automatic installer will download and unpack any further required files into the server directory and keep them up to date.<br><br>

## Automatic Update:

- ArkApi will automatically check for updates and apply any pending updates to the framework itself on each game server boot.<br>
- The automatic update process will also install the Permissions plugin, if it is missing, since it's considered a dependency for other plugins.<br><br>

## Plugin Installation Steps:

- Find a plugin you want to download inside the website's "<b>Resources</b>" section.<br>
- Unzip the contents of the "<b>.ZIP</b>" file into "<b>ARK\ShooterGame\Binaries\Win64\ArkApi\Plugins</b>"<br>
- You may now edit the "<b>.JSON</b>" files located inside the plugin folder you just installed, or you may now start the server.<br><br>

## Product Notes:

- Inside "<b>ShooterGame/Win64/auto_update_config.json</b>" you can opt into the usage of beta builds or toggle the auto update feature on or off<br>
- The API will generate log files in this location "<b>ShooterGame/Win64/logs/ArkApi.log</b>"<br>
- The API has built-in crash logs, which can be located inside "<b>ShooterGame/Saved/Logs/</b>"<br>
- The API will generate an auto update cache folder in this location "<b>ShooterGame/Win64/ArkApi_AutoUpdate</b>" this folder will keep a cache of the current executable version, this is required for checking for updates
- The API has no connection or affiliation with "<b>Wildcard Studios</b>" directly, nor should it ever be considered that "<b>Wildcard Studios</b>" endorses the API. The API is an open-source tool the - community can use to run plugins for their video game servers, similar to how "<b>Minecraft / Rust</b>" and other video games have plugin systems where you can improve the overall health and gameplay of your community servers.<br>
- Please note when installing plugins into the "<b>ARK\ShooterGame\Binaries\Win64\ArkApi\Plugins</b>" folder, you must make sure the "<b>.DLL</b>" plugin name matches the same "<b>folder</b>" name. Changing the folder name to something different or unique will prevent the "<b>.DLL</b>" from reading the folder and preventing it from starting.<br>
- You may join our <a href="https://gameservershub.com/forums/pages/discord/">discord server</a> if you have any questions/feedback or want general support regarding ArkServerAPI.
