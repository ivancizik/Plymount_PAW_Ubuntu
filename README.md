# Linux Plymount PAW Ubuntu Theme

Simple plymount theme for OS X fans with Ubuntu logo

[![PAW Ubuntu Theme](/preview.png?raw=true)](https://www.youtube.com/watch?v=yq5VnWi8YEE)

How to install:

~~~~
sudo cp -R Plymount_PAW_Ubuntu/ /lib/plymouth/themes/

sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/Plymount_PAW_Ubuntu/paw-ubuntu.plymouth 100

sudo update-alternatives --config default.plymouth
~~~~

chose Paw-OSX from list and 
~~~~
sudo update-initramfs -u
~~~~


