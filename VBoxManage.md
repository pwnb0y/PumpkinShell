# Create a NAT Network using VBoxManage utility

## Check existing NAT Networks
```
 VBoxManage list natnetworks
```
## Create a NAT Network
```
VBoxManage natnetwork add --netname NATNetwork101 --network "192.168.10.0/24" --enable
```
## Check the NAT Network
```
VBoxManage list natnetworks
```
`NetworkName:    NATNetwork101
IP:             192.168.10.1 
Network:        192.168.10.0/24
IPv6 Enabled:   No
IPv6 Prefix:    fd17:625c:f037:2::/64
DHCP Enabled:   Yes     
Enabled:        Yes        
`
## Enable or Disable DHCP for the network (on or off)
```
 VBoxManage natnetwork modify --netname NATNetwork101 --dhcp on
```
## Start the NAT service
```
VBoxManage natnetwork start --netname NATNetwork101
```
## Enable Port Forwarding to connect to the VMs
 Forward localhost port 1022 to 192.168.10.5:22 (eg: SSH)
```
 VBoxManage natnetwork modify --netname NATNetwork101 --port-forward-4 "ssh:tcp:[]:1022:[192.168.10.5]:22"
```
## If you need to remove the NAT Network
```
VBoxManage natnetwork remove --netname NATNetwork101
```
## Assign NAT Network to a VM
```
VBoxManage modifyvm UbuntuVM --nic1 NATNetwork101
```
