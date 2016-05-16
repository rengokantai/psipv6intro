#### psipv6intro
#####1
######2
using powershell
```
Get-NetIPAddress -InterfaceIndex 4
```
######4 IPv6 fundamentals
```
Get-NetIPAddress -InterfaceIndex 4 -AddressFamily IPv6 |ft ifIndex, IPAddress -AutoSize ifIndex IPAddress
```

#####2
######1 Address space
2^128 address=3.4*10^38
ipv4=2^32
#####3
a nibble is 4 bits  
a hextet is 16 bits  

