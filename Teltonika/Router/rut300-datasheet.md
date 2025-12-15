Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


BACK VIEW


POWER SOCKET PINOUT



DATASHEET // RUT300


**LAN LEDs** **WAN LEDs**


**LAN Ethernet ports** **WAN Ethernet port**


**Power socket** **USB port**


**Reset button**


**Power / Red wire** **Ground / Black wire**

**Input/ Output / Green wire** **Input/ Output / White wire**



I/O (PIN 3 and 4): Configurable digital Input/Output pins. Open collector output, max output 30 V, 300 mA or Digital input where 0-6 V detected as logic low and
8-30 V – logic high


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **2**


DATASHEET // RUT300


l



l



l


## FEATURES

**ETHERNET**


WAN 1 x WAN port 10/100 Mbps, compliance IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX


l



LAN


**NETWORK**


Routing


Network protocols


VoIP passthrough support


Connection monitoring


l



4 x LAN ports, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX crossover


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)

H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


l



Firewall Port forward, traffic rules, custom rules


l



DHCP

QoS / Smart Queue
Management (SQM)

DDNS


Network backup


l



Static and dynamic IP allocation, DHCP Relay


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


VRRP, Wired options, each of which can be used as an automatic Failover


l



Load balancing Balance Internet traffic over multiple WAN connections


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


WEB filter Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


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


**MODBUS TCP SLAVE**



l


ID filtering



l


Respond to one ID in range [1;255] or any



l


Allow remote access Allow access through WAN

MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP Slave functionality


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **3**


DATASHEET // RUT300



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


TR-069


MQTT


SNMP


JSON-RPC


MODBUS



SSH (v1, v2)


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



Allows monitoring of: WAN Type, WAN IP


Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP



Azure IoT Hub Can send device IP, Number of bytes send/received, Temperature, PIN count to Azure IoT Hub server


**SYSTEM CHARACTERISTICS**



CPU


RAM



QCA9531, MIPS 24kc, 650 MHz


64 MB, DDR2



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


**USB**



Busybox shell, Lua, C, C++


SDK package with build environment provided



Data rate USB 2.0



Applications


External devices



Samba share, USB-to-serial


Possibility to connect external HDD, flash drive, additional modem, printer, USB-serial adapter



Storage formats FAT, FAT32, exFAT, NTFS (read-only), ext2, ext3, ext4


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **4**


DATASHEET // RUT300


**INPUT / OUTPUT**


Input 2 x Configurable digital Inputs. Digital input 0 - 5 V detected as logic low, 8 - 30 V detected as logic high



Output


Events


I/O juggler


**POWER**



2 x Configurable digital Outputs. Open collector output, max output 30 V, 300 mA


Email, RMS


Allows to set certain I/O conditions to initiate event



Connector 4-pin industrial DC power socket



Input voltage range


PoE (passive)


Power consumption


**PHYSICAL INTERFACES**



7 - 30 VDC, reverse polarity protection, voltage surge/transient protection

Passive PoE. Passive PoE over spare pairs. Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at
and 802.3bt standards, Mode B, 9 - 30 VDCto power up through LAN port, not compatible with IEEE802.3af, 802.3at and
802.3bt standards


Idle: 1.3 W, Max: 3 W



Ethernet 5 x RJ45 ports, 10/100 Mbps



I/Os


Status LEDs



2 x Configurable I/O pins on 4-pin power connector


5 x ETH status, 1 x Power



Power 1 x 4-pin power connector



USB


Reset


**PHYSICAL SPECIFICATION**



1 x USB A port for external devices


Reboot/User default reset/Factory reset button



Casing material Aluminum housing



Dimensions (W x H x D)


Weight



100 x 30 x 85 mm


229 g



Mounting options DIN rail, flat surface placement


**OPERATING ENVIRONMENT**


Operating temperature -40 °C to 75 °C



Operating humidity


Ingress Protection Rating



10% to 90% non-condensing


IP30



**REGULATORY & TYPE APPROVALS**


Regulatory CE/RED, UKCA, CB, UCRF, RoHS, REACH, CITC, ANRT, RCM, ETA-WPC, KC, FCC, IC, NOM


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **5**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUT300

- 9 W PSU

- Ethernet cable (1.5 m)

- QSG (Quick Start Guide)

- Packaging box

|ROUTER RUT300|9 W PSU|ETHERNET CABLE (1.5 M)|
|---|---|---|
|**QSG**|||



   - For all standard order codes standard package contents are the same, execpt for PSU.

## STANDARD ORDER CODES



DATASHEET // RUT300



**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUT300 000000



851762 8517.62.00 Standard package with EU PSU



RUT300 000100 851762 8517.62.00 Standard package with US PSU


RUT300 000200 851762 8517.62.00 Standard package with UK PSU


RUT300 000300 851762 8517.62.00 Standard package with AU PSU


For more information on all available packaging options – please contact us directly.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **6**


DATASHEET // RUT300


## RUT300 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUT300:



Device housing*:

Box:



100 x 30 x 85 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUT300 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUT300 and its components as seen from the right side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **7**


DATASHEET // RUT300


**FRONT VIEW**


The figure below depicts the measurements of RUT300 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUT300 and its components as seen from the back panel side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **8**


DATASHEET // RUT300


**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // RUT300


**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **10**


