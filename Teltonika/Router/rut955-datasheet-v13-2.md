# RUT955

Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


**LAN LED**


**Power**
**socket**


BACK VIEW



**LAN Ethernet** **WAN**
**ports** **Ethernet port**



DATASHEET // RUT955


**RS485 interface**

**WAN LED**


**Mobile signal**
**strength**
**indication LEDs**



**RS232**
**interface**



**Input/output**
**connector**



**Mobile AUX** **GNSS antenna** **Mobile MAIN**
**antenna connector** **connector** **antenna connector**





**connector**



|Col1|Col2|Col3|Col4|Col5|
|---|---|---|---|---|
||||||
||||||
|**Reset**<br>**SIM**<br>**USB**<br>|**Reset**<br>**SIM**<br>**USB**<br>||||


**button**



**needle**



POWER SOCKET PINOUT


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


DATASHEET // RUT955


## FEATURES

**MOBILE**


Mobile module



4G (LTE) – Cat 4 up to 150 Mbps, 3G – Up to 42 Mbps, 2G – Up to 236.8 kbps



2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data
SIM switch
connection fail, SIM idle protection



Status


SMS


Black/White list

Band management


APN


Bridge



Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID


SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP

Operator black/white list


Band lock, Used band status display


Auto APN


Direct connection (bridge) between mobile ISP and device on LAN



Passthrough Router assigns its mobile WAN IP address to another device on LAN


Multiple PDN (optional) Possibility to use different PDNs for multiple network access and services (not available in standard FW)


**WIRELESS**


Wireless mode IEEE 802.11b/g/n, Access Point (AP), Station (STA)



WiFi security


SSID



WPA2-Enterprise - PEAP, WPA2-PSK, WEP, WPA-EAP, WPA-PSK; AES-CCMP, TKIP, Auto Cipher modes, client separation


SSID stealth mode and access control based on MAC address



WiFi users up to 100 simultaneous connections


Wireless Hotspot Captive portal (Hotspot), internal/external Radius server, built in customizable landing page


**NETWORK**



Routing


Network protocols


VoIP passthrough support


Connection monitoring



Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2)

TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, FTP, SMTP, SSL v3, TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP, Telnet,
SMPP, MQTT, Wake On Lan (WOL)


H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection



Firewall Port forward, traffic rules, custom rules



DHCP


QoS / Smart Queue
Management (SQM)


DDNS


Network backup



Static and dynamic IP allocation, DHCP Relay, Relayd


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


VRRP, Mobile, Wired and WiFi WAN options, each of which can be used as backup, using automatic Failover



Load balancing Balance your internet traffic over multiple WAN connections


SSHFS (optional) Possibility to mount remote file system via SSH protocol (not available in standard FW)


**SECURITY**



Authentication


Firewall



Pre-shared key, digital certificates, X.509 certificates


Pre-configured firewall rules can be enabled via web-ui, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T



DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (
Attack prevention
SYN-FIN, SYN-RST, X-mas, NULL flags, FIN scan attacks)



VLAN


Mobile quota control


WEB filter


Access control



Port and tag based VLAN separation


Set up custom data limits for both SIM cards


Blacklist for blocking out unwanted websites, whitelist for specifying allowed sites only


Flexible access control of TCP, UDP, ICMP packets, MAC address filter



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


DATASHEET // RUT955


**ETHERNET**


WAN 1 x WAN port (can be configured to LAN) 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX



LAN


**VPN**


OpenVPN


OpenVPN Encryption


IPsec


GRE


PPTP, L2TP


Stunnel



3 x LAN ports, 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX


Multiple clients and server can be running simultaneously, 12 encryption methods


DES-CBC, RC2-CBC, DES-EDE-CBC, DES-EDE3-CBC, DESX-CBC, BF-CBC, RC2-40-CBC, CAST5-CBC, RC2-64-CBC, AES-128-CBC,
AES-192-CBC, AES-256-CBC


IKEv1, IKEv2, supports up to 4 x VPN IPsec tunnels (instances), with 5 encryption methods (DES, 3DES, AES128, AES192, AES256)


GRE tunnel


