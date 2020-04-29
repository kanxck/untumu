# install ubuntu on termux

install termux https://play.google.com/store/apps/details?id=com.termux

# install cmd termux
pkg update -y && pkg install wget -y && pkg install proot -y && wget https://raw.githubusercontent.com/kanxck/untumu/master/ubuntu.sh && bash ubuntu.sh

# run_ubuntu
./startubuntu.sh

# cmd ubuntu
apt update && apt upgrade -y && apt install nano -y && apt install wget -y
