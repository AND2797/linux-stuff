1. Run CMD as Administrator
2. Type DISKPART
3. list disk
4. select disk 1 (if your usb drive mine was 1)
5. clean
6. create partition primary
7. active
8. Choose a format:
   1. FAT32 is the standard for USBs: format fs=fat32 quick
   2. NTFS is more modern, but isn't as widely supported: format fs=ntfs quick
9. assign
10. exit
11. exit

#https://superuser.com/questions/558399/normal-usb-stick-from-bootable-usb
