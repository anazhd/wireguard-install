# Wireguard
This is a fork of complexorganization wireguard installation script with support of Armbian, changed subnet to 10.0.0.0 and option to use custom domain for endpoint connection. 

###### Todo:
- custom subnet
- better resolv.conf management
- out of the box better distro support (not working on some newer distro)

###### Tested on:
- Ubuntu 18.04 x64
- Armbian (rockchip/rock64)

### Wireguard Server Install
sudo/root required
```
wget https://raw.githubusercontent.com/anazhd/wireguard-install/master/wireguard-server.sh
bash wireguard-server.sh
```
