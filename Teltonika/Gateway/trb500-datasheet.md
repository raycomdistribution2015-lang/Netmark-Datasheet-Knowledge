Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // TRB500


## HARDWARE

FRONT VIEW


BACK VIEW


**4-pin power socket**


**Power LED**


POWER SOCKET PINOUT


|Col1|Col2|Col3|
|---|---|---|
|**MOBILE**<br>**RESET**|**OBILE**|**OBILE**|
||||





**Reset button** **Grounding screw**


**Mobile antenna**
**connectors**


**Mobile network**
**type LED**


|Mobile signal strength<br>indication LEDs<br>3G 4G 5G<br>PWR USB LAN|Mobile signal strength<br>indication LEDs|Col3|Col4|Col5|
|---|---|---|---|---|
|**PWR**<br>**3G 4G 5G**<br>**USB**<br>**LAN**<br>**Mobile signal strength**<br>**indication LEDs**|**Mobile signal strength**<br>**indication LEDs**||||



**SIM holder** **USB port**



**LAN Port**


**Ground / Black wire**


**Output / White wire**



**Power / Red wire**


**Input / Green wire**



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


f


fi


i


fi


i i

i i i i


i


## FEATURES

**MOBILE**


Mobile module


Status


SMS


USSD

Black/White list

Multiple PDN f

Band management

APN

Bridge


fi


i


fi


i i

i i i i


i



DATASHEET // TRB500


5G Sub-6Ghz SA/NSA 2.1/3.3Gbps DL (4x4 MIMO), 900/600 Mbps UL (2x2); 4G (LTE) – LTE Cat 20 2.0Gbps DL, 200Mbps UL;
3G – 42 Mbps DL, 5.76Mbps UL

Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID

SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, SMPP

Supports sending and reading Unstructured Supplementary Service Data messages

Operator black/white list

Possibility to use different PDNs for multiple network access and services

Band lock, Used band status display

Auto APN

Direct connection (bridge) between mobile ISP and device on LAN


fi


i


fi


i i

i i i i


i



f


fi


i


fi


i i

i i i i


i



f


Passthrough Router assigns its mobile WAN IP address to another device on LAN


**ETHERNET**


fi


i


fi


i i

i i i i


i



f


LAN


**NETWORK**


fi


i


fi


i i

i i i i


i



f


1 x LAN port, 10/100/1000 Mbps, supports auto MDI/MDIX crossover


fi


i


fi


i i

i i i i


i



f


Routing Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing


fi


i


fi


i i

i i i i


i



f


Network protocols


VoIP passthrough support

Connection monitoring

fi


i


fi


i i

i i i i


i



f


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP,
Telnet, SMPP, SMNP, MQTT, Wake On Lan (WOL)

H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets

Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection

fi


i


fi


i i

i i i i


i



f


Firewall Port forward, traffic rules, custom rules

DHCP Static and dynamic IP allocation, DHCP Relay

DDNS Supported >25 service providers, others can be configured manually


fi


i i

i i i i


i



f


fi


i

Network backup

Load balancing fi


i i

i i i i


i



f


fi


i

Mobile, VRRP, Wired options, each of which can be used as an automatic Failover

Balance Internet traffic over multiple WAN connections


i i

i i i i


i



f


fi


i


fi

SSHFS Possibility to mount remote file system via SSH protocol


**SECURITY**

i i

i i i i


i



f


fi


i


fi


Authentication i i

i i i i


i



f


fi


i


fi


Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block

i i i i


i



f


fi


i


fi


i i

Firewall Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T


i



f


fi


i


fi


i i

i i i i


Attack prevention


i



f


fi


i


fi


i i

i i i i

DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
SYN-RST, X-mas, NULL flags, FIN scan attacks)


i



f


fi


i


fi


i i

i i i i


VLAN Port and tag-based VLAN separation


i



f


fi


i


fi


i i

i i i i


Mobile quota control

WEB filter



f


fi


i


fi


i i

i i i i


Mobile data limit, customizable period, start time, warning limit, phone number

i Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only



f


fi


i


fi


i i

i i i i


i

Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


**VPN**



f


fi


i


fi


i i

i i i i


i


OpenVPN


OpenVPN Encryption


IPsec


GRE



f


fi


i


fi


i i

i i i i


i


Multiple clients and a server can run simultaneously, 27 encryption methods

