# RUT206
## v1.1

Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.


### DATASHEET - RUT206



**HARDWARE**


**FRONT VIEW**


**BACK VIEW**


**POWER SOCKET PINOUT**


**6-PIN TERMINAL BLOCK**


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



2


### DATASHEET - RUT206

**FEATURES**


**Mobile**


**Mobile module** 4G LTE Cat 4 up to 150 DL/50 UL Mbps; 3G up to 21 DL/5.76 UL Mbps; 2G up to 236.8

DL/236.8 UL kbps


**3GPP Release** Release 9


**SIM switch** 2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no

network, network denied, data connection fail, SIM idle protection


**Status** IMSI, ICCID, operator, operator state, data connection state, network type, bandwidth,

connected band, signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, data

sent/received, LAC, TAC, cell ID, ARFCN, UARFCN, EARFCN, MCC, and MNC


**SMS** SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS,

SMS to EMAIL, SMS to HTTP, SMS to SMS, scheduled SMS, SMS autoreply, SMPP


**USSD** Supports sending and reading Unstructured Supplementary Service Data messages


**Block/Allow list** Operator block/allow list (by country or separate operators)


**Band management** Band lock, Used band status display


**SIM idle protection service** Provides the possibility to configure the router to periodically switch to the unused

SIM card and establish a data connection in order to prevent the SIM card from being

blocked


**SIM PIN code management** SIM PIN code management enables setting, changing, or disabling the SIM card's PIN


**APN** Auto APN


**Bridge** Direct connection (bridge) between mobile ISP and device on LAN


**Passthrough** Router assigns its mobile WAN IP address to another device on LAN


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



3


### DATASHEET - RUT206



**Wireless**


**Wireless mode** 802.11b/g/n (Wi-Fi 4), Access Point (AP), Station (STA)


**Wi-Fi security** WPA2-Enterprise: PEAP, WPA2-PSK, WPA-EAP, WPA-PSK, WPA3-SAE, WPA3-EAP,

OWE; AES-CCMP, TKIP, Auto-cipher modes, client separation, EAP-TLS with

PKCS#12 certificates, disable auto-reconnect, 802.11w Protected Management

Frames (PMF)


**SSID/ESSID** SSID stealth mode and access control based on MAC address


**Wi-Fi users** Up to 50 simultaneous connections


**Wireless Connectivity Features** Fast roaming (802.11r), Relayd, BSS transition management (802.11v), radio resource

measurement (802.11k)


**Wireless MAC filter** Allowlist, blocklist


**Wireless QR code generator** Once scanned, a user will automatically enter your network without needing to input

login information


**TravelMate** Forward Wi-Fi hotspot landing page to a subsequent connected device


**Ethernet**


**WAN** 1 x WAN port 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az

standards, supports auto MDI/MDIX crossover


**LAN** 1 x LAN ports, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az

standards, supports auto MDI/MDIX crossover


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



4


### DATASHEET - RUT206

**Network**


**Routing** Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based

routing


**Network protocols** TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL v3,

TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP, Telnet, SMPP, SNMP, MQTT, Wake

on Lan (WOL), VXLAN


**VoIP passthrough support** H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


**Connection monitoring** Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


**Firewall** Port forward, traffic rules, custom rules, TTL target customisation


**Firewall status page** View all your Firewall statistics, rules, and rule counters


**Ports management** View device ports, enable and disable each of them, turn auto-configuration on or off,

change their transmission speed, and so on


**Network topology** Visual representation of your network, showing which devices are connected to which

other devices


**DHCP** Static and dynamic IP allocation, DHCP relay, DHCP server configuration, status,

static leases: MAC with wildcards


**QoS / Smart Queue Management (SQM)** Traffic priority queuing by source/destination, service, protocol or port, WMM,

802.11e


**DDNS** Supported >25 service providers, others can be configured manually


**DNS over HTTPS** DNS over HTTPS proxy enables secure DNS resolution by routing DNS queries over

HTTPS


**Network backup** Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic

Failover


**Load balancing** Balance Internet traffic over multiple WAN connections


**Hotspot** Captive portal (hotspot), internal/external Radius server, Radius MAC authentication,