Client/Server services can run simultaneously


Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the programs' code



DMVPN Method of building scalable IPsec VPNs



SSTP


ZeroTier



SSTP client instance support


ZeroTier VPN



WireGuard WireGuard VPN client and server support


**MODBUS TCP SLAVE**



ID range



Respond to one ID in range [1;255] or any



Allow Remote Access Allow access through WAN


Modbus TCP custom register block requests, which read/write to a file inside the router, and can be used to extend Modbus
Custom registers
TCP Slave functionality


**MODBUS TCP MASTER**



Supported functions


Supported data formats



01, 02, 03, 04, 05, 06, 15, 16


8 bit: INT, UINT; 16 bit: INT, UINT (MSB or LSB first); 32 bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC)



**MODBUS RTU MASTER (RS232)**



Supported baud rates


Supported functions



From 300 to 115200


01, 02, 03, 04, 05, 06, 15, 16



Number of data bits From 5 to 8



Number of stop bits


Parity



1 or 2


None, Even, Odd



Flow None, RTS/CTS, Xon/Xoff


Duplex Full duplex


**MODBUS RTU MASTER (RS485)**



Supported baud rates


Supported functions



From 300 to 115200


01, 02, 03, 04, 05, 06, 15, 16



Number of data bits 8



Number of stop bits


Parity



1


None, Even, Odd



Flow None, Xon/Xoff


Duplex Half duplex


**MODBUS DATA TO SERVER**



Protocol



HTTP(S), MQTT, Azure MQTT



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUT955



**MQTT GATEWAY**


MQTT gateway



Allows sending commands and receiving data from Modbus Master through MQTT broker



**MONITORING & MANAGEMENT**



WEB UI



HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log



FOTA Firmware update from server, automatic notification



SSH


SMS


CALL


TR-069


MQTT


SNMP



SSH (v1, v2)


SMS status, SMS configuration, send/read SMS via HTTP POST/GET


Reboot, Status, WiFi on/off, Mobile data on/off, Output on/off, answer/hang-up with a timer


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher


SNMP (v1, v2, v3), SNMP trap



JSON-RPC Management API over HTTP/HTTPS



MODBUS


RMS


**IoT PLATFORMS**


Clouds of things


ThingWorx



MODBUS TCP status/control


Teltonika Remote Management System (RMS)


Allows monitoring of: Device data, Mobile data, Network info, Availability


Allows monitoring of: WAN Type, WAN IP Mobile Operator Name, Mobile Signal Strength, Mobile Network Type



Allows monitoring of: Device Model, Revision and Serial Number, Mobile Cell ID, ICCID, IMEI, Connection Type, Operator, Signal
Cumulocity
Strength, WAN Type and IP


Can send device IP, Number of bytes send/received/ 3G connection state, Network link state, IMEI, ICCID, Model, Manufacturer,
Azure IoT Hub Serial, Revision, IMSI, Sim State, PIN state, GSM signal, WCDMA RSCP WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID,
Operator, Operator number, Connection type, Temperature, PIN count to Azure IoT Hub server


**SYSTEM CHARACTERISTICS**


CPU Atheros Wasp, MIPS 74Kc, 550 MHz



RAM


FLASH storage



128 MB, DDR2


16 MB, SPI Flash



**FIRMWARE / CONFIGURATION**


WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup, restore point



FOTA


RMS



Update FW/configuration from server


Update FW/configuration for multiple devices



Keep settings Update FW without losing current configuration


**FIRMWARE CUSTOMIZATION**


Operating system RutOS (OpenWrt based Linux OS)



Supported languages


Development tools


**SERIAL**



Busybox shell, Lua, C, C++


SDK package with build environment provided



RS232 DB9 connector, full RS232 (with RTS, CTS)



RS485


Serial functions



RS485 Full Duplex (4 wires) and Half Duplex (2 wires). 300-115200 baud rate


Console, Serial over IP, Modem, Modbus gateway, NTRIP Client



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


DATASHEET // RUT955



**LOCATION TRACKING**


GNSS


Coordinates


NMEA


NTRIP


Server software



GPS, GLONASS, BeiDou, Galileo and QZSS


