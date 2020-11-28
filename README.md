# wireguard-pihole-docker
Wireguard plus pihole in docker-compose. Deploys with usual `docker-compose up -d` etc. Once up, provides VPN with built in pihole adblocker - any device that connects to the VPN will have ads removed from the embedded PiHole instance, which is providing DNS services to VPN clients.

Replace the `SERVERURL` and `PEERS` env vars on the wireguard container with ones for your environment.