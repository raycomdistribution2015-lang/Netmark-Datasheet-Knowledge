# TRB246
## v1.2

Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.


### DATASHEET - TRB246



**HARDWARE**


**FRONT VIEW**


**BACK VIEW**


**INPUT/OUTPUT 16-PIN CONNECTOR PINOUT**


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



2


### DATASHEET - TRB246

**FEATURES**


**Mobile**


**Mobile module** 4G LTE up to 150 DL/50 UL Mbps; 3G up to 42 DL/5.76 UL Mbps; 2G up to 296

DL/236.8 UL Kbps


**3GPP Release** Release 11


**SIM switch** 2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, on roaming, no

network, network denied, data connection fail


**Status** IMSI, ICCID, operator, operator state, data connection state, network type, bandwidth,

connected band, signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, data

sent/received, LAC, TAC, cell ID, ARFCN, UARFCN, EARFCN, MCC, and MNC


**SMS** SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS,

SMS to EMAIL, SMS to HTTP, SMS to SMS, scheduled SMS, SMS autoreply, SMPP


**USSD** Supports sending and reading Unstructured Supplementary Service Data messages


**Block/Allow list** Operator block/allow list (by country or separate operators)


**Multiple PDN** Possibility to use different PDNs for multiple network access and services


**Band management** Band lock, Used band status display


**SIM idle protection service** Provides the possibility to configure the router to periodically switch to the unused

SIM card and establish a data connection in order to prevent the SIM card from being

blocked


**SIM PIN code management** SIM PIN code management enables setting, changing, or disabling the SIM card's PIN


**APN** Auto APN


**Bridge** Direct connection (bridge) between mobile ISP and device on LAN


**Passthrough** Gateway assigns its mobile WAN IP address to another device on LAN


**Ethernet**


**Ethernet** 1 x ETH port, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az

standards, supports auto MDI/MDIX crossover


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



3


### DATASHEET - TRB246

**Network**


**Routing** Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based

routing


**Network protocols** TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, FTP, SMTP, SSL v3, TLS, ARP,

VRRP, PPP, PPPoE, UPNP, SSH, DHCP, Telnet, SMPP, SNMP, MQTT, Wake On Lan

(WOL), VXLAN


**VoIP passthrough support** H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


**Connection monitoring** Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


**Firewall** Port forward, traffic rules, custom rules, TTL target customisation


**Firewall status page** View all your Firewall statistics, rules, and rule counters


**Ports management** View device ports, enable and disable each of them, turn auto-configuration on or off,

change their transmission speed, and so on


**Network topology** Visual representation of your network, showing which devices are connected to which

other devices


**Hotspot** Captive portal (hotspot), internal/external Radius server, Radius MAC authentication,

SMS authorisation, SSO authentication, internal/external landing page, walled garden,

user scripts, URL parameters, user groups, individual user or group limitations, user

management, 9 default customisable themes and optionality to upload and download

customised hotspot themes


**DHCP** Static and dynamic IP allocation, DHCP relay, DHCP server configuration, status,

static leases: MAC with wildcards


**QoS / Smart Queue Management (SQM)** Traffic priority queuing by source/destination, service, protocol or port, WMM,

802.11e


**DDNS** Supported >25 service providers, others can be configured manually


**DNS over HTTPS** DNS over HTTPS proxy enables secure DNS resolution by routing DNS queries over

HTTPS


**Network backup** Mobile, VRRP, Wired options, each of which can be used as an automatic Failover


**SSHFS** Possibility to mount remote file system via SSH protocol


**Traffic Management** Real-time monitoring, wireless signal charts, traffic usage history﻿


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



4


### DATASHEET - TRB246



**Security**


**Authentication** Pre-shared key, digital certificates, X.509 certificates, TACACS+, Internal & External

RADIUS users authentication, IP & login attempts block, time-based login blocking,

built-in random password generator


**Firewall** Preconfigured firewall rules can be enabled via WebUI, unlimited firewall

configuration via CLI, DMZ, NAT, NAT-T, NAT64


**Attack prevention** DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack

prevention), port scan prevention (SYN-FIN, SYN-RST, X-mas, NULL flags, FIN scan

attacks)


**VLAN** Tag-based VLAN separation


**Mobile quota control** Mobile data limit, customizable period, start time, warning limit, phone number


**WEB filter** Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites

only


**Access control** Flexible access control of SSH, Web interface, CLI and Telnet


