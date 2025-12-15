Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


**LAN LEDs**


**Power**
**socket**


BACK VIEW



**LAN Ethernet** **WAN**
**ports** **Ethernet port**



DATASHEET // RUT956


**RS485 interface**

**WAN LED**


**Mobile signal**
**strength**
**indication LEDs**



**RS232**
**interface**



**Input/output**
**connector**


**Mobile MAIN antenna**
**connector (SMA female)**



**Mobile AUX antenna**
**connector (SMA female)**





**port**



|Col1|GPS antenna connector<br>(SMA female)|Col3|Col4|Col5|
|---|---|---|---|---|
||||||
||||||
|**Reset**<br>**SIM**<br>**USB**<br>|**Reset**<br>**SIM**<br>**USB**<br>||||


**button**



**needle**



POWER SOCKET PINOUT


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **2**


DATASHEET // RUT956


l



l


## FEATURES

**MOBILE**


Mobile module


l



l



4G (LTE) – Cat 4 up to 150 Mbps, 3G – Up to 42 Mbps, 2G – Up to 236.8 kbps


l



2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data
SIM switch
connection fail, SIM idle protection


l



Status


SMS


USSD


Black/White list


Multiple PDN


Band management


l



Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID


SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP


Supports sending and reading Unstructured Supplementary Service Data messages


Operator black/white list


Possibility to use different PDNs for multiple network access and services


Band lock, Used band status display


l



APN Auto APN


Bridge Direct connection (bridge) between mobile ISP and device on LAN


Passthrough Router assigns its mobile WAN IP address to another device on LAN


**WIRELESS**


Wireless mode IEEE 802.11b/g/n, Access Point (AP), Station (STA)


l



Wi-Fi security


SSID/ESSID


l



WPA2-Enterprise - PEAP, WPA2-PSK, WEP, WPA-EAP, WPA-PSK; AES-CCMP, TKIP, Auto Cipher modes, client separation


SSID stealth mode and access control based on MAC address


l



Wi-Fi users Up to 100 simultaneous connections


Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
Wireless Hotspot user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes


Wireless Connectivity Features Fast roaming (802.11r), Relayd


Wireless MAC filter Whitelist, blacklist


**ETHERNET**


WAN 1 x WAN port 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX


l



LAN

**NETWORK**


Routing


Network protocols


VoIP passthrough support


Connection monitoring


l



3 x LAN ports, 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)


H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


l



Firewall ort forward, traffic rules, custom rules


l



DHCP


QoS / Smart Queue
Management (SQM)


DDNS


Network backup


l



Static and dynamic IP allocation, DHCP Relay


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover


l



Load balancing Balance Internet traffic over multiple WAN connections


SSHFS Possibility to mount remote file system via SSH protocol

**SECURITY**


l



Authentication


Firewall


l



Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block


Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T


l



DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
Attack prevention
SYN-RST, X-mas, NULL flags, FIN scan attacks)



l


VLAN


Mobile quota control


WEB filter


Access control



l


Port and tag-based VLAN separation


Mobile data limit, customizable period, start time, warning limit, phone number


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Flexible access control of TCP, UDP, ICMP packets, MAC address filter



l


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



l


**3**


**VPN**


OpenVPN


OpenVPN Encryption


IPsec


GRE


PPTP, L2TP


Stunnel



DATASHEET // RUT956


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


SSTP SSTP client instance support


ZeroTier ZeroTier VPN client support



WireGuard


Tinc


**MODBUS TCP SLAVE**


ID range



WireGuard VPN client and server support


Tinc offers encryption, authentication and compression in it's tunnels. Client and server support


Respond to one ID in range [1;255] or any



Allow Remote Access Allow access through WAN


MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Slave functionality


**MODBUS TCP MASTER**



Supported functions


Supported data formats



01, 02, 03, 04, 05, 06, 15, 16


8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC)



**MODBUS RTU MASTER (RS232)**



Supported baud rates



From 300 to 115200



Supported functions 01, 02, 03, 04, 05, 06, 15, 16



Supported data formats



8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC), HEX, ASCII



Number of data bits From 5 to 8


Number of stop bits 1 or 2


Parity None, Even, Odd



Flow


Duplex



None, RTS/CTS, Xon/Xoff


Full duplex



**MODBUS RTU MASTER (RS485)**



Supported baud rates



From 300 to 230400



Supported functions 01, 02, 03, 04, 05, 06, 15, 16



Supported data formats



8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC), HEX, ASCII



Number of data bits 8


Number of stop bits 1


Parity None, Even, Odd



Flow


Duplex


**DATA TO SERVER**



None, Xon/Xoff


Half duplex



