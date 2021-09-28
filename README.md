# minetermux
mine on termux





Termux commands:

 apt get && apt update -y
 lscpu
 pkg install git
 pkg install cmake
 pkg install proot
 proot-distro install ubuntu-20.04
 proot-distro login ubuntu-20.04
 apt-get update && apt-get upgrade -y
 apt-get install libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential git nano
 git clone --single-branch -b ARM https://github.com/monkins1010/ccminer.git
 cd ccminer
 chmod +x build.sh && chmod +x configure.sh && chmod +x autogen.sh
 ./build.sh

run config: (just edit with your own details)
./ccminer -a verus -o stratum+tcp://ap.luckpool.net:3956 -u YOUR_WALLET_ADDRESS.Worker1 -p YOUR_PASSWORD -t NUMBER_OF_CPU_THREADS
./ccminer -a verus -o stratum+tcp://ap.luckpool.net:3956 -u RHuJkbWF4tv2g8Kq2FNbuTKVA7KyUJ4BLL.SHELL5 -p x --cpu 2
