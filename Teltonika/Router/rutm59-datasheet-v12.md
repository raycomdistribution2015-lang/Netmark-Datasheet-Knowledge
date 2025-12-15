# RUTM59
## v1.2

Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.


### DATASHEET - RUTM59



**HARDWARE**


**FRONT VIEW**


**BACK VIEW**


**POWER SOCKET PINOUT**


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



2


### DATASHEET - RUTM59

**FEATURES**


**Mobile**


**Mobile module** 5G Sub-6 GHz SA, NSA 2.4, 3.4Gbps DL (4x4 MIMO) 900, 550Mbps UL (2x2

MIMO); 4G LTE: DL Cat 19 1.6Gbps (4x4 MIMO), UL Cat 18 200Mbps


**3GPP Release** Release 16


**SIM switch** 2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no

network, network denied, data connection fail, SIM idle protection


**Status** IMSI, ICCID, operator, operator state, data connection state, network type, CA

indicator, bandwidth, connected band, signal strength (RSSI), SINR, RSRP, RSRQ,

EC/IO, RSCP, data sent/received, LAC, TAC, cell ID, ARFCN, UARFCN, EARFCN, MCC,

and MNC


**SMS** SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS,

SMS to EMAIL, SMS to HTTP, SMS to SMS, scheduled SMS, SMS autoreply, SMPP


**USSD** Supports sending and reading Unstructured Supplementary Service Data messages


**Black/White list** Operator black/white list (by country or separate operators)


**Multiple PDN** Possibility to use different PDNs for multiple network access and services


**Band management** Band lock, Used band status display


**SIM idle protection service** When working with devices with two SIM slots, the one not currently in use will remain

idle until the device switches to it, meaning that no data is used on the card until then


**SIM PIN code management** SIM PIN code management enables setting, changing, or disabling the SIM card's PIN


**APN** Auto APN


**Bridge** Direct connection (bridge) between mobile ISP and device on LAN


**Passthrough** Router assigns its mobile WAN IP address to another device on LAN


**Framed routing** Framed routing: support an IP network behind 5G UE


**Ethernet**


**WAN** 1 x WAN port 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az

standards, supports auto MDI/MDIX crossover


**LAN** 4 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az

standards, supports auto MDI/MDIX crossover


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



3


### DATASHEET - RUTM59

**Network**


**Routing** Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based

routing


**Network protocols** TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS,

ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP, Telnet, SMPP, SNMP, MQTT, Wake On

Lan (WOL), VXLAN


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


**Load balancing** Balance Internet traffic over multiple WAN connections


**SSHFS** Possibility to mount remote file system via SSH protocol


**VRF support** Initial virtual routing and forwarding (VRF) support


**Traffic Management** Real-time monitoring, traffic usage history


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



4


### DATASHEET - RUTM59



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


**802.1x** Port-based network access control client


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



5


### DATASHEET - RUTM59

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


**Tailscale** Tailscale offers speed, stability, and simplicity over traditional VPNs. Encrypted point
to-point connections using the open source WireGuard protocol


**OPC UA**


**Supported modes** Client, Server


**Supported connection types** TCP


**MODBUS**


**Supported modes** Server, Client


**Supported connection types** TCP, USB


**Custom registers** MODBUS TCP custom register block requests, which read/write to a file inside the

router, and can be used to extend MODBUS TCP Client functionality


**Supported data formats** 8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD

(big-endian), DCBA (little-endian), CDAB, BADC), HEX, ASCII


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



6


### DATASHEET - RUTM59

**DATA TO SERVER**


**Protocol** HTTP(S), MQTT, Azure MQTT


**Data to server** Extract parameters from multiple sources and different protocols, and send them all to

a single server; Custom LUA scripting, allowing scripts to utilize the router's Data to

server feature


**MQTT Gateway**


**Modbus MQTT Gateway** Allows sending commands and receiving data from MODBUS Server through MQTT

broker


**DNP3**


**Supported modes** Station, Outstation


**Supported connection** TCP, USB


**DLMS**


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



7


### DATASHEET - RUTM59



**Monitoring & Management**


**WEB UI** HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, multiple event log

servers, firmware update availability notifications, event log, system log, kernel log,

Internet status


**FOTA** Firmware update from server, automatic notification


**SSH** SSH (v1, v2)


**SMS** SMS status, SMS configuration, send/read SMS via HTTP POST/GET


**Call** Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer


**Email** Receive email message status alerts of various services


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


**CPU** MediaTek, Dual-Core, 880 MHz, MIPS1004Kc


**RAM** 256 MB, DDR3


**FLASH storage** 16 MB serial NOR flash, 256 MB serial NAND flash


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



8


### DATASHEET - RUTM59

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


**Supported languages** Busybox shell, Lua, C, C++, and Python, Java in Package manager


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


**USB**


**Data rate** USB 2.0


**Applications** Samba share, USB-to-serial


**External devices** Possibility to connect external HDD, flash drive, additional modem, printer, USB-serial

adapter


**Storage formats** FAT, FAT32, exFAT, NTFS (read-only), ext2, ext3, ext4


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



9


### DATASHEET - RUTM59

**Input / Output**


**Input** 1 x Configurable digital Input, 0 - 6 V detected as logic low, 8 - 50 V detected as logic

high


**Output** 1 x Configurable digital Output, Open collector output, max output 50 V, 300 mA


