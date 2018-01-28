1. make mount location, `mkdir /mnt/1external`
2. find devices to mount, `lsblk`
3. mount devices, `mount /dev/sda1 /mnt/1external`
4. [add devices to `/etc/fstab`](./configs/etc/fstab)
  1. get device UUID from `ls -l /dev/disk/by-uuid`
  2. add line in `/etc/fstab` `UUID=?   /mnt/1external  ext4    rw  0   0`
