Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## **HARDWARE**

FRONT VIEW


**LAN LEDs**


**Power**
**socket**


BACK VIEW



**LAN Ethernet** **WAN**
**ports** **Ethernet port**


**Power LED** **Mobile connection**
**status LED**



DATASHEET // RUT951


**WAN LED**


**Mobile signal**
**strength**
**indication LEDs**



**Mobile AUX antenna** **Reset** **Mobile MAIN antenna**
**connector (SMA female)** **button** **connector (SMA female)**



**Wi-Fi antenna**

|SIM<br>needl|Col2|Col3|Col4|
|---|---|---|---|
|<br>**SIM**<br>**needl**||||
|<br>**SIM**<br>**needl**||||
|<br>**SIM**<br>**needl**||||
|<br>**SIM**<br>**needl**||<br>**SIM**<br>**needl**|<br>**SIM**<br>**needl**|

**connector**
**(RP-SMA female)**


**Ground / Black wire**


**Output / White wire**



POWER SOCKET PINOUT



**Wi-Fi antenna**
**connector**
**(RP-SMA female)**


**Power / Red wire**


**Input / Green wire**



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


DATASHEET // RUT951


## FEATURES

**MOBILE**


Mobile module



4G (LTE) – Cat 4 up to 150 Mbps, 3G – Up to 42 Mbps, 2G – Up to 236.8 kbps



3GPP Release Release 10/11 depending on the hardware version

2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail,
SIM switch
SIM idle protection



Status


SMS


USSD


Black/White list


Multiple PDN


Band management



Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID

SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP

Supports sending and reading Unstructured Supplementary Service Data messages


Operator black/white list


Possibility to use different PDNs for multiple network access and services


Band lock, Used band status display



APN Auto APN


Bridge Direct connection (bridge) between mobile ISP and device on LAN


Passthrough Router assigns its mobile WAN IP address to another device on LAN

**WIRELESS**


Wireless mode IEEE 802.11b/g/n, Access Point (AP), Station (STA)



WiFi security


SSID/ESSID



WPA2-Enterprise - PEAP, WPA2-PSK, WEP, WPA-EAP, WPA-PSK; AES-CCMP, TKIP, Auto Cipher modes, client separation


SSID stealth mode and access control based on MAC address



WiFi users Up to 100 simultaneous connections


Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
Wireless Hotspot user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes


Wireless Connectivity Features Fast roaming (802.11r), Relayd

**ETHERNET**


WAN 1 x WAN port 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX



LAN

**NETWORK**


Routing


Network protocols


VoIP passthrough support


Connection monitoring



3 x LAN ports, 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing

TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)

H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection



Firewall Port forward, traffic rules, custom rules



DHCP

QoS / Smart Queue
Management (SQM)

DDNS


Network backup



Static and dynamic IP allocation, DHCP Relay


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


WiFi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover



Load balancing Balance Internet traffic over multiple WAN connections


SSHFS Possibility to mount remote file system via SSH protocol

**SECURITY**



Authentication


Firewall



Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block


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



DATASHEET // RUT951


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



DMVPN Method of building scalable IPsec VPNs



SSTP


ZeroTier



SSTP client instance support


ZeroTier VPN client support



WireGuard WireGuard VPN client and server support


Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support.

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


MQTT gateway

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


Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer, WiFi on/off


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher


SNMP (v1, v2, v3), SNMP Trap



JSON-RPC Management API over HTTP/HTTPS



MODBUS


RMS

**IoT PLATFORMS**


Clouds of things


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


DATASHEET // RUT951



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

Passive PoE over spare pairs. Possibility to power up through LAN port, not compatible with IEEE802.3af, 802.3at and 802.3bt
standards, Mode B, LAN1 Port, 9 - 30 VDC



Power consumption < 2 W idle, < 7 W Max


**PHYSICAL INTERFACES**


Ethernet 4 x RJ45 ports, 10/100 Mbps



I/O’s


Status LEDs



1 x Digital Input, 1 x Digital Output on 4-pin power connector


1 x Bi-color connection status, 5 x Mobile connection strength, 4 x ETH status, 1 x Power



SIM 2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders, eSIM (Optional)


Antennas 2 x SMA for LTE, 2 x RP-SMA for WiFi antenna connectors


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


