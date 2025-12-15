# RUTX14

Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


## HARDWARE

FRONT VIEW


**WAN type LEDs**


**SIM needle**


**Power socket**


BACK VIEW


POWER SOCKET PINOUT



**Mobile network**
**type LEDs**



**Mobile signal strength**
**indication LEDs**



DATASHEET // RUTX14


**SIM holders**



**Power** **Reset** **WiFi Band** **LAN Ethernet** **WAN Ethernet**
**LED** **button** **LEDs** **ports** **port**


**Mobile MAIN antenna** **Mobile AUX antenna**
**connector** **connector**

|e AUX antenna<br>onnector|GNSS antenna<br>connector|Col3|Mobile AUX ante<br>connector|Col5|
|---|---|---|---|---|
||||||
||||||



**Grounding** **WiFi antenna** **Bluetooth antenna** **USB port**
**screw** **connectors** **connector**



**Power / Red wire**


**Input / Green wire**



**Ground / Black wire**


**Output / White wire**



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


## FEATURES

**MOBILE**


Mobile module


SIM/mobile module switch


Status


SMS


Black/White list (planned)


Multiple PDN


Band management


APN



DATASHEET // RUTX14


4G (LTE) – Cat 12 up to 600 Mbps, 3G – up to 42 Mbps


2 SIM cards, auto switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail


Signal strength, SINR, RSRP, RSRQ, Bytes sent/received, connected band, carrier aggregation, IMSI, ICCID,


SMS status, SMS configuration, send/read SMS via HTTP POST/GET, Email to SMS, SMS to Email, SMS to HTTP, SMS to SMS, SMS
auto replay


Operator black/white list


Possibility to use different PDNs for multiple network access and services


Band lock, Used band status display


Auto APN



Bridge mode Direct connection (bridge) between mobile ISP and device on LAN


**WIRELESS**


802.11b/g/n/ac Wave 2 (WiFi 5) with data transmission rates up to 867 Mbps (Dual Band, MU-MIMO), 802.11r fast transition,
Wireless mode
Access Point (AP), Station (STA)



WiFi security


ESSID



WPA3-EAP, WPA3-SAE, WPA2-Enterprise-PEAP, WPA2-PSK, WEP; AES-CCMP, TKIP, Auto Cipher modes, client separation


ESSID stealth mode



WiFi users up to 150 simultaneous connections


Wireless Hotspot Captive portal (Hotspot), internal/external Radius server, built in customizable landing page


**ETHERNET**


1 x WAN port (can be configured as LAN) 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards,
WAN
supports auto MDI/MDIX crossover



LAN


**BLUETOOTH**



4 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX



Bluetooth 4.0 Bluetooth low energy (LE) for short range communication


**NETWORK**



Routing


Network protocols


VoIP passthrough support


Connection monitoring



Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP)


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, FTP, SMTP, SSL v3, TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP, Telnet
client, SNMP, MQTT, Wake on LAN (WOL), DLNA


H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets


Ping Reboot, Wget reboot, Periodic Reboot, LCP and ICMP for link inspection



Firewall Port forwards, traffic rules, custom rules



DHCP


QoS / Smart Queue
Management (SQM)


DDNS


Network backup



Static and dynamic IP allocation, DHCP Relay, Relayd


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


VRRP, Mobile, Wired and WiFi WAN options, each of which can be used as an automatic Failover



Load balancing Balance Internet traffic over multiple WAN connections


SSHFS Possibility to mount remote file system via SSH protocol


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


**SECURITY**


Authentication


Firewall



DATASHEET // RUTX14


Pre-shared key, digital certificates, X.509 certificates


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



Port and tag based VLAN separation


Custom data limits for both SIM cards


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Flexible access control of TCP, UDP, ICMP packets, MAC address filter


Multiple clients and a server can run simultaneously, 12 encryption methods



DES-CBC, RC2-CBC, DES-EDE-CBC, DES-EDE3-CBC, DESX-CBC, BF-CBC, RC2-40-CBC, CAST5-CBC, RC2-64-CBC, AES-128-CBC,
OpenVPN Encryption
AES-192-CBC, AES-256-CBC



IPsec


