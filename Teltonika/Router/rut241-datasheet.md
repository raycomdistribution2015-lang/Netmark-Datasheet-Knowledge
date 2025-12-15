Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // RUT241


## HARDWARE

FRONT VIEW


BACK VIEW


POWER SOCKET PINOUT



**Mobile AUX antenna**
**connector (SMA female)**


**Power / Red wire**


**Input / Green wire**



**Power socket**



**Mobile signal**



**LAN LED** **WAN LED**





**Power LED**



**SIM slot**


**Reset button**





**Ground / Black wire**


**Output / White wire**



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


DATASHEET // RUT241


## FEATURES

**MOBILE**


Mobile module



4G (LTE) – Cat 4 up to 150 Mbps, 3G – Up to 42 Mbps, 2G – Up to 236.8 kbps



3GPP Release Release 10/11 depending on the hardware version


Status Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID



SMS


USSD


Black/White list


Multiple PDN


Band management



SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP


Supports sending and reading Unstructured Supplementary Service Data messages


Operator black/white list


Possibility to use different PDNs for multiple network access and services


Band lock, Used band status display



APN Auto APN



Bridge



Direct connection (bridge) between mobile ISP and device on LAN



Passthrough Router assigns its mobile WAN IP address to another device on LAN


**WIRELESS**


Wireless mode IEEE 802.11b/g/n, Access Point (AP), Station (STA)



Wi-Fi security


SSID/ESSID



WPA2-Enterprise - PEAP, WPA2-PSK, WEP, WPA-EAP, WPA-PSK; AES-CCMP, TKIP, Auto Cipher modes, client separation


SSID stealth mode and access control based on MAC address



Wi-Fi users Up to 50 simultaneous connections


Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
Wireless Hotspot user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes


Wireless Connectivity Features Fast roaming (802.11r), Relayd


Wireless MAC filter Whitelist, blacklist


**ETHERNET**


WAN 1 x WAN port 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX



LAN

**NETWORK**


Routing


Network protocols


VoIP passthrough support



1 x LAN port, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)


H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets



Connection monitoring Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection



Firewall


DHCP


QoS / Smart Queue
Management (SQM)


DDNS


Network backup



Port forward, traffic rules, custom rules


Static and dynamic IP allocation, DHCP Relay


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover



Load balancing Balance Internet traffic over multiple WAN connections


SSHFS Possibility to mount remote file system via SSH protocol


**SECURITY**



Authentication


Firewall



Possibility to mount remote file system via SSH protocol


Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T



DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
Attack prevention
SYN-RST, X-mas, NULL flags, FIN scan attacks)



VLAN


Mobile quota control


WEB filter


Access control



Port and tag-based VLAN separation


Mobile data limit, customizable period, start time, warning limit, phone number


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Flexible access control of TCP, UDP, ICMP packets, MAC address filter



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


**VPN**


OpenVPN


OpenVPN Encryption


IPsec


GRE


PPTP, L2TP


Stunnel


DMVPN


SSTP



DATASHEET // RUT241


Multiple clients and a server can run simultaneously, 27 encryption methods


DES-CBC 64, RC2-CBC 128, DES-EDE-CBC 128, DES-EDE3-CBC 192, DESX-CBC 192,
BF-CBC 128, RC2-40-CBC 40, CAST5-CBC 128, RC2-64-CBC 64, AES-128-CBC 128, AES-128-CFB 128, AES-128-CFB1 128,
AES-128-CFB8 128, AES-128-OFB 128, AES-128-GCM 128, AES-192-CFB 192, AES-192-CFB1 192, AES-192-CFB8 192, AES-192-OFB
192, AES-192-CBC 192, AES-192-GCM 192, AES-256-GCM 256, AES-256-CFB 256, AES-256-CFB1 256, AES-256-CFB8 256,
AES-256-OFB 256, AES-256-CBC 256


IKEv1, IKEv2, with 14 encryption methods for IPsec (3DES, DES, AES128, AES192, AES256, AES128GCM8, AES192GCM8,
AES256GCM8, AES128GCM12, AES192GCM12, AES256GCM12, AES128GCM16, AES192GCM16, AES256GCM16)


GRE tunnel, GRE tunnel over IPsec support


Client/Server instances can run simultaneously, L2TPv3, L2TP over IPsec support


Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code


Method of building scalable IPsec VPNs


SSTP client instance support



ZeroTier ZeroTier VPN client support


WireGuard WireGuard VPN client and server support


Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support

