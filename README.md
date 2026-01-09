# Radio-Mesh-Project
TESTING HARDWARE: 
- https://www.digikey.ca/en/products/detail/stmicroelectronics/NUCLEO-L452RE-P/7380300
- https://www.amazon.ca/ECSiNG-Wireless-Transceiver-Compatible-Arduinos/dp/B0DS1V77BC?source=ps-sl-shoppingads-lpcontext&psc=1&smid=A11Y908TWHSOTO



OSI NETWORK LAYERS
  PHY:  CC1101 @ 433MHz ISM Band
  L2: AX.25 Framing (+ some HDLC protocols) on nodes and linux AX.25 stack on Raspberry Pi
  L3: for digipeaters and nodes: AX.25 addresses + digipeater path for multi-hopping. For Raspberry Pi server: IPv4 over AX.25
  L4: AX.25 connected mode between Raspberry Pi and nodes. TCP over IP over AX.25 for Raspberry Pi server for HTTP
  L5: TCP and AX.25
  L6: implicitly handled in code on Raspberry Pi server (e.g. data encryption, etc..)
  L7: BBS over AX.25 and HTTP (web UI/API) on Raspberry Pi (over TCP/IP which is run over AX.25)


HARDWARE: 
- TI CC1101 Sub-GHz Transceiver IC
- Raspberry Pi server
- 

NETWORKING: 

WEB: 
-

FUTURE: 
- add network sniffer
- add 