GRE


PPTP, L2TP


Stunnel


DMVPN


SSTP

ZeroTier


WireGuard


**MODBUS TCP SLAVE**



IKEv1, IKEv2, with 5 encryption methods for IPsec (DES, 3DES, AES128, AES192, AES256)


GRE tunnel


Client/Server instances can run simultaneously, L2TPv3 support


Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code


Method of building scalable IPsec VPNs


SSTP client instance support

ZeroTier VPN client support


WireGuard VPN client and server support



ID filtering Respond to one ID in range [1;255] or any



Allow remote access


Custom registers


**MODBUS TCP MASTER**


Supported functions



Allow access through WAN


Modbus TCP custom register block, which allows to read/write to a file inside the router, and can be used to extend Modbus
TCP slave functionality


01, 02, 03, 04, 05, 06, 15, 16



8 bit: INT, UINT; 16 bit: INT, UINT (MSB or LSB first); 32 bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
Supported data formats
BADC), HEX, ASCII


**MQTT GATEWAY**



Gateway


**DATA TO SERVER**


Protocols


**IoT PLATFORMS**


Clouds of things


ThingWorx



Allows sending commands and receiving data from Modbus Master trough MQTT broker


HTTP(S), MQTT, Azure MQTT, Kinesis


Allows monitoring of: Device data, Mobile data, Network info, Availability


Allows monitoring of: WAN Type, WAN IP Mobile Operator Name, Mobile Signal Strength, Mobile Network Type



Allows monitoring of: Device Model, Revision and Serial Number, Mobile Cell ID, ICCID, IMEI, Connection Type, Operator, Signal
Cumulocity
Strength, WAN Type and IP


Can send device IP, Number of bytes send/received/ 3G connection state, Network link state, IMEI, ICCID, Model, Manufacturer,
Azure IoT Hub Serial, Revision, IMSI, Sim State, PIN state, GSM signal, WCDMA RSCP, WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID,
Operator, Operator number, Connection type, Temperature, PIN count to Azure IoT Hub server


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUTX14



**MONITORING & MANAGEMENT**



WEB UI



HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log



FOTA Firmware update from server, automatic notification



SSH


SMS


CALL


TR-069


MQTT


SNMP



SSH (v1, v2)


SMS status, SMS configuration, send/read SMS via HTTP POST/GET


Reboot, Status, Mobile data on/off, Output on/off


OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT Broker, MQTT publisher


SNMP (v1, v2, v3), SNMP trap



JSON-RPC Management API over HTTP/HTTPS



MODBUS


RMS


**SYSTEM CHARACTERISTICS**



MODBUS TCP status/control


Teltonika Remote Management System (RMS)



CPU Quad-core ARM Cortex A7, 717 MHz



RAM


FLASH storage



256 MB, DDR3


256 MB, SPI Flash



**FIRMWARE / CONFIGURATION**



WEB UI



Update FW from file, check FW on server, configuration profiles, configuration backup



FOTA Update FW/configuration from server



RMS


Keep settings


**FIRMWARE CUSTOMIZATION**



Update FW/configuration for multiple devices at once


Update FW without losing current configuration



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



Server software Supported server software: TAVL, RMS


Geofencing Configurable multiple geofence zones


**USB**


Data rate USB 2.0



Applications


External devices



Samba share, USB-to-serial


Possibility to connect external HDD, flash drive, additional modem, printer



Storage formats FAT, FAT32, NTFS


**INPUT/OUTPUT**


Input 1 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high



Output


Events



1 x Digital Output, Open collector output, max output 30 V, 300 mA


SMS, Email, RMS



I/O juggler Allows to set certain I/O conditions to initiate event


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


DATASHEET // RUTX14



**POWER**


Connector 4 pin industrial DC power socket



Input voltage range


PoE (passive)



9 – 50 VDC, reverse polarity protection, voltage surge/transient protection


Passive PoE. Possibility to power up through LAN1 port, not compatible with IEEE802.3af, 802.3at and 802.3bt standards



Power consumption Idle: <4 W, Max: <22 W


**PHYSICAL INTERFACES (PORTS, LEDS, ANTENNAS, BUTTONS, SIM)**


