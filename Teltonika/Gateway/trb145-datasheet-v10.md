# TRB145

Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


BACK VIEW


POWER SOCKET PINOUT


DB9 CONNECTOR PINOUT


1. Driver negative signal (D-).
2. Receiver negative signal (R-).
3. Ground (GND).
4. Driver positive (D+).
5. Receiver positive signal (R+).
6. Power input 9-30 VDC (Vin).



**Power socket**


**Power LED**



**RS485 interface**


**Mobile network**
**type LEDs**



**Mobile antenna** **Mobile signal strength**
**connector** **indication LEDs**



**Power / Red wire**


**I/O / Green wire**



**Ground / Black wire**


**I/O / White wire**



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


## FEATURES

**MOBILE**


Mobile module


Status


SMS/Call



DATASHEET // TRB145


4G (LTE) – Cat 1 up to 10 Mbps, 3G – Up to 42 Mbps, 2G – Up to 236.8 kbps


Signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP Bytes sent/received, connected band, IMSI, ICCID.


SMS status, SMS configuration, send/read SMS via HTTP POST/GET, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS,
scheduled SMS, SMS autoreply, Call utilities



USSD Supports sending and reading Unstructured Supplementary Service Data messages


Black/White list Operator black/white list

Band management Band lock, Used band status display


APN Auto APN


Bridge Direct connection (bridge) between mobile ISP and device on LAN


Passthrough Gateway assigns its mobile WAN IP address to another device on LAN

Multiple PDN Possibility to use different PDNs for multiple network access and services


**NETWORK**



Routing


Network protocols


Connection monitoring


Firewall



Static routing


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SMTP, SSL v3, TLS, PPP, SSH, DHCP, SNMP, MQTT


Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection


Port forwards, traffic rules, custom rules



DHCP Static and dynamic IP allocation



QoS / Smart Queue
Management (SQM) (planned)


DDNS



Traffic priority queuing by source/destination, service, protocol or port


Supported >25 service providers, others can be configured manually



SSHFS Possibility to mount remote file system via SSH protocol


**SECURITY**



Authentication


Firewall


Attack prevention



Pre-shared key, digital certificates, X.509 certificates


Pre-configured firewall rules can be enabled via the WebUI, unlimited firewall configuration via CLI; NAT; NAT-T


DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (
SYN-FIN, SYN-RST, X-mas, NULL flags, FIN scan attacks)



Mobile quota control Set up custom data limits for SIM card


WEB filter Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


**VPN**



OpenVPN



Multiple clients and a server can run simultaneously, 12 encryption methods



DES-CBC, RC2-CBC, DES-EDE-CBC, DES-EDE3-CBC, DESX-CBC, BF-CBC, RC2-40-CBC, CAST5-CBC, RC2-64-CBC, AES-128-CBC,
OpenVPN Encryption
AES-192-CBC, AES-256-CBC



IPsec


GRE



IKEv1, IKEv2, supports up to 5 x VPN IPsec tunnels (instances), with 5 encryption methods (DES, 3DES, AES128, AES192, AES256)


GRE tunnel



PPTP, L2TP Client/Server services can run simultaneously, L2TPv3 support


ZeroTier ZeroTier VPN


WireGuard WireGuard VPN client and server support


**SERIAL COMMUNICATION MODES**



Modes


**MODBUS TCP SLAVE**



Console, OverIP, Modem (Full or Partial control), MODBUS RTU master, MODBUS gateway, NTRIP client (planned)



ID filtering Respond to one ID in range [1;255] or any



Allow remote access


Custom registers



Allow access through WAN


MODBUS TCP custom register block, which allows to read/write to a file inside the router, and can be used to extend MODBUS
TCP slave functionality



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


**MODBUS TCP MASTER**


Supported functions


Supported data formats


**MODBUS RTU MASTER**


Supported baud rates



DATASHEET // TRB145


01, 02, 03, 04, 05, 06, 15, 16


8 bit: INT, UINT; 16 bit: INT, UINT (MSB or LSB first); 32 bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC), HEX, ASCII


From 300 to 115200



Supported functions 01, 02, 03, 04, 05, 06, 15, 16



Supported data formats


Number of data bits



8 bit: INT, UINT; 16 bit: INT, UINT (MSB or LSB first); 32 bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC), HEX, ASCII


From 5 to 8



Number of stop bits 1 or 2


Parity None, Even, Odd


Flow control None, Xon/Xoff


**DATA TO SERVER**

Protocols HTTP(S), MQTT, Azure MQTT, Kinesis


**MQTT GATEWAY**

Gateway Allows sending commands and receiving data from MODBUS Master trough MQTT broker


**MONITORING & MANAGEMENT**



WEB UI



HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, system log, kernel log



FOTA Firmware update from sever, automatic notification



SSH


SMS


Call


TR-069


MQTT


JSON-RPC


MODBUS


RMS


**IoT PLATFORMS**



SSH (v1, v2)


SMS status, SMS configuration, send/read SMS via HTTP POST/GET


Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher


Management API over HTTP/HTTPS


MODBUS TCP status/control


