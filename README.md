# Docker-Compose-Files
This repository contains several examples of Docker images using docker-compose.
As an administrator of a server, I myself use many of the images that are contained here.

## Introduction
Each folder contains only one piece of software.
I use Traefik as a reverse proxy for web interfaces, so all docker-compose files are configured for Traefik.

Before use, the .env.example must be copied to .env and configured.


##### Software (Sorted alphabetically)

Name | Source/Link | Date
------------ | ------------- | -------------
[Bitwarden_rs](https://github.com/deanomus/docker-compose-files/tree/main/bitwarden) | [Docker-Hub](https://hub.docker.com/r/bitwardenrs/server) , [GitHub](https://github.com/dani-garcia/bitwarden_rs) | 08.03.2021
[Endlessh](https://github.com/deanomus/docker-compose-files/tree/main/endlessh) | [Docker-Hub](https://hub.docker.com/r/harshavardhanj/endlessh) | 14.03.2021
[LOK_RestAPI (WIP)](https://github.com/deanomus/docker-compose-files/tree/main/LOK_RestAPI) | [GitHub](https://github.com/Laufen-oder-Kaufen/LOK_RestAPI) | 11.03.2021
[MySQL & phpmyadmin](https://github.com/deanomus/docker-compose-files/tree/main/mysql_phpmyadmin) | [MySQL Docker-Hub](https://hub.docker.com/_/mysql) , [phpmyadmin Docker-Hub](https://hub.docker.com/r/phpmyadmin/phpmyadmin/) | 08.03.2021
Spigot [Game](https://github.com/deanomus/docker-compose-files/tree/main/spigotserver/gameserver) & [Test](https://github.com/deanomus/docker-compose-files/tree/main/spigotserver/testserver) Server| [Docker-Hub](https://hub.docker.com/r/itzg/minecraft-server) , [GitHub](https://github.com/itzg/docker-minecraft-server) | 14.03.2021
[Statping](https://github.com/deanomus/docker-compose-files/tree/main/statping) | [Docker-Hub](https://hub.docker.com/r/hunterlong/statping) , [GitHub](https://github.com/statping/statping) | 18.03.2021
[Traefik](https://github.com/deanomus/docker-compose-files/tree/main/traefik) | [Docker-Hub](https://hub.docker.com/_/traefik) , [Docs](https://doc.traefik.io/traefik/) | 04.03.2021
[Whoami](https://github.com/deanomus/docker-compose-files/tree/main/whoami) | [Docker-Hub](https://hub.docker.com/r/containous/whoami) , [GitHub](https://github.com/traefik/whoami) | 04.03.2021