GNSS coordinates via WebUI, SMS, TAVL, RMS


NMEA 0183


NTRIP protocol (Networked Transport of RTCM via Internet Protocol)


Supported server software TAVL, RMS



Geofencing Configurable multiple geofence zones


**INPUT/OUTPUT**


1 x digital input (0 - 3 V), 1 x digital galvanically isolated input (0 - 30 V), 1 x analog input (0 - 24 V), 1 x Digital non-isolated input
Input
(on 4 pin power connector)


1 x digital open collector output (30 V, 250 mA), 1 x SPST relay output (40 V, 4 A), 1 x Digital open collector output (30 V, 300 mA,
Output
on 4 pin power connector)


Events SMS, EMAIL, RMS


**USB**



Data rate


Applications


External devices


Storage formats


**SD CARD**


Physical size


Applications


Capacity



USB 2.0


Samba share, USB-to-serial


Possibility to connect external HDD, flash drive, additional modem, printer


FAT, FAT32, NTFS


Micro SD


Samba share, Storage Memory Expansion, DLNA


Up to 64 GB



Storage Formats FAT32, NTFS, ext2, ext3, ext4


**POWER**


Connector 4 pin industrial DC power socket



Input voltage range


PoE (passive)



9 – 30 VDC reverse polarity protection; surge protection >31 VDC 10us max


Passive PoE over spare pairs. Possibility to power up through LAN port, not compatible with IEEE802.3af, 802.3at and 802.3bt
standards



Power consumption < 2 W idle, < 7 W Max


**PHYSICAL INTERFACES (PORTS, LEDS, ANTENNAS, BUTTONS, SIM)**


Ethernet 4 x RJ45 ports, 10/100 Mbps



I/O’s


Status LEDs



2 x Inputs and 2 x Outputs on 10 pin industrial socket, 1 x Digital input and 1 x Digital output on 4 pin power connector
(available from HW revision 1600)


1 x bi-color connection status LED, 5 x connection strength LEDs, 4 x LAN status LEDs, 1 x Power LED



SIM 2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders, eSIM (Optional)



Power


Input/output



1 x 4 pin power connector


1x 10 pin industrial socket for inputs/outputs



Antennas 2 x SMA for LTE, 2 x RP-SMA for WiFi, 1 x SMA for GNSS


USB 1 x USB A port for external devices


SD card Micro SD card slot



RS232


RS485



1 x DB9 socket


1 x 6 pin industrial socket



Reset Reboot/User default reset/Factory reset button


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // RUT955



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



Regulatory


Operator



CE/RED, FCC, IC/ISED, EAC, RCM, PTCRB, RoHS, WEEE, Wi-Fi Alliance CE/RED, FCC, IC, PTCRB, RCM, EAC, CCC, RoHS, WEEE, IP
rating, Anatel, GCF, REACH, E-mark, DNV GL, ECE Regulation 118, Morocco ANRT, Thailand NBTC, Ukraine UCRF, SDPPI
(POSTEL), WiFi Certified, Modbus Conformance


AT&T, Verizon



ECE R10 (E-mark)
Regulatory
ECE R118


**EMI IMMUNITY**



Standards


ESD


RS


EFT



Draft EN 301 489-1 V2.2.0, Draft EN 301 489-17 V3.2.0, Draft EN 301 489-19 V2.1.0, Draft EN 301 489-52 V1.1.0
FCC 47 CFR Part 15B (2017), ANSI C63.4 (2014)


EN61000-4-2:2009


EN 61000-4-3:2006 + A1:2008 + A2:2010


EN 61000-4-4:2012



Surge immunity
EN 61000-4-5:2006
(AC Power Line)



Surge immunity
(Ethernet ports)


Transient and surges



EN 61000-4-5:2014, clause 7.1 of ITU-T K21


ISO 7632-2:2004



CS EN 61000-4-6:2009


DIP EN 61000-4-11:2004


**RF**



Standards


**SAFETY**


Standards


**ENVIRONMENTAL**



