1. add `chris` user, `useradd -m -g users -s /etc/bash chris`
1. set password for `chris` user, `passwd chris`
1. add desktop public ssh key to pi's `.ssh/authorized_users`
1. make `andy` user
1. make `superchris` user
1. remove `alarm` user
---
# System users
1. create system users group if not already there `groupadd service-account`
  * `grep '^service-account' /etc/group` to check if a group already exists
2. add system user account `useradd -r -s /usr/bin/nologin username -g service-account`

1. web, shield, windows
