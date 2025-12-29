git clone https://github.com/RENAN029/jq.git

cd jq

chmod +x b.sh

./b.sh

sudo pacman -Scc pnpm github-cli

sudo pacman -S python-pip rustup

sudo pacman -Syu $(pacman -Qnq) 

sudo pacman -Rsnu $(pacman -Qdtq) 
