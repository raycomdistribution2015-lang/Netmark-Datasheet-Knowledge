# OTD140

Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


**ETH status LEDs**

**ETH ports**


**Mounting Bracket**


RJ45 LED MEANING



**Mobile connection**
**strength LEDs**





**Mobile connection**
**type LEDs**



DATASHEET // OTD140


**SIM1/SIM2 slots**


**Reset button**



**Orange LED on: link established**
**10/100 Mbps**
**Orange LED blinking: active connection**


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **2**


## FEATURES

**MOBILE**


Mobile module



DATASHEET // OTD140


4G (LTE) - LTE Cat 4 150 Mbps DL, 50 Mbps UL; 3G - 21 Mbps DL, 5.76 Mbps UL; 2G - 236.8 kbps DL, 236.8 kbps UL



2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail,
SIM switch
SIM idle protection


Status Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID



SMS


USSD


Black/White list


Band management


APN



SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP


Supports sending and reading Unstructured Supplementary Service Data messages


Operator black/white list


Band lock, Used band status display


Auto APN



Bridge Direct connection (bridge) between mobile ISP and device on LAN



Passthrough


**ETHERNET**



Router assigns its mobile WAN IP address to another device on LAN



2 x ETH ports (can be configured as WAN), 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports
LAN
auto MDI/MDIX crossover

**POE IN**



PoE ports


PoE standards


**POE OUT**


PoE ports



1 x PoE In


802.3af/at


1 x PoE Out



PoE standards 802.3af


PoE Max Power per Port (at PSE) 15 W (only available if device is powered by 802.3at PoE In)


**NETWORK**



Routing


Network protocols



Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SNMP, MQTT, Wake On Lan (WOL)



VoIP passthrough support H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets



Connection monitoring


Firewall


Firewall status page


Ports management


Network topology



Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


Port forward, traffic rules, custom rules


View all your Firewall statistics, rules, and rule counters


View device ports, enable and disable each of them, turn auto-configuration on or off, change their transmission speed,
and so on


Visual representation of your network, showing which devices are connected to which other devices



DHCP Static and dynamic IP allocation, DHCP Relay


QoS / Smart Queue
Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e
Management (SQM)



DDNS


Network backup


Hotspot



Supported >25 service providers, others can be configured manually


VRRP, Wired options, each of which can be used as an automatic Failover


Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes and option to upload and download customised hotspot themes



SSHFS Possibility to mount remote file system via SSH protoco


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **3**


**SECURITY**


Authentication


Firewall



DATASHEET // OTD140


Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block


Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T



DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
Attack prevention
SYN-RST, X-mas, NULL flags, FIN scan attacks)



VLAN


Mobile quota control


WEB filter


Access control


**VPN**


OpenVPN


OpenVPN Encryption


IPsec


GRE


PPTP, L2TP


Stunnel


DMVPN


SSTP



Port and tag-based VLAN separation


Mobile data limit, customizable period, start time, warning limit, phone number


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Flexible access control of SSH, Web interface, CLI and Telnet


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



ZeroTier ZeroTier VPN client support


WireGuard WireGuard VPN client and server support


Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support


**OPC UA**



Supported modes



Client, Server (planned)



Supported connection types TCP


**MODBUS**



Supported modes



Server, Client



Supported connection types TCP


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



Supported connection TCP


**DLMS**



DLMS Support



DLMS - standard protocol for utility meter data exchange



Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **4**


DATASHEET // OTD140



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


Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher


SNMP (v1, v2, v3), SNMP Trap



JSON-RPC Management API over HTTP/HTTPS



MODBUS


RMS

**IoT PLATFORMS**


Cloud of Things


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



128 MB


16 MB



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



Busybox shell, Lua, C, C++, and Python, Java in Package manager


SDK package with build environment provided



You can now create your own custom firmware and web page application, with some examples to make the creation process
GPL customization
easier; and brand our firmware by changing colours, logos, and so on to fit your or your clients’ needs

**INPUT / OUTPUT**


Events Email, RMS, SMS

**POWER**


Connector RJ45 Socket


