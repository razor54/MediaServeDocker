# MediaServeDocker
Docker media server with radarr, sonarr, jackett and plex

## Startup
* Create a new .env file with the following variables:
```
VPN_CONFIG=./vpn/vpn.ovpn
MOUNT_POINT=
VPN_PASSWORD=
VPN_USERNAME=
```
Note: For VPN config file, please find the ovpn file from your VPN provider, or else get NordVPN account and just add the environment variables for vpn username and password

* Might want to create this folder structure:
- `Deluge/`
- `deluge-config/`
- `jackett/`
- `plex/`
- `plex-config/`
- `radarr-config/`
- `sonarr/`
- `transmission/`
- `vpn/`

* Run `docker compose up` and everything should start