EN 300 328 V2.1.1, EN 301 511 V12.5.1, EN 301 908-1 V11.1.1, EN 301 908-2 V11.1.1, EN 301 908-13 V11.1.1, EN 303 413 V1.1.0
AS/CA S042.1:2018, AS/ACIF S042.3:2005, AS/CA S042.4:2018, AS/NZS 4268:2017
FCC 47 CFR Part 15C (2017), FCC 47 CFR Part 2 (2017), FCC 47 CFR Part 22H (2017), FCC 47 CFR Part 24E (2017), FCC 47 CFR Part
27C (2017)
RSS-Gen Issue 4 (2014), RSS-247 Issue 2 (2017), RSS-132 Issue 3 (2013), RSS-133 Issue 6 (2013), RSS-139 Issue 3, RSS-130 Issue 1


IEC 60950-1:2005 (Second Edition) + Am 1:2009 + Am 2:2013
AS/NZS 60950.1:2015
EN 50665:2017, EN 62311:2008
FCC 47 CFR Part 1 1.1310
RSS-102 Issue 5 (2015)



Ingress Protect LST EN 60529:1999+A1+AC:2002


Class guideline-DNVGL-CG-0339:2016
Vibration
EN 60068-2-6:2008


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUT955

## HARDWARE INSTALLATION


1. Push the SIM holder button with the SIM needle.
2. Pull out the SIM holder.
3. Insert your SIM card into the SIM holder.
4. Slide the SIM holder back into the router.
5. Attach all antennas.
6. Connect the power adapter to the socket on the front of the device. Then plug the other end of the power adapter into a power outlet.
7. Connect to the device wirelessly using SSID and password provided on the device information label or use an Ethernet cable connected to
LAN port.


LOGIN TO DEVICE


1. To enter the router's Web interface (WebUI), type http://192.168.1.1 into the URL field of your Internet browser.
2. Use login information shown in image A when prompted for authentication.
3. After you log in, you will be prompted to change your password for security reasons. The new password must contain at least 8 characters,
including at least one uppercase letter, one lowercase letter, and one digit. This step is mandatory, and **you will not be able to interact with**
**the router's WebUI before you change the password.**
4. When you change the router's password, the Configuration Wizard will start. The Configuration Wizard is a tool used to set up some of the
router's main operating parameters.
5. Go to the Overview page and pay attention to the Signal Strength indication (image B). To maximize the cellular performance try adjusting
the antennas or changing the location of your device to achieve the best signal conditions.











TECHNICAL INFORMATION










|Radio specifications|Col2|
|---|---|
|RF technologies|2G, 3G, 4G, WiFi, GNSS|
|Max RF power|33 dBm@GSM, 24 dBm@WCDMA, 23 dBm@LTE, 20 dBm@ WiFi|
||**Bundled accessories speciﬁcations***|
|Power adapter|Input: 0.4A@100-240VAC, Output: 9VDC, 1A, 4-pin plug|
|Mobile antenna|698~960/1710~2690 MHz, 50 Ω, VSWR<3, gain** 3 dBi, omnidirectional, SMA male connector|
|WiFi antenna|2400~2483.5 MHz, 50 Ω, VSWR<2, gain** 5 dBi, omnidirectional, RP-SMA male connector|
|GNSS antenna|1575.42~1602 MHz, 2.2~5 VDC, VSWR<1.5, gain** 28 dB (typ.), RHCP polarization, SMA male connector|



*Order code dependent.
**Higher gain antenna can be connected to compensate for cable attenuation when a cable is used. The user is responsible for the compliance with the legal regulations.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUT955

- 9 W PSU

- 2 x LTE antennas (magnetic mount, SMA male, 3 m cable)

- 2 x WiFi antennas (magnetic mount, RP-SMA male, 1.5 m cable)

- GNSS antenna (adhesive, SMA male, 3 m cable)

- RS485 connector block

- I/O connector block

- Ethernet cable (1.5 m)

- SIM Adapter kit

- RMS Flyer

- QSG (Quick Start Guide)

- Packaging box



DATASHEET // RUT955







