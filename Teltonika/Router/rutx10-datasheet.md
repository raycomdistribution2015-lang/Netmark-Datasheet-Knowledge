Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // RUTX10


## HARDWARE

FRONT VIEW


BACK VIEW


POWER SOCKET PINOUT



**Power** **Reset** **LAN Ethernet**


|socket button ports|Col2|Col3|Col4|Col5|Col6|Col7|Col8|
|---|---|---|---|---|---|---|---|
|||||||||
|||||||||
|||||||||
|||||||||
|||||||||



**Power**
**LED**



**WiFi band**
**LEDs**



**LAN LEDs**



**WiFi antenna** **WiFi antenna** **Bluetooth antenna**
**connector** **connector** **connector**


**Grounding**
**screw**



**WAN LEDs**


**WAN Ethernet**
**port**


**USB port**



**Power / Red wire**


**Input / Green wire**



**Ground / Black wire**


**Output / White wire**



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **2**


## FEATURES

**ETHERNET**


WAN


LAN


**WIRELESS**


Wireless mode


Wi-Fi security


SSID/ESSID



DATASHEET // RUTX10


1 x WAN port 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
crossover


3 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
crossover


802.11b/g/n/ac Wave 2 (WiFi 5) with data transmission rates up to 867 Mbps (Dual Band, MU-MIMO), 802.11r fast transition,
Access Point (AP), Station (STA)


WPA2-Enterprise - PEAP, WPA2-PSK, WEP, WPA-EAP, WPA-PSK; AES-CCMP, TKIP, Auto Cipher modes, client separation


ESSID stealth mode



Wi-Fi users up to 150 simultaneous connections


Wireless Connectivity Features Wireless mesh (802.11s), fast roaming (802.11r), Relayd


Wireless MAC filter Whitelist, blacklist


Wireless QR code generator Once scanned, a user will automatically enter your network without needing to input login information


**NETWORK**



Hotspot


Routing


Network protocols


VoIP passthrough support


Connection monitoring


Firewall


Firewall status page


Ports management


Network topology



Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes and option to upload and download customised hotspot themes


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)


H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


Port forward, traffic rules, custom rules


View all your Firewall statistics, rules, and rule counters


View device ports, enable and disable each of them, turn auto-configuration on or off, change their transmission speed, and so on


Visual representation of your network, showing which devices are connected to which other devices



Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
Hotspot user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes and option to upload and download customised hotspot themes



DHCP


QoS / Smart Queue
Management (SQM)


DDNS


Network backup


Load balancing


SSHFS


**BLUETOOTH**



Static and dynamic IP allocation, DHCP Relay


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


Wi-Fi WAN, VRRP, Wired options, each of which can be used as an automatic Failover


Balance Internet traffic over multiple WAN connections


Possibility to mount remote file system via SSH protocol



Bluetooth 4.0 Bluetooth low energy (LE) for short range communication


**SECURITY**



Authentication


Firewall



Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block


Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T



DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
Attack prevention
SYN-RST, X-mas, NULL flags, FIN scan attacks)



VLAN


WEB filter



Port and tag-based VLAN separation


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only



Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


**VPN**


OpenVPN


OpenVPN Encryption



DATASHEET // RUTX10


Multiple clients and a server can run simultaneously, 27 encryption methods


DES-CBC 64, RC2-CBC 128, DES-EDE-CBC 128, DES-EDE3-CBC 192, DESX-CBC 192,
BF-CBC 128, RC2-40-CBC 40, CAST5-CBC 128, RC2-64-CBC 64, AES-128-CBC 128, AES-128-CFB 128, AES-128-CFB1 128,
AES-128-CFB8 128, AES-128-OFB 128, AES-128-GCM 128, AES-192-CFB 192, AES-192-CFB1 192, AES-192-CFB8 192, AES-192-OFB
192, AES-192-CBC 192, AES-192-GCM 192, AES-256-GCM 256, AES-256-CFB 256, AES-256-CFB1 256, AES-256-CFB8 256,
AES-256-OFB 256, AES-256-CBC 256



