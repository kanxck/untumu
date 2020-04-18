# install ubuntu on termux

# install cmd termux
pkg update -y

pkg install wget -y

pkg install proot -y

wget https://raw.githubusercontent.com/kanxck/untumu/master/ubuntu.sh && bash ubuntu.sh

# run_ubuntu
./startubuntu.sh

# cmd ubuntu
apt update

apt install wget -y

apt install php -y

apt install git
