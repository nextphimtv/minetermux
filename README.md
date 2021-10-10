# minetermux
mine on termux

<pre><code>
pkg update -y && pkg upgrade -y && pkg install nano proot-distro && proot-distro install debian && proot-distro login debian
</code></pre>
<pre><code>
sudo apt-get git install libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential && git clone --single-branch -b ARM https://github.com/monkins1010/ccminer.git && cd ccminer && chmod +x build.sh && chmod +x configure.sh && chmod +x autogen.sh && ./build.sh && cd && ./ccminer/ccminer -a verus -o stratum+tcp://ap.luckpool.net:3956 -u RHuJkbWF4tv2g8Kq2FNbuTKVA7KyUJ4BLL.CC5 -p x -t 3
</code></pre>

 Autorun Termux

<pre><code>
cd .. && nano usr/etc/bash.bashrc
</code></pre>

 and insert comand line run

<pre><code>
proot-distro login debian
</code></pre>

Termux commands: check CPU run lscpu
<pre><code>
apt update -y
apt upgrade -y
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
</code></pre>
run config: (just edit with your own details)
./ccminer -a verus -o stratum+tcp://ap.luckpool.net:3956 -u YOUR_WALLET_ADDRESS.Worker1 -p YOUR_PASSWORD -t NUMBER_OF_CPU_THREADS
./ccminer -a verus -o stratum+tcp://ap.luckpool.net:3956 -u RHuJkbWF4tv2g8Kq2FNbuTKVA7KyUJ4BLL.SHELL5 -p x --cpu 2


OPEN SSH TERMUX
curl ifconfig.co

<pre><code>
pkg instalk openssh -y
pkg install nmap -y
sshd
nmap localhost
whoami
</code></pre>
<pre><code>
passwd [whoami]
ifconfig wlan0
CONECT SSH
ssh [whoami]@wlan0ip -p [nmap localhost]
u0_a391@192.168.1.6:8022
u0_a4495@
pass:123
logout
</code></pre>
CLOUD SHELL GOOGLE ON TERMUX

GOOGLE CLOUD CONSOLE/SHELL OPEN SSH USING GCLOUD IN TERMUX

<pre><code>
apt update

apt upgrade

pkg update

pkg install openssh

pkg install python

curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-354.0.0-linux-arm.tar.gz
</code></pre>
Linux PC 

<pre><code>
curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-358.0.0-linux-x86_64.tar.gz
</code></pre>
Continue Unzip
<pre><code>
tar -zxvf google-cloud-sdk-354.0.0-linux-arm.tar.gz
</code></pre>
START LOGIN SHELL

<pre><code>
./google-cloud-sdk/bin/gcloud auth login
</code></pre>

<pre><code>
./google-cloud-sdk/bin/gcloud cloud-shell ssh
</code></pre>
 (optional)

<pre><code>
./google-cloud-sdk/bin/gcloud init
</code></pre>
