### HARDWARE

FRONT VIEW


**WAN type LEDs**


**SIM needle**


**Power socket**


BACK VIEW


POWER SOCKET PINOUT



**Wi-Fi antenna**
**connectors**


**Power / Red wire**


**Input / Green wire**



**Mobile network type** **Mobile signal strength**
**LEDs** **indication LEDs**



DATASHEET // RUTM50


**SIM holders**



**Power** **Reset** **Wi-Fi Band** **LAN Ethernet** **WAN Ethernet**
**LED** **button** **LEDs** **ports** **port**


**Mobile MAIN antenna** **Mobile MAIN antenna**
**connector** **connector**



**Wi-Fi antenna**
**connectors**


**Ground / Black wire**


**Output / White wire**



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


DATASHEET // RUTM50

### FEATURES


**MOBILE**

5G Sub-6 GHz SA, NSA 2.4, 3.4Gbps DL (4x4 MIMO) 900, 550Mbps UL (2x2 MIMO); 4G (LTE): DL Cat 19 1.6Gbps (4x4 MIMO), UL
Mobile module
Cat 18 200Mbps

2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail,
SIM switch
SIM idle protection

Status Signal strength (RSSI), SINR, RSRP, RSRQ, EC, IO, RSCP Bytes sent, received, connected band, IMSI, ICCID.

SMS status, SMS configuration, send, read SMS via HTTP POST, GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
SMS
scheduled SMS, SMS autoreply, Call utilities

USSD Supports sending and reading Unstructured Supplementary Service Data messages


Black, White list Operator black, white list


Multiple PDN Possibility to use different PDNs for multiple network access and services


Band management Band lock, Used band status display


APN Auto APN


Bridge Direct connection (bridge) between mobile ISP and device on LAN


Passthrough Router assigns its mobile WAN IP address to another device on LAN


**WIRELESS**


Wireless mode 802.11b/g/n/ac Wave 2 (Wi-Fi 5) with data transmission rates up to 867 Mbps (Dual Band, MU-MIMO)


Wi-Fi security WPA3-EAP, WPA3-SAE, WPA2-Enterprise-PEAP, WPA2-PSK, WEP; AES-CCMP, TKIP, Auto Cipher modes, client separation


ESSID ESSID stealth mode


Wi-Fi users Up to 150 simultaneous connections


Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
Wireless Hotspot user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes


Wireless Connectivity Features Wireless mesh (802.11s), fast roaming (802.11r), Relayd


Wireless MAC filter Whitelist, blacklist


**ETHERNET**

1 x WAN port (can be configured as LAN) 10, 100, 1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards,
WAN
supports auto MDI, MDIX crossover

LAN 4 x ETH ports, 10/100/1000 Mbps, supports auto MDI/MDIX crossover


**NETWORK**


Routing Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Network protocols
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)


VoIP passthrough support H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Connection monitoring Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


Firewall Port forwards, traffic rules, custom rules


DHCP Static and dynamic IP allocation, DHCP Relay


QoS / Smart Queue
Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e
Management (SQM)


DDNS Supported >25 service providers, others can be configured manually


Network backup Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover


Load balancing Balance Internet traffic over multiple WAN connections


SSHFS Possibility to mount remote file system via SSH protocol


**SECURITY**


Authentication Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block


Firewall Pre-configured firewall rules can be enabled via the WebUI, unlimited firewall configuration via CLI; NAT; NAT-T


DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
Attack prevention
SYN-RST, X-mas, NULL flags, FIN scan attacks)


VLAN Port and tag-based VLAN separation


Mobile quota control Mobile data limit, customizable period, start time, warning limit, phone number


WEB filter Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


DATASHEET // RUTM50



**VPN**


OpenVPN Multiple clients and a server can run simultaneously, 27 encryption methods



OpenVPN Encryption



