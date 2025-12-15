Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // RUT360


## HARDWARE

FRONT VIEW


**Power socket**


**Power LED**


BACK VIEW


POWER SOCKET PINOUT



**Reset button**


**Power / Red wire** **Ground / Black wire**

**Input/ Output / Green wire** **Input/ Output / White wire**



**Mobile network type LEDs**



**Mobile signal strength indication LEDs**





**ETH activity LEDs**


**Mobile MAIN**
**WiFi antenna**
**antenna**
**connector**
**connector**








- **I/O** : programmable Input/Output pins (Open Collector output max 30 V, 300 mA or Digital input where 0-6 V detected as logic low and 8-30 V - logic high).


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **2**


DATASHEET // RUT360


l



l


## FEATURES

**MOBILE**


Mobile module


l



l



4G (LTE) – Cat 6 up to 300 Mbps, 3G – Up to 42 Mb


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



Wireless Connectivity Features Wireless mesh (802.11s), fast roaming (802.11r), Relayd


Wireless MAC filter Whitelist, blacklist


**NETWORK**


l



Hotspot


Routing


Network protocols


VoIP passthrough support


l



Captive portal (Hotspot), internal/external Radius server, SMS authorization, internal/external landing page, walled garden,
user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customizable
themes and option to upload and download customised hotspot themes


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)

H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


l



Connection monitoring Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


l



Firewall


l



Port forward, traffic rules, custom rules


l



DHCP Static and dynamic IP allocation, DHCP Relay


l



QoS / Smart Queue
Management (SQM)

DDNS


Network backup


l



Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover


l



Load balancing Balance Internet traffic over multiple WAN connections


SSHFS Possibility to mount remote file system via SSH protocol


**ETHERNET**


WAN 1 x WAN port 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX


l



LAN


**SECURITY**


Authentication


Firewall


Attack prevention

l

VLAN



1 x LAN ports, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX crossover


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


Flexible access control of TCP, UDP, ICMP packets, MAC address filter



l


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **3**


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



DATASHEET // RUT360


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


**MODBUS TCP SLAVE**



ID filtering



Respond to one ID in range [1;255] or any



Allow remote access Allow access through WAN

MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Slave functionality


**MODBUS TCP MASTER**



Supported functions



01, 02, 03, 04, 05, 06, 15, 16



8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC)


**DATA TO SERVER**



Protocol


**MQTT GATEWAY**


MQTT Gateway


**DNP3**


Supported modes



HTTP(S), MQTT, Azure MQTT, Kinesis


Allows sending commands and receiving data from MODBUS Master through MQTT broker


TCP Master, DNP3 Outstation



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


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **4**


DATASHEET // RUT360



**SYSTEM CHARACTERISTICS**


CPU


RAM



QCA9531, MIPS 24kc, 650 MHz


128 MB, DDR2



FLASH storage 16 MB, SPI Flash


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


**INPUT / OUTPUT**



Busybox shell, Lua, C, C++


SDK package with build environment provided



Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high



Output


Events



1 x Digital Output, Open collector output, max output 30 V, 300 mA


Email, RMS, SMS



I/O juggler Allows to set certain I/O conditions to initiate event


**POWER**


Connector 4-pin industrial DC power socket



Input voltage range


Power consumption


**PHYSICAL INTERFACES**



9 – 30 VDC, reverse polarity protection; surge protection >31 VDC 10us max


10.5 W max



Ethernet 2 x RJ45 ports, 10/100 Mbps



I/Os


Status LEDs



1 x Digital Input, 1 x Digital Output on 4-pin power connector


2 x Mobile connection type, 3 x Mobile connection strength, 2 x Eth status, 1 x Power



SIM 1 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders



Power


Antennas



1 x 4-pin power connector


2 x SMA for LTE, 2 x RP-SMA for Wi-Fi



Reset Reboot/User default reset/Factory reset button


**PHYSICAL SPECIFICATION**


Casing material Aluminum housing



Dimensions (W x H x D)


Weight



100 x 30 x 85 mm


247 g



Mounting options DIN rail, flat surface placement


**OPERATING ENVIRONMENT**


Casing material -40 °C to 75 °C



Dimensions (W x H x D)


Weight



10% to 90% non-condensing


IP30



**REGULATORY & TYPE APPROVALS**


Regulatory CE/RED, UKCA, CB, UCRF, RoHS, REACH, ICASA, ANRT, RCM, ETA-WPC, NTC, FCC, IC, PTCRB, NOM, GCF


Operator AT&T, Verizon, T-Mobile, UScellular


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **5**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUT360

- 12 W PSU

- 2x LTE antennas (swivel, SMA male)

- 2x Wi-Fi antennas (swivel, RP-SMA male)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box







DATASHEET // RUT360


|ROUTER RUT360|12 W PSU|2 X LTE ANTENNAS (SWIVEL, SMA<br>MALE)|
|---|---|---|
|**2 X WIFI ANTENNA (SWIVEL, RP-SMA**<br>**MALE)**|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**|
|**QSG**|||




   - For all standard order codes standard package contents are the same, execpt for PSU.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **6**


DATASHEET // RUT360

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUT360 000000



851762 8517.62.00 Standard package with EU PSU



RUT360 100100 851762 8517.62.00 Standard package with US PSU


For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



RUT360 0*****



Europe [2], The Middle East, Africa,
Australia, APAC [3], Brazil, Malaysia



RUT360 1*****
North America [4]


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 - LTE-FDD B29 and B32 support receiving only, and are only for secondary component carrier in 2×CA
2 - Regional availability - excluding Russia & Belarus.
3 - Excluding Japan and CMCC
4 - For more detailed information about certified carriers, visit our Wiki page




**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B20, B28, B32 [1]

**• 4G (LTE-TDD):** B38, B40, B41

**• 3G:** B1, B3, B5, B8

**• 4G (LTE-FDD):** B2, B4, B5, B7, B12, B13, B25,
B26, B291, B30, B66

**• 3G:** B2, B4, B5



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **7**


DATASHEET // RUT360


## RUT360 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUT360:



Device housing*:

Box:



100 x 30 x 85 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUT360 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUT360 and its components as seen from the right side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **8**


DATASHEET // RUT360


**FRONT VIEW**


The figure below depicts the measurements of RUT360 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUT360 and its components as seen from the back panel side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // RUT360


**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **10**


DATASHEET // RUT360


**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **11**


