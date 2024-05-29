#Install Dependencies

sudo apt-get install binutils cmake dpkg-dev g++ gcc libssl-dev git libx11-dev \ libxext-dev libxft-dev libxpm-dev python3 libtbb-dev libgif-dev 

#Updating the Library Cache

sudo ldconfig

#Download root
$ wget https://root.cern/download/root_v6.32.00.Linux-almalinux9.4-x86_64-gcc11.4.tar.gz
$ tar -xzvf root_v6.32.00.Linux-almalinux9.4-x86_64-gcc11.4.tar.gz

#Build root

cd root

cd bin

cd source thisroot.sh

root

export DISPLAY=\"localhost:0\"