Ethernet 5 x RJ45 ports, 10/100/1000 Mbps



I/Os


Status LEDs



1 x Digital Input, 1 x Digital Output on 4 pin power connector


2 x connection status LEDs, 3 x connection strength LEDs, 10 x Ethernet port status LEDs, 4 x WAN status LEDs, 1x Power LED,
2 x 2.4G and 5G WiFi LEDs



SIM 2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders



Power


Antennas



1 x 4 pin DC connector


4 x SMA for LTE, 2 x RP-SMA for WiFi, 1 x RP-SMA for Bluetooth, 1 x SMA for GNNS



USB 1 x USB A port for external devices


Reset Reboot/User default reset/Factory reset button


Other 1 x Grounding screw


**PHYSICAL SPECIFICATION**



Casing material


Dimensions (W x H x D)


Weight


Mounting options


**OPERATING ENVIRONMENT**


Operating temperature


Operating humidity



Full aluminium housing


132 x 44 x 95 mm


515 g


DIN rail (can be mounted on two sides), flat surface placement


-40 C to 75 C


10 % to 90 % non-condensing



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // RUTX14

## HARDWARE INSTALLATION


1. Pull out the SIM needle from the front panel of the router and push the SIM holder button with the SIM needle.
2. Pull out the SIM holder.
3. Insert your SIM card into the SIM holder.
4. Slide the SIM holder back into the router.
5. Attach all antennas.
6. Connect the power adapter to the socket on the front of the device. Then plug the other end of the power adapter into a power outlet.
7. Connect to the device wirelessly using SSID and password provided on the device information label or use an Ethernet cable connected to
LAN port.


LOGIN TO DEVICE


1. To enter the router's Web interface (WebUI), type http://192.168.1.1 into the URL field of your Internet browser.
2. Use login information shown in image A when prompted for authentication.
3. After you log in, you will be prompted to change your password for security reasons. The new password must contain at least 8 characters,
including at least one uppercase letter, one lowercase letter, and one digit. This step is mandatory, and **you will not be able to interact with**
**the router's WebUI before you change the password.**
4. When you change the router's password, the Configuration Wizard will start. The Configuration Wizard is a tool used to set up some of the
router's main operating parameters.
5. Go to the Overview page and pay attention to the Signal Strength indication (image B). To maximize the cellular performance try adjusting
the antennas or changing the location of your device to achieve the best signal conditions.











TECHNICAL INFORMATION





|Radio specifications|Col2|
|---|---|
|RF technologi|es<br>3G, 4G, GNSS, WiFi, BLE|
|Max RF powe|r<br>24 dBm@WCDMA, 23 dBm@LTE, 23 dBm@WiFi 10 dBm@BLE|
|**Bundled accessories speciﬁcations***|**Bundled accessories speciﬁcations***|
|Power adapt|er<br>Input: 0.6 A@100-240 VAC, Output: 12 VDC, 1.5 A, 4 pin plug|
|Mobile anten|na<br>698~960 / 1710~2690 MHz, 50 Ω, VSWR<3, gain** 3 dBi, omnidirectional, SMA male connector|
|GNSS antenn|a<br>1575.42~1602 MHz, 2.2~5 VDC, VSWR<1.5, active total gain** 28 dB (typ.), RHCP polarization, SMA male connector|
|WiFi antenna|400~2483.5 MHz/5150~5905 MHz, 50 Ω, VSWR<2.0, gain** 3.0 dBi, omnidirectional, RP-SMA male connector|
|BLE antenna|2400~2500 MHz, 50 Ω, VSWR<2.5, gain** 2.5 dBi, omnidirectional, RP-SMA male connector|


*Order code dependent.
**Higher gain antenna can be connected to compensate for cable attenuation when a cable is used. The user is responsible for the compliance with the legal regulations.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router RUTX14

- 24 W PSU

- 4 x LTE antennas (swivel, SMA male)

- 2 x WiFi antennas (magnetic mount, RP-SMA male, 1.5 m cable)

- 1 x GNSS antenna (adhesive, SMA male, 3 m cable)

- 1 x Bluetooth antenna (magnetic mount, RP-SMA male, 1.5 m cable)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- RMS Flyer

