```
cd $HOME
wget -O zenrockd.zip https://github.com/Zenrock-Foundation/zrchain/releases/download/v5.11.4/zenrockd.zip
unzip zenrockd.zip
rm zenrockd.zip
chmod +x $HOME/zenrockd
mkdir -p $HOME/.zrchain/cosmovisor/upgrades/v5rev5/bin
sudo mv $HOME/zenrockd $HOME/.zrchain/cosmovisor/upgrades/v5rev5/bin/zenrockd
```