SMS authorisation, SSO authentication, internal/external landing page, walled garden,

user scripts, URL parameters, user groups, individual user or group limitations, user

management, 9 default customisable themes and optionality to upload and download

customised hotspot themes


**Hotspot 2.0** Hotspot 2.0 is a Wi-Fi standard that enables seamless, secure, and automatic

connection to trusted wireless networks


**SSHFS** Possibility to mount remote file system via SSH protocol


**Traffic Management** Real-time monitoring, wireless signal charts, traffic usage history﻿


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



5


### DATASHEET - RUT206



**Security**


**Authentication** Pre-shared key, digital certificates, X.509 certificates, TACACS+, Internal & External

RADIUS users authentication, IP & login attempts block, time-based login blocking,

built-in random password generator


**Firewall** Preconfigured firewall rules can be enabled via WebUI, unlimited firewall

configuration via CLI, DMZ, NAT, NAT-T, NAT64


**Attack prevention** DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack

prevention), port scan prevention (SYN-FIN, SYN-RST, X-mas, NULL flags, FIN scan

attacks)


**VLAN** Port and tag-based VLAN separation


**Mobile quota control** Mobile data limit, customizable period, start time, warning limit, phone number


**WEB filter** Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites

only


**Access control** Flexible access control of SSH, Web interface, CLI and Telnet


**SSL certificate generation** Let's Encrypt and SCEP certificate generation methods


**802.1x** Port-based network access control server


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



6


### DATASHEET - RUT206



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


**OPC UA**


**Supported modes** Client, Server


**Supported connection types** TCP


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



7


### DATASHEET - RUT206

**MODBUS**


**Supported modes** Server, Client


**Supported connection types** RTU, TCP


**Custom registers** MODBUS TCP custom register block requests, which read/write to a file inside the

router, and can be used to extend MODBUS TCP Client functionality


**Supported data formats** 8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD

(big-endian), DCBA (little-endian), CDAB, BADC), HEX, ASCII


**DATA TO SERVER**


**Protocol** HTTP(S), MQTT, Azure MQTT


**Data to server** Extract parameters from multiple sources and different protocols, and send them all to

a single server; Custom LUA scripting, allowing scripts to utilize the router's Data to

server feature


**MQTT Gateway**


**Modbus MQTT Gateway** Allows sending commands and receiving data from MODBUS Server through MQTT

broker


**DNP3**


**Supported modes** TCP Master, DNP3 Outstation


**Supported connection types** RS232, RS485, TCP


**DLMS/COSEM**


**DLMS Support** DLMS - standard protocol for utility meter data exchange


**Supported modes** Client


**Supported connection types** TCP


**COSEM** Allows to scan meter COSEM objects for automatic detection and configuration


**API**



**Teltonika Networks Web API (beta)**

**support**



Expand your device's possibilities by using a set of configurable API endpoints to

retrieve or change data. For more information, please refer to this documentation:

