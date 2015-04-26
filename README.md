# zfsonlinux systemd units

If you want to run zfsonlinux on systemd on ubuntu 15.04 then this is for you.

```
$ git clone https://github.com/paulczar/zfs-systemd.git
$ cd zfs-systemd
$ cp zfs* /etc/systemd/system
$ sudo systemctl enable zfs.target
$ sudo reboot
```

