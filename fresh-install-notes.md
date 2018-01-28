1. ssh in as alarm/alarm
1. escalate with `su root` password: root
1. add `chris` user, `useradd -m -g users -s /etc/bash chris`
1. set password for `chris` user, `passwd chris`
1. add desktop public ssh key to pi's `.ssh/authorized_users`
1. update system `pacman -Syu`
1. install `sudo` with `pacman -S sudo`
1. (EDIT WITH (visudo)) add `chris` to sudoers by adding `chris ALL=(ALL) ALL` line to `/etc/sudoers`
1. [configure external drives](./setup_external_drives.md)
1. [configure SMB](./setup_smb.md)
1. [configure plex drive shares](./setup-plex-shares.md)
1. [configure qBittorrent-nox](./setup-qbittorrent-nox.md)