|ROUTER RUT955|9 W PSU|2 X LTE ANTENNAS (MAGNETIC<br>MOUNT, SMA MALE, 3 M CABLE)|
|---|---|---|
|**2 X WIFI ANTENNAS (MAGNETIC**<br>**MOUNT, RP-SMA MALE, 1.5 M CABLE)**|**GNSS ANTENNA (ADHESIVE, SMA**<br>**MALE, 3 M CABLE)**|**RS485 CONNECTOR BLOCK**|
|**I/O CONNECTOR BLOCK**|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**|



- For all standard order codes standard package contents are the same, execpt for PSU.





Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // RUT955

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUT955 T033B0



851762 8517.62.00 Standard package with Euro PSU



RUT955 K034S0 851762 8517.62.00 Standard package with US PSU


RUT955 J034S0 851762 8517.62.00 Standard package with US PSU


RUT955 W03660 851762 8517.62.00 Standard package with US PSU


For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**


4G (LTE-FDD): B1, B3, B5, B7, B8, B20

4G (LTE-TDD): B40
RUT955 0***** Europe [1], the Middle East, Africa
3G: B1, B5, B8

2G: B3, B8



Europe [1], the Middle East, Africa,
RUT955 T*****
Korea, Thailand, India, Malaysia


Europe [1], the Middle East, Africa,
RUT955 H*****
Korea, Thailand, India, Malaysia


RUT955 J***** North America (AT&T, Bell, T-Mobile) [1]


RUT955 K***** North America (Verizon)



4G (LTE-FDD): B1, B3, B7, B8, B20, B28A
4G (LTE-TDD): B38, B40, B41
3G: B1, B8
2G: B3, B8


4G (LTE-FDD): B1, B3, B5, B7, B8, B20
4G (LTE-TDD): B38, B40, B41
3G: B1, B5, B8
2G: B3, B8


4G (LTE-FDD): B2, B4, B12
3G: B2, B4, B5


4G (LTE-FDD): B4, B13



4G (LTE-FDD): B2, B4, B5, B12, B13, B14, B66, B71
RUT955 W***** North America (AT&T/ Verizon/ T-mobile)
3G: B2, B4, B5



South America, Australia, New Zealand,
RUT955 M*****
Taiwan



4G (LTE-FDD): B1, B2, B3, B4, B5, B7, B8, B28
4G (LTE-TDD): B40
3G: B1, B2, B5, B8
2G: B2, B3, B5, B8



4G (LTE-FDD): B1, B3, B8, B18, B19, B26
RUT955 P***** Japan 4G (LTE-TDD): B41
3G: B1, B6, B8, B19


4G (LTE-FDD): B1, B2, B3, B4, B5, B7, B8, B12,
B13, B18, B19, B20, B25, B26, B28

RUT955 V***** Global [1] 4G (LTE-TDD): B38, B39, B40, B41
3G: B1, B2, B4, B5, B6, B8, B19
2G: B2, B3, B5, B8



4G (LTE-FDD): B1, B3, B7, B8, B20, B28A



Europe [1], the Middle East, Africa, Korea, 4G (LTE-TDD): B38, B40, B41
RUT955 Z*****
Thailand 3G: B1, B8



2G: B3, B8



The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 - Regional availability - excluding Russia & Belarus.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // RUT955


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



**11**


DATASHEET // RUT955


## RUT955 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUT955:



Device housing*:

Box:



110 x 50 x 100

355 x 60 x 175



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUT955 and its components as seen from the top:


**RIGHT VIEW**

|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|
|---|---|---|---|---|---|---|---|---|
|ements of RUT955 and its components as seen from the right side:|ements of RUT955 and its components as seen from the right side:|ements of RUT955 and its components as seen from the right side:|ements of RUT955 and its components as seen from the right side:|ements of RUT955 and its components as seen from the right side:|ements of RUT955 and its components as seen from the right side:|ements of RUT955 and its components as seen from the right side:|ements of RUT955 and its components as seen from the right side:|ements of RUT955 and its components as seen from the right side:|
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



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


DATASHEET // RUT955



**FRONT VIEW**


The figure below depicts the measurements of RUT955 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUT955 and its components as seen from the back panel side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**13**


DATASHEET // RUT955



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**14**


DATASHEET // RUT955



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**15**


