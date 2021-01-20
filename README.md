# Archiso with zfs

* archzfs repo added
* zfs-linux installed


Build image:

```
mkarchiso -v -w work -o out .
```

Record it on a device:

```
sudo dd if=out/archlinux_zfs-DATE-x86_64.iso of=/dev/sdevice status=progress
```