**Events** Email, RMS, SMS


**I/O juggler** Allows to set certain I/O conditions to initiate event


**Power**


**Connector** 4-pin industrial DC power socket


**Input voltage range** 9 – 50 VDC, reverse polarity protection, surge protection >51 VDC 10us max


**PoE (passive)** Passive PoE over spare pairs. Possibility to power up through LAN port, not

compatible with IEEE802.3af, 802.3at and 802.3bt standards, Mode B, LAN1 Port, 9 
50 VDC


**Power consumption** Idle: 5 W, Max: 18 W


**Physical Interfaces**


**Ethernet** 5 x RJ45 ports, 10/100/1000 Mbps


**I/O’s** 1 x Digital Input, 1 x Digital Output on 4-pin power connector


**Status LEDs** 3 x WAN status LEDs, 3 x Mobile connection type, 3 x Mobile connection strength, 10

x Ethernet port status LEDs, 1 x Power


**SIM** 2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders


**Power** 1 x 4-pin power connector


**Antennas** 4 x SMA for Mobile, 1 x SMA for GNNS


**USB** 1 x USB A port for external devices


**Reset** Reboot/User default reset/Factory reset button



**Other**


**Physical Specification**



1 x Grounding screw



**Casing material** Aluminium housing


**Dimensions (W x H x D)** 132 x 44.2 x 95 mm


**Weight** 530 g


**Mounting options** DIN rail, wall mount, flat surface (all require additional kit)


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



10


### DATASHEET - RUTM59



**Operating Environment**


**Operating temperature** -40 °C to 75 °C


**Operating humidity** 10% to 90% non-condensing


**Ingress Protection Rating** IP30


**Regulatory & Type Approvals**


**Regulatory** FCC, ISED, WEEE


**EMC Emissions & Immunity**


**Standards** FCC/ISED:

47 CFR Part 15 Subpart B

ICES-003: Issue 7 (October 2020)


**Safety**


**Standards** FCC/ISED:

47 CFR - § 2.1091

KDB 447498 D04 Interim General RF Exposure Guidance v01

RSS-102 Issue 5 (March 2015) Amendment 1


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



11


**ORDERING**


**STANDARD PACKAGE***


RUTM59 Router

[18 W PSU](https://teltonika-networks.com/products/accessories/powering-options/us-power-supply-18w)

[4 x Mobile antennas (swivel, SMA male)](https://teltonika-networks.com/products/accessories/antenna-options/5g-mobile-sma-antenna)

[1 x GNSS antenna (adhesive, SMA male, 3 m cable)](https://teltonika-networks.com/products/accessories/antenna-options/gnss-adhesive-sma-antenna)

[Ethernet cable (1.5 m)](https://teltonika-networks.com/products/accessories/other-2/ethernet-cable-15m)

[SIM Adapter kit](https://teltonika-networks.com/products/accessories/other-2/sim-adapter-kit)

QSG (Quick Start Guide)

Packaging box


*Standard package contents may differ based on standard order codes.


[For more information on all available packaging options – please contact us](https://teltonika-networks.com/about-us/contacts/) directly.


**CLASSIFICATION CODES**


**HS Code:** 851762

**HTS:** 8517.62.00


**AVAILABLE VERSIONS**



RUTM59 ******

North America [1]



**5G NR NSA** : n2, n5, n7, n12, n13, n14, n25, n26,

n29, n30, n38, n41, n48, n66, n70, n71, n77, n78

**5G NR SA** : n2, n5, n7, n12, n13, n14, n25, n26, n29,

n30, n38, n41, n48, n66, n70, n71, n77, n78

**5G DL 4 × 4 MIMO:** n2, n5, n7, n12, n13*, n14, n25,

n26*, n29, n30, n38, n41, n48, n66, n70, n71, n77,

n78

**4G (LTE-FDD)** : B2, B4, B5, B7, B12, B13, B14, B17,

B25, B26, B29, B30, B66, B71

**4G (LTE-TDD)** : B38, B41, B42, B43, B48


### DATASHEET - RUTM59

RUTM59000000 / Standard

package with US PSU

RUTM59000200 / Mass

packing code



The price and lead-times for region (operator) specific versions may vary. For more information please [contact us.](https://teltonika-networks.com/about-us/contacts/)


[1 - For more detailed information about certified carriers, visit our Wiki](https://wiki.teltonika-networks.com/view/Certificates#Americas.2C_Carrier.2C_and_Miscellaneous_table) page


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



12


### DATASHEET - RUTM59



**RUTM59 SPATIAL MEASUREMENTS**


**PHYSICAL SPECIFICATION**


**Device housing (W x H x D)*** 132 x 103.5 x 44.2 mm


**Box (W x H x D):** 355 x 175 x 60 mm


*Housing measurements are presented without antenna connectors and screws; for

measurements of other device elements look to the sections below.


**TOP VIEW**

The figure below depicts the measurements of device and its components as seen from the top:


**RIGHT VIEW**

The figure below depicts the measurements of device and its components as seen from the right side:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



13


### DATASHEET - RUTM59



**FRONT VIEW**

The figure below depicts the measurements of device and its components as seen from the front panel side:


**REAR VIEW**

The figure below depicts the measurements of device and its components as seen from the back panel side:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



14


### DATASHEET - RUTM59



**MOUNTING SPACE REQUIREMENTS**

The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



15


