# Unifi-network-application

This docker compose configuration helps generating a new unifi network application install with the external mongo-db database service.
#### Docker images
Unifi network application is based on the new Linuxserver.io and official Mongo docker images.
 
[linuxserver/unifi-network-application](https://hub.docker.com/r/linuxserver/unifi-network-application)
 
[mongo:4.0.28](https://hub.docker.com/_/mongo)

## Installation
1. Clone repo to your docker server in desired folder:
```git clone https://github.com/Mysticsilent/unifi-network-application```
2. Change the variables in **'docker-compose.yaml'** and **'init-mongo.js'** making sure they match in both files.
3. Start the stack:
```docker compose up -d```
or if you use older docker-compose version:
```docker-compose up -d```
4. Open up the web interface:
https://hostname:8443 and follow the wizard.

Enjoy!
