Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


**WAN type LEDs**


**SIM needle**


**Power socket**


BACK VIEW


POWER SOCKET PINOUT



**screw**

**WiFi antenna** **WiFi antenna**
**connector** **connector**
**(RP-SMA female)** **(RP-SMA female)**


**Power / Red wire**


**Input / Green wire**



**Mobile network type**
**LEDs**



**Mobile signal strength**
**indication LEDs**



**Power** **Reset** **LAN Ethernet** **WAN Ethernet**
**LED** **button** **ports** **port**



**Mobile MAIN antenna**
**connector (SMA female)**



**GNSS antenna** **Mobile AUX antenna**
**connector (SMA female)** **connector (SMA female)**



DATASHEET // RUTX11


**SIM holders**


**WAN LEDs**


**USB port**



**(RP-SMA Female)**


**Ground / Black wire**


**Output / White wire**



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


DATASHEET // RUTX11


## FEATURES

**MOBILE**

Mobile module



4G (LTE) – Cat 6 up to 300 Mbps, 3G – Up to 42 Mbps



2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail,
SIM switch
SIM idle protection

Status Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID, Carrier aggregation

SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
SMS
scheduled SMS, SMS autoreply, SMPP

USSD Supports sending and reading Unstructured Supplementary Service Data messages

Black/White list Operator black/white list

Multiple PDN Possibility to use different PDNs for multiple network access and services

When working with devices with two SIM slots, the one not currently in use will remain idle until the device switches to it,
SIM idle protection service
meaning that no data is used on the card until then

Band management Band lock, Used band status display

APN Auto APN

Bridge Direct connection (bridge) between mobile ISP and device on LAN

Passthrough Router assigns its mobile WAN IP address to another device on LAN


**WIRELESS**

802.11b/g/n/ac Wave 2 (WiFi 5) with data transmission rates up to 867 Mbps (Dual Band, MU-MIMO), 802.11r fast transition,
Wireless mode
Access Point (AP), Station (STA)

Wi-Fi security WPA2-Enterprise - PEAP, WPA2-PSK, WEP, WPA-EAP, WPA-PSK; AES-CCMP, TKIP, Auto Cipher modes, client separation

SSID/ESSID ESSID stealth mode

Wi-Fi users up to 150 simultaneous connections

Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
Wireless Hotspot user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes


Wireless Connectivity Features Wireless mesh (802.11s), fast roaming (802.11r), Relayd

Wireless MAC filter Whitelist, blacklist


Wireless QR code generator Once scanned, a user will automatically enter your network without needing to input login information


**BLUETOOTH**

Bluetooth 4.0 Bluetooth low energy (LE) for short range communication


**ETHERNET**

1 x WAN port 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
WAN
crossover

3 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
LAN
crossover

**NETWORK**

Routing Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing

TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Network protocols
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)

VoIP passthrough support H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets

Connection monitoring Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection

Firewall Port forward, traffic rules, custom rules

Firewall status page View all your Firewall statistics, rules, and rule counters

Ports management View device ports, enable and disable each of them, turn auto-configuration on or off, change their transmission speed, and so on

Network topology Visual representation of your network, showing which devices are connected to which other devices

Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
Hotspot user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes and option to upload and download customised hotspot themes


DHCP Static and dynamic IP allocation, DHCP Relay

QoS / Smart Queue
Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e
Management (SQM)

DDNS Supported >25 service providers, others can be configured manually

Network backup Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover

Load balancing Balance Internet traffic over multiple WAN connections

SSHFS Possibility to mount remote file system via SSH protocol


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


DATASHEET // RUTX11


**SECURITY**

Authentication Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block

Firewall Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T

DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
Attack prevention
SYN-RST, X-mas, NULL flags, FIN scan attacks)

VLAN Port and tag-based VLAN separation

Mobile quota control Mobile data limit, customizable period, start time, warning limit, phone number

WEB filter Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only

Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


**VPN**



l



l


OpenVPN


OpenVPN Encryption



l



l


Multiple clients and a server can run simultaneously, 27 encryption methods

DES-CBC 64, RC2-CBC 128, DES-EDE-CBC 128, DES-EDE3-CBC 192, DESX-CBC 192,
BF-CBC 128, RC2-40-CBC 40, CAST5-CBC 128, RC2-64-CBC 64, AES-128-CBC 128, AES-128-CFB 128, AES-128-CFB1 128,
AES-128-CFB8 128, AES-128-OFB 128, AES-128-GCM 128, AES-192-CFB 192, AES-192-CFB1 192, AES-192-CFB8 192, AES-192-OFB
192, AES-192-CBC 192, AES-192-GCM 192, AES-256-GCM 256, AES-256-CFB 256, AES-256-CFB1 256, AES-256-CFB8 256,
AES-256-OFB 256, AES-256-CBC 256



l


