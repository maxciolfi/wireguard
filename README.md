# Installation
### OLD Kernel <5.6
```
add-apt-repository ppa:wireguard/wireguard
apt update
apt install wireguard-dkms wireguard-tools linux-headers-$(uname -r)
```
### Download and change folder
```
cd ~
git clone https://github.com/maxciolfi/wireguard.git

cd wireguard
```
### Run install
```
./install.sh
```
### Not wg0 run
```
systemctl enable --now systemd-resolved
```



# Uninstallation

### Change to dotfiles folder
```
cd ~/wireguard
```

### Run uninstaller
```
./uninstall.sh
```