DES-CBC 64, RC2-CBC 128, DES-EDE-CBC 128, DES-EDE3-CBC 192, DESX-CBC 192,
BF-CBC 128, RC2-40-CBC 40, CAST5-CBC 128, RC2-64-CBC 64, AES-128-CBC 128, AES-128-CFB 128, AES-128-CFB1 128,
AES-128-CFB8 128, AES-128-OFB 128, AES-128-GCM 128, AES-192-CFB 192, AES-192-CFB1 192, AES-192-CFB8 192, AES-192-OFB
192, AES-192-CBC 192, AES-192-GCM 192, AES-256-GCM 256, AES-256-CFB 256, AES-256-CFB1 256, AES-256-CFB8 256,
AES-256-OFB 256, AES-256-CBC 256



IKEv1, IKEv2, with 14 encryption methods for IPsec (3DES, DES, AES128, AES192, AES256, AES128GCM8, AES192GCM8,
IPsec
AES256GCM8, AES128GCM12, AES192GCM12, AES256GCM12, AES128GCM16, AES192GCM16, AES256GCM16)

GRE GRE tunnel, GRE tunnel over IPsec support


PPTP, L2TP Client, Server instances can run simultaneously, L2TPv3, L2TP over IPsec support


Stunnel Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code


DMVPN Method of building scalable IPsec VPNs


SSTP SSTP client instance support


ZeroTier ZeroTier VPN client support


WireGuard WireGuard VPN client and server support


Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support


**BACNET**


Supported modes Router


Supported connection types TCP


**OPC UA**


Supported modes Client, Server (planned)


Supported connection types TCP


**DNP3**


Supported modes Station, Outstation


Supported connection types TCP, USB


**MODBUS**


Supported modes Server, Client


Supported connection types TCP, USB

MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Slave functionality

8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC), HEX, ASCII


**DATA TO SERVER**


Protocols HTTP(S), MQTT, Azure MQTT


**Modbus MQTT GATEWAY**



Modbus MQTT Gateway



Allows sending commands and receiving data from MODBUS Master through MQTT broker



**MONITORING & MANAGEMENT**


WEB UI HTTP, HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log


FOTA Firmware update from server, automatic notification


SSH SSH (v1, v2)


SMS SMS status, SMS configuration, send, read SMS via HTTP POST, GET


Call Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer, Wi-Fi on/off


TR-069 OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT MQTT Broker, MQTT publisher


SNMP SNMP (v1, v2, v3), SNMP trap


JSON-RPC Management API over HTTP, HTTPS


Modbus Modbus TCP status, control


RMS Teltonika Remote Management System (RMS)


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUTM50


**IOT PLATFORMS**


Cloud of Things Allows monitoring of: Device data, Mobile data, Network info, Availability


ThingWorx Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type

Allows monitoring of: Device Model, Revision and Serial Number, Mobile Cell ID, ICCID, IMEI, Connection Type, Operator, Signal
Cumulocity
Strength, WAN Type and IP

Can send device IP, Number of bytes send, received, Mobile connection state, Network link state, IMEI, ICCID, Model, ManufacAzure IoT Hub turer, Serial, Revision, IMSI, SIM State, PIN state, GSM signal, WCDMA RSCP, WCDMA EC, IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL
ID, Operator, Operator number, Connection type, Temperature, PIN count to Azure IoT Hub server


**SYSTEM CHARACTERISTICS**


CPU MediaTek MT7621A, Dual-Core, 880 MHz, MIPS1004Kc


RAM 256MB DDR3


FLASH storage 16MB serial NOR flash, 256MB serial NAND flash


**FIRMWARE, CONFIGURATION**


WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup


FOTA Update FW


RMS Update FW, configuration for multiple devices at once


Keep settings Update FW without losing current configuration


**FIRMWARE CUSTOMIZATION**


Operating system RutOS (OpenWrt based Linux OS)


Supported languages Busybox shell, Lua, C, C++, and Python, Java in Package manager


Development tools SDK package with build environment provided


**LOCATION TRACKING**


GNSS GPS, GLONASS, BeiDou, Galileo and QZSS


Coordinates GNSS coordinates via WebUI, SMS, TAVL, RMS


NMEA NMEA 0183


NTRIP NTRIP protocol (Networked Transport of RTCM via Internet Protocol)


