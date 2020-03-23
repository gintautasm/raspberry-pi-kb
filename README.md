# raspberry-pi-kb

if wireless mouse is slow, open **cmdline.txt**

    sudo nano /boot/cmdline.txt

add at the end of the line  **usbhid.mousepoll=0** or **1**

    console=serial0,115200 console=tty1 root=PARTUUID=d9b3f436-02 rootfstype=ext4 elevator=deadline fsck.repair=yes rootwait quiet splash plymouth.ignore-serial-consoles usbhid.mousepoll=0

