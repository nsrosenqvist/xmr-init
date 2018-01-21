# xmr-init
*Upstart compatible init scripts for the Monero daemon and [miner](https://github.com/tpruvot/cpuminer-multi)*

## Install
Put the files in /etc/init.d/ and run the following to configure the service to start on system startup:

**Monero Node**
```
sudo chmod a+x /etc/init.d/monerod && sudo update-rc.d monerod defaults
```

**Monero [Miner](https://github.com/tpruvot/cpuminer-multi)**
```
sudo chmod a+x /etc/init.d/xmr-miner && sudo update-rc.d xmr-miner defaults
```

## Configure
Both scripts have variables in the top section of the file to configure your setup.