IKEv1, IKEv2, with 14 encryption methods for IPsec (3DES, DES, AES128, AES192, AES256, AES128GCM8, AES192GCM8,
IPsec
AES256GCM8, AES128GCM12, AES192GCM12, AES256GCM12, AES128GCM16, AES192GCM16, AES256GCM16)

GRE GRE tunnel, GRE tunnel over IPsec support

PPTP, L2TP Client/Server instances can run simultaneously, L2TPv3, L2TP over IPsec support

Stunnel Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code

DMVPN Method of building scalable IPsec VPNs

SSTP SSTP client instance support

ZeroTier ZeroTier VPN client support

WireGuard WireGuard VPN client and server support

Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support


**MODBUS TCP SLAVE**

ID range Respond to one ID in range [1;255] or any

Allow Remote Access Allow access through WAN

MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Slave functionality


**MODBUS TCP MASTER**

Supported functions 01, 02, 03, 04, 05, 06, 15, 16

8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC)


**DATA TO SERVER**

Protocol HTTP(S), MQTT, Azure MQTT, Kinesis

Data to server Extract parameters from multiple sources and different protocols, and send them all to a single server


**MQTT GATEWAY**

MQTT Gateway Allows sending commands and receiving data from MODBUS Master through MQTT broker


**DNP3**

Supported modes TCP Master, DNP3 Outstation


**DLMS**

DLMS Support DLMS - standard protocol for utility meter data exchange


**MONITORING & MANAGEMENT**

WEB UI HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log

FOTA Firmware update from server, automatic notification

SSH SSH (v1, v2)

SMS SMS status, SMS configuration, send/read SMS via HTTP POST/GET

Call Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer, Wi-Fi on/off

TR-069 OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem

MQTT MQTT Broker, MQTT publisher

SNMP SNMP (v1, v2, v3), SNMP Trap

JSON-RPC Management API over HTTP/HTTPS

MODBUS MODBUS TCP status/control

RMS Teltonika Remote Management System (RMS)


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



l


**4**


DATASHEET // RUTX11


**IOT PLATFORMS**

Cloud of Things Allows monitoring of: Device data, Mobile data, Network info, Availability

ThingWorx Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type


Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP, Mobile Cell ID, ICCID, IMEI, Connection
Cumulocity
Type, Operator, Signal Strength


Can send device IP, Number of bytes send/received, Temperature, PIN count to Azure IoT Hub server, Mobile connection state,
Azure IoT Hub Network link state, IMEI, ICCID, Model, Manufacturer, Serial, Revision, IMSI, SIM State, PIN state, GSM signal, WCDMA RSCP,
WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID, Operator, Operator number, Connection type


**SYSTEM CHARACTERISTICS**



CPU



Quad-core ARM Cortex A7, 717 MHz



RAM 256 MB, DDR3

FLASH storage 256 MB, SPI Flash


**FIRMWARE / CONFIGURATION**

WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup

FOTA Update FW

RMS Update FW/configuration for multiple devices at once

Keep settings Update FW without losing current configuration

**FIRMWARE CUSTOMIZATION**



Operating system



RutOS (OpenWrt based Linux OS)



Supported languages Busybox shell, Lua, C, C++, and Python, Java in Package manager

Development tools SDK package with build environment provided

You can now create your own custom firmware and web page application, with some examples to make the creation process
GPL customization
easier; and brand our firmware by changing colours, logos, and so on to fit your or your clients’ needs

**LOCATION TRACKING**

GNSS GPS, GLONASS, BeiDou, Galileo and QZSS

Coordinates GNSS coordinates via WebUI, SMS, TAVL, RMS

NMEA NMEA 0183

NTRIP NTRIP protocol (Networked Transport of RTCM via Internet Protocol)

Server software Supported server software TAVL, RMS

Geofencing Configurable multiple geofence zones


**USB**

Data rate USB 2.0

Applications Samba share, USB-to-serial

External devices Possibility to connect external HDD, flash drive, additional modem, printer

Storage formats FAT, FAT32, exFAT, NTFS (read-only), ext2, ext3, ext4

**INPUT / OUTPUT**

Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high

Output 1 x Digital Output, Open collector output, max output 30 V, 300 mA

Events Email, RMS, SMS

I/O juggler Allows to set certain I/O conditions to initiate event


**POWER**

Connector 4-pin industrial DC power socket

9 - 50 VDC, reverse polarity protection, voltage surge/transient protection
Input voltage range
24 - 36 VDC for railway version of the code RUTX11 020G00

Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at and 802.3bt standards,
PoE (passive)
Mode B, 9 - 30 VDC

Power consumption 16 W Max


**PHYSICAL INTERFACES**

Ethernet 4 x RJ45 ports, 10/100/1000 Mbps

I/O’s 1 x Digital Input, 1 x Digital Output on 4-pin power connector

Status LEDs 4 x WAN type LEDs, 2 x Mobile connection type, 5 x Mobile connection strength, 8 x LAN status, 1 x Power, 2 x 2.4G and 5G Wi-Fi