**MODBUS TCP SLAVE**



ID range



Respond to one ID in range [1;255] or any



Allow Remote Access Allow access through WAN


MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Slave functionality

**MODBUS TCP MASTER**



Supported functions


Supported data formats


**DATA TO SERVER**


Protocol

**MQTT GATEWAY**


MQTT Gateway

**DNP3**


Supported modes



01, 02, 03, 04, 05, 06, 15, 16


8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC)


HTTP(S), MQTT, Azure MQTT, Kinesis


Allows sending commands and receiving data from MODBUS Master through MQTT broker


TCP Master, DNP3 Outstation



**MONITORING & MANAGEMENT**



WEB UI



HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log



FOTA Firmware update from server, automatic notification



SSH


SMS


Call


TR-069


MQTT


SNMP



SSH (v1, v2)


SMS status, SMS configuration, send/read SMS via HTTP POST/GET


Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer, Wi-Fi on/off


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher


SNMP (v1, v2, v3), SNMP Trap



JSON-RPC Management API over HTTP/HTTPS



MODBUS


RMS

**IoT PLATFORMS**


Cloud of Things


ThingWorx



MODBUS TCP status/control


Teltonika Remote Management System (RMS)


Allows monitoring of: Device data, Mobile data, Network info, Availability


Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type



Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP, Mobile Cell ID, ICCID, IMEI, Connection
Cumulocity
Type, Operator, Signal Strength


Can send device IP, Number of bytes send/received, Temperature, PIN count to Azure IoT Hub server, Mobile connection state,
Azure IoT Hub Network link state, IMEI, ICCID, Model, Manufacturer, Serial, Revision, IMSI, SIM State, PIN state, GSM signal, WCDMA RSCP,
WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID, Operator, Operator number, Connection type


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUT241



**SYSTEM CHARACTERISTICS**


CPU Mediatek, 580 MHz, MIPS 24KEc



RAM


FLASH storage



128 MB, DDR2


16 MB, SPI Flash



**FIRMWARE / CONFIGURATION**


WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup



FOTA


RMS



Update FW


Update FW/configuration for multiple devices at once



Keep settings Update FW without losing current configuration


**FIRMWARE CUSTOMIZATION**


Operating system RutOS (OpenWrt based Linux OS)



Supported languages


Development tools


**INPUT/OUTPUT**



Busybox shell, Lua, C, C++


SDK package with build environment provided



Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high



Output


Events



1 x Digital Output, Open collector output, max output 30 V, 300 mA


Email, RMS, SMS



I/O juggler Allows to set certain I/O conditions to initiate event


**POWER**


Connector 4-pin industrial DC power socket



Input voltage range


PoE (passive)



9 – 30 VDC, reverse polarity protection; surge protection >31 VDC 10us max


Passive PoE over spare pairs. Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at and 802.3bt
standards, Mode B, 9 - 30 VDC



Power consumption < 6.5 W Max


**PHYSICAL INTERFACES**


Ethernet 2 x RJ45 ports, 10/100 Mbps



I/O’s


Status LEDs



1 x Digital Input, 1 x Digital Output on 4-pin power connector


3 x Connection type status LEDs, 5 x Connection strength LEDs, 2 x LAN status LEDs, 1 x Power LED



SIM 1 x SIM slot (Mini SIM – 2FF), 1.8 V/3 V, external SIM holder



Power


Antennas



1 x 4-pin power connector


2 x SMA for LTE, 1 x RP-SMA for Wi-Fi antenna connectors



Reset Reboot/User default reset/Factory reset button


**PHYSICAL SPECIFICATION**



Casing material


Dimensions (W x H x D)


Weight


Mounting options


**OPERATING ENVIRONMENT**


Operating temperature


Operating humidity



Aluminium housing, plastic panels


83 x 25 x 74 mm


125 g


Bottom and sideways DIN rail mounting slots


-40 °C to 75 °C


10% to 90% non-condensing



Ingress Protection Rating IP30


**REGULATORY & TYPE APPROVALS**


Regulatory CE/RED, UKCA, CB, EAC, RoHS, REACH, ICASA, ANRT, RCM, IMDA, ETA-WPC, KC, GITEKI, NTC, FCC, IC, PTCRB, NOM, GCF, E-mark


Operator AT&T, Verizon, T-Mobile, UScellular


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


**EMI IMMUNITY**


IMMUNITY Standards


ESD


RS


EFT



DATASHEET // RUT241