- Packaging box





|ROUTER RUTX14|24 W PSU|4 X LTE ANTENNAS (SWIVEL,<br>SMA MALE)|
|---|---|---|
|**2 X WIFI ANTENNAS (MAGNETIC**<br>**MOUNT, RP-SMA MALE, 1.5 M CABLE)**|**1 X GNSS ANTENNA (ADHESIVE, SMA**<br>**MALE, 3 M CABLE)**|**1 X BLUETOOTH ANTENNA (MAGNETIC**<br>**MOUNT, RP-SMA MALE, 1.5 M CABLE)**|
|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**||



   - For all standard order codes standard package contents are the same, execpt for PSU.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUTX14

## STANDARD ORDER CODES


**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUTX14000000



851762 8517.62.00 Standard package



For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



4G (LTE-FDD): B1, B3, B5, B7, B8, B20, B28, B32 [1]

4G (LTE-TDD): B38, B40, B41
3G: B1, B3, B5, B8



RUTX14 0*****



Europe, the Middle East, Africa, APAC [2], Brazil,
Australia



The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 - LTE-FDD and B32 Support Rx Only, and in 2×CA it is Only for Secondary Component Carrier.
2 - Excluding Japan and CMCC


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // RUTX14


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



**10**


DATASHEET // RUTX14


## RUTX14 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTX14:



Device housing*:

Box:



132 x 44 x 95

355 x 60 x 175



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTX14 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of RUTX14 and its components as seen from the right side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // RUTX14



**FRONT VIEW**


The figure below depicts the measurements of RUTX14 and its components as seen from the front panel side:









**REAR VIEW**

|WAN 3G 4G<br>SIM1 SIM2 WiFi ETH<br>SIM1 SIM2<br>WiFi<br>PWR RESET 2.4 5 LAN1 LAN2 LAN3 LAN4 WAN|Col2|Col3|Col4|
|---|---|---|---|
|icts the measurements of RUTX14 and its components as seen from the back panel side:<br>**MOBILE AUX**<br>**MOBILE AUX**<br>**MOBILE MAIN**<br>**MOBILE AUX**<br>**WiFi**<br>**WiFi**<br>**BT**<br>**USB**<br>**GPS**|icts the measurements of RUTX14 and its components as seen from the back panel side:<br>**MOBILE AUX**<br>**MOBILE AUX**<br>**MOBILE MAIN**<br>**MOBILE AUX**<br>**WiFi**<br>**WiFi**<br>**BT**<br>**USB**<br>**GPS**|icts the measurements of RUTX14 and its components as seen from the back panel side:<br>**MOBILE AUX**<br>**MOBILE AUX**<br>**MOBILE MAIN**<br>**MOBILE AUX**<br>**WiFi**<br>**WiFi**<br>**BT**<br>**USB**<br>**GPS**|icts the measurements of RUTX14 and its components as seen from the back panel side:<br>**MOBILE AUX**<br>**MOBILE AUX**<br>**MOBILE MAIN**<br>**MOBILE AUX**<br>**WiFi**<br>**WiFi**<br>**BT**<br>**USB**<br>**GPS**|
|**MO**||||
|**MO**|**BILE AUX**<br>**MOBILE**|**BILE AUX**<br>**MOBILE**|**MOB**<br>** MAIN**<br>**GPS**|
|**MO**|**WiF**|**i**|**WiFi**<br>**BT**|
|||||


|Col1|WAN|Col3|Col4|3G 4G|
|---|---|---|---|---|
||<br>|<br>|||
|~~**SIM1 SI**~~|~~** 2**~~<br>~~**W**~~|~~** 2**~~<br>~~**W**~~|~~**Fi**~~<br>~~**ETH**~~||
|||||~~**SIM1**~~|
||||**WiFi**<br>**2.4**<br>**5**|**LAN1**<br>**LAN2**<br>**LAN3**|
|**PWR**|**RES**|**ET**|**ET**|**ET**|



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


DATASHEET // RUTX14



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**13**


DATASHEET // RUTX14



**DIN RAIL**


The scheme below depicts protrusion measurements of an attached DIN Rail:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**14**


