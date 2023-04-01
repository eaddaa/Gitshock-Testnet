# Sunucu güncelleyelim.

```
sudo apt-get update && sudo apt-get upgrade -y
```

# Gerekli kütüphaneler.

```
sudo apt install build-essential -y
```
```
sudo apt install micro -y
```
```
sudo apt-get install software-properties-common
```
```
sudo add-apt-repository -y ppa:ethereum/ethereum
```
```
sudo apt install ethereum -y
```
```
sudo apt install jq -y
```

# Go yükleyin.

```
wget https://go.dev/dl/go1.18.2.linux-amd64.tar.gz
sudo rm -rf /usr/local/go && sudo tar -C /usr/local -xzf go1.18.2.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
go install github.com/protolambda/eth2-testnet-genesis@latest
go install github.com/protolambda/eth2-val-tools@latest
```


# nvm yükleyin.

```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```
```
export NVM_DIR="$HOME/.nvm"
```
```
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```
```
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```
```
nvm install --lts
```
```
nvm use --lts
```




