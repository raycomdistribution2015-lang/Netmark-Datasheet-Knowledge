# TRB140


DATASHEET // TRB140


## HARDWARE

FRONT VIEW


BACK VIEW


POWER SOCKET PINOUT



**Power socket**


**Power LED**



**Ethernet port**


**Mobile network**
**type LEDs**



**Mobile antenna** **Mobile signal strength**
**connector** **indication LEDs**



**Power / Red wire**


**I/O / Green wire**



**Ground / Black wire**


**I/O / White wire**



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **2**


## FEATURES

**MOBILE**

Mobile module

Status


SMS



DATASHEET // TRB140


4G (LTE) – Cat 4 up to 150 Mbps, 3G – Up to 42 Mbps, 2G – Up to 236.8 kbps

Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID

SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP



USSD Supports sending and reading Unstructured Supplementary Service Data messages

Black/White list Operator black/white list

Multiple PDN Possibility to use different PDNs for multiple network access and services

Band management Band lock, Used band status display

APN Auto APN

Bridge Direct connection (bridge) between mobile ISP and device on LAN

Passthrough Router assigns its mobile WAN IP address to another device on LAN


**NETWORK**



Routing


Network protocols


VoIP passthrough support

Connection monitoring

Firewall



Static routing

TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)

H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets

Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection

Port forward, traffic rules, custom rules



DHCP Static and dynamic IP allocation, DHCP Relay



QoS / Smart Queue
Management (SQM)

DDNS



Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually



Network backup Mobile, VRRP, Wired options, each of which can be used as an automatic Failover

Load balancing Balance Internet traffic over multiple WAN connections

SSHFS Possibility to mount remote file system via SSH protocol


**SECURITY**



Authentication

Firewall


Attack prevention



Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block

Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T

DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
SYN-RST, X-mas, NULL flags, FIN scan attacks)



VLAN Port and tag-based VLAN separation

Mobile quota control Mobile data limit, customizable period, start time, warning limit, phone number

WEB filter Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only

Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


**VPN**



OpenVPN


OpenVPN Encryption


IPsec


GRE



Multiple clients and a server can run simultaneously, 27 encryption methods


DES-CBC 64, RC2-CBC 128, DES-EDE-CBC 128, DES-EDE3-CBC 192, DESX-CBC 192,
BF-CBC 128, RC2-40-CBC 40, CAST5-CBC 128, RC2-64-CBC 64, AES-128-CBC 128, AES-128-CFB 128, AES-128-CFB1 128,
AES-128-CFB8 128, AES-128-OFB 128, AES-128-GCM 128, AES-192-CFB 192, AES-192-CFB1 192, AES-192-CFB8 192, AES-192-OFB
192, AES-192-CBC 192, AES-192-GCM 192, AES-256-GCM 256, AES-256-CFB 256, AES-256-CFB1 256, AES-256-CFB8 256,
AES-256-OFB 256, AES-256-CBC 256


IKEv1, IKEv2, with 14 encryption methods for IPsec (3DES, DES, AES128, AES192, AES256, AES128GCM8, AES192GCM8,
AES256GCM8, AES128GCM12, AES192GCM12, AES256GCM12, AES128GCM16, AES192GCM16, AES256GCM16)

GRE tunnel, GRE tunnel over IPsec support



PPTP, L2TP Client/Server instances can run simultaneously, L2TPv3, L2TP over IPsec support

Stunnel Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code

DMVPN Method of building scalable IPsec VPNs

SSTP SSTP client instance support

ZeroTier ZeroTier VPN client support

WireGuard WireGuard VPN client and server support

Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


DATASHEET // TRB140



**MODBUS TCP SLAVE**

ID range Respond to one ID in range [1;255] or any



Allow Remote Access


Custom registers


**MODBUS TCP MASTER**

Supported functions


Supported data formats


**DATA TO SERVER**



Allow access through WAN

MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
TCP Slave functionality


01, 02, 03, 04, 05, 06, 15, 16

8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC)



Protocol HTTP(S), MQTT, Azure MQTT, Kinesis


**MQTT GATEWAY**

MQTT Gateway Allows sending commands and receiving data from MODBUS Master through MQTT broker


**DNP3**

Supported modes TCP Master, DNP3 Outstation


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

JSON-RPC

MODBUS



SSH (v1, v2)

SMS status, SMS configuration, send/read SMS via HTTP POST/GET

Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer

OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem

MQTT Broker, MQTT publisher

SNMP (v1, v2, v3), SNMP Trap

Management API over HTTP/HTTPS

MODBUS TCP status/control



RMS Teltonika Remote Management System (RMS)


**IOT PLATFORMS**

Cloud of Things Allows monitoring of: Device data, Mobile data, Network info, Availability



ThingWorx


Cumulocity



Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type

Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP, Mobile Cell ID, ICCID, IMEI, Connection
Type, Operator, Signal Strength



Can send device IP, Number of bytes send/received, Temperature, PIN count to Azure IoT Hub server, Mobile connection state,
Azure IoT Hub Network link state, IMEI, ICCID, Model, Manufacturer, Serial, Revision, IMSI, SIM State, PIN state, GSM signal, WCDMA RSCP,
WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID, Operator, Operator number, Connection type


**SYSTEM CHARACTERISTICS**

CPU ARM Cortex-A7 1.2 GHz



