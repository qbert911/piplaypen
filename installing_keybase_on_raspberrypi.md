# Install keybase on Raspberry Pi (tested on 3b+)
---
## Install golang manually by downloading deb from website
```here```

## Set two path export commands in .bashrc
```here```

## Set swapfile to large and on
```
sudo dphys-swapfile swapoff
sudo nano /etc/dphys-swapfile 
```
modify the variable CONF_SWAPSIZE to read: ```CONF_SWAPSIZE=1024```
```
sudo dphys-swapfile setup 
sudo dphys-swapfile swapon
```

## Git clone/Build/Install keybase  
[Source](https://yakczar.com/blog/installing-keybase-on-chromebook/ "keybase blog")
```sh
mkdir -p $GOPATH/src/github.com/keybase
cd $GOPATH/src/github.com/keybase
git clone --depth 1 https://github.com/keybase/client
go install -v -tags production github.com/keybase/client/go/keybase
```

## Create service folders and manually copy keybase .service files
```here```

## Edit service files to point to compiled binary
```here```

## Set swapfile to small and off
```here```