IKEv1, IKEv2, with 14 encryption methods for IPsec (3DES, DES, AES128, AES192, AES256, AES128GCM8, AES192GCM8,
IPsec
AES256GCM8, AES128GCM12, AES192GCM12, AES256GCM12, AES128GCM16, AES192GCM16, AES256GCM16)



GRE


PPTP, L2TP



GRE tunnel, GRE tunnel over IPsec support


Client/Server instances can run simultaneously, L2TPv3, L2TP over IPsec support



Stunnel Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code



DMVPN


SSTP



Method of building scalable IPsec VPNs


SSTP client instance support



ZeroTier ZeroTier VPN client support


WireGuard WireGuard VPN client and server support


Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support


**MODBUS TCP SLAVE**



ID range


Allow Remote Access



Respond to one ID in range [1;255] or any


Allow access through WAN



MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Slave functionality


**MODBUS TCP MASTER**



Supported functions


Supported data formats


**DATA TO SERVER**


Protocol


Data to server


**MQTT GATEWAY**



01, 02, 03, 04, 05, 06, 15, 16


8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB, BADC)


HTTP(S), MQTT, Azure MQTT, Kinesis


Extract parameters from multiple sources and different protocols, and send them all to a single server



MQTT Gateway Allows sending commands and receiving data from MODBUS Master through MQTT broker


**DNP3**


Supported modes TCP Master, DNP3 Outstation


**DLMS**


DLMS Support DLMS - standard protocol for utility meter data exchange


**MONITORING & MANAGEMENT**


WEB UI HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log


FOTA Firmware update from server, automatic notification


SSH SSH (v1, v2)



TR-069


MQTT



OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher



SNMP SNMP (v1, v2, v3), SNMP Trap


JSON-RPC Management API over HTTP/HTTPS


MODBUS MODBUS TCP status/control


RMS Teltonika Remote Management System (RMS)


**IOT PLATFORMS**


Cloud of Things Allows monitoring of: Device data, Mobile data, Network info, Availability


ThingWorx Allows monitoring of: WAN Type, WAN IP


Cumulocity Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP


Azure IoT Hub Can send device IP, Number of bytes send/received, Temperature, PIN count to Azure IoT Hub server


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUTX10


**SYSTEM CHARACTERISTICS**


CPU Quad-core ARM Cortex A7, 717 MHz


RAM 256 MB, DDR3


FLASH storage 256 MB, SPI Flash

**FIRMWARE / CONFIGURATION**


WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup


FOTA Update FW


RMS Update FW/configuration for multiple devices at once


Keep settings Update FW without losing current configuration

**FIRMWARE CUSTOMISATION**


Operating system RutOS (OpenWrt based Linux OS)


Supported languages Busybox shell, Lua, C, C++, and Python, Java in Package manager


Development tools SDK package with build environment provided


You can now create your own custom firmware and web page application, with some examples to make the creation process
GPL customization
easier; and brand our firmware by changing colours, logos, and so on to fit your or your clients’ needs


**USB**


Data rate USB 2.0


Applications Samba share, USB-to-serial


External devices Possibility to connect external HDD, flash drive, additional modem, printer, USB-serial adapter


Storage formats FAT, FAT32, exFAT, NTFS (read-only), ext2, ext3, ext4

**INPUT / OUTPUT**


Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high


Output 1 x Digital Output, Open collector output, max output 30 V, 300 mA


Events Email, RMS


I/O juggler Allows to set certain I/O conditions to initiate event


**POWER**


Connector 4-pin industrial DC power socket


Input voltage range 9 - 50 VDC, reverse polarity protection, voltage surge/transient protection


PoE (passive) Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at and 802.3bt standards, Mode B, 9 - 30 VDC


Power consumption 9 W Max


**PHYSICAL INTERFACES**