Input voltage range for PoE 42.5–57.0 VDC, reverse polarity protection, voltage surge/transient protection


Power consumption Idle: < 2.5 W / Max: < 6 W / PoE Max < 21 W

**PHYSICAL INTERFACES**


Ethernet 2 x RJ45 ports, 10/100 Mbps



Status LEDs


SIM



3 x Mobile connection type, 3 x Mobile connection strength, 4 x ETH status LEDs


2 x SIM slots (Mini SIM – 2FF), 1.8 V/3 V



Power RJ45, PoE In, 42.5 – 57.0 VDC



Antennas


Reset



2 x Internal antennas


Reboot/User default reset/Factory reset button



Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **5**


DATASHEET // OTD140



**PHYSICAL SPECIFICATION**


Casing material


Dimensions (W x H x D)


Weight


Mounting options


**OPERATING ENVIRONMENT**


Operating temperature


Operating humidity



Plastic (PC+ASA)


110 x 49.30 x 235 mm


855 g


Mounting Bracket (for vertical flat surface or pole mounting)


-40 °C to 75 °C


10% to 90% non-condensing



Ingress Protection Rating IP55


**REGULATORY & TYPE APPROVALS**


Regulatory CE, UKCA, EAC, UCRF, RCM


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **6**


DATASHEET // OTD140

## STANDARD PACKAGE*


- OTD140 Router

- Router Holder

- QSG (Quick Start Guide)

- Packaging Box

**OTD140 ROUTER** **ROUTER HOLDER** **QSG (QUICK START GUIDE)**


   - Standard package contents may differ based on standard order codes.

## CLASSIFICATION CODES


HS Code: 851762

HTS: 8517.62.00


For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**HARDWARE VERSION** **SUPPORTED FREQUENCIES** **STANDARD ORDER CODE / PACKAGE CONTAINS**



OTD140 0*****
Australia, Europe, Asia-Pacific



**4G (LTE-FDD):** B1, B3, B5, B7, B8, B20, B28
**4G (LTE-TDD):** B38, B40, B41
**3G:** B1, B5, B8
**2G:** B3, B8



OTD140 000000 / Standard Package



The price and lead-times for region (operator) specific versions may vary. For more information please contact us.


1 - Regional availability - excluding Russia & Belarus
2 - For more detailed information about certified carriers, visit our Wiki page


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **7**


DATASHEET // OTD140


## OTD140 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for OTD140:



Device housing*:

Box:



110 x 49.30 x 235 mm

355 mm x 175 mm x 60 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of OTD140 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of OTD140 and its components as seen from the right side:

|194.99<br>234.91|Col2|Col3|
|---|---|---|
||||



Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **8**


DATASHEET // OTD140


**FRONT VIEW**


The figure below depicts the measurements of OTD140 and its components as seen from the front panel side:

|Col1|Col2|Col3|Col4|
|---|---|---|---|
|||||
|||||
||** 50.45**|** 50.45**|** 50.45**|
|||||



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // OTD140



**MOUNTING SPACE REQUIREMENTS**



**49.30**

|3.4<br>15.00<br>104.50<br>15.00|Col2|Col3|3.4|
|---|---|---|---|
|** 15.00**<br> <br>** 3.4**<br>** 15.00**<br>** 104.50**|** 15.00**<br> <br>** 3.4**<br>** 15.00**<br>** 104.50**|||
|** 15.00**<br> <br>** 3.4**<br>** 15.00**<br>** 104.50**||||
|** 15.00**<br> <br>** 3.4**<br>** 15.00**<br>** 104.50**||||
|** 15.00**<br> <br>** 3.4**<br>** 15.00**<br>** 104.50**|||** 15.00**|
|** 15.00**<br> <br>** 3.4**<br>** 15.00**<br>** 104.50**||** 104.50**|** 104.50**|
|** 15.00**<br> <br>** 3.4**<br>** 15.00**<br>** 104.50**|||** 15.00**|
|** 15.00**<br> <br>** 3.4**<br>** 15.00**<br>** 104.50**||||



Copyright © 2024, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **10**