Server software Supports server software: TAVL, RMS


Geofencing Multiple configurable geofence zones


**USB**


Data rate USB 2.0


Applications Samba share, USB-to-serial


External devices Possibility to connect external HDD, flash drive, additional modem, printer, USB-serial adapter


Storage formats FAT, FAT32, exFAT, NTFS (read-only), ext2, ext3, ext4


**INPUT / OUTPUT**


Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 50 V detected as logic high


Output 1 x Digital Output, Open collector output, max output 50 V, 300 mA


Events SMS, Email, RMS


I/O juggler Allows setting certain I, O conditions to initiate event


**POWER**


Connector 4-pin industrial DC power socket


Input voltage range 9 – 50 VDC, reverse polarity protection, surge protection >51 VDC 10us max


Passive PoE over spare pairs. Possibility to power up through LAN port, not compatible with IEEE802.3af, 802.3at and 802.3bt
PoE (passive)
standards, Mode B, LAN1 Port, 9 - 50 VDC


Power consumption Idle: <5 W, Max: <18 W


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **5**


DATASHEET // RUTM50


**PHYSICAL INTERFACES (PORTS, LEDS, ANTENNAS, BUTTONS, SIM)**


Ethernet 5 x RJ45 ports, 10, 100, 1000 Mbps


I/O’s 1 x Digital Input, 1 x Digital Output on 4-pin power connector


3 x connection status LEDs, 3 x connection strength LEDs, 10 x Ethernet port status LEDs, 4 x WAN status LEDs, 1x Power LED, 2
Status LEDs
x 2.4G and 5G Wi-Fi LEDs


SIM 2 x SIM slot (Mini SIM – 2FF), 1.8 V, 3 V


Power 1 x 4-pin DC power connector


Antennas 4 x SMA for Mobile, 2 x RP-SMA for Wi-Fi, 1 x SMA for GNSS


USB 1 x USB A port for external devices


Reset Reboot, User default reset, Factory reset button


Grounding 1 x Grounding screw


**PHYSICAL SPECIFICATION**


Casing material Aluminum housing


Dimensions (W x H x D) 132 x 44.2 x 95.1 mm


Weight 519 g


Mounting options DIN rail (can be mounted on two sides), flat surface placement


**OPERATING ENVIRONMENT**


Operating temperature -40 °C to 75 °C


Operating humidity 10 % to 90 % non-condensing


Ingress Protection Rating IP30


**REGULATORY & TYPE APPROVALS**


Regulatory FCC, IC, PTCRB


Operator AT&T


**RF**



Standards
(Wi-Fi 2.4 GHz, 5 GHz)


Standards
(4G, 5G)



47 CFR Part 15 Subpart C - § 15.247, Subpart E - § 15.407
RSS-247 Issue 2 (February 2017), RSS-Gen Issue 5 (April 2018) Amendment 2 (February 2021)
KDB 905462 D02 UNII DFS Compliance Procedures New Rules v02
KDB 905462 D04 Operational Modes for DFS Testing New Rules v01


47 CFR Part 2, Part 22 Subpart H, Part 24 Subpart E, Part 27 Subpart C, Part 90 Subpart R/S, Part 96
RSS-130 Issue 2 (February 2019), RSS-132 Issue 3 (January 2013), RSS-133 Issue 6 (January 2018) Amendment, RSS-139 Issue 3
(July 2015), RSS-140 Issue 1 (April 2018), RSS-192 Issue 4 (May 2020), RSS-195 Issue 2 (April 2014), RSS-197 Issue 1 (February
2010), RSS-199 Issue 3 (December 2016), RSS-Gen Issue 5 (April 2018) Amendment 2
SRSP-503 Issue 7 (September 2008), SRSP-510 Issue 5 (February 2009), SRSP-513 Issue 3 (July 2015), SRSP-516 Issue 1 (April
2014), SRSP-517 Issue 1 (July 2014), SRSP-518 Issue 2 (February 2019), SRSP-520 Issue 2 (November 2021)



