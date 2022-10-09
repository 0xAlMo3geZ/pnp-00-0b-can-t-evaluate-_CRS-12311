# Warning: pnp 00:0b: can't evaluate _CRS: 12311, dev/sda1: clean, ... files, ... blocks

Finally
the solution to the immortal kernel boot error messages:
![alt text](https://pbs.twimg.com/media/FenxXEUXwAA9KGg?format=jpg&name=4096x4096)

if you wanna just have a beautiful blank screen before your login screen
follow these steps 👇

** Ubuntu 22.04 **

![alt text](https://pbs.twimg.com/media/Fen1oraXwAAKbSF?format=png&name=900x900)

1- sudo nano /etc/default/grub
2- change these two lines to :
GRUB_CMDLINE_LINUX_DEFAULT="loglevel=0"
GRUB_CMDLINE_LINUX="console=tty12"
3- sudo update-grub
4- Reboot

and there ya have it!

don't forget to show some 🥰 by staring some of the repositories! 🫶🫡
