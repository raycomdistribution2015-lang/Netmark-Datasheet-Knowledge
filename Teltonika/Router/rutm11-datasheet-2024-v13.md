# RUTM11

Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


**WAN type LEDs**


**SIM needle**


**Power socket**


BACK VIEW


POWER SOCKET PINOUT



**screw**

**Wi-Fi antenna** **Wi-Fi antenna**
**connector** **connector**
**(RP-SMA female)** **(RP-SMA female)**


**Power / Red wire**


**Input / Green wire**



**Mobile network type**
**LEDs**



**Mobile signal strength**
**indication LEDs**





**Reset**
**button**



**Mobile MAIN antenna**
**connector (SMA female)**



**GNSS antenna** **Mobile AUX antenna**
**connector (SMA female)** **connector (SMA female)**



DATASHEET // RUTM11


**SIM holders**


**WAN LEDs**


**USB port**



**Ground / Black wire**


**Output / White wire**



Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice. **2**


i


## FEATURES

**MOBILE**


Mobile module


SIM switch


Status


SMS


i



DATASHEET // RUTM11


4G (LTE) – Cat 6 up to 300 Mbps, 3G – Up to 42 Mbps


2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail,
SIM idle protection

IMSI, ICCID, operator, operator state, data connection state, network type, CA indicator, bandwidth, connected band, signal
strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, data sent/received, LAC, TAC, cell ID, ARFCN, UARFCN, EARFCN, MCC, and MNC

SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP


i



i



USSD Supports sending and reading Unstructured Supplementary Service Data messages


i



Black/White list


Multiple PDN


Band management


SIM idle protection service


i



Operator black/white list (by country or separate operators)


Possibility to use different PDNs for multiple network access and services


Band lock, Used band status display


When working with devices with two SIM slots, the one not currently in use will remain idle until the device switches to it,
meaning that no data is used on the card until then


i



APN Auto APN


Bridge Direct connection (bridge) between mobile ISP and device on LAN


Passthrough Router assigns its mobile WAN IP address to another device on LAN


**WIRELESS**


i



Wireless mode


Wi-Fi security

i

SSID/ESSID


Wi-Fi users



802.11b/g/n/ac Wave 2 (Wi-Fi 5) with data transmission rates up to 867 Mbps (Dual Band, MU-MIMO)


WPA2-Enterprise - PEAP, WPA2-PSK, WPA-EAP, WPA-PSK, WPA3-SAE, WPA3-EAP, OWE; AES-CCMP, TKIP, Auto-cipher modes,
client separation, EAP-TLS with PKCS#12 certificates, disable auto-reconnect

ESSID stealth mode


Up to 150 simultaneous connections



i


Wireless Connectivity Features Wireless mesh (802.11s), fast roaming (802.11r), BSS transition management (802.11v), radio resource measurement (802.11k)



i


Wireless MAC filter


Wireless QR code generator


**ETHERNET**



i


Whitelist, blacklist


Once scanned, a user will automatically enter your network without needing to input login information



i


WAN 1 x WAN port 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX crossover



i


LAN


**NETWORK**


Routing


Network protocols


VoIP passthrough support


Connection monitoring



i


3 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX crossover


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SNMP, MQTT, Wake On Lan (WOL)

H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection



i


Firewall Port forward, traffic rules, custom rules



i


Firewall status page


Ports management


Network topology


DHCP



i


View all your Firewall statistics, rules, and rule counters


View device ports, enable and disable each of them, turn auto-configuration on or off, change their transmission speed, and so on


Visual representation of your network, showing which devices are connected to which other devices


Static and dynamic IP allocation, DHCP relay, DHCP server configuration, status, static leases: MAC with wildcards



i


QoS / Smart Queue
Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e
Management (SQM)

DDNS Supported >25 service providers, others can be configured manually



i


Network backup


Load balancing



i


Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover


Balance Internet traffic over multiple WAN connections



i


Captive portal (hotspot), internal/external Radius server, Radius MAC authentication, SMS authorisation, internal/external
Hotspot landing page, walled garden, user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customisable themes and optionality to upload and download customised hotspot themes


SSHFS Possibility to mount remote file system via SSH protocol


VRF support Initial virtual routing and forwarding (VRF) support


Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice. **3**


l



**SECURITY**


Authentication


Firewall


Attack prevention

l

VLAN



DATASHEET // RUTM11


Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & login attempts block, time-based login blocking,
built-in random password generator


Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T

DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
SYN-RST, X-mas, NULL flags, FIN scan attacks)

Port and tag-based VLAN separation



l



l


Mobile quota control Mobile data limit, customizable period, start time, warning limit, phone number


WEB filter Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Access control Flexible access control of SSH, Web interface, CLI and Telnet


**VPN**



l


OpenVPN


OpenVPN Encryption