Teltonika Remote Management System (RMS)



Cloud of Things Allows monitoring of: Device data, Mobile data, Network info, Availability



ThingWorx


Cumulocity



Allows monitoring of: WAN Type, WAN IP Mobile Operator Name, Mobile Signal Strength, Mobile Network Type


Allows monitoring of: Device Model, Revision and Serial Number, Mobile Cell ID, ICCID, IMEI, Connection Type, Operator, Signal
Strength, WAN Type and IP



Can send device IP, Number of bytes send/received/ 3G connection state, Network link state, IMEI, ICCID, Model, Manufacturer,
Azure IoT Hub Serial, Revision, IMSI, Sim State, PIN state, GSM signal, WCDMA RSCP WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID,
Operator, Operator number, Connection type, Temperature, PIN count to Azure IoT Hub server


**SYSTEM CHARACTERISTICS**


CPU ARM Cortex-A7 1.2 GHz CPU



RAM


FLASH storage



128 MB (50 MB available for userspace)


512 MB (200 MB available for userspace)



**FIRMWARE / CONFIGURATION**


WEB UI Update FW from file, check FW on server, configuration profiles, configuration backup



FOTA


RMS



Update FW/configuration from server


Update FW/configuration for multiple devices



Keep settings Update FW without losing current configuration


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // TRB145


**FIRMWARE CUSTOMIZATION**


Operating system RutOS (OpenWrt based Linux OS)


Supported languages Busybox shell, Lua, C, C++


Development tools SDK package with build environment provided


**INPUT/OUTPUT**


2 x Configurable Inputs/Outputs. Digital input 0 - 5 V detected as logic low, 8 - 30 V detected as logic high. Open collector
Configurable I/O
output, max output 30 V, 300 mA (not available in TRB145*2****)


Output control HTTP POST/GET, Schedule

Events SMS, EMAIL


I/O juggler Allows to set certain I/O conditions to initiate event


**POWER**


Connector 4 pin industrial DC power socket


Input voltage range 9 – 30 VDC (4 pin industrial socket), reverse polarity protection, surge protection >33 VDC 10us max


Power consumption < 5 W


**PHYSICAL INTERFACES (PORTS, LEDS, ANNTENAS, BUTTONS, SIM)**


RS485 1 x 6 pin terminal block for 2-wire or 4 wire interface


i



i



I/Os


USB


i



i



2 x Configurable I/O pins on 4 pin power connector (I/O not available in TRB145*2****)


1 x Virtual network interface via micro USB


i



Status LEDs 3 x connection type status LEDs, 5 x connection strength LEDs, 1x Power LED


i



SIM


Power


i



1 x SIM slot (Mini SIM – 2FF), 1.8 V/3 V


4 pin power connector with 2 x configurable Digital Inputs/Outputs (I/O not available in TRB145*2****)


i



Anntena 1 x SMA for LTE

Reset Reboot/User default reset/Factory reset button


**PHYSICAL SPECIFICATION**


i



Casing material


Dimensions (W x H x D)


Weight


Mounting options


**OPERATING ENVIRONMENT**


Operating temperature


Operating humidity


i



Aluminum housing


74.5 x 25 x 64.4 mm


130 g


Bottom and sideways DIN rail, Flat surface


-40 °C to 75 °C


10 % to 90 % non-condensing


IP30


i



Ingress Protection Rating


Regulatory


**EMI**


Standards


ESD


RS


EFT


Surge protection


CS


DIP


**RF**


Standards


**SAFETY**


Standards


**Copyright © 202** 21 i



**REGULATORY & TYPE APPROVALS**


i



Regulatory


i



CE/RED, EAC, RoHS, WEEE


i



**EMI**


i



Standards Draft ETSI EN 301 489-1 V2.2.0, Draft EN 301 489-19 V2.1.0, Draft ETSI EN 301 489-52 V1.1.0


i



ESD


i



EN 61000-4-2:2009


EN 61000-4-3:2006 + A1:2008 + A2:2010


i



RS


i



EFT EN 61000-4-4:2012


i



Surge protection


i



EN 61000-4-5:2014


EN 61000-4-6:2014


i



CS


i



DIP EN 61000-4-11:2004


i



**RF**


i



Standards EN 300 511 V12.5.1, ETSI EN 301 908-1 V11.1.1, ETSI EN 301 908-2 V11.1.2, ETSI EN 301 908-13 V11.1.2


i



**SAFETY**


i



IEC 62368-1:2014(Second Edition), EN 62368-1:2014+A11:2017
Standards EN 50385:2017
EN 62232:2017


i



Copyright © 2020, Teltonika. Specifications and information given in this document are subject to change by Teltonika without prior notice.

i **5**



**Copyright © 202** 21 **, TELTONIKA NETWORKS. Specif** i **cations and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.**


DATASHEET // TRB145

## HARDWARE INSTALLATION


1. Unscrew two back panel hex bolts and remove the back panel.
2. Insert your SIM card into the SIM socket.
3. Attach the panel and tighten the hex bolts.
4. Attach the mobile antenna (max torque 0.4 N·m / 3.5 lbf·in) and connect the USB cable.


