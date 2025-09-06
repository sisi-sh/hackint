## hackintosh opencore usb folder

attempting opencore for sonoma 15

system:
- ryzen 5959x
- asus x570-i strix
- rx 6900xt
- gskill 64gb ddr4 3600mhz (running at 3500mhz due to stability issues)

wd 1tb boot nvme /dev/nvme1n1:
- 4gb efi part running systemd-boot 
- 1 100gb arch part 
- 350gb unalloc for this
- 1 windows part in that order) 

other drives
+ 980 pro 2tb storage /dev/nvme0n1 (i.e. in primary slot, boot in seconary slot)
+ sata sdd /dev/sda 

a lot of usbs, 3 hubs (2 monitors with hubs hooked + 1 kvm switch)
focusrite 2i2 + mainboard jack populated
