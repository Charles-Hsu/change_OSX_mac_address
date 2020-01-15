# change_OSX_mac_address
`
% openssl rand -hex 6 | sed 's/\(..\)/\1:/g; s/.$//'
6b:ff:11:4d:d8:3f
`
`
% sudo ifconfig en4 ether 6b:ff:11:4d:d8:3f
`
