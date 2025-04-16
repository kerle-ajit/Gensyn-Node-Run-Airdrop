# Gensyn-x-Earn-By-Abhi

## Requirements :-

* Min 16 GB RAM
* RTX 3090/4090 GPU ( Optional )

You Can Run Through 
* Own Device If Compatible 
* VPS ( Watch Video )

## COMMANDS 👇🏻

```bash
apt update && apt install -y sudo
```

```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof && curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && sudo apt update && sudo apt install -y yarn
```
  
```bash
curl -sSL https://raw.githubusercontent.com/ABHIEBA/Gensyn/main/node.sh | bash
```

```bash
screen -S gensyn
```
```bash
cd $HOME && rm -rf gensyn-testnet && git clone https://github.com/zunxbt/gensyn-testnet.git && chmod +x gensyn-testnet/gensyn.sh && ./gensyn-testnet/gensyn.sh
```
* Use `Ctrl + A` and then press `D`
```
[ -f backup.sh ] && rm backup.sh; curl -sSL -O https://raw.githubusercontent.com/AbhiEBA/gensyn1/main/backup.sh && chmod +x backup.sh && ./backup.sh
```

## Explorer : https://t.me/gensyntrackbot
## Bot : https://gensyn-testnet.explorer.alchemy.com
## Dashboard: https://dashboard.gensyn.ai/
