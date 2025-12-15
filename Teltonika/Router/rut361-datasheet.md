Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // RUT361


## HARDWARE

FRONT VIEW


**Power socket**


**Power LED**


BACK VIEW


POWER SOCKET PINOUT



**Reset button**


**Power / Red wire** **Ground / Black wire**



**Mobile network type LEDs**



**Mobile signal strength indication LEDs**





**ETH activity LEDs**


**Mobile MAIN**
**WiFi antenna**
**antenna**
**connector**
**connector**







**Input/ Output / Green wire** **Input/ Output / White wire**


- **I/O** : programmable Input/Output pins (Open Collector output max 30 V, 300 mA or Digital input where 0-6 V detected as logic low and 8-30 V - logic high).


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **2**


DATASHEET // RUT361


l



l


## FEATURES

**MOBILE**


Mobile module


l



l



4G (LTE) – Cat 6 up to 300 Mbps, 3G – Up to 42 Mbps


l



Status Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID, Carrier aggregation


l



SMS


USSD


Black/White list


Multiple PDN


Band management


l



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


Wireless mode 802.11 b/g/n, 2x2 MIMO, Access Point (AP), Station (STA)


l



Wi-Fi security


SSID/ESSID


l



WPA3-EAP, WPA3-SAE, WPA2-Enterprise-PEAP, WPA2-PSK, WEP; AES-CCMP, TKIP, Auto Cipher modes, client separation


ESSID stealth mode


l



Wi-Fi users Up to 50 simultaneous connections


Wireless Connectivity Features Wireless mesh (802.11s), fast roaming (802.11r)


Wireless MAC filter Whitelist, blacklist


Wireless QR code generator Once scanned, a user will automatically enter your network without needing to input login information

**ETHERNET**


WAN 1 x WAN port 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX


l



LAN

**NETWORK**


Routing


Network protocols


VoIP passthrough support


l



1 x LAN ports, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX crossover


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SNMP, MQTT, Wake On Lan (WOL)

H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


l



Connection monitoring Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


l



Firewall


l



Port forward, traffic rules, custom rules


l



Firewall status page View all your Firewall statistics, rules, and rule counters


l



Ports management


Network topology


DHCP


l



View device ports, enable and disable each of them, turn auto-configuration on or off, change their transmission speed, and so on


Visual representation of your network, showing which devices are connected to which other devices


Static and dynamic IP allocation, DHCP Relay


l



QoS / Smart Queue
Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e
Management (SQM)

DDNS Supported >25 service providers, others can be configured manually


Network backup VRRP, Wired options, each of which can be used as an automatic Failover, Wi-Fi WAN, Mobile


Load balancing Balance Internet traffic over multiple WAN connections


Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
Hotspot user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes and option to upload and download customised hotspot themes


SSHFS Possibility to mount remote file system via SSH protocol

**SECURITY**


l



Authentication


Firewall


Attack prevention

l

VLAN



Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block


Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T

DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
SYN-RST, X-mas, NULL flags, FIN scan attacks)

Port and tag-based VLAN separation



l


Mobile quota control Mobile data limit, customizable period, start time, warning limit, phone number



l


WEB filter


Access control



l


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Flexible access control of SSH, Web interface, CLI and Telnet



l


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



l


**3**


**VPN**


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



DATASHEET // RUT361


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



Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support


Tailscale offers speed, stability, and simplicity over traditional VPNs. Encrypted point-to-point connections using the open
Tailscale
source WireGuard protocol


**OPC UA**



Supported modes



Client, Server



Supported connection types TCP


**MODBUS**



Supported modes



Server, Client



Supported connection types TCP, USB

MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Slave functionality

8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC), HEX, ASCII


**DATA TO SERVER**



Protocol



HTTP(S), MQTT, Azure MQTT



Data to server Extract parameters from multiple sources and different protocols, and send them all to a single server


**MODBUS MQTT GATEWAY**



Modbus MQTT Gateway


**DNP3**


Supported modes



Allows sending commands and receiving data from MODBUS Master through MQTT broker


Station, Outstation



Supported connection TCP, USB


**DLMS**



DLMS Support



DLMS - standard protocol for utility meter data exchange



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


MODBUS MODBUS TCP status/control


RMS Teltonika Remote Management System (RMS)


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUT361



**IoT PLATFORMS**


Clouds of things



Allows monitoring of: Device data, Mobile data, Network info, Availability



ThingWorx Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type

Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP, Mobile Cell ID, ICCID, IMEI, Connection
Cumulocity
Type, Operator, Signal Strength