**SSL certificate generation** Let's Encrypt and SCEP certificate generation methods


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



5


### DATASHEET - TRB246

**VPN**


**OpenVPN** Multiple clients and a server can run simultaneously, 27 encryption methods


**OpenVPN Encryption** DES-CBC 64, RC2-CBC 128, DES-EDE-CBC 128, DES-EDE3-CBC 192, DESX-CBC 192,

BF-CBC 128, RC2-40-CBC 40, CAST5-CBC 128, RC2-64-CBC 64, AES-128-CBC 128,

AES-128-CFB 128, AES-128-CFB1 128, AES-128-CFB8 128, AES-128-OFB 128, AES
128-GCM 128, AES-192-CFB 192, AES-192-CFB1 192, AES-192-CFB8 192, AES-192
OFB 192, AES-192-CBC 192, AES-192-GCM 192, AES-256-GCM 256, AES-256-CFB

256, AES-256-CFB1 256, AES-256-CFB8 256, AES-256-OFB 256, AES-256-CBC 256


**IPsec** XFRM, IKEv1, IKEv2, with 14 encryption methods for IPsec (3DES, DES, AES128,

AES192, AES256, AES128GCM8, AES192GCM8, AES256GCM8, AES128GCM12,

AES192GCM12, AES256GCM12, AES128GCM16, AES192GCM16, AES256GCM16)


**GRE** GRE tunnel, GRE tunnel over IPsec support


**PPTP, L2TP** Client/Server instances can run simultaneously, L2TPv3, L2TP over IPsec support


**Stunnel** Proxy designed to add TLS encryption functionality to existing clients and servers

without any changes in the program’s code


**DMVPN** Method of building scalable IPsec VPNs, Phase 2 and Phase 3 and Dual Hub support


**SSTP** SSTP client instance support


**ZeroTier** ZeroTier VPN client support


**WireGuard** WireGuard VPN client and server support


**Tinc** Tinc offers encryption, authentication and compression in it's tunnels. Client and

server support.


**BACNET**


**Supported modes** Router


**Supported connection types** RS485, TCP


**Configuration options** Support for multiple BACnet/IP interfaces, Network number assignment,

Preconfigured BDT entries for BBMD (BACnet Broadcast Management Device)


**OPC UA**


**Supported modes** Client, Server


**Supported connection types** TCP


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



6


### DATASHEET - TRB246

**MODBUS**


**Supported modes** Server, Client


**Supported connection types** RTU (RS232, RS485), TCP


**Custom registers** MODBUS TCP custom register block requests, which read/write to a file inside the

router, and can be used to extend MODBUS TCP Client functionality


**Supported data formats** 8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD

(big-endian), DCBA (little-endian), CDAB, BADC), HEX, ASCII


**DATA TO SERVER**


**Protocol** HTTP(S), MQTT, Azure MQTT, Kinesis


**Data to server** Extract parameters from multiple sources and different protocols, and send them all to

a single server; Custom LUA scripting, allowing scripts to utilize the router's Data to

server feature


**MQTT Gateway**


**Modbus MQTT Gateway** Allows sending commands and receiving data from MODBUS Server through MQTT

broker


**DNP3**


**Supported modes** Station, Outstation


**Supported connection types** RS232, RS485, TCP


**DLMS/COSEM**


**DLMS Support** DLMS - standard protocol for utility meter data exchange. Support trough serial and

TCP


**Supported modes** Client


**Supported connection types** RS232, RS485, TCP


**API**



**Teltonika Networks Web API (beta)**

**support**



Expand your device's possibilities by using a set of configurable API endpoints to

retrieve or change data. For more information, please refer to this documentation:

[https://developers.teltonika-networks.com](https://developers.teltonika-networks.com)



Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



7


### DATASHEET - TRB246



**Monitoring & Management**


**WEB UI** HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, multiple event log

servers, firmware update availability notifications, event log, system log, kernel log,

Internet status


**FOTA** Firmware update from server, automatic notification


**SSH** SSH (v1, v2)


**SMS** SMS status, SMS configuration, send/read SMS via HTTP POST/GET


**Call** Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer


**TR-069** OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP,

Friendly tech, AVSystem


**MQTT** MQTT Broker, MQTT publisher


**SNMP** SNMP (v1, v2, v3), SNMP Trap, Brute force protection


**JSON-RPC** Management API over HTTP/HTTPS


**RMS** Teltonika Remote Management System (RMS)


**IoT Platforms**


**ThingWorx** Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal

Strength, Mobile Network Type


**Cumulocity - Cloud of Things** Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP,

Mobile Cell ID, ICCID, IMEI, Connection Type, Operator, Signal Strength. Has reboot

and firmware upgrade actions


**Azure IoT Hub** Can be configured with Data to Server to send all the available parameters to the

cloud. Has Direct method support which allows to execute RutOS API calls on the IoT

Hub. Also has Plug and Play integration with Device Provisioning Service that allows

zero-touch device provisioning to IoT Hubs


**AWS IoT Core** Utility to interact with the AWS cloud platform. Jobs Support: Call the device's API

using AWS Jobs functionality


**System Characteristics**


**CPU** Mediatek, 580 MHz, MIPS 24KEc


**RAM** 128 MB


**FLASH storage** 16 MB


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



8


### DATASHEET - TRB246

**Firmware / Configuration**


**WEB UI** Update FW from file, check FW on server, configuration profiles, configuration

backup


**FOTA** Update FW


**RMS** Update FW/configuration for multiple devices at once


**Keep settings** Update FW without losing current configuration


**Factory settings reset** A full factory reset restores all system settings, including the IP address, PIN, and user

data to the default manufacturer's configuration


**FIRMWARE CUSTOMISATION**


**Operating system** RutOS (OpenWrt based Linux OS)


**Supported languages** Busybox shell, Lua, C, C++


**Development tools** SDK package with build environment provided


**GPL customization** You can create your own custom, branded firmware and web page application by

changing colours, logos, and other elements in our firmware to fit your or your clients’

needs


**Package Manager** The Package Manager is a service used to install additional software on the device


**Location Tracking**


**GNSS** GPS, GLONASS, BeiDou, Galileo and QZSS


**Coordinates** GNSS coordinates via WebUI, SMS, TAVL, RMS


**NMEA** NMEA 0183


**NTRIP** NTRIP protocol (Networked Transport of RTCM via Internet Protocol)


**Server software** Supported server software TAVL, RMS


**Geofencing** Configurable multiple geofence zones


**Tracking sensitivity** -157 dBm


**Position Accuracy** 2.5m CEP


**Serial**


**RS232** Terminal block connector: TX, RX, RTS, CTS


**RS485** Terminal block connector: D+, D-, R+, R- (2 or 4 wire interface)


**Serial functions** Console, Serial over IP, Modem, MODBUS gateway, NTRIP Client


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



9


### DATASHEET - TRB246

**Input / Output**


**Input** 3x Configurable Digital Inputs, 0 - 6 V detected as logic low, 8 - 30 V detected as

logic high, 1x Analog input (0 - 30 V)


**Output** 3x Configurable Digital Outputs, Open collector output, max output 30 V, 300 mA


**Events** Email, RMS, SMS


**I/O juggler** Allows to set certain I/O conditions to initiate event


**Power**


**Connector** 2-pin in 16-pin industrial terminal block


**Input voltage range** 9 – 30 VDC, reverse polarity protection, surge protection +/-1 kV 50 µs max


**Power consumption** Idle: < 1.5 W, Max: < 3.5 W


**Physical Interfaces**


**Ethernet** 1 x RJ45 port, 10/100 Mbps


**I/O’s** 3 x Configurable digital I/O in 16-pin terminal block


**Status LEDs** 3 x connection status LEDs, 3 x connection strength LEDs, 1 x power LED, 1 x Eth port

status LED


**SIM** 2 x SIM slots (Mini SIM – 2FF), 1.8 V/3 V, double stacked SIM tray


**Power** 1 x 16-pin terminal block


**Antennas** 1 x SMA connector for LTE, 1 x SMA connector for GNSS


**RS232** 4-pin in 16-pin terminal block (TX, RX, RTS, CTS)


**RS485** 4-pin in 16-pin terminal block (D+, D-, R+, R-)


**Reset** Reboot/User default reset/Factory reset button


**Physical Specification**


**Casing material** Aluminium housing


**Dimensions (W x H x D)** 83 x 25 x 74.2 mm


**Weight** 165 g


**Mounting options** DIN rail, wall mount, flat surface (all require additional kit)


**Operating Environment**


**Operating temperature** -40 °C to 75 °C


**Operating humidity** 10% to 90% non-condensing


**Ingress Protection Rating** IP30


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



10


### DATASHEET - TRB246



**Regulatory & Type Approvals**


**Regulatory** CE, UKCA, EAC, RCM, FCC, IC, CB, WEEE


**EMC Emissions & Immunity**


**Standards** EN 55032:2015+A11:2020+A1:2020

EN 55035:2017+A11:2020

EN 61000-3-3:2013+A1:2019+A2:2021

EN IEC 61000-3-2:2019+A1:2021

EN 301 489-1 V2.2.3

EN 301 489-19 V2.2.1

EN 301 489-52 V1.2.1


**ESD** EN 61000-4-2:2009


**Radiated Immunity** EN IEC 61000-4-3:2020


**EFT** EN 61000-4-4:2012


**Surge Immunity (AC Mains Power Port)** EN 61000-4-5:2014 +A1:2017


**CS** EN 61000-4-6:2014


**DIP** EN 61000-4-11:2020


**RF**


**Standards** EN 301 511 V12.5.1

EN 301 908-1 V15.2.1

EN 301 908-2 V13.1.1

EN 301 908-13 V13.2.1

EN 303 413 V1.2.1


**Safety**


**Standards** CE: EN IEC 62368-1:2020 + A11:2020, EN IEC 62311:2020

CB: IEC 62368-1:2018


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



11


### DATASHEET - TRB246



**ORDERING**


**STANDARD PACKAGE***


**TRB246** **2X8 PIN CONNECTOR** **1 X HEX KEY**


**QSG (QUICK START GUIDE)**


Gateway TRB246

[16-pin terminal block](https://teltonika-networks.com/products/accessories/other-2/2x8pin-connector)

1x hex key

QSG (Quick start guide)

Packaging box


*Standard package contents may differ based on standard order codes.


[For more information on all available packaging options – please contact us](https://teltonika-networks.com/about-us/contacts/) directly.


**CLASSIFICATION CODES**


**HS Code:** 851762

**HTS:** 8517.62.00


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



12


**AVAILABLE VERSIONS**


TRB246 **0** *****

EMEA [2]


TRB246 **1** *****

South America, Australia, New Zealand,

Taiwan


TRB246 **2** *****

North America


TRB246 **000A03**

Thailand



**4G (LTE-FDD):** B1, B3, B7, B8,

B20, B28A

**4G (LTE-TDD):** B38, B40, B41

**3G:** B1, B8

**2G:** B3, B8

**4G (LTE-FDD):** B1, B2 [1], B3, B4,

B5, B7, B8, B28

**4G (LTE-TDD):** B40

**3G:** B1, B2, B4, B5, B8

**2G:** B2, B3, B5, B8


**4G (LTE-FDD):** B2, B4, B5, B12,

B13, B14, B66, B71

**3G:** B2, B4, B5


**4G (LTE-FDD):** B1, B3, B7, B8,

B20

**4G (LTE-TDD):** B38, B40

**3G:** B1, B8

**2G:** B3, B8


### DATASHEET - TRB246

TRB246000600 / Standard package


TRB246100300 / Standard package with AU PSU

TRB246100500 / Standard package with US PSU

without connector


TRB246200500 / Standard package with US

PSU


TRB246000A03 / Standard package



The price and lead-times for region (operator) specific versions may vary. For more information please [contact us.](https://teltonika-networks.com/about-us/contacts/)


1 - LTE-FDD B2 does not support Rx-diversity

2 - Regional availability - excluding Russia, Belarus & Iran


**TRB246 SPATIAL MEASUREMENTS**


**PHYSICAL SPECIFICATION**


**Device housing (W x H x D)*:** 83 x 25 x 74.2 mm


**Box (W x H x D):** 111 x 31 x 89 mm


*Housing measurements are presented without antenna connectors and screws; for

measurements of other device elements look to the sections below.


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



13


### DATASHEET - TRB246



**TOP VIEW**

The figure below depicts the measurements of device and its components as seen from the top:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



14


### DATASHEET - TRB246



**RIGHT VIEW**

The figure below depicts the measurements of device and its components as seen from the right side:


**FRONT VIEW**

The figure below depicts the measurements of device and its components as seen from the front panel side:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



15


### DATASHEET - TRB246



**REAR VIEW**

The figure below depicts the measurements of device and its components as seen from the back panel side:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



16


### DATASHEET - TRB246



**MOUNTING SPACE REQUIREMENTS**

The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



17


