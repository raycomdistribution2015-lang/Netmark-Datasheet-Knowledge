# TRB255

Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // TRB255


## HARDWARE

FRONT VIEW


BACK VIEW


|Input/output connector Ethernet port|Col2|ut/output onnector Ethern|net port|
|---|---|---|---|
|||||
|||||



**Power LED**


**Mobile network type**



**Input/output**



**Mobile signal strength**



**GNSS antenna** **Mobile antenna**

|Mobile signal strength indication LEDs Mobile network type LEDs|Mobile sign indicatio twork type Ds|Col3|Col4|nal strength on LEDs|
|---|---|---|---|---|
|<br> <br><br>**Reset**<br>**button**|||||
|<br> <br><br>**Reset**<br>**button**||<br> <br>**Reset**<br>**button**|||

**connector** **connector**


INPUT/OUTPUT 16 PIN CONNECTOR PINOUT


**D1, D2, D3**      - Configurable digital Input/Output pins.
Open collector output, max output 30 V, 300 mA or
Digital input where 0-6 V detected as logic low and
8-30 V – logic high.

**+**     - 9-30 VDC positive power pin
**CTS**     - RS232 clear data to send pin (output).
**RTS**     - RS232 request data to send pin (input).
**R+**     - RS485 receiver positive signal pin.
**D+**     - RS485 driver positive signal pin.

**-**          - Negative/ground power pin.
       - Ground pins for D1, D2, D3, A, RS232 and RS485.
**A**     - Analog input pin. Analog voltage range 0-30 V.
**TX**      - RS232 transmitted data (input).
**RX**      - RS232 received data (output).
**R-**      - RS485 receiver negative signal.
**D-**       - RS485 driver negative signal.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **2**


## FEATURES

**MOBILE**

Mobile module


SIM switch



DATASHEET // TRB255


LTE (Cat M1) / NB-IoT / EGPRS

2 SIM cards, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail,
SIM idle protection



Status Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, Bytes sent/received, connected band, IMSI, ICCID

SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
SMS
scheduled SMS, SMS autoreply, SMPP

USSD Supports sending and reading Unstructured Supplementary Service Data messages

Black/White list Operator black/white list

Multiple PDN Possibility to use different PDNs for multiple network access and services

Band management Band lock, Used band status display

APN Auto APN

Bridge Direct connection (bridge) between mobile ISP and device on LAN

Passthrough Router assigns its mobile WAN IP address to another device on LAN


**ETHERNET**

LAN 1 x LAN port, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX


**NETWORK**



Routing


Network protocols


VoIP passthrough support

Connection monitoring

Firewall



Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing

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


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **3**


DATASHEET // TRB255



**MODBUS TCP SLAVE**

ID range Respond to one ID in range [1;255] or any



Allow Remote Access


Custom registers


**MODBUS TCP MASTER**

Supported functions


Supported data formats



Allow access through WAN

MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS
TCP Slave functionality


01, 02, 03, 04, 05, 06, 15, 16

8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC)



Supported baud rates From 300 - 3000000


**MODBUS RTU MASTER (RS232)**



Supported functions


Supported data formats



01, 02, 03, 04, 05, 06, 15, 16

8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC), HEX, ASCII



Number of data bits From 7 to 8

Number of stop bits 1 or 2

Parity None, Even, Odd

Flow None, RTS/CTS, Xon/Xoff

Duplex Full duplex


**MODBUS RTU MASTER (RS485)**



Supported baud rates

Supported functions


Supported data formats



From 300 to 300000

01, 02, 03, 04, 05, 06, 15, 16

8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC), HEX, ASCII



Number of data bits 7 or 8

Number of stop bits 1 or 2

Parity None, Even, Odd

Flow None, Xon/Xoff

Duplex Half duplex


**DATA TO SERVER**

Protocol HTTP(S), MQTT, Azure MQTT, Kinesis


**MQTT GATEWAY**

MQTT Gateway Allows sending commands and receiving data from MODBUS Master through MQTT broker


**DNP3**

Supported modes TCP Master, DNP3 Outstation, RTU Master


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


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **4**


DATASHEET // TRB255



**SYSTEM CHARACTERISTICS**

CPU Qualcomm QCA9531, MIPS 24kc, 650 MHz



RAM

FLASH storage



64 MB, DDR2

16 MB, SPI Flash



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

**LOCATION TRACKING**



Busybox shell, Lua, C, C++

SDK package with build environment provided