**EMC EMISSIONS & IMMUNITY**


47 CFR Part 15 Subpart B
Standards
ICES-003: Issue 7 (October 2020)


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **6**


### WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- RUTM50 Router

- 18 W PSU

- 4 x Mobile antennas (swivel, SMA male)

- 2 x WiFi antennas (magnetic mount, RP-SMA male, 1.5 m cable)

- 1 x GNSS antenna (adhesive, SMA male, 3 m cable)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box



DATASHEET // RUTM50



|RUTM50 ROUTER|18 W PSU|4X MOBILE ANTENNAS<br>(SWIVEL SMA MALE)|
|---|---|---|
|**2 X WI-FI ANTENNAS (MAGNETIC**<br>**MOUNT, RP-SMA MALE, 1.5 M CABLE)**|**1 X GNSS ANTENNA (ADHESIVE, SMA**<br>**MALE, 3 M CABLE)**|**ETHERNET CABLE (1.5 M)**|
|**SIM ADAPTER KIT**|**QSG**||



- For all standard order codes standard package contents are the same, except for PSU.





Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUTM50


### STANDARD ORDER CODES

**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUTM50 000000



851762 8517.62.00 Standard package



For more information on all available packaging options – please contact us directly.

### AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



RUTM50 0*****



North America [2]




- **5G NR NSA:** n2, n5, n7, n12, n13, n14, n25, n26, n29,
n30, n38, n41, n48, n66, n70, n71, n77, n78

- **5G NR SA:** 5G NR SA: n2, n5, n7, n12, n13, n14, n25,
n26, n29, n30, n38, n41, n48, n66, n70, n71, n77, n78

- **5G DL 4 × 4 MIMO:** n2, n5, n7, n12, n13*, n14, n25,
n26*, n29, n30, n38, n41, n48, n66, n70, n71, n77, n78

- **4G (LTE-FDD):** B2, B4, B5, B7, B12, B13, B14, B17, B25,
B26, B29, B30, B66, B71

- **4G (LTE-TDD):** B38, B41, B42, B43, B48



The price and lead-times for region (operator) specific versions may vary. For more information

please contact us.

1 - Regional availability - excluding Russia & Belarus.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUTM50


### RUTM50 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTM50:



Device housing*:

Box:



132 x 44.2 x 95.1 mm

355 x 60 x 175 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTM50 and its components as seen from the top:


**RIGHT VIEW**

|101.10<br>95.10<br>132.00|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|Col12|Col13|Col14|Col15|Col16|Col17|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|** 95.10**<br>** 101.10**<br>** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 132.00**|** 101.10**|
|** 95.10**<br>** 101.10**<br>** 132.00**|||||||||||||||||
||||||||||||||||||



The figure below depicts the measurements of RUTM50 and its components as seen from the right side:


**103.10**

|Col1|Col2|Col3|Col4|5.40|
|---|---|---|---|---|
||||||
||||||
||||||
||||||
||||||
||||||
||||||
||||||



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // RUTM50



**FRONT VIEW**


The figure below depicts the measurements of RUTM50 and its components as seen from the front panel side:


**44.20**

**33.42**

**31.08**

**27.48**

**24.24**

**22.05**

**10.64**

**8.55**

**0**


**REAR VIEW**


The figure below depicts the measurements of RUTM50 and its components as seen from the back panel side:


**44.20**


**33.39**


**18.27**

**13.89**

**11.77**

**11.34**

**0**


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // RUTM50



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // RUTM50



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:

|16.64 44.20 199.19|Col2|Col3|Col4|
|---|---|---|---|
|** 199.19**<br>** 44.20**<br>** 16.64**|** 199.19**<br>** 44.20**<br>** 16.64**|** 199.19**<br>** 44.20**<br>** 16.64**||
|** 199.19**<br>** 44.20**<br>** 16.64**|** 199.19**<br>** 44.20**<br>** 16.64**|** 199.19**<br>** 44.20**<br>** 16.64**||
|** 199.19**<br>** 44.20**<br>** 16.64**||||



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


