# Mining RIG


## Desempenho

### GPUs
https://www.betterhash.net/mining/
https://whattomine.com/


https://technical.city/en/video/Radeon-RX-5500-XT-vs-Radeon-RX-580

### Pools

https://miningpoolstats.stream/

### Cripto moedas

https://coinmarketcap.com/



## DAG Size

https://minerstat.com/dag-size-calculator

https://rvn.2miners.com/




## Monero CPU

https://minexmr.com/dashboard

https://miningpoolstats.stream/monero

Intel(R) Core(TM) i3-7100 CPU @ 3.90GHz 

https://www.betterhash.net/Intel(R)-Core(TM)-i3-7100-CPU-@-3.90GHz-mining-profitability-642377.html

https://www.cryptocompare.com/mining/calculator/xmr?HashingPower=636&HashingUnit=KH%2Fs&PowerConsumption=130&CostPerkWh=0.19&MiningPoolFee=1


## Ethermine

Se der pau de GPU, remover overclock reiniciar, observar e reaplicar o overclock

### Pool
Ethermine

### Miner
Phoenix Miner


### Trust Wallet
https://ethermine.org/miners/52CD91F835bA2D6EE5Ea2F179178A450a74785c7/dashboard


### Binance Wallet
https://ethermine.org/miners/382d2ed5ea31d0465fa86f714b8d9503d8788857/dashboard


## Ravencoin

https://ravencoin.flypool.org

### 💴 A MELHOR POOL PARA MINERAR RAVENCOIN - Como minerar ravencoin no Windows Mini RIG de mineração

https://www.youtube.com/watch?v=Ywg-wxVIxXM

### Best pools

* https://miningpoolstats.stream/ravencoin
* https://ravencoin.flypool.org/

### Pool

https://rvn.2miners.com/

### Wallet

https://ravencoin.org/wallet/

### Miners

For Nvidia GPU's we recommend GMiner (Guide - How to use GMiner) or T-Rex (Guide - How to use T-Rex).
For AMD GPU's we recommend NBMiner or TeamRedMiner.
Quick start - Download ready to go version of the GPU Miner (archive password - 2miners).

https://coinmarketcap.com/

## Hive OS

https://github.com/nicehash/excavator/tree/master/examples/single_oc_cards

https://hiveos.farm/getting_started-start_oc/

https://hiveos.farm/install/

https://medium.com/hiveon/getting-started-with-hive-os-worker-installation-and-setup-159c8779e082

```
unxz --keep hiveos-0.6-190-stable@210108.img.xz

dd if=hiveos-0.6-190-stable@210108.img of=/dev/sdb bs=10M status=progress
```


https://hiveos.farm/guides-security/
user
cisco


### POWER SUPPLY 

https://outervision.com/power-supply-calculator

https://miningpoolstats.stream/ethereum


52.75 Mhs
Overclock profile

0
450
50
135


### Resize 

https://forum.hiveos.farm/t/resize-filesystem-to-fill-disk/3769

## LM sensors

https://www.cyberciti.biz/faq/how-to-find-fan-speed-in-linux-for-cpu-and-gpu/

sudo apt-get install lm-sensors

sudo sensors-detect


## Monitoring NVIDIA

https://itsfoss.com/monitor-cpu-gpu-temp-linux/

watch -n 2 nvidia-smi


## Ubuntu and NVIDIA

https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-ubuntu-18-04-bionic-beaver-linux

https://forums.linuxmint.com/viewtopic.php?t=281922


## HiveOS

https://hiveos.farm/install/#howto-image

After the image is flashed you will discover newly created drive in your system where you will be able to precreate rig.conf with worker's ID and password or FARM_HASH. Please find rig-config-example.txt on HIVE drive. The ready rig.conf file can be downloaded from the rig’s settings.

Advanced Unix (Linux or Mac) users can use dd to write RAW image to disk. Something like dd if=hive-xxx.img of=/dev/sdb bs=10M status=progress. But be careful finding out output disk "of", use fdisk -l to list your partitions.

SSDs are much more reliable and advised to use in production environments. If you want to prolong the life of your USB flash drive please run logs-off after installation.



## Binance


https://miningpoolstats.stream/ethereum

https://pool.binance.com/en/workers


https://www.binance.com/en/support/faq/9bd21a9536d74d1fb65c83f8e60ded93

### Wallet

https://ethermine.org


### BMINER

https://www.bminer.me/releases/


```
./bminer -uri ethproxy://<MINER-NAME>.rig1worker1@ethash.poolbinance.com:8888
```




## Ethermine

https://phoenixminer.org/


https://linuxconfig.org/ethereum-mining-on-ubuntu-18-04-and-debian

```
sudo add-apt-repository ppa:ethereum/ethereum
sudo apt update
```

Install it

```
sudo apt install ethereum
```

https://github.com/ethereum/mist/releases

```
sudo dpkg -i Ethereum-Wallet-linux64-0-11-1.deb
sudo apt-get install -f
```
## Net HiveOS


netconf-set --dhcp=no --test=0 --address=192.168.20.20/24 --gateway=192.168.20.10 --dns=8.8.8.8now


netconf-set --dhcp=yes


## CoreCTRL

### Install it in Ubuntu 18

Add PPA 

```
sudo add-apt-repository ppa:ernstp/mesarc
sudo apt-get update
```

Installing it

```
sudo apt install corectrl -y
```


### Useful links

[Core CTRL](https://gitlab.com/corectrl/corectrl)
[PPA Package](https://launchpad.net/~ernstp/+archive/ubuntu/mesarc)