# NS-3 Wifi acces point with multiple nodes simulation

This is a network simulation meant to be run on the NS-3 simulator: https://www.nsnam.org/

## Network toplogy
There is a wifi access point that is connected to a server via ethernet. This 
simulation examines what happens as more and more nodes attatch themselves to 
the same access point (a new node attaches itself every second until there are
30 nodes on the AP). The number of wifi or csma nodes can be increased up to 250.
TCP is used on the transport layer.