IPsec


GRE


PPTP, L2TP


Stunnel


DMVPN


SSTP


ZeroTier


WireGuard



l


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


ZeroTier VPN client support


WireGuard VPN client and server support



l


Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support


Tailscale offers speed, stability, and simplicity over traditional VPNs. Encrypted point-to-point connections using the open
Tailscale
source WireGuard protocol


**OPC UA**



l


Supported modes



l


Client, Server



l


Supported connection types TCP


**MODBUS**



l


Supported modes



l


Server, Client



l


Supported connection types TCP, USB

MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Client functionality

8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC), HEX, ASCII


**DATA TO SERVER**



l


Protocol



l


HTTP(S), MQTT, Azure MQTT



l


Data to server Extract parameters from multiple sources and different protocols, and send them all to a single server


**MQTT GATEWAY**



l


Modbus MQTT Gateway


**DNP3**


Supported modes



l


Allows sending commands and receiving data from MODBUS Server through MQTT broker


Station, Outstation



l


Supported connection TCP, USB


**DLMS**



l


DLMS Support



l


DLMS - standard protocol for utility meter data exchange



l


Supported modes Client


Supported connection types TCP, USB


**API**



l


Teltonika Networks Web API
(beta) support



l


Expand your device's possibilities by using a set of configurable API endpoints to retrieve or change data. For more information, please refer to this documentation: https://developers.teltonika-networks.com



l


Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice.



l


**4**


DATASHEET // RUTM11


i



i



i



**MONITORING & MANAGEMENT**


i



WEB UI

i



HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, multiple event log servers, firmware update availability
notifications, event log, system log, kernel log, Internet status



i

FOTA Firmware update from server, automatic notification



i


SSH


SMS


Call


Email


TR-069


MQTT



i


SSH (v1, v2)


SMS status, SMS configuration, send/read SMS via HTTP POST/GET


Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer


Receive email message status alerts of various services


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher



i


SNMP SNMP (v1, v2, v3), SNMP Trap


RMS Teltonika Remote Management System (RMS)

**IOT PLATFORMS**


Cloud of Things Allows monitoring of: Device data, Mobile data, Network info, Availability



i


ThingWorx


Cumulocity


Azure IoT Hub


**SYSTEM CHARACTERISTICS**



i


Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type


Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP, Mobile Cell ID, ICCID, IMEI, Connection
Type, Operator, Signal Strength

Can send device IP, Number of bytes send/received, Temperature, PIN count to Azure IoT Hub server, Mobile connection state,
Network link state, IMEI, ICCID, Model, Manufacturer, Serial, Revision, IMSI, SIM State, PIN state, GSM signal, WCDMA RSCP,
WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID, Operator, Operator number, Connection type



i


CPU MediaTek, Dual-core, 880 MHz, MIPS1004KC



i


RAM


FLASH storage



i


256 MB, DDR3


16MB serial NOR flash, 256MB serial NAND flash



i


**FIRMWARE / CONFIGURATION**


WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup



i


FOTA


RMS


Keep settings



i


Update FW


Update FW/configuration for multiple devices at once


Update FW without losing current configuration



i


A full factory reset restores all system settings, including the IP address, PIN, and user data to the default manufacturer's
Factory settings reset
configuration

**FIRMWARE CUSTOMISATION**


Operating system RutOS (OpenWrt based Linux OS)



i


Supported languages


Development tools


GPL customization


**LOCATION TRACKING**



i


Busybox shell, Lua, C, C++


SDK package with build environment provided


You can create your own custom, branded firmware and web page application by changing colours, logos, and other elements
in our firmware to fit your or your clients’ needs



i


GNSS GPS, GLONASS, BeiDou, Galileo and QZSS



i


Coordinates


NMEA



i


GNSS coordinates via WebUI, SMS, TAVL, RMS


NMEA 0183



i


NTRIP NTRIP protocol (Networked Transport of RTCM via Internet Protocol)



i


Server software


Geofencing

**USB**



i


Supported server software TAVL, RMS


Configurable multiple geofence zones



i


Data rate USB 2.0



i


Applications


External devices



i


Samba share, USB-to-serial


Possibility to connect external HDD, flash drive, additional modem, printer, USB-serial adapter



i


Storage formats FAT, FAT32, exFAT, NTFS (read-only), ext2, ext3, ext4

**INPUT / OUTPUT**


Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 50 V detected as logic high



i


Output


Events



i


1 x Digital Output, Open collector output, max output 50 V, 300 mA


Email, RMS, SMS



i


I/O juggler Allows to set certain I/O conditions to initiate event


Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice. **5**


DATASHEET // RUTM11



**POWER**


Connector 4-pin industrial DC power socket



Input voltage range


PoE (passive)


Power consumption


**PHYSICAL INTERFACES**