110 x 50 x 100 mm


287 g


DIN rail (can be mounted on two sides), flat surface placement


-40 °C to 75 °C


10% to 90% non-condensing



Ingress Protection Rating IP30


**REGULATORY & TYPE APPROVALS**


Regulatory CE/RED, UKCA, CB, EAC, RoHS, REACH, CITC, ICASA, ANRT, RCM, SDPPI(Postel), KC, GITEKI, FCC, IC, PTCRB, UL/CSA Safety, NOM, E-mark


Operator AT&T, Verizon, T-Mobile


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


**EMI IMMUNITY**


Standards


ESD


RS


EFT



DATASHEET // RUT951


EN 301 489-1 V2.2.3, EN 301 489-17 V3.2.4, Final draft EN 301 489-52 V1.2.0, EN 55032:2015+A1:2020, EN
55035:2017+A11:2020, EN 61000-3-3:2013+A1:2019, EN IEC 61000-3-2:2019


EN 61000-4-2:2009


EN 61000-4-3:2020


EN 61000-4-4:2012



Surge Immunity
EN 61000-4-5:2014+A1:2017
(AC Mains Power Port)


CS EN 61000-4-6:2014


DIP EN IEC 61000-4-11:2020


**RF**

Standards EN 300 328 V2.2.2, EN 301 908-1 V13.1.1, EN 301 908-2 V13.1.1, EN 301 908-13 V13.1.1


**SAFETY**


Standards EN IEC 62311:2020 IEC 62368-1:2018 EN IEC 62368-1:2020+A11:2020


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUT951

- 9 W PSU

- 2 x LTE antennas (swivel, SMA male)

- 2 x WiFi antennas (swivel, RP-SMA male)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box



DATASHEET // RUT951






|ROUTER RUT951|9 W PSU|2 X LTE ANTENNAS (SWIVEL,<br>SMA MALE)|
|---|---|---|
|**2 X WI-FI ANTENNAS (SWIVEL, RP-SMA**<br>**MALE)**|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**|
|**QSG**|||




   - For all standard order codes standard package contents are the same, except for PSU.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUT951

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUT951 000000



851762 8517.62.00 Standard package with Euro PSU



RUT951 100000 851762 8517.62.00 Standard package with Euro PSU


RUT951 200000 851762 8517.62.00 Standard package with Euro PSU


RUT951 600600 851762 8517.62.00 Standard package with AU PSU


RUT951 A00800 851762 8517.62.00 Standard package with US PSU


RUT951 900A00 851762 8517.62.00 Standard package with JP PSU


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


**• 4G (LTE-FDD):** B1, B2, B3, B4, B5, B7, B8, B12,
B13, B18, B19, B20, B25, B26, B28

**• 4G (LTE-TDD):** B38, B39, B40, B41

**• 3G:** B1, B2, B4, B5, B6, B8, B19

**• 2G:** B2, B3, B5, B8


**• 4G (LTE-FDD):** B1, B3, B4, B5, B7, B8, B28

**• 4G (LTE-TDD):** B40

**• 3G:** B1, B2, B4, B5, B8

**• 2G:** B2, B3, B5, B8


**• 4G (LTE-FDD):** B2, B4, B5, B12, B13, B14, B66,
B71

**• 3G:** B2, B4, B5



RUT951 0*****


RUT951 1*****


RUT951 2*****


RUT951 6*****


RUT951 A*****



Europe [1], the Middle East, Africa,
Korea, Thailand


Europe [1], the Middle East, Africa


Global [1]


South America, Australia, New
Zealand, Taiwan


North America [2]




**• 4G (LTE-FDD):** B1, B3, B8, B18, B19, B26
RUT951 9***** North America [2] **• 4G (LTE-TDD):** B41

**• 3G:** B1, B6, B8, B19


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 - Regional availability - excluding Russia & Belarus.
2 - For more detailed information about certified carriers, visit our Wiki page.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUT951


## RUT951 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUT951:



Device housing*:

Box:



110 x 50 x 100 mm

355 x 60 x 175 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUT951 and its components as seen from the top:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // RUT951



**FRONT VIEW**


The figure below depicts the measurements of RUT951 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUT951 and its components as seen from the back panel side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // RUT951



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // RUT951



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