SIM 2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders

Power 1 x 4-pin power connector

Antennas 2 x SMA for LTE, 2 x RP-SMA for Wi-Fi, 1 x RP-SMA for Bluetooth, 1 x SMA for GNSS

USB 1 x USB A port for external devices

Reset Reboot/User default reset/Factory reset button

Other 1 x Grounding screw


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


DATASHEET // RUTX11


**PHYSICAL SPECIFICATION**

Casing material Aluminum housing

Dimensions (W x H x D) 115 x 44.2 x 95.1 mm

Weight 456 g

Mounting options DIN rail, flat surface placement


**OPERATING ENVIRONMENT**

Operating temperature -40 °C to 75 °C

Operating humidity 10% to 90% non-condensing

Ingress Protection Rating IP30


**REGULATORY & TYPE APPROVALS**

CE/RED, UKCA, CB, EAC, RoHS, REACH, Railway [EN 50155, EN 50121], UCRF, CITC, ICASA, ANRT, RCM, SIRIM, IMDA, ETA-WPC,
Regulatory
NTC,, FCC, IC (ISED), PTCRB, UL/CSA, NOM

Operator AT&T, Verizon, T-Mobile, Deutsche Telekom


**EMI IMMUNITY**

Standards EN 55032:2015, EN 55035:2017, Draft ETSI EN 301 489-1 V2.2.1, ETSI EN 301 489-3 V2.1.1, Draft ETSI EN 301 489-17 V3.2.0

ESD EN 61000-4-2:2009

RS EN 61000-4-3:2006 + A1:2008 + A2:2010

EFT EN 61000-4-4:2012

Surge protection EN 61000-4-5:2014

CS EN 61000-4-6:2014

DIP EN 61000-4-11:2004


**RF**

Standards ETSI EN 300 328 V2.1.1, ETSI EN 301 893 V2.1.1, ETSI EN 300 440 V2.1.1


**SAFETY**

Standards IEC 62368-1:2014 (Second Edition) EN 62368-1:2014+A11:2017 EN 50385:2017 EN 62232:2017


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*


- Router RUTX11

- 18 W PSU

- 2 x LTE antennas (swivel, SMA male)

- 2 x WiFi antennas (swivel, RP-SMA male)

- 1 x GNSS antenna (adhesive, SMA male, 3 m cable)

- 1 x Bluetooth antenna (magnetic mount, RP-SMA male, 1.5 m cable)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box



DATASHEET // RUTX11





|ROUTER RUTX11|18 W PSU|2 X LTE ANTENNAS (SWIVEL,<br>SMA MALE)|
|---|---|---|
|**2 X WIFI ANTENNAS (SWIVEL, RP-SMA**<br>**MALE)**|**1 X GNSS ANTENNA (ADHESIVE, SMA**<br>**MALE, 3 M CABLE)**|**1 X BLUETOOTH ANTENNA (MAGNETIC**<br>**MOUNT, RP-SMA MALE, 1.5 M CABLE)**|
|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**||



- For all standard order codes standard package contents are the same, execpt for PSU.





Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUTX11


## STANDARD ORDER CODES

**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUTX11000000



851762 8517.62.00 Standard package with EU PSU



RUTX11100400 851762 8517.62.00 Standard package with US PSU


For more information on all available packaging options – please contact us directly.
## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



Europe [3], The Middle East, Africa, Australia,
RUTX11 0*****
APAC [2], Brazil, Malaysia


Europe [3], The Middle East, Africa, Australia,
RUTX11 020G00
**Railway version** APAC2, Brazil, Malaysia




**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B20, B28, B32 [1]

**• 4G (LTE-TDD):** B38, B40, B41

**• 3G:** B1, B3, B5, B8


**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B20, B28, B32 [1]

**• 4G (LTE-TDD):** B38, B40, B41

**• 3G:** B1, B3, B5, B8




**• 4G (LTE-FDD):** B2, B4, B5, B7, B12, B13, B25, B26,
RUTX11 1***** North America [2] B29 [1], B30, B66

**• 3G:** B2, B4, B5


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.


1 - LTE-FDD B29 and B32 support Rx only, and in 2×CA it is only for secondary component carrier.
2 - Excluding Japan and CMCC.
3 - Regional availability - excluding Russia & Belarus.
4 - For more detailed information about certified carriers, visit our Wiki page


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUTX11


## RUTX11 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTX11:



Device housing*:

Box:



115 x 44.2 x 95.1 mm

355 x 60 x 175 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTX11 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUTX11 and its components as seen from the right side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // RUTX11



**FRONT VIEW**


The figure below depicts the measurements of RUTX11 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUTX11 and its components as seen from the back panel side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // RUTX11



**MOUNTING SPACE REQUIREMENTS**



The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // RUTX11



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


