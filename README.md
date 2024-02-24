<h2>Newtowkring conversioon and exampl</h2>
Subnetting is changing the subnetmask to suite host and network needs
IP address always needed broadcast(last) and subnet address so -2 on USABLE addresses
the ending side writing for addressing tells newtwork bits ex /24 = 24 networking bit means a sube net mask of 11111111.11111111.11111111.00000000 = a subnet of 255.255.255.0 ... 0 = host bits
2^ of host bits = address available
Private address
192.168.0.1
255.255.255.0
increment will always be the last network bit or 2^ amount of host bits
CONVERSION TABLE
128 64  32 16 8  4 2 1 for conversion
256 128 64 32 16 8 4 2 for converting hosts needed to bits need from subnetmask

Decimal subnet 11111111.11111111.11111111.00000000
Decimal IP 11000000.10101000.00000000.00000001

SUBNETTING Example: Need 3 networks
14.2.0.22
255.255.0.0

oG 11111111.11111111.00000000.00000000 
Needed 11111111.11111111.11000000.00000000 
which gives 14.2.0.22 /16
new subnet 255.255.192.0
increment 64
2^14 = 16,384 IP addresses
New ranges are
14.2.0.0-14.2.63.0
14.2.64.0-14.2.127.0
14.2.128.0-14.2.191.0
14.2.192.0-14.2.255.0





