# autonomous_car_sim_kickstarter_2020
This repository contains all the files and instructions to get your own autonomous car simulator up and running using Unity, Udacity's car simulator and pytorch.

## Installations
1. Unity
- We need a specific version of Unity to run the Udacity simulator (namely 5.5.1.xf1)
- First, download the .deb file from [here](https://beta.unity3d.com/download/f5287bef00ff/public_download.html)
- The next step is to execute the following command to install necessary dependencies: ```sudo apt install gconf-service lib32gcc1 lib32stdc++6 libc6-i386 libgconf-2-4 npm libpq5```
- In case of errors, run ```sudo apt --fix-broken install```
- Now, we can begin installation of Unity. (Note that the path to your .deb file may vary) ```sudo dpkg -i ~/Downloads/unity-editor_amd64-5.5.1xf1Linux.deb```