RAM

FLASH storage



128 MB, DDR2

512 MB, SPI Flash



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



Busybox shell, Lua, C, C++

SDK package with build environment provided



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // TRB140



**INPUT / OUTPUT**

Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high

Output 1 x Digital Output, Open collector output, max output 30 V, 300 mA

Events Email, RMS, SMS

I/O juggler Allows to set certain I/O conditions to initiate event


**POWER**

Connector 4-pin industrial DC power socket



Input voltage range


PoE (passive)



9 – 30 VDC, reverse polarity protection; surge protection >31 VDC 10us max

Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at and 802.3bt standards, Mode B, 9 - 30
VDC



Power consumption < 5 W


**PHYSICAL INTERFACES**

Ethernet 1 x RJ45 port, 10/100/1000 Mbps



I/O’s

Status LEDs



1 x Digital Input, 1 x Digital Output on 4-pin power connector

3 x connection type status LEDs, 5 x connection strength LEDs, 2 x LAN status LEDs, 1x Power LED



SIM 1 x SIM slot (Mini SIM – 2FF), 1.8 V/3 V



Power

Antennas



1 x 4-pin power connector

1 x SMA for LTE



USB 1 x Virtual network interface via micro USB

Reset Reboot/User default reset/Factory reset button


**PHYSICAL SPECIFICATION**



Casing material

Dimensions (W x H x D)

Weight

Mounting options


**OPERATING ENVIRONMENT**

Operating temperature

Operating humidity

Ingress Protection Rating



Aluminum housing

74.5 x 25 x 64.4 mm

134 g

Bottom and sideways DIN rail, Flat surface


-40 °C to 75 °C

10% to 90% non-condensing

IP30



**REGULATORY & TYPE APPROVALS**



Regulatory



CE/RED, EAC, RoHS, WEEE



**EMC EMISSIONS & IMMUNITY**

Draft EN 301 489-1 V2.2.0, Draft EN 301 489-17 V3.2.0, Draft EN 301 489-19 V2.1.0, Draft EN 301 489-52 V1.1.0
Standards
FCC 47 CFR Part 15B (2017), ANSI C63.4 (2014)



ESD

RS



EN 61000-4-2:2009

EN 61000-4-3:2006 + A1:2008 + A2:2010



EFT EN 61000-4-4:2012



Surge protection

CS



EN 61000-4-5:2014

EN 61000-4-6:2014



DIP EN 61000-4-11:2004


**RF**

Standards EN 300 511 V12.5.1, ETSI EN 301 908-1 V11.1.1, ETSI EN 301 908-1 V11.1.2, EN 301 908-2 V11.1.2, ETSI EN 301 908-13 V11.1.2


**SAFETY**


IEC 62368-1:2014(Second Edition), EN 62368-1:2014+A11:2017
Standards EN 50385:2017
EN 62232:2017


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*


- TRB140 Gateway

- 9 W PSU

- 1x LTE antenna (magnetic mount, SMA male, 3 m cable)

- Micro-USB cable (0.8 m)

- 1x hex key

- LAN cable

- QSG (Quick Start Guide)

- Packaging box



DATASHEET // TRB140



|TRB140 GATEWAY|9 W PSU|1X LTE ANTENNA (MAGNETIC<br>MOUNT, SMA MALE, 3 M CABLE)|
|---|---|---|
|**MICRO-USB CABLE (0.8 M)**|**1X HEX KEY**|**LAN CABLE**|
|**QSG**|||



- For all standard order codes standard package contents are the same, execpt for PSU.





Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // TRB140


## STANDARD ORDER CODES

**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



TRB140 003000



851762 8517.62.00 Standard Package with EU PSU



TRB140 107000 851762 8517.62.00 Standard Package with AU PSU

TRB140 40C400 851762 8517.62.00 Standard Package with JP PSU


For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



Europe [1], The Middle East, Africa, Korea,
TRB140 0*****
Thailand, India, Malaysia


South America, Australia, New Zealand,
TRB140 1*****
Taiwan, Malaysia




**• 4G (LTE-FDD):** B1, B3, B7, B8, B20, B28A

**• 4G (LTE-TDD):** B38, B40, B41

**• 3G:** B1, B8

**• 2G:** B3, B8


**• 4G (LTE-FDD):** B1, B2 [2], B3, B4, B5, B7, B8, B28

**• 4G (LTE-TDD):** B40

**• 3G:** B1, B2, B5, B8

**• 2G:** B2, B3, B5, B8




**• 4G (LTE-FDD):** B1, B3, B8, B18, B19, B26
TRB140 4***** Japan **• 4G (LTE-TDD):** B41

**• 3G:** B1, B6, B8, B19


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.


- - Versions for other regions are under development.
** - For more detailed information, visit our Wiki.
1 - Regional availability - excluding Russia & Belarus.
2 - LTE-FDD B2 does not support Rx-diversity.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // TRB140


## TRB140 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for TRB140



Device housing*:

Box:



74.5 x 25 x 64.4 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of TRB140 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of TRB140 and its components as seen from the right side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // TRB140



**FRONT VIEW**


The figure below depicts the measurements of TRB140 and its components as seen from the front:


**REAR VIEW**


The figure below depicts the measurements of TRB140 and its components as seen from the back:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // TRB140



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // TRB140



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


