Before installing virtual environment
make sure u install ubuntu in termux first 


Looks like Python 3.12 actually Works!! U have to create a virtual environment so here is the guide:


To run ComfyUI in a separate environment on Termux with Python 3.10.11, follow these steps:


---

1. Install Required Packages

First, ensure your Termux is updated and install necessary packages:

apt update -y && apt upgrade -y
apt install python3-full git ffmpeg


---

2. Install & Setup a Virtual Environment

Create and activate a virtual environment:

python3 -m venv comfyui-env
source comfyui-env/bin/activate







First copy all then paste in termux


pkg update -y && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu22/ubuntu22.sh -O ubuntu22.sh && chmod +x ubuntu22.sh && bash ubuntu22.sh

Second copy all then paste in termux

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-pip python3-venv python-is-python3 -y && apt dist-upgrade -y && apt install wget && apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y && apt-get install google-perftools &&
apt install libgoogle-perftools-dev && pip install moviepy==1.0.3 && apt-get install -y build-essential python3-dev python3-setuptools make cmake && apt-get install -y ffmpeg libavcodec-dev libavfilter-dev libavformat-dev libavutil-dev && pip install accelerate


Install Decord

Third

git clone --recursive https://github.com/dmlc/decord


apt-get install libavformat-dev libavfilter-dev libavdevice-dev ffmpeg 


3.5>PRESS ENTER ON make!

cd decord
mkdir build && cd build
cmake .. -DUSE_CUDA=0 -DCMAKE_BUILD_TYPE=Release
make



Forth

cd ../python
python3 setup.py install --user

Six

python


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













