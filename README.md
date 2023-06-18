# ironfish
wget -q -O ironfish.sh https://api.nodes.guru/ironfish.sh && chmod +x ironfish.sh && ./ironfish.sh
. $HOME/.bashrc
. $HOME/.bash_profile
ironfish wallet:create $IRONFISH_WALLET
ironfish wallet:use $IRONFISH_WALLET
