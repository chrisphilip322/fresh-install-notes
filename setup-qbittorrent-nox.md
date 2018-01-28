1. install `qbittorrent-nox`
1. [setup `web` service account](./setup-users.md)
1. qbittorrent-nox requires the running user to have a home directory
  1. `mkdir /home/web -m 700`
  2. `chown web:service-account /home/web`
2. [install(copy) the custom systemd service](./configs/etc/systemd/system/qbittorrent-nox.service)
3. enable/start `qbittorrent-nox.service`
4. configure the server through the web frontend `ip:8080`, admin:adminadmin
