# Access ext4 on mac

- Paragon
  -  works, but is paid
- ex4fuse
  - read only
  - writes will corrupt disk
- fuse-ext2
  - works for ext2, 3 & 4
  - write access is experimental
- Linux VM
  - Pass drive through to VM
  - Safest way to access
  - Risk free read & write access

### Install ext4fuse
```
ports install ext4fuse
```
### Mount device
```
diskutil list
ext4fuse $DEVICE $MOUNTPOINT
```