LOGIN TO DEVICE


1. Power on the device and connect the USB cable to your computer.
2. Allow the gateway to boot up. This might take up to 30 seconds.
3. Your computer's OS should detect the USB device and install the driver.
4. To enter the gateway's Web interface (WebUI), type **http://192.168.2.1** into the URL field of your Internet browser.
5. Use login information shown in image A when prompted for authentication.
6. After logging in pay attention to the Signal Strength indication displayed in the Mobile widget (image B). To maximize the cellular performance try adjusting the antennas or changing the location of your device to achieve the best signal conditions.











TECHNICAL INFORMATION





|Radio specifications|Col2|
|---|---|
|RF technologies|2G, 3G, 4G|
|Max RF power|33 dBm@GSM, 24 dBm@WCDMA, 23 dBm@LTE|
|**Bundled accessories speciﬁcations***|**Bundled accessories speciﬁcations***|
|Power adapter|Input: 0.4A@100-240VAC, Output: 9VDC, 0.5A, 4-pin plug|
|Mobile antenna|698~960/1710~2690 MHz, 50 Ω, VSWR<2, gain** 2 dBi, omnidirectional, SMA male connector|


*Order code dependent.
**Higher gain antenna can be connected to compensate for cable attenuation when a cable is used. The user is responsible for the compliance with the legal regulations.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*


- TRB145

- 4.5 W PSU

- 1 x LTE antenna (magnetic mount, SMA male, 3 m cable)

- Micro-USB cable (0.8 m)

- 1 x hex key

- RS485 connector

- QSG (Quick Start Guide)

- RMS Flyer

- Packaging box





|TRB145|4.5 W PSU|1 X LTE ANTENNA (MAGNETIC<br>MOUNT, SMA MALE, 3 M CABLE)|
|---|---|---|
|**MICRO-USB CABLE (0.8 M)**|**1 X HEX KEY**|**RS485 CONNECTOR**|



   - For all standard order codes standard package contents are the same, execpt for PSU.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


DATASHEET // TRB145

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



TRB1450 03000



851762 8517.62.00 Standard Package



For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



TRB145 0*****



Europe, the Middle East, Africa, Korea,
Thailand, India



South America, Australia, New Zealand,
TRB145 1*****
Taiwan


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.

- - Versions for other regions are under development.



4G (LTE-FDD): B1, B3, B7, B8, B20, B28A
3G: B1, B8
2G: B3, B8


4G (LTE-FDD): B1, B2, B3, B4, B5, B7, B8, B28
4G (LTE-TDD): B40
3G: B1, B2, B5, B8
2G: B2, B3, B5, B8



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // TRB145


## MOUNTING OPTIONS

DIN RAIL KIT



Parameter


Mounting standard


Material


Weight


Screws included


Dimensions


RoHS Compliant


**DIN RAIL KIT**


DIN Rail adapter



Value


35mm DIN Rail


Low carbon steel


57g


Philips Pan Head screw #6-32×3/16, 2pcs


82 mm x 46 mm x 20 mm


V



Philips Pan Head screw #6-32×3/16, 2pcs for RUT2xx/RUT9xx


**ORDER CODE** **HS CODE** **HTS CODE**



PR5MEC00


For more information on all available packaging options – please contact us directly.


COMPACT DIN RAIL KIT



73269098 7326.90.98



Parameter


Mounting standard


Material


Weight


Screws included


Dimensions


RoHS Compliant


**DIN RAIL KIT**



Value


35mm DIN Rail


ABS + PC plastic


6.5 g


Philips Pan Head screw #6-32×3/16, 2pcs


70 mm x 25 mm x 14,5 mm


V



Compact plastic DIN Rail adapter (70x25x14,5mm)


Philips Pan Head screw #6-32×3/16, 2pcs


**ORDER CODE** **HS CODE** **HTS CODE**



PR5MEC11


For more information on all available packaging options – please contact us directly.


SURFACE MOUNTING KIT



73269098 7326.90.98



Parameter


Mounting standard


Material


Weight


Screws included


Dimensions


RoHS Compliant


**DIN RAIL KIT**


Surface mounting kit



Value


Flat surface mount


ABS + PC plastic


2x5 g


Philips Pan Head screw #6-32×3/16, 2pcs


25 mm x 48 mm x 7.5 mm


V



Philips Pan Head screw #6-32×3/16, 2pcs


**ORDER CODE** **HS CODE** **HTS CODE**



PR5MEC12


For more information on all available packaging options – please contact us directly.



73269098 7326.90.98



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // TRB145


## TRB145 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for TRB145



Device housing*:

Box:



74.5 x 25 x 64.4

173 x 71 x 148



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of TRB145 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of TRB145 and its components as seen from the right side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // TRB145



**FRONT VIEW**


The figure below depicts the measurements of TRB145 and its components as seen from the front:


**REAR VIEW**


The figure below depicts the measurements of TRB145 and its components as seen from the back:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // TRB145



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


DATASHEET // TRB145



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**13**