DES-CBC 64, RC2-CBC 128, DES-EDE-CBC 128, DES-EDE3-CBC 192, DESX-CBC 192,
BF-CBC 128, RC2-40-CBC 40, CAST5-CBC 128, RC2-64-CBC 64, AES-128-CBC 128, AES-128-CFB 128, AES-128-CFB1 128,
AES-128-CFB8 128, AES-128-OFB 128, AES-128-GCM 128, AES-192-CFB 192, AES-192-CFB1 192, AES-192-CFB8 192, AES-192-OFB
192, AES-192-CBC 192, AES-192-GCM 192, AES-256-GCM 256, AES-256-CFB 256, AES-256-CFB1 256, AES-256-CFB8 256,
AES-256-OFB 256, AES-256-CBC 256


IKEv1, IKEv2, with 14 encryption methods for IPsec (3DES, DES, AES128, AES192, AES256, AES128GCM8, AES192GCM8,
AES256GCM8, AES128GCM12, AES192GCM12, AES256GCM12, AES128GCM16, AES192GCM16, AES256GCM16)

GRE tunnel, GRE tunnel over IPsec support



f


fi


i


fi


i i

i i i i


i


PPTP, L2TP Client/Server instances can run simultaneously, L2TPv3, L2TP over IPsec support

Stunnel Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code



f


fi


i


fi


i i

i i i i


i


DMVPN

SSTP



f


fi


i


fi


i i

i i i i


i


Method of building scalable IPsec VPNs

SSTP client instance support



f


fi


i


fi


i i

i i i i


i


ZeroTier ZeroTier VPN client support

WireGuard WireGuard VPN client and server support

Tinc Tinc offers encryption, authentication and compression in it's tunnels. Client and server support.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



f


fi


i


fi


i i

i i i i


i


**3**


DATASHEET // TRB500


**MODBUS TCP SLAVE**

ID filtering Respond to one ID in range [1;255] or any

Allow remote access Allow access through WAN

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


**MQTT GATEWAY**

MQTT Gateway Allows sending commands and receiving data from MODBUS Master through MQTT broker


**DNP3**

Supported modes TCP Master, DNP3 Outstation


**MONITORING & MANAGEMENT**

i

i


i

f f


i i i i


i


i



i

i


i

f f


i i i i


i


i



WEB UI i

FOTA i

SSH

SMS i

f f


i i i i


i


i



i

i


i

f f


i i i i


i


i



HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log

Firmware update from server, automatic notification

SSH (v1, v2)

SMS status, SMS configuration, send/read SMS via HTTP POST/GET

f f


i i i i


i


i



i

i


i

Call Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer


i i i i


i


i



i

i


i

f f

TR-069

MQTT


i i i i


i


i



i

i


i

f f

OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem

MQTT Broker, MQTT publisher


i i i i


i


i



i

i


i

f f


SNMP SNMP (v1, v2, v3), SNMP Trap

JSON-RPC Management API over HTTP/HTTPS

MODBUS MODBUS TCP status/control

RMS Teltonika Remote Management System (RMS)


**IoT PLATFORMS**


i i i i


i


i



i

i


i

f f


Clouds of things

ThingWorx


Cumulocity


Azure IoT Hub


**SYSTEM CHARACTERISTICS**

CPU

RAM


i i i i


i


i



i

i


i

f f


Allows monitoring of: Device data, Mobile data, Network info, Availability

Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type

Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP, Mobile Cell ID, ICCID, IMEI, Connection
Type, Operator, Signal Strength

Can send device IP, Number of bytes send/received, Temperature, PIN count to Azure IoT Hub server, Mobile connection state,
Network link state, IMEI, ICCID, Model, Manufacturer, Serial, Revision, IMSI, SIM State, PIN state, GSM signal, WCDMA RSCP,
WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID, Operator, Operator number, Connection type


Single core ARM Cortex A7, 1.5 GHz

256 MB (128 MB available for userspace)


i i i i


i


i



i

i


i

f f


FLASH storage 512 MB (200 MB available for userspace)


**FIRMWARE / CONFIGURATION**

i i i i


i


i



i

i


i

f f


WEB UI i i i i

FOTA

i


i



i

i


i

f f


Update FW from file, check FW on server, configuration profiles, configuration backup

Update FW

i


i



i

i


i

f f


i i i i


RMS Update FW/configuration for multiple devices at once

Keep settings Update FW without losing current configuration


**FIRMWARE CUSTOMIZATION**


i



i

i


i

f f


i i i i


i


Operating system

Supported languages


i



i

i


i

f f


i i i i


i


RutOS (OpenWrt based Linux OS)

