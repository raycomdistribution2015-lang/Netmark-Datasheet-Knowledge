# RUTX08

Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // RUTX08


## HARDWARE

FRONT VIEW


BACK VIEW


POWER SOCKET PINOUT



**Power** **Reset** **LAN Ethernet**



**WAN LEDs**

|socket button ports|Col2|Col3|Col4|Col5|Col6|Col7|
|---|---|---|---|---|---|---|
||||||||
||||||||
||||||||
||||||||
||||||||



**WAN Ethernet**
**port**


**USB port**



**Power**
**LED**



**LAN LEDs**



**Grounding**
**screw**



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


## FEATURES

**ETHERNET**


WAN


LAN


**NETWORK**


Routing


Network protocols


VoIP passthrough support



DATASHEET // RUTX08


1 x WAN port (can be configured as LAN) 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards,
supports auto MDI/MDIX crossover


3 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
crossover


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP)


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, FTP, SMTP, SSL v3, TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP, Telnet,
SNMP, MQTT, Wake on LAN (WOL), DLNA


H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets



Connection monitoring Ping Reboot, Wget reboot, Periodic Reboot, LCP and ICMP for link inspection



Firewall


DHCP


QoS / Smart Queue
Management (SQM)


DDNS



Port forwards, traffic rules, custom rules


Static and dynamic IP allocation, DHCP Relay, Relayd


Traffic priority queuing by source/destination, service, protocol or port


Supported >25 service providers, others can be configured manually



Network backup VRRP



Hotspot


SSHFS


**SECURITY**


Authentication


Firewall



Internal/external Radius server, captive portal, built in customizable landing page


Possibility to mount remote file system via SSH protocol


Pre-shared key, digital certificates, X.509 certificates


Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T



DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
Attack prevention
SYN-RST, X-mas, NULL flags, FIN scan attacks)



VLAN


WEB filter



Port and tag based VLAN separation


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only



Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


**VPN**



OpenVPN



Multiple clients and a server can run simultaneously, 12 encryption methods



DES-CBC, RC2-CBC, DES-EDE-CBC, DES-EDE3-CBC, DESX-CBC, BF-CBC, RC2-40-CBC, CAST5-CBC, RC2-64-CBC, AES-128-CBC,
OpenVPN Encryption
AES-192-CBC, AES-256-CBC



IPsec


GRE


PPTP, L2TP


Stunnel


DMVPN


SSTP


ZeroTier


WireGuard


**MODBUS TCP SLAVE**


ID filtering



IKEv1, IKEv2, with 5 encryption methods for IPsec (DES, 3DES, AES128, AES192, AES256)


GRE tunnel


Client/Server instances can run simultaneously, L2TPv3 support


Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code


Method of building scalable IPsec VPNs


SSTP client instance support


ZeroTier VPN client support


WireGuard VPN client and server support


Respond to one ID in range [1;255] or any



Allow remote access Allow access through WAN


Modbus TCP custom register block, which allows to read/write to a file inside the router, and can be used to extend Modbus
Custom registers
TCP slave functionality


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


DATASHEET // RUTX08



**MODBUS TCP MASTER**


Supported functions



01, 02, 03, 04, 05, 06, 15, 16



8 bit: INT, UINT; 16 bit: INT, UINT (MSB or LSB first); 32 bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC), HEX, ASCII


**MQTT GATEWAY**



Gateway


**DATA TO SERVER**


Protocols



Allows sending commands and receiving data from Modbus Master trough MQTT broker


HTTP(S), MQTT, Azure MQTT, Kinesis



**MONITORING & MANAGEMENT**



WEB UI



HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log



FOTA Firmware update from server, automatic notification



SSH


TR-069


MQTT


SNMP


JSON-RPC


MODBUS



SSH (v1, v2)


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher


SNMP (v1, v2, v3), SNMP trap


Management API over HTTP/HTTPS


MODBUS TCP status/control



RMS Teltonika Remote Management System (RMS)


**SYSTEM CHARACTERISTICS**


CPU Quad-core ARM Cortex A7, 717 MHz



RAM


FLASH storage



256 MB, DDR3


256 MB, SPI Flash



**FIRMWARE / CONFIGURATION**


WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup



FOTA


RMS



Update FW/configuration from server


Update FW/configuration for multiple devices at once



Keep settings Update FW without losing current configuration


**FIRMWARE CUSTOMIZATION**


Operating system RutOS (OpenWrt based Linux OS)



Supported languages


Development tools


**USB**



Busybox shell, Lua, C, C++


SDK package with build environment provided



Data rate USB 2.0



Applications


External devices



Samba share, USB-to-serial


Possibility to connect external HDD, flash drive, additional modem, printer



External devices FAT, FAT32, NTFS


**INPUT/OUTPUT**


Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high



Output


Events



1 x Digital Output, Open collector output, max output 30 V, 300 mA


Email, RMS



I/O juggler Allows to set certain I/O conditions to initiate event


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUTX08



**POWER**


Connector 4 pin industrial DC power socket



Input voltage range


PoE (passive)



9 - 50 VDC, reverse polarity protection, voltage surge/transient protection


Passive PoE. Possibility to power up through LAN port, not compatible with IEEE 802.3af, 802.3at and 802.3bt standards



Power consumption 6 W Max


**PHYSICAL INTERFACES (PORTS, LEDS, BUTTONS)**



Ethernet



4 x RJ45 ports, 10/100/1000 Mbps



