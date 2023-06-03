# skeletonbased1
# Steps for setting:
# Step 1 : Install python3.8 , and pip
apt-get update

apt-get upgrade

add-apt-repository ppa:deadsnakes/ppa -y

apt install software-properties-common

apt-get install python3.8 python3-pip

sudo apt install 3.8-dev

sudo apt install python3.8-distutils

apt-get install build-essential checkinstall

apt install wget

wget https://bootstrap.pypa.io/get-pip.py

sudo python3.8 get-pip.py

python3.8 get-pip.py

pip install scikit-learn

python ./torchlight/setup.py install

pip install torchvision
# Step 3 : Change the default python to python3.8
compgen -c python | sort -u

update-alternatives --install /usr/bin/python python /usr/bin/python3.8 3

# Step 2 : Install relevant module for dev
apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev libffi-dev zlib1g-dev
# Step 3 : Install tensorboardX 
pip install tensorboardX

