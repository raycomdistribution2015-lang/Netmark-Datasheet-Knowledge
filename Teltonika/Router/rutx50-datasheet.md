Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice


#### HARDWARE

FRONT VIEW


**WAN type LEDs**


**SIM needle**


**4-pin power socket**


BACK VIEW


**Grounding**
**screw**


POWER SOCKET PINOUT



**Mobile network**
**type LEDs**



**Mobile signal strength**
**indication LEDs**



DATASHEET // RUTX50


**SIM holders**



|Reset LAN Ethernet WAN Ethernet<br>button ports port|Col2|
|---|---|
|**WAN Ethernet**<br>**port**<br>**LAN Ethernet**<br>**ports**<br>**Reset**<br>**button**||
|||
|||
|||
||**Reset**<br>**button**|


**Power** **WiFi Band**
**LED** **LEDs**


**Mobile antenna** **Mobile antenna**
**connector** **connector**

|Mobile antenna GPS antenna Mobile anten<br>connector connector connector|Col2|Col3|GPS antenna<br>connector|Col5|Mobile anten<br>connector|Col7|
|---|---|---|---|---|---|---|
|**GPS antenna**<br>**connector**<br>**Mobile anten**<br>**connector**<br>**Mobile antenna**<br>**connector**|||||||
|**GPS antenna**<br>**connector**<br>**Mobile anten**<br>**connector**<br>**Mobile antenna**<br>**connector**|||||||



**WiFi antenna** **WiFi antenna** **USB port**
**connector** **connector**



**Power / Red wire**


**Input / Green wire**



**Ground / Black wire**


**Output / White wire**



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



**2**


l


#### FEATURES

**MOBILE**


Mobile module


SIM switch


Status


SMS


USSD

Black/White list

Multiple PDN


l



DATASHEET // RUTX50


5G Sub-6Ghz SA/NSA 2.1/3.3Gbps DL (4x4 MIMO), 900/600 Mbps UL (2x2); 4G (LTE) – LTE Cat 20 2.0Gbps DL, 200Mbps UL;
3G – 42 Mbps DL, 5.76Mbps UL

2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail,
SIM idle protection

Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID, Carrier aggregation

SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP

Supports sending and reading Unstructured Supplementary Service Data messages

Operator black/white list

Possibility to use different PDNs for multiple network access and services


l



l



Band management Band lock, Used band status display

APN Auto APN

Bridge Direct connection (bridge) between mobile ISP and device on LAN

Passthrough Router assigns its mobile WAN IP address to another device on LAN


**WIRELESS**

802.11b/g/n/ac Wave 2 (WiFi 5) with data transmission rates up to 867 Mbps (Dual Band, MU-MIMO), 802.11r fast transition,
Wireless mode
Access Point (AP), Station (STA)


l



Wi-Fi security

SSID/ESSID


l



WPA2-Enterprise - PEAP, WPA2-PSK, WEP, WPA-EAP, WPA-PSK; AES-CCMP, TKIP, Auto Cipher modes, client separation

ESSID stealth mode


l



Wi-Fi users up to 150 simultaneous connections

Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden, user
Wireless Hotspot
scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable themes

Wireless Connectivity Features Wireless mesh (802.11s), fast roaming (802.11r), Relayd

Wireless MAC filter Whitelist, blacklist


**ETHERNET**

1 x WAN port 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
WAN
crossover


l



LAN


**NETWORK**

Routing


Network protocols


VoIP passthrough support

Connection monitoring


l



4 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
crossover


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing

TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)

H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets

Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


l



Firewall Port forward, traffic rules, custom rules


l



DHCP

QoS / Smart Queue
Management (SQM)

DDNS


l



Static and dynamic IP allocation, DHCP Relay


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


l



Network backup Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover


l



Load balancing

SSHFS


**SECURITY**

Authentication

Firewall


l



Balance Internet traffic over multiple WAN connections

Possibility to mount remote file system via SSH protocol


Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block

Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T


l



DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention
Attack prevention
(SYN-FIN, SYN-RST, X-mas, NULL flags, FIN scan attacks)

VLAN Port and tag-based VLAN separation



l


Mobile quota control

WEB filter



l


Mobile data limit, customizable period, start time, warning limit, phone number

Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only



l


Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



l


**3**


**VPN**

OpenVPN


OpenVPN Encryption



DATASHEET // RUTX50


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



SSTP Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code



STUNNEL

DMVPN



Method of building scalable IPsec VPNs

SSTP client instance support



WireGuard ZeroTier VPN client support

ZeroTier WireGuard VPN client and server support

ZeroTier Tinc offers encryption, authentication and compression in it's tunnels. Client and server support.


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



01, 02, 03, 04, 05, 06, 15, 16



8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC)


**DATA TO SERVER**



Protocol


**DNP3**

MQTT Gateway


**DNP3**

Supported modes



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


**SYSTEM CHARACTERISTICS**

CPU Quad-core ARM Cortex A7, 717 MHz



RAM

FLASH storage



256 MB (100 MB available for userspace)

256 MB (80 MB available for userspace)



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



**4**


DATASHEET // RUTX50



**FIRMWARE / CONFIGURATION**



WEB UI



Update FW from file, check FW on server, configuration profiles, configuration backup



FOTA Update FW



RMS

Keep settings


**FIRMWARE CUSTOMIZATION**



Update FW/configuration for multiple devices at once

Update FW without losing current configuration



Operating system RutOS (OpenWrt based Linux OS)



Supported languages

Development tools


**LOCATION TRACKING**



Busybox shell, Lua, C, C++

SDK package with build environment provided



GNSS GPS, GLONASS, BeiDou, Galileo and QZSS



Coordinates

NMEA



GNSS coordinates via WebUI, SMS, TAVL, RMS

