# Animatediff-Android-Termux
I've figured out how to install animatediff official on android XD I almost Gave Up!!





First copy all then paste in termux


pkg update && pkg upgrade -y && termux-setup-storage && pkg install wget -y && pkg install git -y && pkg install proot -y && cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh


Second copy all then paste in termux

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y && apt dist-upgrade -y && apt install wget && apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y && apt-get install google-perftools &&
apt install libgoogle-perftools-dev && pip install moviepy==1.0.3 && apt-get install -y build-essential python3-dev python3-setuptools make cmake && apt-get install -y ffmpeg libavcodec-dev libavfilter-dev libavformat-dev libavutil-dev


Install Decord

Third

git clone --recursive https://github.com/dmlc/decord

Forth copy all at once then paste in termux press enter also when u see. make

cd decord
mkdir build && cd build
cmake .. -DUSE_CUDA=0 -DCMAKE_BUILD_TYPE=Release
make

Fith copy all at once then paste in termux press enter

cmake .. -DUSE_CUDA=OFF -DCMAKE_BUILD_TYPE=Release

Six

git clone https://github.com/guoyww/AnimateDiff.git

Seventh

cd AnimateDiff

Eight

pip install torch

Ninth

pip install accelerate

Tenth

pip install -r requirements.txt

To Start AnimateDiff 

python -u app.py


















