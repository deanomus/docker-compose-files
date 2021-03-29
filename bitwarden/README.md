# [Bitwarden_rs](https://hub.docker.com/r/bitwardenrs/server)
Bitwarden RS is an unofficial implementation of the Bitwarden password manager
written in Rust. It uses significantly fewer resources and only requires a single
docker container to run it.
It also allows the use of the normally paid features like organisations and reports.


## What is Bitwarden?
Bitwarden is a free and open-source password management service that stores
sensitive information such as website credentials in an encrypted vault.
The Bitwarden platform offers a variety of client applications including a web interface,
desktop applications, browser extensions, mobile apps, and a CLI.
Bitwarden offers a cloud-hosted service as well as the ability to deploy
the solution on-premises.


## ⚠️**IMPORTANT**⚠️
If you using this server, please report any bugs or suggestions to [bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs) directly,
regardless of whatever clients you are using (mobile, desktop, browser...).
DO NOT use the official support channels.


## Setup
1. Copy example env file:
   - ```cp .env.example .env```
2. Configure the .env file:
   - ```vim .env``` or ```nano .env```
3. Create data folder
   - ```mkdir data```
