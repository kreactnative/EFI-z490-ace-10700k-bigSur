# z490-ace-10700k-bigSur EFI
```
hdid -nomount "[..path dmg...]/macOS_11.dmg"
diskutil list
diskutil unmountDisk /dev/diskX
Restore from diskX to diskX
sudo dd if=/dev/diskX of=/dev/diskX bs=32m
```