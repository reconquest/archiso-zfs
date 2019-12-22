# Archiso with zfs

* archzfs repo added
* zfs-linux installed
* fixed https://bugs.archlinux.org/task/58868
* fixed https://bugs.archlinux.org/task/59137

# Usage

Build image:

```
sudo ./build.sh -v
```

Record it on a device:

```
sudo dd if=out/archlinux-DATE-x86_64.iso of=/dev/sdevice status=progress
```
