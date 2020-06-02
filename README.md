# autonomous_car_sim_kickstarter_2020
This repository contains all the files and instructions to get your own autonomous car simulator up and running on your Linux machine using Unity, Udacity's car simulator and PyTorch.

Pre-requisites: python3.6+, pip, venv (recommended)

## Installations
**1. Unity**
- We need a specific version of Unity to run the Udacity simulator (namely 5.5.1.xf1)
- First, download the .deb file from [here](https://beta.unity3d.com/download/f5287bef00ff/public_download.html)
- The next step is to execute the following command to install necessary dependencies: ```sudo apt install gconf-service lib32gcc1 lib32stdc++6 libc6-i386 libgconf-2-4 npm libpq5```
- In case of errors, run ```sudo apt --fix-broken install```
- Now, we can begin installation of Unity. (Note that the path to your .deb file may vary) ```sudo dpkg -i ~/Downloads/unity-editor_amd64-5.5.1xf1Linux.deb```

**2. Udacity Car Simulator**
- Download the .zip file for the Linux version, which can be found [here](https://s3-us-west-1.amazonaws.com/udacity-selfdrivingcar/Term1-Sim/term1-simulator-linux.zip)
- After unzipping the file, add executable permissions to the file (Note that path to executable may vary): ```sudo chmod +x ./beta_simulator_linux/beta_simulator.x86_64```
- Now, you will be able to run the simulator.

**3. Clone this repository**
- Now, clone this repository: ```git clone https://github.com/SiddAjriY2Jaccount/autonomous_car_sim_kickstarter_2020```
- Now we install all the requirements and dependencies to train a model using PyTorch as well as link the model's results to the Simulator: ```pip install -r requirements.txt ```  
- Unzip the file ```prebuilt_selfdriving.tar.gz```
- It will give you the 'data' directory wherein an example training set of images are provided.
- If you want to gather your own data, then run the Simulator in 'Training Mode' and select 'data' directory to store the recorded images and log file.