Protocol HTTP(S), MQTT, Azure MQTT, Kinesis


**MQTT GATEWAY**


MQTT Gateway Allows sending commands and receiving data from MODBUS Master through MQTT broker


**DNP3**


Supported modes TCP Master, DNP3 Outstation, RTU Master


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUT956



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


**LOCATION TRACKING**


GNSS



Busybox shell, Lua, C, C++


SDK package with build environment provided


GPS, GLONASS, BeiDou, Galileo and QZSS



Coordinates GNSS coordinates via WebUI, SMS, TAVL, RMS



NMEA


NTRIP


Server software


Geofencing


**SERIAL**



NMEA 0183


NTRIP protocol (Networked Transport of RTCM via Internet Protocol)


Supported server software TAVL, RMS


Configurable multiple geofence zones



RS232 DB9 connector, RS232 (with RTS, CTS flow control)


RS485 RS485 Full Duplex (4 wires) and Half Duplex (2 wires). 300-115200 baud rate


Serial functions Console, Serial over IP, Modem, MODBUS gateway, NTRIP Client


**USB**


Data rate USB 2.0


Applications Samba share, USB-to-serial


External devices Possibility to connect external HDD, flash drive, additional modem, printer, USB-serial adapter


Storage formats FAT, FAT32, exFAT, NTFS (read-only), ext2, ext3, ext4


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


DATASHEET // RUT956


**INPUT / OUTPUT**

1 x digital dry input (0 - 3 V), 1 x digital galvanically isolated input (0 - 30 V), 1 x analog input (0 - 24 V), 1 x Digital non-isolated
Input
input (on 4-pin power connector, 0 - 5 V detected as logic low, 8 - 30 V detected as logic high)

1 x digital open collector output (30 V, 250 mA), 1 x SPST relay output (40 V, 4 A), 1 x Digital open collector output (30 V, 300 mA,
Output
on 4-pin power connector)


Events Email, RMS, SMS


I/O juggler Allows to set certain I/O conditions to initiate event

**POWER**


Connector 4-pin industrial DC power socket



Input voltage range


PoE (passive)



9 – 30 VDC, reverse polarity protection; surge protection >31 VDC 10us max


Passive PoE over spare pairs. Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at and 802.3bt
standards, Mode B, 9 - 30 VDC



Power consumption < 2 W idle, < 7 W Max

**PHYSICAL INTERFACES**


Ethernet 4 x RJ45 ports, 10/100 Mbps


2 x Inputs and 2 x Outputs on 10-pin industrial socket, 1 x Digital input and 1 x Digital output on 4-pin power connector
I/O’s
(available from HW revision 1600)


Status LEDs 1 x Bi-color connection status, 5 x Mobile connection strength, 4 x ETH status, 1 x Power



SIM


Power



2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders, eSIM (Optional)


1 x 4-pin power connector



Input/output 1 x 10-pin industrial socket for inputs/outputs


Antennas 2 x SMA for LTE, 2 x RP-SMA for Wi-Fi, 1 x SMA for GNSS



USB


RS232



1 x USB A port for external devices


1 x DB9 socket



RS485 1 x 6-pin industrial socket


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


Regulatory CE/RED, UKCA, CB, EAC, RoHS, REACH, CITC, ICASA, ANRT, RCM, SIRIM, IMDA, ETA-WPC, GITEKI, FCC, IC, PTCRB, UL/CSA, Anatel, NOM, E-mark


Operator AT&T, FirstNet, Verizon, T-Mobile, UScellular

**EMC EMISSIONS & IMMUNITY**



Standards


ESD


RS


EFT

Surge immunity
(AC Power Line)


CS


DIP

**RF**



EN 301 489-1 V2.2.3, EN 301 489-17 V3.2.4, Draft EN 301 489-19 V2.2.0, Final draft EN 301 489-52 V1.2.0, EN
55032:2015+A1:2020, EN 55035:2017+A11:2020, EN 61000-3-3:2013+A1:2019, EN IEC 61000-3-2:2019


EN 61000-4-2:2009


EN 61000-4-3:2020


EN 61000-4-4:2012


EN 61000-4-5:2014+A1:2017


EN 61000-4-6:2009


EN IEC 61000-4-11:2020



Standards EN 300 328 V2.2.2, EN 301 908-1 V13.1.1, EN 301 908-2 V13.1.1, EN 301 908-13 V13.1.1, EN 303 413 V1.1.1

**SAFETY**



Standards



EN IEC 62311:2020
AS/NZS 60950.1:2015
IEC 62368-1:2018,
EN IEC 62368-1:2020+A11:2020



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUT956



DATASHEET // RUT956