I/Os 1 x Digital Input, 1 x Digital Output on 4 pin power connector



Status LEDs


Power


USB


Reset



8 x LAN status LEDs, 1 x Power LED


1 x 4 pin DC connector


1 x USB A port for external devices


Reboot/User default reset/Factory reset button



Other 1 x Grounding screw


**PHYSICAL SPECIFICATION**


Casing material Aluminium housing with DIN tail mounting option



Dimensions (W x H x D)


Weight



115 x 32.2 x 95.2 mm


345 g



Mounting options DIN rail, flat surface placement


**OPERATING ENVIRONMENT**


Operating temperature -40 C to 75 C



Operating humidity


Ingress Protection Rating



10 % to 90 % non-condensing


IP30



**REGULATORY & TYPE APPROVALS**


Regulatory & Type Approvals CE, RoHS, REACH


**EMI IMMUNITY**



Standards



EN 55032:2015, EN 55035:2017



ESD EN 61000-4-2:2009



RS


EFT


Surge protection


CS



EN 61000-4-3:2006+A1:2008+A2:2010


EN 61000-4-4:2012


EN 61000-4-5:2014


EN 61000-4-6:2014



DIP EN 61000-4-11:2004


**SAFETY**


Standards IEC 62368-1:2014 EN 62368-1:2014+A11:2017


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


DATASHEET // RUTX08

## HARDWARE INSTALLATION


1. Connect the power adapter to the socket on the front of the device. Then plug the other end of the power adapter into a power outlet.
2. Connect to the device via an Ethernet cable connected to LAN port.


LOGIN TO DEVICE


1. To enter the router's Web interface (WebUI), type http://192.168.1.1 into the URL field of your Internet browser.
2. Use login information shown in image A when prompted for authentication.
3. After you log in, you will be prompted to change your password for security reasons. The new password must contain at least 8 characters,
including at least one uppercase letter, one lowercase letter, and one digit. This step is mandatory, and you will not be able to interact with the
router's WebUI before you change the password.
4. When you change the router's password, the Configuration Wizard will start. The Configuration Wizard is a tool used to set up some of the
router's main operating parameters.


**A.**

|Col1|Col2|
|---|---|
||**admin**<br>**admin01**|
|||



TECHNICAL INFORMATION


After logging in to the router’s WebUI, you will be prompted to change the default password and the Setup Wizard will start:

1. Choose your time zone and sync the router's time with the browser if needed.


2. Default LAN settings are recommended unless you have specific requirements for your LAN network.


TECHNICAL INFORMATION

|Bundled accessories specifications*|Col2|
|---|---|
|Power adapter|Input: 0.6A@100-240VAC, Output: 12VDC, 1.5A, 4-pin plug|



*Order code dependent.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUTX08

- 18 W PSU

- Ethernet cable (1.5 m)

- QSG (Quick Start Guide)

- RMS Flyer

- Packaging box






   - For all standard order codes standard package contents are the same, execpt for PSU.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUTX08

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUTX08000000



851762 8517.62.00 Standard package



For more information on all available packaging options – please contact us directly.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUTX08


## MOUNTING OPTIONS

DIN RAIL KIT



Parameter


Mounting standard


Material


Weight


Screws included


Dimensions


RoHS Compliant


**DIN RAIL KIT**


DIN Rail adapter



Value


35mm DIN Rail


Low carbon steel


57g


Philips Pan Head screw #6-32×3/16, 2pcs


82 mm x 46 mm x 20 mm


V



Philips Pan Head screw #6-32×3/16, 2pcs for RUT2xx/RUT9xx


**ORDER CODE** **HS CODE** **HTS CODE**



PR5MEC00


For more information on all available packaging options – please contact us directly.


COMPACT DIN RAIL KIT



73269098 7326.90.98



Parameter


Mounting standard


Material


Weight


Screws included


Dimensions


RoHS Compliant


**DIN RAIL KIT**



Value


35mm DIN Rail


ABS + PC plastic


6.5 g


Philips Pan Head screw #6-32×3/16, 2pcs


70 mm x 25 mm x 14,5 mm


V



Compact plastic DIN Rail adapter (70x25x14,5mm)


Philips Pan Head screw #6-32×3/16, 2pcs


**ORDER CODE** **HS CODE** **HTS CODE**



PR5MEC11


For more information on all available packaging options – please contact us directly.


SURFACE MOUNTING KIT



73269098 7326.90.98



Parameter


Mounting standard


Material


Weight


Screws included


Dimensions


RoHS Compliant


**DIN RAIL KIT**


Surface mounting kit



Value


Flat surface mount


ABS + PC plastic


2x5 g


Philips Pan Head screw #6-32×3/16, 2pcs


25 mm x 48 mm x 7.5 mm


V



Philips Pan Head screw #6-32×3/16, 2pcs


**ORDER CODE** **HS CODE** **HTS CODE**



PR5MEC12


For more information on all available packaging options – please contact us directly.



73269098 7326.90.98



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // RUTX08


## RUTX08 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTX08:



Device housing*:

Box:



115 x 32.2 x 95.2

173 x 71 x 148



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTX08 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUTX08 and its components as seen from the right side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // RUTX08



**FRONT VIEW**


The figure below depicts the measurements of RUTX08 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUTX08 and its components as seen from the back panel side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // RUTX08



**MOUNTING SPACE REQUIREMENTS**



The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


DATASHEET // RUTX08



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:

|Col1|Col2|17.0|Col4|Col5|32.2|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||||||



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**13**


