# change_OSX_mac_address
## generate a random MAC address
`
% openssl rand -hex 6 | sed 's/\(..\)/\1:/g; s/.$//'
6b:ff:11:4d:d8:3f
`
## change MAC address
`
% sudo ifconfig en4 ether 6b:ff:11:4d:d8:3f
`