|• Router RUT956<br>• 9 W PSU<br>• 2 x LTE antennas (magnetic mount, SMA male, 3 m cable)<br>• 2 x WiFi antennas (magnetic mount, RP-SMA male, 1.5 m cable)<br>• GNSS antenna (adhesive, SMA male, 3 m cable)<br>• RS485 connector block<br>• I/O connector block<br>• Ethernet cable (1.5 m)<br>• SIM Adapter kit<br>• QSG (Quick Start Guide)<br>• Packaging box|Col2|ROUTER RUT956|
|---|---|---|
|**9 W PSU**|**2 X LTE ANTENNAS (MAGNETIC MOUNT,**<br>**SMA MALE, 3 M CABLE)**|**2 X WI-FI ANTENNAS (MAGNETIC MOUNT,**<br>**RP-SMA MALE, 1.5 M CABLE)**|
|**GNSS ANTENNA (ADHESIVE, SMA**<br>**MALE, 3 M CABLE)**|**RS485 CONNECTOR BLOCK**|**I/O CONNECTOR BLOCK**|
|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**|**QSG**|



- For all standard order codes standard package contents are the same, execpt for PSU.





Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUT956

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUT956 100000



851762 8517.62.00 Standard package with EU PSU



RUT956 200000 851762 8517.62.00 Standard package with EU PSU


RUT956 400000 851762 8517.62.00 Standard package with EU PSU


RUT956 700700 851762 8517.62.00 Standard package with AU PSU


RUT956 A00A00 851762 8517.62.00 Standard package with US PSU


RUT956 900C00 851762 8517.62.00 Standard package with JP PSU


For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



RUT956 1*****


RUT956 2*****


RUT956 4*****


RUT956 7*****



Europe [1], The Middle East, Africa, Korea, Thailand


Europe [1], The Middle East, Korea, Thailand


Global [1]


South America, Australia, New Zealand, Taiwan




**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B20

**• 4G (LTE-TDD):** B40

**• 3G:** B1, B5, B8

**• 2G:** B3, B8


**• 4G (LTE-FDD):** B1, B3, B7, B8, B20, B28A

**• 4G (LTE-TDD):** B38, B40, B41

**• 3G:** B1, B8

**• 2G:** B3, B8


**• 4G (LTE-FDD):** B1, B2, B3, B4, B5, B7, B8, B12,
B13, B18, B19, B20, B25, B26, B28

**• 4G (LTE-TDD):** B38, B39, B40, B41

**• 3G:** B1, B2, B4, B5, B6, B8, B19

**• 2G:** B2, B3, B5, B8


**• 4G (LTE-FDD):** B1, B2, B3, B4, B5, B7, B8, B28

**• 4G (LTE-TDD):** B40

**• 3G:** B1, B2, B4, B5, B8

**• 2G:** B2, B3, B5, B8




**• 4G (LTE-FDD):** B2, B4, B5, B12, B13, B14, B66, B71
RUT956 A***** North America [2]

**• 3G:** B2, B4, B5


**• 4G (LTE-FDD):** B1, B3, B8, B18, B19, B26
RUT956 9***** Japan **• 4G (LTE-TDD):** B41

**• 3G:** B1, B6, B8, B19



RUT956 200505



Thailand




**• 4G (LTE-FDD):** B1, B3, B7, B8, B20

**• 4G (LTE-TDD):** B38, B40

**• 3G:** B1, B8

**• 2G:** B3, B8



The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 - Regional availability - excluding Russia & Belarus.
2 - For more detailed information about certified carriers, visit our Wiki page.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUT956


## RUT956 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUT956:



Device housing*:

Box:



110 x 50 x 100 mm

355 x 60 x 175 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUT956 and its components as seen from the top:


**RIGHT VIEW**

|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|
|---|---|---|---|---|---|---|---|---|
|ements of RUT956 and its components as seen from the right side:|ements of RUT956 and its components as seen from the right side:|ements of RUT956 and its components as seen from the right side:|ements of RUT956 and its components as seen from the right side:|ements of RUT956 and its components as seen from the right side:|ements of RUT956 and its components as seen from the right side:|ements of RUT956 and its components as seen from the right side:|ements of RUT956 and its components as seen from the right side:|ements of RUT956 and its components as seen from the right side:|
||||||||||
||||||||||
||||||||||
||||||||||
||||||||||
||||||||||
||||||||||
||||||||||
||||||||||
||||||||||
||||||||||
||||||||||



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // RUT956


**FRONT VIEW**


The figure below depicts the measurements of RUT956 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUT956 and its components as seen from the back panel side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **10**


DATASHEET // RUT956


**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **11**


DATASHEET // RUT956


**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **12**


