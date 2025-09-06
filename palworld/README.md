# Palworld
These eggs are made for users that want modded dedicated servers.

## Default Ports
| Port            | Default |
| --------------- | ------- |
| Game            | 8211    |
| RESTAPI         | 8212    |
| RCON            | 25575   |

## Server Requirements
> [Official Requirements](https://docs.palworldgame.com/getting-started/requirements)
- **CPU:**: 4+ Cores (AMD or Intel)
- **RAM:**: 16-48GB of R
- **Storage:**: 6GB~

## Known Issues
**Why won't my Proton server start?**
 This is due to some weird issue with Proton and UE4SS. Just change the **Docker Image Configuration** to `ghcr.io/parkervcp/steamcmd:proton_8` in the admin startup tab of your server.