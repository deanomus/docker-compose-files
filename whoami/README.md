# [Whoami](https://hub.docker.com/r/containous/whoami)
Whoami is a tiny Go webserver that prints os information and HTTP request to output

## Setup
1. Copy example env file:
   - ```cp .env.example .env```
2. Configure the .env file
   - ```vim .env``` or ```nano .env```
3. Create ACME File for lets-encrypt to save certificates:
   - ```touch config/ACME/acme.json```
4. Set Permissions:
   - ```chmod 600 config/ACME/acme.json```