EN 301 489-1 V2.2.3 EN 301 489-17 V3.2.4 Final draft EN 301 489-52 V1.2.0 EN 55032:2015+A1:2020 EN 55035:2017+A11:2020
EN 61000-3-3:2013+A1:2019 EN IEC 61000-3-2:2019


EN 61000-4-2:2009


EN 61000-4-3:2020


EN 61000-4-4:2012



Surge immunity
EN 61000-4-5:2014+A1:2017
(AC Power Line)


CS EN 61000-4-6:2014


DIP EN IEC 61000-4-11:2020


**RF**


Standards EN 300 328 V2.2.2, EN 301 511 V12.5.1, EN 301 908-1 V13.1.1, EN 301 908-2 V13.1.1, EN 301 908-13 V13.1.1


**SAFETY**


Standards EN IEC 62311:2020, EN 50665:2017, EN IEC 62368-1:2020+A11:2020, IEC 62368-1:2018


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **6**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUT241

- 9 W PSU

- 2 x LTE antennas (swivel, SMA male)

- 1 x Wi-Fi antenna (swivel, RP-SMA male)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box

|ROUTER RUT241|9 W PSU|2 X LTE ANTENNAS (SWIVEL, SMA<br>MALE)|
|---|---|---|
|**1 X WI-FI ANTENNA (SWIVEL, RP-SMA**<br>**MALE)**|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**|
|**QSG**|||



   - For all standard order codes standard package contents are the same, except for PSU.



DATASHEET // RUT241



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **7**


DATASHEET // RUT241

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUT241 000000



851762 8517.62.00 Standard package with EU PSU



RUT241 010000 851762 8517.62.00 Standard package with EU PSU


RUT241 022020 851762 8517.62.00 Standard package without PSU


RUT241 030000 851762 8517.62.00 Standard package with EU PSU


RUT241 065000 851762 8517.62.00 Standard package with AU PSU


RUT241 070000 851762 8517.62.00 Standard package with EU PSU


RUT241 087000 851762 8517.62.00 Standard package with JP PSU


RUT241 098000 851762 8517.62.00 Standard package with US PSU


For more information on all available packaging options – please contact us directly.
## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**




**• 4G (LTE-FDD):** B1, B3, B7, B8, B20, B28A

**• 3G:** B1, B8

**• 2G:** B3, B8


**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B20

**• 4G (LTE-TDD):** B40

**• 3G:** B1, B5, B8

**• 2G:** B3, B8


**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B20

**• 4G (LTE-TDD):** B38, B40, B41

**• 3G:** B1, B5, B8

**• 2G:** B3, B8


**• 4G (LTE-FDD):** B1, B2, B3, B4, B5, B7, B8, B12,
B13, B18, B19, B20, B25, B26, B28

**• 4G (LTE-TDD):** B38, B39, B40, B41

**• 3G:** B1, B2, B4, B5, B6, B8, B19

**• 2G:** B2, B3, B5, B8


**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B28

**• 4G (LTE-TDD):** B40

**• 3G:** B1,B5, B8

**• 2G:** B3, B5, B8


**• 4G (LTE-FDD):** B1, B2, B3, B4, B5, B7, B8, B28

**• 4G (LTE-TDD):** B40

**• 3G:** B1, B2, B4, B5, B8

**• 2G:** B2, B3, B5, B8



RUT241 *0****



Europe [1], The Middle East, Africa,
Thailand



RUT241 *1**** Europe [1], The Middle East, Africa


RUT241 *3**** South Korea


RUT241 *6**** Global [1]


RUT241 *9**** Australia, New Zealand, Taiwan


RUT241 *8**** Latin America




**• 4G (LTE-FDD):** B1, B3, B8, B18, B19, B26
RUT241 *8**** Japan **• 4G (LTE-TDD):** B41

**• 3G:** B1, B6, B8, B19


**• 4G (LTE-FDD):** B2, B4, B5, B12, B13, B14, B66, B71﻿
RUT241 *8**** North America [2]

**• 3G:** B2, B4, B5


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.


1 - Regional availability - excluding Russia & Belarus
2 - For more detailed information about certified carriers, visit our Wiki page


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUT241


## RUT241 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUT241:



Device housing*:

Box:



83 x 25 x 74 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUT241 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUT241 and its components as seen from the right side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // RUT241


**FRONT VIEW**


The figure below depicts the measurements of RUT241 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUT241 and its components as seen from the back panel side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **10**


DATASHEET // RUT241


**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **11**


DATASHEET // RUT241


**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **12**


