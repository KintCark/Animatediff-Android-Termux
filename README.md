# Animatediff-Android-Termux
I've figured out how to install animatediff official on android XD I almost Gave Up!!





First copy all then paste in termux


pkg update && pkg upgrade -y && termux-setup-storage && pkg install wget -y && pkg install git -y && pkg install proot -y && cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh


Second copy all then paste in termux

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y && apt dist-upgrade -y && apt install wget && apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y && apt-get install google-perftools &&
apt install libgoogle-perftools-dev && pip install moviepy==1.0.3 && apt-get install -y build-essential python3-dev python3-setuptools make cmake && apt-get install -y ffmpeg libavcodec-dev libavfilter-dev libavformat-dev libavutil-dev && pip install accelerate


Install Decord

Third

git clone --recursive https://github.com/dmlc/decord



3.5>PRESS ENTER ON make!

cd decord
mkdir build && cd build
cmake .. -DUSE_CUDA=0 -DCMAKE_BUILD_TYPE=Release
make



Forth

cd

Fith

cd decord

cd python

python setup.py install --user

Six

cd

then

git clone https://github.com/guoyww/AnimateDiff.git

Seventh



cd AnimateDiff

'Fix' the issue with Python running in PRoot 

export ANDROID_DATA=anything

Eight

pip install torch

pip install diffusers[torch]==0.11.1

Ninth

pip install accelerate

Tenth

pip install -r requirements.txt

To Start AnimateDiff 

python -u app.py




in order to use this repo u have to navigate to the animatediff folder then open app.py file in a text editor then change line 40 pretraind_sd to Jiali/stable-diffusion-1.5 then save.













