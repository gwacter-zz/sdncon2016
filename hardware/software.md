Here is the software that is installed on the controller and hosts.

```
=== openflow
ryu          controllerOnly
faucet       controllerOnly

=== terminal multiplexers
tmux         hostsAndController
screen       hostsAndController

=== serial connections
cu           controllerOnly
minicom      controllerOnly

=== traffic generators and manipulators
nmap (nping) hostsOnly
python-scapy hostsOnly
iperf        hostsOnly
d-itg        hostsOnly

=== traffic sniffing
tcpdump      hostsAndController

=== general
vim          hostsAndController
git          hostsAndController
python-yaml  controllerOnly
libpcap-dev  hostsOnly
ipaddr       controllerOnly
python-dev   hostsAndController
python-pip   hostsAndController
```