[https://developers.teltonika-networks.com](https://developers.teltonika-networks.com)



Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



8


### DATASHEET - RUT206



**Monitoring & Management**


**WEB UI** HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, multiple event log

servers, firmware update availability notifications, event log, system log, kernel log,

Internet status


**FOTA** Firmware update from server, automatic notification


**SSH** SSH (v1, v2)


**SMS** SMS status, SMS configuration, send/read SMS via HTTP POST/GET


**Call** Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer, Wi-Fi

on/off


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


**RAM** 128 MB, DDR2


**FLASH storage** 32 MB, NOR Flash


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



9


### DATASHEET - RUT206

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


**Serial**


**RS232** RS232 interface without flow control signals


**RS485** Half duplex (2-wire) RS485 interface


**Input / Output**


**Events** Email, RMS, SMS


**SD CARD**


**Physical size** Micro SD (internal)


**Applications** Samba share


**Capacity** Up to 2 TB


**Storage Formats** FAT32, NTFS, ext2, ext3, ext4


**POE IN**


**PoE ports** 1 x PoE In


**PoE standards** Active PoE input 802.3af Class 0 (12.94 W) on LAN port


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



10


### DATASHEET - RUT206

**Power**


**Connector** 2-pin industrial DC power socket


**Input voltage range** 9 - 57 VDC, reverse polarity protection, surge protection >58V @10us min


**PoE (passive)** Passive PoE over spare pairs 4,5 (+) / 7,8 (-). Possibility to power up through LAN

port, passive PoE voltage: 16 - 57 VDC


**Power consumption** Idle: < 2 W, Max: < 3.5 W


**Physical Interfaces**


**Ethernet** 2 x RJ45 ports, 10/100 Mbps


**Status LEDs** 3 x Connection type status LEDs, 3 x Connection strength LEDs, 2 x LAN status LEDs,

1 x Power LED


**SIM** 2 x SIM slots (Mini SIM – 2FF), 1.8 V/3 V, double stacked SIM tray


**Power** 1 x 2-pin power connector


**Antennas** 2 x SMA for Mobile, 1 x RP-SMA for Wi-Fi


**RS232, RS485** 1 x 6-pin terminal block


**Reset** Reboot/User default reset/Factory reset button


**Physical Specification**


**Casing material** Anodized aluminum housing and panels


**Dimensions (W x H x D)** 83 x 25 x 83 mm


**Weight** 132 g


**Mounting options** DIN rail, wall mount, flat surface (all require additional kit)


**Operating Environment**


**Operating temperature** -40 °C to 75 °C


**Operating humidity** 10% to 90% non-condensing


**Ingress Protection Rating** IP30


**Regulatory & Type Approvals**


**Regulatory** CE, UKCA, CB, RCM, EAC, UCRF


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



11


### DATASHEET - RUT206



**ORDERING**


**STANDARD PACKAGE***


**RUT206** **2-PIN TERMINAL BLOCK** **2X3PIN CONNECTOR**


**1 X HEX KEY** **SIM ADAPTER KIT** **QSG (QUICK START GUIDE)**


RUT206 router

2-pin terminal block

[2X3PIN connector](https://teltonika-networks.com/products/accessories/other-2/2x3pin-connector)

1 x hex key

[SIM Adapter kit](https://teltonika-networks.com/products/accessories/other-2/sim-adapter-kit)

QSG (Quick Start Guide)

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


RUT206 * **1** ****

Europe [1], Australia, Asia-Pacific


RUT206 * **2** ****

North America


RUT206 * **3** ****

Latin America



**4G (LTE-FDD)** : B1, B3, B5, B7, B8, B20,

B28

**4G (LTE-TDD)** : B38, B40, B41

**3G** : B1, B5, B8

**2G** : B3, B8


**4G (LTE-FDD)** : B2, B4, B12, B13, B14,

B66, B71

**3G** : B2, B4, B5


**4G (LTE-FDD)** : B1, B2, B3, B4, B5, B7,

B8, B28, B66

**4G (LTE-TDD)** : B40

**3G** : B1, B2, B4, B5, B8

**2G** : B2, B3, B5, B8


### DATASHEET - RUT206

RUT206010000 / Standard package

without PSU


RUT206020000 / Standard Package

without PSU


RUT206030000 / Standard Package

without PSU



The price and lead-times for region (operator) specific versions may vary. For more information please [contact us.](https://teltonika-networks.com/about-us/contacts/)


1 - Regional availability - excluding Russia, Belarus & Iran


**RUT206 SPATIAL MEASUREMENTS**


**PHYSICAL SPECIFICATION**


**Device housing (W x H x D)*** 83 x 25 x 83 mm


**Box (W x H x D):** 100 x 31 x 107 mm


*Housing measurements are presented without antenna connectors and screws; for

measurements of other device elements look to the sections below.


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



13


### DATASHEET - RUT206



**TOP VIEW**

The figure below depicts the measurements of device and its components as seen from the top:


**RIGHT VIEW**

The figure below depicts the measurements of device and its components as seen from the right side:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



14


### DATASHEET - RUT206



**FRONT VIEW**

The figure below depicts the measurements of device and its components as seen from the front panel side:


**REAR VIEW**

The figure below depicts the measurements of device and its components as seen from the back panel side:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



15


### DATASHEET - RUT206



**MOUNTING SPACE REQUIREMENTS**

The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



16


