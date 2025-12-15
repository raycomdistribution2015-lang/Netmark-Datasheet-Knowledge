# RUTX09

Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


**WAN type LEDs**


**SIM needle**


**Power socket**


BACK VIEW


POWER SOCKET PINOUT



**Mobile MAIN antenna**
**connector**


**Grounding**
**screw**


**Power / Red wire**


**Input / Green wire**



DATASHEET // RUTX09


**SIM holders**



**Mobile network type**
**LEDs**



**Mobile signal strength**
**indication LEDs**



**Power**
**LED**



**Reset** **LAN Ethernet** **WAN Ethernet**
**button** **ports** **port**



**GNSS antenna** **Mobile AUX antenna**
**connector** **connector**


**USB port**


**Ground / Black wire**


**Output / White wire**



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


## FEATURES

**MOBILE**


Mobile module


SIM switch


Status


SMS


USSD


Black/White list


Multiple PDN


Band management



DATASHEET // RUTX09


4G (LTE) – Cat 6 up to 300 Mbps, 3G – Up to 42 Mbps


2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail


Signal strength, SINR, RSRP, RSRQ, Bytes sent/received, connected band, carrier aggregation, IMSI, ICCID


SMS status, SMS configuration, send/read SMS via HTTP POST/GET, Email to SMS, SMS to Email, SMS to HTTP, SMS to SMS, SMS
auto reply


Supports sending and reading Unstructured Supplementary Service Data messages


Operator black/white list


Possibility to use different PDNs for multiple network access and services


Band lock, Used band status display



APN Auto APN


Bridge mode Direct connection (bridge) between mobile ISP and device on LAN


**ETHERNET**


1 x WAN port (can be configured as LAN) 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards,
WAN
supports auto MDI/MDIX crossover



LAN


**NETWORK**


Routing


Network protocols


VoIP passthrough support


Connection monitoring



3 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
crossover


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP)


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, FTP, SMTP, SSL v3, TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP, Telnet
client, SNMP, MQTT, Wake on LAN (WOL)


H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Ping Reboot, Wget reboot, Periodic Reboot, LCP and ICMP for link inspection



Firewall Port forwards, traffic rules, custom rules



DHCP


QoS / Smart Queue
Management (SQM)


DDNS


Network backup



Static and dynamic IP allocation, DHCP Relay, Relayd


Traffic priority queuing by source/destination, service, protocol or port


Supported >25 service providers, others can be configured manually


VRRP, Mobile and Wired WAN options, each of which can be used as an automatic Failover



Load balancing Balance Internet traffic over multiple WAN connections



Hospot


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


Mobile quota control


WEB filter


Access control



Port and tag based VLAN separation


Custom data limits for both SIM cards


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Flexible access control of TCP, UDP, ICMP packets, MAC address filter



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


DATASHEET // RUTX09



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


**MODBUS TCP MASTER**



Supported functions



01, 02, 03, 04, 05, 06, 15, 16



8 bit: INT, UINT; 16 bit: INT, UINT (MSB or LSB first); 32 bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC), HEX, ASCII


**MQTT GATEWAY**


Gateway Allows sending commands and receiving data from Modbus Master trough MQTT broker


**DATA TO SERVER**


Protocols HTTP(S), MQTT, Azure MQTT, Kinesis


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


SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to Email, SMS to HTTP, SMS to SMS,
SMS autoreply


Reboot, Status, Mobile data on/off, Output on/off


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher


SNMP (v1, v2, v3), SNMP trap



JSON-RPC Management API over HTTP/HTTPS


MODBUS MODBUS TCP status/control


RMS Teltonika Remote Management System (RMS)


**SYSTEM CHARACTERISTICS**


CPU Quad-core ARM Cortex A7, 717 MHz



RAM


FLASH storage



256 MB, DDR3


256 MB, SPI Flash



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUTX09



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


**LOCATION TRACKING**



Busybox shell, Lua, C, C++


SDK package with build environment provided



GNSS GPS, GLONASS, BeiDou, Galileo and QZSS



Coordinates


NMEA



GNSS coordinates via WebUI, SMS, TAVL, RMS


NMEA 0183



Server software Supported server software: TAVL, RMS


Geofencing Configurable multiple geofence zones


**USB**



Data rate


Applications


External devices


Storage formats


**INPUT/OUTPUT**


Input


Output



USB 2.0


Samba share, USB-to-serial


Possibility to connect external HDD, flash drive, additional modem, printer


FAT, FAT32, NTFS


1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high


1 x Digital Output, Open collector output, max output 30 V, 300 mA



Events SMS, Email, RMS


I/O juggler Allows to set certain I/O conditions to initiate event


**POWER**



Connector


Input voltage range


PoE (passive)


Power consumption



4 pin industrial DC power socket


9 – 50 VDC, reverse polarity protection, voltage surge/transient protection


Passive PoE. Possibility to power up through LAN port, not compatible with IEEE 802.3af, 802.3at and 802.3bt standards


9 W Max



**PHYSICAL INTERFACES (PORTS, LEDS, ANTENNAS, BUTTONS, SIM)**


Ethernet 4 x RJ45 ports, 10/100/1000 Mbps



I/Os


Status LEDs



1 x Digital Input, 1 x Digital Output on 4 pin power connector


