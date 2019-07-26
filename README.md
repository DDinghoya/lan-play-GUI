
# Lan Play GUI
![Image of Lan Play GUI](https://github.com/takashi1kun/lan-play-GUI/raw/master/titleImage.png)  
  
This is a Visual Interface based on electron for lan play, it also doubles as a server list manager, you can add servers, edit server, remove them, change the order and launch lan-play with any of the servers you have on your list.  
It also tells you if the server is online, and if it is online, also can tell you the users playing on it on that moment, and the version of lan-play the server is using.
## Instructions
### Windows  
1.- Download the executable of lan-play adequate for your system (64/32 bits)  
2.- Download the RAR with lan play GUI adequate for your system (64/32 bits)  
3.- Uncompress the RAR wherever you want  
4.- Put the executable of lan-play without renaming it in the same folder as lan play GUI  
5.- if you have done this well you should have lan-play-GUI.exe and the executable of lan play on the same folder  
6.- Execute lan-play-GUI.exe as administrator  
7.- ???  
8.- Profit  
PS.- When you Connect to a server a cmd windows would pop up, you just select your interface and it would work, when you want to change server close that command line window and click Connect to Server on a new server
### Linux
1.- Download lan-play-linux  
2.- Download lan-play-GUI-linux  
3.- Put lan-play-linux in home  
4.- sudo setcap 'CAP_NET_RAW+eip CAP_NET_ADMIN+eip' lan-play-linux  
5.- chmod 777 lan-play-linux  
6.- Execute lan-play-gui-linux  
7.- ???  
8.- Profit  
PS.- When you Connect to a server a terminal would pop up, you just select your interface and it would work, when you want to change server close that terminal and click Connect to Server on a new server

#### Arch Linux  
1.- Download [switch-lan-play](https://aur.archlinux.org/packages/switch-lan-play/) from the AUR  
2.- Download ```lan-play-GUI-linux``` from releases  
3.- Open ```lan-play-GUI``` and go to settings  
4.- On the _Main Configuration_ page, browse to ```/usr/local/bin/lan-play```  
4a.- If ```lan-play``` isn't there, run ```pacman -Ql switch-lan-play``` in a terminal to find your directory  
5.- ???  
6.- Profit  
  
## Credits

### Main Credits:

#### Main dev: takashi1kun (Red1Reaper on GBAtemp, and Aitor in Discord, and lyoko1 on reddit).
#### Thanks to Svahnen for helping with the linux porting, linux testing, and helping me whit the project in general.
#### Thanks to Space as Space provided me whit the function to ping
#### Thanks to the devs of lan-play for making it in general, as this is just a Visual Interface for launching it
____________
### Credits for resources/tools:
#### Node:
https://nodejs.org/

#### Electron:
https://electronjs.org/

#### Electron-builder:
https://www.electron.build/

#### Bootstrap:
https://getbootstrap.com/

#### Jquery:
https://jquery.com/

#### popper.js:
https://popper.js.org/

#### fontawesome:
https://fontawesome.com

#### bootstrap-checkbox:
https://vsn4ik.github.io/bootstrap-checkbox/

#### flag-icon-css:
http://flag-icon-css.lip.is/

#### Icon:
https://www.shareicon.net/server-gear-623151

#### q:  
https://github.com/kriskowal/q
