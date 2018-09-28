[connection]
id=hassos-network
uuid=72111c67-4a5d-4d5c-925e-f8ee26efb3c3
type=802-11-wireless

[802-11-wireless]
mode=infrastructure
ssid=GWlan

[802-11-wireless-security]
auth-alg=open
key-mgmt=wpa-psk
psk=17122715

[ipv4]
method=manual
address1=192.168.0.15/24,192.168.0.1
dns=148.122.16.253;148.122.164.253;

[ipv6]
addr-gen-mode=stable-privacy
method=auto