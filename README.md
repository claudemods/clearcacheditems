simple service menu
clear cached items on ubuntu or debian plasma 5 or 6
simple script to clear cached items simply right click in dolphin
click clear cached items and enter your password
the scripts will do the rest
all commands used are given below
or you can check the scripts file your self in a text editor application such as kate

How to install:
install the desktop file from context store in dolphin only
download the scripts.zip from this website
https://github.com/claudemods/clearcacheditems/releases/download/final/scripts.zip

and unpack to the follow locations depending on your plasma version as its needed for this menu to work

For kde5 move the downloaded scripts.sh file file to ~/.local/share/kservices5/ServiceMenus (create the folder if it's missing)
Also use right click on the file > Properties > Permissions > And mark the checkbox next to the text "Is executable".
and use $ chmod +x ./scripts.sh

For kde6 move the downloaded scripts.sh
to ~/.local/share/kio/servicemenus/ (create the folder if it's missing)
Also use right click on the file > Properties > Permissions > And mark the checkbox next to the text "Is executable".
and use $ chmod +x ./scripts.sh


commands used in this menu are
sudo apt-get clean
sudo rm -rf /var/cache/
sudo rm -rf /tmp
sudo rm -rf /root/.cache/
sudo rm -rf /home/lancaster/.local/share/Trash
sudo rm -rf /root/.local/share/Trash/

support me on paypal with link https://paypal.me/claudemods?country.x=GB&local