Ethernet 4 x RJ45 ports, 10/100/1000 Mbps


I/O’s 1 x Digital Input, 1 x Digital Output on 4-pin power connector


Status LEDs 8 x LAN status LEDs, 1 x Power LED, 2 x 2.4G and 5G Wi-Fi LEDs



Power


Antennas



1 x 4-pin power connector


2 x RP-SMA for Wi-Fi, 1 x RP-SMA for Bluetooth



USB 1 x USB A port for external devices


Reset Reboot/User default reset/Factory reset button


Other 1 x Grounding screw


**PHYSICAL SPECIFICATION**


Casing material Aluminum housing


Dimensions (W x H x D) 115 x 32.2 x 95.2 mm


Weight 355 g


Mounting options DIN rail, flat surface placement

**OPERATING ENVIRONMENT**


Operating temperature -40 °C to 75 °C


Operating humidity 10% to 90% non-condensing


Ingress Protection Rating IP30


**REGULATORY & TYPE APPROVALS**


Regulatory CE/RED, UKCA, CB, EAC, UCRF, RoHS, REACH, CITC, ICASA, ANRT, RCM, NBTC, GITEKI, NTC, FCC, IC, NOM


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **5**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUTX10

- 18 W PSU

- 2x Wi-Fi antennas (swivel, RP-SMA male)

- 1x Bluetooth antenna (magnetic mount, RP-SMA male, 1.5 m cable)

- Ethernet cable (1.5 m)

- QSG (Quick Start Guide)

- Packaging box



DATASHEET // RUTX10



|ROUTER RUTX10|18 W PSU|2 X WIFI ANTENNAS (SWIVEL,<br>RP-SMA MALE)|
|---|---|---|
|**1 X BLUETOOTH ANTENNA (MAGNETIC**<br>**MOUNT, RP-SMA MALE, 1.5 M CABLE)**|**ETHERNET CABLE (1.5 M)**|**QSG**|



   - For all standard order codes standard package contents are the same, execpt for PSU.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // RUTX10

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUTX10 000000



851762 8517.62.00 Standard package with EU PSU



RUTX10 000200 851762 8517.62.00 Standard package with US PSU


RUTX10 000300 851762 8517.62.00 Standard package with UK PSU


RUTX10 000400 851762 8517.62.00 Standard package with AU PSU


For more information on all available packaging options – please contact us directly.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUTX10


## RUTX10 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTX10:



Device housing*:

Box:



115 x 32.2 x 95.2 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTX10 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUTX10 and its components as seen from the right side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUTX10


**FRONT VIEW**


The figure below depicts the measurements of RUTX10 and its components as seen from the front panel side:


**REAR VIEW**

|Col1|Col2|Col3|Col4|Col5|
|---|---|---|---|---|
|picts the measurements of RUTX10 and its components as seen from the back panel side:|picts the measurements of RUTX10 and its components as seen from the back panel side:|picts the measurements of RUTX10 and its components as seen from the back panel side:|picts the measurements of RUTX10 and its components as seen from the back panel side:|picts the measurements of RUTX10 and its components as seen from the back panel side:|
|picts the measurements of RUTX10 and its components as seen from the back panel side:|||||
|picts the measurements of RUTX10 and its components as seen from the back panel side:|||||
|picts the measurements of RUTX10 and its components as seen from the back panel side:|||||
|picts the measurements of RUTX10 and its components as seen from the back panel side:|||||
|picts the measurements of RUTX10 and its components as seen from the back panel side:|||||



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // RUTX10



**MOUNTING SPACE REQUIREMENTS**



The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **10**


DATASHEET // RUTX10



**DIN RAIL**



The scheme below depicts protrusion measurements of an attached DIN Rail:

|139.0|Col2|Col3|Col4|Col5|Col6|
|---|---|---|---|---|---|
|||||||
|||||||
|||||||
|||||||
|||||||



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **11**