NMEA 0183



NTRIP NTRIP protocol (Networked Transport of RTCM via Internet Protocol)

Server software Supported server software TAVL, RMS

Geofencing Configurable multiple geofence zones


**USB**

Data rate USB 2.0



Applications

External devices



Samba share, USB-to-serial

Possibility to connect external HDD, flash drive, additional modem, printer, USB-serial adapter



Storage formats FAT, FAT32, exFAT, NTFS (read-only), ext2, ext3, ext4


**INPUT/OUTPUT**

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



9 – 50 VDC, reverse polarity protection, surge protection >51 VDC 10us max

Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at and 802.3bt standards, Mode B, 9 - 30 VDC



Power consumption Idle: < 4W, Max: 18W


**PHYSICAL INTERFACES (PORTS, LEDS, ANTENNAS, BUTTONS, SIM)**

Ethernet 5 x RJ45 ports, 10/100/1000 Mbps



I/O’s


Status LEDs



1 x Digital Input, 1 x Digital Output on 4-pin power connector

3 x connection status LEDs, 3 x connection strength LEDs, 10 x Ethernet port status LEDs, 4 x WAN status LEDs, 1 x Power
LED, 2 x 2.4G and 5G Wi-Fi LEDs



SIM 2 x SIM slot (Mini SIM – 2FF), 1.8 V/3 V



Power

Antennas



1 x 4-pin power connector

4 x SMA for Mobile, 2 x RP-SMA for Wi-Fi, 1 x SMA for GNNS



USB 1 x USB A port for external devices

Reset Reboot/User default reset/Factory reset button

Other 1 x Grounding screw


**PHYSICAL SPECIFICATION**



Casing material

Dimensions (W x H x D)

Weight

Mounting options


**OPERATING ENVIRONMENT**

Operating temperature

Operating humidity



Aluminum housing

132 x 44.2 x 95.1 mm

533 g

DIN rail (can be mounted on two sides), flat surface placement


-40 °C to 75 °C

10% to 90% non-condensing



Ingress Protection Rating IP30


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



**5**


#### WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- RUTX50 Router

- 18 W PSU

- 4x Mobile antennas (swivel, SMA male)

- 2x Wi-Fi antennas (magnetic mount, RP-SMA male, 1.5 m cable)

- 1x GNSS antenna (adhesive, SMA male, 3 m cable)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box





|RUTX50 ROUTER|18 W PSU|4X MOBILE ANTENNAS<br>(SWIVEL, SMA MALE)|
|---|---|---|
|**2X WI-FI ANTENNAS (MAGNETIC**<br>**MOUNT, RP-SMA MALE, 1.5 M CABLE)**|**1X GNSS ANTENNA (ADHESIVE, SMA**<br>**MALE, 3 M CABLE)**|**ETHERNET CABLE (1.5 M)**|
|**SIM ADAPTER KIT**|||



   - For all standard order codes standard package contents are the same, execpt for PSU.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



**6**


DATASHEET // RUTX50


#### STANDARD ORDER CODES

**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUTX50 000000



851762 8517.62.00 Standard package with EU PSU



For more information on all available packaging options – please contact us directly.

#### AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**




- **5G NR NSA:** n1, n3, n5, n7, n8, n20, n28, n38, n40,
n41, n77

- **5G NR SA:** n1, n3, n5, n7, n8, n20, n28, n38, n40, n41,
n77, n78

- **4G (LTE-FDD):** B1, B3, B5, B7, B8, B20, B28, B32

- **4G (LTE-TDD):** B38, B40, B41, B42, B43

- **3G:** B1, B5, B8


- **5G NR NSA:** n7, n40, n77, n78

- **5G NR SA:** n1, n3, n5, n7, n8, n20, n38, n40, n41, n77,
n78

- **4G (LTE-FDD):** B1, B3, B5, B7, B8, B20

- **4G (LTE-TDD):** B38, B40, B41, B42, B43

- **3G:** B1, B8



RUTX50 0*****



Europe [1], The Middle East, Africa, Oceania,
Brazil



RUTX50 000305 Thailand


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.

1 - Regional availability - excluding Russia & Belarus.



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



**7**


DATASHEET // RUTX50


#### RUTX50 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTX50:



Device housing*:

Box:



132 x 44.2 x 95.1 mm

355 x 60 x 175 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTX50 and its components as seen from the top:


**RIGHT VIEW**

|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|Col12|
|---|---|---|---|---|---|---|---|---|---|---|---|
|||||||||||||
|||||||||||||
||132.00|||||||||||
|||||||||||||



The figure below depicts the measurements of RUTX50 and its components as seen from the right side:

|Col1|Col2|103.10|Col4|Col5|Col6|
|---|---|---|---|---|---|
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice


|5.40|Col2|
|---|---|
|5.40||
|||
|||
|||



**8**


DATASHEET // RUTX50



**FRONT VIEW**


The figure below depicts the measurements of RUTX50 and its components as seen from the front panel side:


##### 44.20 33.42 31.08 27.48 24.24 22.05 10.64 8.55 0



**REAR VIEW**


The figure below depicts the measurements of RUTX50 and its components as seen from the back panel side:

##### 44.20 33.39


##### 18.27 13.89 11.77 11.34 0

Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



**9**


DATASHEET // RUTX50



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



**10**


DATASHEET // RUTX50



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:

|16.64 44.20 199.19|Col2|Col3|Col4|
|---|---|---|---|
|199.19<br> 44.20<br> 16.64|199.19<br> 44.20<br> 16.64|199.19<br> 44.20<br> 16.64||
|199.19<br> 44.20<br> 16.64|199.19<br> 44.20<br> 16.64|199.19<br> 44.20<br> 16.64||
|199.19<br> 44.20<br> 16.64||||



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice



**11**


