## mamecraft server

MameCraft is paperMC Minecraft server that has hosted in 'Mame' Discord server, built on Docker
And this is public repository for 'MameCraft' server for version 1.21.4 with pre-prepared plugins, includes discord-auth, Japanese-localisation support, and message sync with discord channel.
You can join this server from my [Discord server](https://discord.gg/nAmPrUzVsN), or If you want to try this template, just clone it to try.

## Getting started
To start, you need to find paperMC's website and download paper-1.21.4-66.jar.(beta version) and install all required plugins.

### Required plugins
To avoid any trouble that has related with licensing of plugins, you have to download these plugins manually.
Config files are already set, so just add these plugin .jar files to start.
 - bluemap-5.5-paper
 - DiscordSRV-build-1.29.0
 - floodgate-spigot
 - Geyser-Spigot
 - Lunachat (for Japanese Romaji typing support)

### Run server

just type in `docker compose up -d` to start(Docker environment required).