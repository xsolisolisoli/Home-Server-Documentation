# Home-Server-Documentation
Documentation for my home network

I've started self-hosting given my propensity for buying up small linux PCs, here is what I've accomplished so far:
Network Diagram: Note, I screenshotted this off an online service, needs to be redone
![Server Diagram 1](https://github.com/xsolisolisoli/Home-Server-Documentation/assets/69920747/052ffb3f-911c-49fe-a439-81ca7a095377)

Home Server:
-Desktop PC (Windows 10, custom built PC)
-2x Dell Wyse 5070 Thin Client
-1x Network switch
-2tb USB File storage

Currently, only one thin client is in active use. In the future, I would like to use a kubernetes cluster to simplify having multiple changes.
Thin clients are controlled via SSH in desktop. Password authentication is disabled, SSH keys are enabled.
Docker images are deployed, configurated & managed via CLI or accessed via web browser.


Currently I have deployed:
- a vpn enabled Docker service for routing specific applications securely
- a jellyfin server deployed via Docker for media digitization
- a portainer instance to manage any and all Docker instances