9 – 50 VDC, reverse polarity protection, surge protection >51 VDC 10us max


Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at and 802.3bt standards, Mode B, 9 - 50 VDC


Idle: < 3.9 W, Max: < 12.3 W



Ethernet 4 x RJ45 ports, 10/100/1000 Mbps



I/O’s


Status LEDs



1 x Digital Input, 1 x Digital Output on 4-pin power connector


4 x WAN type LEDs, 2 x Mobile connection type, 5 x Mobile connection strength, 8 x LAN status, 1 x Power, 2 x 2.4G and 5G Wi-Fi



SIM 2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders



Power


Antennas



1 x 4-pin power connector


2 x SMA for Mobile, 2 x RP-SMA for Wi-Fi, 1 x SMA for GNSS



USB 1 x USB A port for external devices


Reset Reboot/User default reset/Factory reset button


Other 1 x Grounding screw


**PHYSICAL SPECIFICATION**


Casing material Anodized aluminum housing and panels



Dimensions (W x H x D)


Weight



115 x 44.2 x 95.1 mm


460 g



Mounting options DIN rail, wall mount, flat surface (all require additional kit)


**OPERATING ENVIRONMENT**


Operating temperature -40 °C to 75 °C



Operating humidity


Ingress Protection Rating



10% to 90% non-condensing


IP30



**REGULATORY & TYPE APPROVALS**


Regulatory WEE


**EMC EMISSIONS & IMMUNITY**



Standards


ESD


Radiated Immunity



EN 55032:2015 + A11:2021
EN 55035:2017 + A11:2020
EN IEC 61000-3-2:2019 + A1:2021
EN 61000-3-3:2013 + A1:2019 + A2:2021
EN 301 489-1 V2.2.3
EN 301 489-3 V2.1.1
EN 301 489-17 V3.2.4
EN 301 489-19 V2.2.1
EN 301 489-52 V1.2.1


EN 61000-4-2:2009


EN IEC 61000-4-3:2020



EFT EN 61000-4-4:2012



Surge Immunity
(AC Mains Power Port)


CS



EN 61000-4-5:2014 + A1:2017


EN 61000-4-6:2014



DIP EN 61000-4-11:2020


**RF**



Standards


**SAFETY**



EN 301 908-1 V15.2.1
EN 301 908-2 V13.1.1
EN 301 908-13 V13.2.1
EN 303 413 V1.2.1
EN 300 328 V2.2.2
EN 301 893 V2.1.1
EN 300 440 V2.2.1



**CE:** EN IEC 62368-1:2020 + A11:2020, EN IEC 62311:2020
Standards **RCM:** AS/NZS 62368.1:2022
**CB:** IEC 62368-1:2018


Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice.



**6**


## STANDARD PACKAGE*


- Router RUTM11

- 18 W PSU

- 2x Mobile antennas (swivel, SMA male)

- 2x Wi-Fi antennas (swivel, RP-SMA male)

- 1x GNSS antenna (adhesive, SMA male, 3 m cable)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box



DATASHEET // RUTM11



|ROUTER RUTM11|18 W PSU|2X MOBILE ANTENNAS<br>(SWIVEL, SMA MALE)|
|---|---|---|
|**2X WI-FI ANTENNAS (SWIVEL,**<br>**RP-SMA MALE)**|**1X GNSS ANTENNA (ADHE-**<br>**SIVE, SMA MALE, 3 M CABLE)**|**ETHERNET CABLE (1.5 M)**|
|**SIM ADAPTER KIT**|**QSG (QUICK START GUIDE)**||



- Standard package contents may differ based on standard order codes.





Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUTM11

## CLASSIFICATION CODES


HS Code: 851762

HTS: 8517.62.00


For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**HARDWARE VERSION** **SUPPORTED FREQUENCIES** **STANDARD ORDER CODE / PACKAGE CONTAINS**



RUTM11 0*****
Europe [1], the Middle East,
Africa, Australia, Brazil



**4G (LTE-FDD):** B1, B3, B5, B7, B8, B20,
B28, B32
**4G (LTE-TDD):** B38, B40, B41
**3G:** B1, B3, B5, B8



RUTM11000000 / Standard package with EU PSU



The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 - Regional availability - excluding Russia & Belarus.


Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice. **8**


DATASHEET // RUTM11


## RUTM11 SPATIAL MEASUREMENTS

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTM11:



Device housing*:

Box:



115 x 44.2 x 95.1 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTM11 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUTM11 and its components as seen from the right side:


Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // RUTM11


**FRONT VIEW**


The figure below depicts the measurements of RUTM11 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUTM11 and its components as seen from the back panel side:


Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice. **10**


DATASHEET // RUTM11



**MOUNTING SPACE REQUIREMENTS**



The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2024, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB TELTONIKA NETWORKS without prior notice. **11**