Can send device IP, Number of bytes send/received, Temperature, PIN count to Azure IoT Hub server, Mobile connection state,
Azure IoT Hub Network link state, IMEI, ICCID, Model, Manufacturer, Serial, Revision, IMSI, SIM State, PIN state, GSM signal, WCDMA RSCP,
WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID, Operator, Operator number, Connection type

**SYSTEM CHARACTERISTICS**



CPU


RAM



Mediatek, 580 MHz, MIPS 24KEc


128 MB, DDR2



FLASH storage 16 MB serial NOR flash

**FIRMWARE / CONFIGURATION**


WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup



FOTA


RMS



Update FW


Update FW/configuration for multiple devices at once



Keep settings Update FW without losing current configuration

**FIRMWARE CUSTOMISATION**


Operating system RutOS (OpenWrt based Linux OS)



Supported languages


Development tools



Busybox shell, Lua, C, C++


SDK package with build environment provided



You can create your own custom, branded firmware and web page application by changing colours, logos, and other elements
Development tools
in our firmware to fit your or your clients’ needs

**INPUT / OUTPUT**


Input 2 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high



Output


Events



2 x Digital Output, Open collector output, max output 30 V, 300 mA


Email, RMS, SMS



I/O juggler Allows to set certain I/O conditions to initiate event

**POWER**


Connector 4-pin industrial DC power socket



Input voltage range


PoE (passive)



9 - 30 VDC, reverse polarity protection, voltage surge/transient protection


Passive PoE can be installed upon request



Power consumption Idle: < 2.4 W, Max: < 4.7 W

**PHYSICAL INTERFACES**


Ethernet 2 x RJ45 ports, 10/100 Mbps



I/O’s


Status LEDs



2 x Digital Input, 2 x Digital Output on 4-pin power connector


2 x Mobile connection type, 3 x Mobile connection strength, 2 x Eth status, 1 x Power



SIM 1 x SIM slot (Mini SIM - 2FF), 1.8 V/3 V, external SIM holder



Power


Antennas



1 x 4-pin power connector


2 x SMA for LTE, 2 x RP-SMA for Wi-Fi



Reset Reboot/User default reset/Factory reset button

**PHYSICAL SPECIFICATION**


Casing material Aluminum housing



Dimensions (W x H x D)


Weight



93.2 x 100 x 30 mm


243 g



Mounting options DIN rail, flat surface placement

**OPERATING ENVIRONMENT**


Casing material -40 °C to 75 °C



Dimensions (W x H x D)


Weight



10% to 90% non-condensing


IP30



**REGULATORY & TYPE APPROVALS**


Regulatory CE, UKCA, RCM, UCRF, EAC, WEEE, CB


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


## STANDARD PACKAGE*


- Router RUT361

- 18 W PSU

- 2x Mobile antennas (swivel, SMA male)

- 2x Wi-Fi antennas (swivel, RP-SMA male)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box



|ROUTER RUT361|18 W PSU|2X MOBILE ANTENNAS (SWIVEL,<br>SMA MALE)|
|---|---|---|
|**2X WI-FI ANTENNAS (SWIVEL, RP-SMA**<br>**MALE)**|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**|
|**QSG**|||



- Standard package contents may differ based on standard order codes.





DATASHEET // RUT361



Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // RUT361

## CLASSIFICATION CODES


HS Code: 851762

HTS: 8517.62.00


For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**HARDWARE VERSION** **SUPPORTED FREQUENCIES** **STANDARD ORDER CODE / PACKAGE CONTAINS**



RUT361 1*****
EMEA, Australia, Brazil



**4G (LTE-FDD):** B1, B3, B5, B7, B8, B20,
B28, B321
**4G (LTE-TDD):** B38, B40, B41, B42², B43 ²
**3G:** B1, B3, B5, B8



RUT361100000 / Standard package with EU PSU



The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 LTE-FDD B32, B29 supports Rx only and is only for secondary component carrier.
2 B42, B43 bands are optional.


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // RUT361


## RUT361 SPATIAL MEASUREMENTS

**MAIN MEASUREMENTS**


W x H x D dimensions for RUT361:



Device housing*:

Box:



93.2 x 100 x 30 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUT361 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUT361 and its components as seen from the right side:


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUT361



**FRONT VIEW**


The figure below depicts the measurements of RUT361 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUT361 and its components as seen from the back panel side:


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // RUT361



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // RUT361



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


