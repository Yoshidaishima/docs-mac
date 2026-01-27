# Use macfuse + ext4fuse
### Install
```
ports install ext4fuse
```
### Mount device
```
diskutil list
ext4fuse $DEVICE $MOUNTPOINT
```
