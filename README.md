<h2>Newtowrking conversioon and example and learning</h2>
<p>Subnetting is changing the subnetmask to suite host and network needs</p>
<p>IP address always needed broadcast(last) and subnet address so -2 on USABLE addresses</p>
<p>the ending side writing for addressing tells newtwork bits ex /24 = 24 networking bit means a sube net mask of 11111111.11111111.11111111.00000000 = a subnet of 255.255.255.0 ... 0 = host bits</p>
<p>2^ of host bits = address available</p>
<p>Private address</p>
<p>192.168.0.1</p>
<p>255.255.255.0</p>
<p>increment will always be the last network bit or 2^ amount of host bits</p>
<p>CONVERSION TABLE</p>
<p>128 64  32 16 8  4 2 1 for conversion</p>
<p>256 128 64 32 16 8 4 2 for converting hosts needed to bits need from subnetmask</p>

<p>Decimal subnet 11111111.11111111.11111111.00000000</p>
<p>Decimal IP 11000000.10101000.00000000.00000001</p>

<p>SUBNETTING Example: Need 3 networks</p>
<p>14.2.0.22</p>
<p>255.255.0.0</p>

<p>oG 11111111.11111111.00000000.00000000</p>
<p>Needed 11111111.11111111.11000000.00000000 </p>
<p>which gives 14.2.0.22 /16</p>
<p>new subnet 255.255.192.0</p>
<p>increment 64</p>
<p>2^14 = 16,384 IP addresses</p>
<p>New ranges are</p>
<p>14.2.0.0-14.2.63.0</p>
<p>14.2.64.0-14.2.127.0</p>
<p>14.2.128.0-14.2.191.0</p>
<p>14.2.192.0-14.2.255.0</p>

<p>VLSM</p>
<p>same process except start with highest network requirements and go backwards resuming from previously made network range</p>



