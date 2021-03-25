# [Spigotserver](https://hub.docker.com/r/itzg/minecraft-server)
This docker image provides a Minecraft Server that will automatically download the latest stable version at startup.
Currently it is configured for spigot version 1.16.5, to change this, adjust the .env file.


## Setup
1. Copy example env file:
    - ```cp .env.example .env```
2. Configure the .env file
    - ```vim .env``` or ```nano .env```
3. Create data folder (for plugins, world, spigot configs etc)
    - ```mkdir data```