# Assetto-Server-Files
The files in shutotest consist of all the files used to run my server. I'll explain to the best of my knowledge to what the important files are and how it works.
###
## Main Configuration
Located in *shutotest\cfg*
###
**The *entry_list.ini* and *server_cfg.ini* is the main files that are require for the server to run properly.** <br>
The first one tells what cars are going to be used and the second configures how the server and world is set up. AssettoServer.exe allows the use of *extra_cfg.yml* to use custom configurations that are documented on the website. *csp_extra_options.ini* Allows *Custom Shaders Patch* to use extra configuration files and resources for the server.
###
## Cars and Tracks Configuration
Located in *shutotest\content*

Cars Folder: <br>
###
**This is where all the car's data is stored. No actual .fbx models are in here.** <br>
When a player connect to the server via content manager, the server request the *data.acd* stored on the player's computer to the corresponding car. The server has IgnoreConfigurationErrors - Missing CarCheckSums, if this is set to false, players with modified data won't be let in or kicked when they enter.
###

Tracks Folder: <br>
###
**Just like the Cars Folder, it has the track data but instead of *data.acd* it's .ini files.** <br>
If you notice there is a csp folder, this is for *Custom Shaders Patch* and also for allowing traffic to be added in. The ai folder contains fast_lane.aip for ai car pathing.
###
## Plugins 
Located in *shutotest\plugins*
###
This is where community plugins are installed


# Websites: 
###
Custom Shaders Patch Configurations <br>
https://github.com/ac-custom-shaders-patch/acc-extension-config
###
Custom Shaders Patch <br>
https://acstuff.ru/patch/
###
AssettoServer.exe <br>
https://assettoserver.org
