# [Endlessh](https://hub.docker.com/r/harshavardhanj/endlessh)
Endlessh is an SSH tarpit [that very slowly sends an endless, random SSH banner](https://nullprogram.com/blog/2019/03/22/).
It keeps SSH clients locked up for hours or even days at a time.
The purpose is to put your real SSH server on another port and then let the script kiddies
get stuck in this tarpit instead of bothering a real server.


## Setup
1. Copy example env file:
    - ```cp .env.example .env```
2. Configure the .env file
    - ```vim .env``` or ```nano .env```