3 x WAN type, 2 x Mobile connection type, 5 x Mobile connection strength, 8 x LAN status, 3 x WAN status, 1x Power



SIM 2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders



Power


Antennas



1 x 4 pin DC connector


2 x SMA for LTE, 1 x SMA for GNNS



USB 1 x USB A port for external devices


Reset Reboot/User default reset/Factory reset button


Other 1 x Grounding screw


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


DATASHEET // RUTX09



**PHYSICAL SPECIFICATION**


Casing material Aluminium housing with DIN rail mounting option



Dimensions (W x H x D)


Weight



115 x 44.2 x 95.1 mm


455 g



Mounting options DIN rail, flat surface placement


**OPERATING ENVIRONMENT**


Operating temperature -40 C to 75 C



Operating humidity


Ingress Protection Rating



10 % to 90 % non-condensing


IP30



**REGULATORY & TYPE APPROVALS**



Regulatory


**EMI IMMUNITY**


Standards


EN61000-4-2:2009


RS


EFT



CE/RED, EAC, RoHS, WEEE


Draft EN 301 489-1 V2.2.0, Draft EN 301 489-19 V2.1.0, Draft EN 301 489-52 V1.1.0


ESD


EN 61000-4-3:2006 + A1:2008 + A2:2010


EN 61000-4-4:2012



Surge protection EN 61000-4-5:2014



CS


DIP


**RF**


Standards


**SAFETY**


Standards



EN 61000-4-6:2014


EN 61000-4-11:2014


EN 301 908-1 V11.1.1, EN 301 908-2 V11.1.1, EN 301 908-13 V11.1.2, EN303 413 V1.1.1


IEC 62368-1:2014, EN 62368-1:2014 + A11:2017
EN 50665:2017, EN 62311:2008



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // RUTX09

## HARDWARE INSTALLATION


1. Pull out the SIM needle from the front panel of the router.
2. Push the SIM holder button with the SIM needle.
3. Pull out the SIM holder.
4. Insert your SIM card into the SIM holder.
5. Slide the SIM holder back into the router.
6. Attach all antennas.
7. Connect the power adapter to the socket on the front of the device. Then plug the other end of the power adapter into a power outlet.
8. Connect to the device via an Ethernet cable connected to LAN port.


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








|Col1|Col2|
|---|---|
||admin<br>admin01|
|||



TECHNICAL INFORMATION







|Radio specifications|Col2|
|---|---|
|RF technologie|s<br>3G, 4G, GNSS|
|Max RF power|24 dBm@WCDMA, 23 dBm@LTE|
|**Bundled accessories speciﬁcations***|**Bundled accessories speciﬁcations***|
|Power adapter|<br>Input: 0.6A@100-240VAC, Output: 12VDC, 1.5A, 4-pin plug|
|Mobile antenn|a<br>698~960/1710~2690 MHz, 50 Ω, VSWR<3, gain** 3 dBi, omnidirectional, SMA male connector|
|GNSS antenna|1575.42~1602 MHz, 2.2~5 VDC, VSWR<1.5, active total gain** 28 dB (typ.), RHCP polarization, SMA male connector|


*Order code dependent.
**Higher gain antenna can be connected to compensate for cable attenuation when a cable is used. The user is responsible for the compliance with the legal regulations.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUTX09

- 18 W PSU

- 2 x LTE antennas (swivel, SMA male)

- 1 x GNSS antenna (adhesive, SMA male, 3 m cable)

- SIM Adapter kit

- Ethernet cable (1.5 m)

- QSG (Quick Start Guide)

- RMS Flyer

- Packaging box





|ROUTER RUTX09|18 W PSU|2 X LTE ANTENNA (MAGNETIC<br>MOUNT, SMA MALE, 3 M CABLE)|
|---|---|---|
|**1 X GNSS ANTENNA (ADHESIVE, SMA**<br>**MALE, 3 M CABLE)**|**SIM ADAPTER KIT**|**ETHERNET CABLE (1.5 M)**|



   - For all standard order codes standard package contents are the same, execpt for PSU.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUTX09


## STANDARD ORDER CODES

**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUTX09000000



851762 8517.62.00 Standard package



For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



4G (LTE-FDD): B1, B3, B5, B7, B8, B20, B28, B32 [1]

4G (LTE-TDD): B38, B40, B41
3G: B1, B3, B5, B8



RUTX09 0*****



Europe, the Middle East, Africa, APAC [2],
Brazil



4G (LTE-FDD): B2, B4, B5, B7, B12, B13, B25, B26, B29 [1], B30,
RUTX09 1***** North America B66
3G: B2, B4, B5


RUTX09 4***** Australia 4G (LTE-FDD): B3, B7, B28


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 - LTE-FDD B29 and B32 Support Rx Only, and in 2×CA it is Only for Secondary Component Carrier.
2 - Excluding Japan and CMCC.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // RUTX09


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



**10**


DATASHEET // RUTX09


## RUTX09 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTX09:



Device housing*:

Box:



115 x 44.2 x 95.1

355 x 60 x 175



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTX09 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUTX09 and its components as seen from the right side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // RUTX09



**FRONT VIEW**


The figure below depicts the measurements of RUTX09 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUTX09 and its components as seen from the back panel side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


DATASHEET // RUTX09



**MOUNTING SPACE REQUIREMENTS**



The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**13**


DATASHEET // RUTX09



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**14**


