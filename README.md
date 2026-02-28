# Virtual-machines-archlinux
```
yay -S qemu-full libvirt virt-manager dnsmasq iptables-nft bridge-utils
```

```
sudo systemctl enable virtqemud.socket
sudo systemctl enable virtnetworkd.socket
sudo systemctl enable virtnodedevd.socket
sudo systemctl enable virtnwfilterd.socket
sudo systemctl enable virtsecretd.socket
sudo systemctl enable virtsecretd.socket
sudo systemctl enable virtstoraged.socket
```
