# Assign static IPs for virtual servers

## definitions

x.x.x.1     - default gateway
x.x.x.100   - host ip

x.x.x.11

## NAT networks
### common
10.0.2.0/24

### consul
10.2.0.0/24

## host-only interface
eth1
10.42.0.100/255.255.0.0

Enabling DHCP on this server, in range 10.40.2.200-10.40.2.250  

Any new servers gets to this  range and will be bootstrapped

### bootstrup pseudonet
10.42.42.1-10.42.42.250