GNSS GPS, GLONASS, BeiDou, Galileo and QZSS



Coordinates

NMEA



GNSS coordinates via WebUI, SMS, TAVL, RMS

NMEA 0183



NTRIP NTRIP protocol (Networked Transport of RTCM via Internet Protocol)



Server software

Geofencing

**SERIAL**



Supported server software TAVL, RMS

Configurable multiple geofence zones



RS232 Terminal block connector: TX, RX, RTS, CTS



RS485

Serial functions

**INPUT / OUTPUT**



Terminal block connector: D+, D-, R+, R- (2 or 4 wire interface)

Console, Serial over IP, Modem, MODBUS gateway, NTRIP Client



Input 3 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high. 1 x Analog input (0 - 30 V)



Output

Events



3 x Digital Output, Open collector output, max output 30 V, 300 mA

Email, RMS, SMS



I/O juggler Allows to set certain I/O conditions to initiate event

**POWER**

Connector 2 pins in 16-pin industrial terminal block



Input voltage range

Power consumption

**PHYSICAL INTERFACES**



9 – 30 VDC, reverse polarity protection, surge protection +/-1 kV 50 µs max

Idle: < 1.2 W, Max: < 5 W



Ethernet 1 x RJ45 port, 10/100 Mbps



I/O’s

Status LEDs



3 x Configurable I/O, 1 x Analog input in 16 pin terminal block

3 x connection status LEDs, 3 x connection strength LEDs, 1 x power LED, 1 x Eth port status LED



SIM 2 x SIM slots (Mini SIM – 2FF), 1.8 V/3 V, double stacked SIM tray



Power

Antennas



1 x 16-pin terminal block

1 x SMA connector for LTE, 1 x SMA connector for GNSS



RS232 4 pins in 16-pin terminal block (TX, RX, RTS, CTS)

RS485 4 pins in 16-pin terminal block (D+, D-, R+, R-)

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

83 x 25 x 74.2 mm

165 g

DIN rail (can be mounted on two sides), flat surface placement


-40 °C to 75 °C

10% to 90% non-condensing

IP30



**REGULATORY & TYPE APPROVALS**


Regulatory CE/RED, UKCA, EAC, UCRF, RoHS, REACH, CITC, ICASA, GITEKI, NTC, FCC, IC, NOM


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **5**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*


- Gateway TRB255

- 9 W PSU

- 1x Mobile antenna (swivel, SMA male)

- 1x GNSS antenna (adhesive, SMA male, 3 m cable)

- 16 pin terminal block

- 1x hex key

- Ethernet cable (1.5 m)

- QSG (Quick start guide)

- Packaging box



DATASHEET // TRB255






|GATEWAY TRB245|9 W PSU|1X LTE ANTENNA (SWIVEL, SMA<br>MALE)|
|---|---|---|
|**1X GNSS ANTENNA (ADHESIVE, SMA**<br>**MALE, 3 M CABLE)**|**16 PIN TERMINAL BLOCK**|**1X HEX KEY**|
|**ETHERNET CABLE (1.5 M)**|**QSG**||




   - For all standard order codes standard package contents are the same, execpt for PSU.


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **6**


DATASHEET // TRB255

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



TRB255 000000



851762 8517.62.00 Standard Package with EU PSU



For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



TRB255 0***** Global [1 ]


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.


1 - Regional availability - excluding Russia & Belarus.
2 - LTE-FDD B2 does not support Rx-diversity.



**4G (LTE-FDD):** B1, B2, B3, B4, B5, B8, B12, B13, B18,
B19, B20, B26, B28
**4G (LTE-TDD):** B39 (for Cat M1 only)
**2G:** 850, 900, 1800, 1900 MHz



Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **7**


DATASHEET // TRB255


## TRB255 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for TRB255:



Device housing*:

Box:



83 x 25 x 74.2 mm

173 x 71 x 148 mm



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of TRB255 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of TRB255 and its components as seen from the right side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **8**


DATASHEET // TRB255


**FRONT VIEW**


The figure below depicts the measurements of TRB255 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of TRB255 and its components as seen from the back panel side:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **9**


DATASHEET // TRB255


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


23 **, TELTONIKA NETWORKS. Specif** i **cations and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.** **1013**



i



i



**MOUNTING SPACE REQUIREMENTS**


i



The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


i



i



**Copyright © 202** 23 **, TELTONIKA NETWORKS. Specif** i **cations and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.**



i **13**


DATASHEET // TRB255


**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2023, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **11**


