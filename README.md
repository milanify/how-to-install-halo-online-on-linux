# how-to-install-halo-online-on-linux

<p align="center">
  <img src="https://raw.githubusercontent.com/milan102/how-to-install-halo-online-on-linux/master/images/halo-3-master-chief-150x150.jpg" height="150" width="150">
</p>

## Installation
Install Lutris https://lutris.net/downloads/

Install Wine
- Ubuntu https://wiki.winehq.org/Ubuntu
- Debian https://wiki.winehq.org/Debian
- Fedora https://wiki.winehq.org/Fedora

[Download the patched zip file containing all game assets](https://github.com/)
(*Note: This particular file contains additional maps that aren't typically included. You can alternatively find a smaller zip file by going to https://www.reddit.com/r/ms23downloads/ or searching for a patched (eldewrito 0.6.0) cert_ms23 archive on the web*)

Navigate to https://lutris.net/games/halo-online/

Click "Install" (as shown in the bottom right of this screenshot)

<p align="center">
  <img src="https://raw.githubusercontent.com/milan102/how-to-install-halo-online-on-linux/master/images/screenshot1.png">
</p>

Follow the Lutris prompts, and select the downloaded zip file when asked to

Once installed, right click the game in Lutris and select "Configure"

<p align="center">
  <img src="https://raw.githubusercontent.com/milan102/how-to-install-halo-online-on-linux/master/images/screenshot2.png">
</p>

Go to the "Runner options" tab and change the DXVK version to 1.2.3, then click "Save"

<p align="center">
  <img src="https://raw.githubusercontent.com/milan102/how-to-install-halo-online-on-linux/master/images/screenshot3.png">
</p>

Congratulations, you can now launch the game by clicking on it in Lutris. ***You must change your in-game settings for Video to NOT use High settings***, otherwise the game will be unplayable due a texture bug. Despite this fix, you may encounter black textures anyway in certain parts of certain maps. 

