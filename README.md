# Docker-Compose-Files
This repository contains several examples of Docker images using docker-compose.
As an administrator of a server, I myself use many of the images that are contained here.

## Introduction
Each folder contains only one piece of software.
I use [Traefik](#traefik) as a reverse proxy for web interfaces, so all docker-compose files are configured for Traefik.

Before use, the .env.example must be copied to .env and configured.


## Software (Sorted alphabetically)

Name | Source/Link | Date
------------ | ------------- | -------------
[Bitwarden_rs](#bitwarden_rs) | [Docker-Hub](https://hub.docker.com/r/bitwardenrs/server) , [GitHub](https://github.com/dani-garcia/bitwarden_rs) | 08.03.2021
[Endlessh](#endlessh) | [Docker-Hub](https://hub.docker.com/r/harshavardhanj/endlessh) | 14.03.2021
[LOK_RestAPI (WIP)](#lok) | [GitHub](https://github.com/Laufen-oder-Kaufen/LOK_RestAPI) | 11.03.2021
[MySQL & phpmyadmin](#mysql) | [MySQL Docker-Hub](https://hub.docker.com/_/mysql) , [phpmyadmin Docker-Hub](https://hub.docker.com/r/phpmyadmin/phpmyadmin/) | 08.03.2021
[Spigot Server](#spigot) | [Docker-Hub](https://hub.docker.com/r/itzg/minecraft-server) , [GitHub](https://github.com/itzg/docker-minecraft-server) | 14.03.2021
[Statping](#statping) | [Docker-Hub](https://hub.docker.com/r/hunterlong/statping) , [GitHub](https://github.com/statping/statping) | 18.03.2021
[Traefik](#traefik) | [Docker-Hub](https://hub.docker.com/_/traefik) , [Docs](https://doc.traefik.io/traefik/) | 04.03.2021
[Whoami](#whoami) | [Docker-Hub](https://hub.docker.com/r/containous/whoami) , [GitHub](https://github.com/traefik/whoami) | 04.03.2021
[Wordpress](#wordpress) | [Docker-Hub](https://hub.docker.com/_/wordpress) | 28.03.2021


## About contained software


<br><br>
<a name="bitwarden_rs"></a>
<img align="left" width="320" src="https://i.imgur.com/lcoBQEZ.png">
## [Bitwarden rs](https://github.com/deanomus/docker-compose-files/tree/main/bitwarden)
Bitwarden RS is an unofficial implementation of the Bitwarden password manager
written in Rust. It uses significantly fewer resources and only requires a single
docker container to run it.
It also allows the use of the normally paid features like organisations and reports.


<br><br>
<a name="endlessh"></a>
<img align="right" width="320" src="https://i2.wp.com/www.linuxlinks.com/wp-content/uploads/2017/10/FTP-Client-Software.jpg?fit=700%2C209&ssl=1&resize=350%2C200">
## [Endlessh](https://github.com/deanomus/docker-compose-files/tree/main/endlessh)
Endlessh is an SSH tarpit [that very slowly sends an endless, random SSH banner](https://nullprogram.com/blog/2019/03/22/).
It keeps SSH clients locked up for hours or even days at a time.
The purpose is to put your real SSH server on another port and then let the script kiddies
get stuck in this tarpit instead of bothering a real server.


<br><br>
<a name="lok"></a>
<img align="left" width="320" src="https://www.szut.de/cms/upload/00_allgemein/startseite/wir_sind_europa.jpg">
## [LOK RestAPI (WIP)](https://github.com/deanomus/docker-compose-files/tree/main/LOK_RestAPI)
This is an education project from Europaschule Schulzentrum Utbremen and is still **W**ORK-**I**N-**P**ROGRESS.


<br><br>
<a name="mysql"></a>
<img align="right" width="320" src="https://d1.awsstatic.com/asset-repository/products/amazon-rds/1024px-MySQL.ff87215b43fd7292af172e2a5d9b844217262571.png">
## [MySQL & phpmyadmin](https://github.com/deanomus/docker-compose-files/tree/main/mysql_phpmyadmin)
MySQL Server with phpmyadmin as web interface to manage databases.
Find more information [here](https://github.com/deanomus/docker-compose-files/tree/main/mysql_phpmyadmin/README.md).


<br><br>
<a name="spigot"></a>
<img align="left" width="320" src="https://i.ytimg.com/vi/-wm5IS7GWwM/maxresdefault.jpg">
## Spigot [Game](https://github.com/deanomus/docker-compose-files/tree/main/spigotserver/gameserver) & [Test](https://github.com/deanomus/docker-compose-files/tree/main/spigotserver/testserver) Server
This docker image provides a Minecraft Server with Spigot that will
automatically download the latest stable version at startup.
Spigot is an open-source Java project that lets users run their own
Minecraft server and add plugins to extend the possibilities of their server.


<br><br>
<a name="statping"></a>
<img align="right" width="320" src="https://image.winudf.com/v2/image1/Y29tLnN0YXRwaW5nX3NjcmVlbl84XzE1NTUxMTM3MjVfMDgz/screen-8.jpg?fakeurl=1&type=.jpg">
## [Statping](https://github.com/deanomus/docker-compose-files/tree/main/statping)
Statping is a easy to use Status Page for your websites and applications.
Statping will automatically fetch the application and render a beautiful
status page with tons of features for you to build an even better status page.
This Status Page generator allows you to use MySQL, Postgres, or SQLite on multiple operating systems.


<br><br>
<a name="traefik"></a>
<img align="left" width="320" src="https://doc.traefik.io/traefik/assets/img/traefik-architecture.png">
[Traefik](https://github.com/deanomus/docker-compose-files/tree/main/traefik)
Traefik is a reverse proxy (like [NGINX Reverse Proxy](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/))
and configures itself almost completely automatically.
It also automatically creates and renews SSL certificates.
The advantage over the NGINX is that the Traefik can be controlled via Docker.


<br><br>
<a name="whoami"></a>
<img align="right" width="320" src="https://user-images.githubusercontent.com/26530975/27141029-64954410-5127-11e7-87a0-83a87157cfff.png">
## [Whoami](https://github.com/deanomus/docker-compose-files/tree/main/whoami)
Whoami is a tiny Go webserver that prints os information and HTTP request to output


<br><br>
<a name="wordpress"></a>
<img align="left" width="320" src="https://www.pachnerweb.at/pachnerweb/wp-content/uploads/2019/06/WordPress-logotype-alternative.png">
## [Wordpress](https://github.com/deanomus/docker-compose-files/tree/main/wordpress)
WordPress is open source software that you can use to create a beautiful website, blog, or app.
On a slightly more technical level, WordPress is an open source content management system
that is licensed under the GPLv2.
This means that anyone can use or change the WordPress software for free.