Busybox shell, Lua, C, C++, and Python, Java in Package manager


i



i

i


i

f f


i i i i


i


Development tools SDK package with build environment provided


**INPUT/OUTPUT**

Configurable I/O 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high



i

i


i

f f


i i i i


i


i

Output control

Events



i

i


i

f f


i i i i


i


i

1 x Digital Output, Open collector output, max output 30 V, 300 mA

Email, RMS, SMS



i

i


i

f f


i i i i


i


i


I/O juggler Allows to set certain I/O conditions to initiate event


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



i

i


i

f f


i i i i


i


i


**4**


DATASHEET // TRB500


i



i



**POWER**

Connector

Input voltage range


i



i



4-pin industrial DC power socket

9 – 30 VDC, reverse polarity protection, surge protection +/-1 kV 50 µs max


i



Power consumption Idle: < 3 W, Max < 6 W


**PHYSICAL INTERFACES (PORTS, LEDS, ANTENNAS, BUTTONS, SIM)**

Ethernet 1 x RJ45 port, 10/100/1000 Mbps

i



I/O’s i

Status LEDs

SIM

Power

Antennas

USB



2 x Configurable I/O pins on 4-pin power connector

3 x connection type status LEDs, 3 x connection strength LEDs, 2 x LAN status LEDs, 1 x Power LED

1 x SIM slot (Mini SIM – 2FF), 1.8 V/3 V

1 x 4-pin power connector

4 x SMA for Mobile

1 x Virtual network interface via micro USB



i


Reset Reboot/User default reset/Factory reset button


**PHYSICAL SPECIFICATION**

Casing material Aluminum housing



i


Dimensions (W x H x D)

Weight



i


100 x 30 x 93.4 mm

241g



i


Mounting options DIN rail, Flat surface


**OPERATING ENVIRONMENT**

Operating temperature -40 °C to 75 °C



i


Operating humidity

Ingress Protection Rating



i


10 % to 90 % non-condensing

IP30



i


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



i


**5**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*


- TRB500 Gateway

- 9 W PSU

- 4x Mobile antennas (swivel, SMA male)

- Micro-USB cable (0.8 m)

- Ethernet cable

- SIM Adapter kit

- QSG (Quick Start Guide)

- Packaging box



DATASHEET // TRB500



|TRB500 GATEWAY|9 W PSU|4 X MOBILE ANTENNAS (SWIVEL,<br>SMA MALE)|
|---|---|---|
|**MICRO-USB CABLE (0.8 M)**|**ETHERNET CABLE**|**SIM ADAPTER KIT**|
|**QSG**|||



   - For all standard order codes standard package contents are the same, except for PSU.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // TRB500


## STANDARD ORDER CODES

**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



TRB500 000000



851762 8517.62.00 Standard Package with EU PSU



For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



TRB500 0*****



Europe [1], the Middle East, Africa, Oceania,
Brazil



TRB500 **000601** Thailand


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.

1 - Regional availability - excluding Russia & Belarus.




**• 5G NR NSA:** n1, n3, n5, n7, n8, n20, n28, n38, n40, n41, n77

**• 5G NR SA:** n1, n3, n5, n7, n8, n20, n28, n38, n40, n41, n77, n78

**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B20, B28, B32

**• 4G (LTE-TDD):** B38, B40, B41, B42, B43

**• 3G:** B1, B5, B8


**• 5G NR NSA:** n7, n40, n77, n78

**• 5G NR SA:** n1, n3, n5, n7, n8, n20, n38, n40, n41, n77, n78

**• 4G (LTE-FDD):** B1, B3, B5, B7, B8, B20, B32

**• 4G (LTE-TDD):** B38, B40, B41, B42, B43

**• 3G:** B1, B8



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // TRB500


## TRB500 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for TRB500:



Device housing*:

Box:



100 x 30 x 93.4 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of TRB500 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of TRB500 and its components as seen from the right side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // TRB500



**FRONT VIEW**


The figure below depicts the measurements of TRB500 and its components as seen from the front panel side:

|LAN|Col2|Col3|Col4|Col5|Col6|Col7|Col8|
|---|---|---|---|---|---|---|---|
|**LAN**||||||||
|**LAN**||**LAN**|**LAN**|**LAN**|**LAN**|**LAN**|**LAN**|
|**LAN**||||||||
|**LAN**||||||||
|||||||||



**REAR VIEW**


The figure below depicts the measurements of TRB500 and its components as seen from the back panel side:





Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // TRB500



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // TRB500



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


