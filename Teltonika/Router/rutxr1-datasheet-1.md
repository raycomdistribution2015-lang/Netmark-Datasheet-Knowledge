# RUTXR1

Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // RUTXR1


## HARDWARE

FRONT VIEW


**Reserve power** **Mobile network** **Console** **WAN Ethernet**
**LED** **type LEDs** **port** **port**


**Main power**
**LED**







|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|
|---|---|---|---|---|---|---|---|---|
|||||||||RUTXR1|
||||||||||
||||||||||
|**SIM**<br>**holders**<br>**Reset**<br>**button**|||||||||
|**SIM**<br>**holders**<br>**Reset**<br>**button**||||**WAN SFP**<br>**port**<br>**LAN Ethernet**<br>**ports**<br>**USB port**<br>**WAN type**<br>**LEDs**|**WAN SFP**<br>**port**<br>**LAN Ethernet**<br>**ports**<br>**USB port**<br>**WAN type**<br>**LEDs**|**WAN SFP**<br>**port**<br>**LAN Ethernet**<br>**ports**<br>**USB port**<br>**WAN type**<br>**LEDs**|**WAN SFP**<br>**port**<br>**LAN Ethernet**<br>**ports**<br>**USB port**<br>**WAN type**<br>**LEDs**|**WAN SFP**<br>**port**<br>**LAN Ethernet**<br>**ports**<br>**USB port**<br>**WAN type**<br>**LEDs**|


**Mobile signal**
**strength LEDs**


**BACK VIEW**



**Reserve power** **Mobile AUX**
**connector** **antenna connector**



|Main power<br>connector|Col2|Col3|Col4|Col5|Security<br>slot|Col7|
|---|---|---|---|---|---|---|
|**MOBILE MAIN**<br>**WiFi**<br>**WiFi**<br>**MOBILE AUX**<br>**POWER**<br>**M**<br>**R**|||||||
|**MOBILE MAIN**<br>**WiFi**<br>**WiFi**<br>**MOBILE AUX**<br>**POWER**<br>**M**<br>**R**|**POWER**|**POWER**|**POWER**|**POWER**|**POWER**|**POWER**|
|**MOBILE MAIN**<br>**WiFi**<br>**WiFi**<br>**MOBILE AUX**<br>**POWER**<br>**M**<br>**R**|**M**<br>**R**|**M**<br>**R**|**M**<br>**R**|**M**<br>**R**|**M**<br>**R**|**M**<br>**R**|
||||||||


POWER SOCKET PINOUT



**WiFi antenna** **Mobile MAIN**
**connectors** **antenna connector**



**Grounding**
**screw**



**Power / Red wire**


**Not connected**



**Ground / Black wire**


**Not connected**



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


## FEATURES

**MOBILE**


Mobile module


SIM switch


Status


SMS



DATASHEET // RUTXR1


4G (LTE) – Cat 6 up to 300 Mbps, 3G – up to 42 Mbps


2 SIM cards, auto switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail


Signal strength, SINR, RSRP, RSRQ, Bytes sent/received, connected band, carrier aggregation, IMSI, ICCID


SMS status, SMS configuration, send/read SMS via HTTP POST/GET, Email to SMS, SMS to Email, SMS to HTTP, SMS to SMS, SMS
auto replay



USSD Supports sending and reading Unstructured Supplementary Service Data messages



Black/White list


Multiple PDN


Band management


APN



Operator black/white list


Possibility to use different PDNs for multiple network access and services


Band lock, Used band status display


Auto APN



Bridge mode Direct connection (bridge) between mobile ISP and device on LAN


**WIRELESS**



Wireless mode


WiFi security


ESSID



802.11b/g/n/ac Wave 2 (WiFi 5) with data transmission rates up to 867 Mbps (Dual Band, MU-MIMO), 802.11r fast transition,
Access Point (AP), Station (STA)


WPA3-EAP, WPA3-SAE, WPA2-Enterprise-PEAP, WPA2-PSK, WEP; AES-CCMP, TKIP, Auto Cipher modes, client separation


ESSID stealth mode



WiFi users up to 150 simultaneous connections


Wireless Hotspot Captive portal (Hotspot), internal/external Radius server, built in customizable landing page


**ETHERNET**


1 x WAN port 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
WAN
crossover



Fiber



1 x SFP port (cannot work simultaneously with Ethernet WAN port)



LAN 4 x LAN ports, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX
crossover


**CONSOLE**



Console


**NETWORK**


Routing


Network protocols


VoIP passthrough support



RS-232 (RJ45) console port for router configuration and debuging


Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP)


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, FTP, SMTP, SSL v3, TLS, ARP, VRRP, PPP, UPNP, SSH, DHCP, Telnet, SNMP,
MQTT, Wake on LAN (WOL), DLNA


H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets



Connection monitoring Ping Reboot, Wget reboot, Periodic Reboot, LCP and ICMP for link inspection



Firewall


DHCP


QoS / Smart Queue
Management (SQM)


DDNS



Port forwards, traffic rules, custom rules


Static and dynamic IP allocation, DHCP Relay, Relayd


Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually



Network backup VRRP, Mobile, Wired, Fiber and WiFi WAN options, each of which can be used as an automatic Failover



Load balancing


SSHFS



Balance Internet traffic over multiple WAN connections


Possibility to mount remote file system via SSH protocol



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


DATASHEET // RUTXR1



**SECURITY**


Authentication



Pre-shared key, digital certificates, X.509 certificates, TACACS+, Radius, IP & Login attempts block



Firewall Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T



Attack prevention


VLAN


Mobile quota control


WEB filter



DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
SYN-RST, X-mas, NULL flags, FIN scan attacks)


Port and tag based VLAN separation


Custom data limits for both SIM cards


Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only



Access control Flexible access control of TCP, UDP, ICMP packets, MAC address filter


**VPN**



OpenVPN


OpenVPN Encryption


IPsec



Multiple clients and a server can run simultaneously, 12 encryption methods


DES-CBC, RC2-CBC, DES-EDE-CBC, DES-EDE3-CBC, DESX-CBC, BF-CBC, RC2-40-CBC, CAST5-CBC, RC2-64-CBC, AES-128-CBC,
AES-192-CBC, AES-256-CBC


IKEv1, IKEv2, with 5 encryption methods for IPsec (DES, 3DES, AES128, AES192, AES256)



GRE GRE tunnel



PPTP, L2TP


Stunnel


DMVPN



Client/Server instances can run simultaneously, L2TPv3 support


Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code


Method of building scalable IPsec VPNs



SSTP SSTP client instance support


Zerotier Zerotier VPN client support


WireGuard WireGuard VPN client and server support


**MODBUS TCP SLAVE**


ID filtering Respond to one ID in range [1;255] or any


Allow remote access Allow access through WAN


Modbus TCP custom register block, which allows to read/write to a file inside the router, and can be used to extend Modbus
Custom registers
TCP slave functionality


**MODBUS TCP MASTER**



Supported functions


Supported data formats



01, 02, 03, 04, 05, 06, 15, 16


8 bit: INT, UINT; 16 bit: INT, UINT (MSB or LSB first); 32 bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC)



**MODBUS RTU MASTER CONSOLE**


Supported baud rates From 300 to 1000000



Supported functions


Number of data bits


Number of stop bits


Parity



01, 02, 03, 04, 05 (only for alarms), 06 (only for alarms), 15 (only for alarms), 16 (only for alarms)


From 5 to 8


1 or 2


None, Even, Odd



Flow None, RTS/CTS, Xon/Xoff


**MQTT GATEWAY**


Gateways Allows sending commands and receiving data from Modbus Master trough MQTT broker


**DATA TO SERVER**


Protocols HTTP(S), MQTT, Azure MQTT, Kinesis


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // RUTXR1



**MONITORING & MANAGEMENT**



WEB UI


FOTA



HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, event log, system log, kernel log


Firmware update from server, automatic notification



SSH SSH (v1, v2)


SMS SMS status, SMS configuration, send/read SMS via HTTP POST/GET


Call Reboot, Status, Mobile data on/off, Output on/off


TR-069 OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem


MQTT MQTT Broker, MQTT publisher


SNMP SNMP (v1, v2, v3), SNMP Trap


JSON-RPC Management API over HTTP/HTTPS


MODBUS MODBUS TCP status/control


**IOT PLATFORMS**



Clouds of things


ThingWorx



Allows monitoring of: Device data, Mobile data, Network info, Availability


Allows monitoring of: WAN Type, WAN IP Mobile Operator Name, Mobile Signal Strength, Mobile Network Type



Cumulocity Allows monitoring of: Device Model, Revision and Serial Number, Mobile Cell ID, ICCID, IMEI, Connection Type, Operator, Signal
Strength, WAN Type and IP


Can send device IP, Number of bytes send/received/ 3G connection state, Network link state, IMEI, ICCID, Model, Manufacturer,
Azure IoT Hub Serial, Revision, IMSI, Sim State, PIN state, GSM signal, WCDMA RSCP, WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL ID,
Operator, Operator number, Connection type, Temperature, PIN count to Azure IoT Hub server


**SYSTEM CHARACTERISTICS**



CPU


RAM



Quad-core ARM Cortex A7, 717 MHz


256 MB, DDR3



FLASH storage 256 MB, SPI Flash


**FIRMWARE/CONFIGURATION**



WEB UI


FOTA



Update FW from file, check FW on server, configuration profiles, configuration backup


Update FW/configuration from server



RMS Update FW/configuration for multiple devices at once


Keep settings Update FW without losing current configuration


**FIRMWARE CUSTOMIZATION**



Operating system


Supported languages



RutOS (OpenWrt based Linux OS)


Busybox shell, Lua, C, C++



Development tools SDK package with build environment provided


**SERIAL**



RS232


Serial functions


**USB**


Data rate


Applications



RJ45 connector, full RS232 (with RTS, CTS)


Console (active by default), Modbus gateway, Modbus RTU master, Serial OverIP, Modem mode (Full or partial) (planned), Ntrip
client


USB 2.0


Samba share, USB-to-serial



External devices Possibility to connect external HDD, flash drive, additional modem, printer


Storage formats FAT, FAT32, NTFS


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


DATASHEET // RUTXR1



**POWER**


Connector


Input voltage range



2 x 4 pin industrial DC power sockets for main and redundancy power sources


9 – 50 VDC, reverse polarity protection, voltage surge/transient protection



Power consumption idle: <3W, max: 18W


**PHYSICAL INTERFACES (PORTS, LEDS, ANTENNAS, BUTTONS, SIM)**



Ethernet


Console



5 x RJ45 ports, 10/100/1000 Mbps


1 x RJ45, RS232 communication



Fiber 1 x SFP port


2 x WAN type, 2 x Mobile connection type, 3 x Mobile signal strength, 2 x active SIM, 10 x Ethernet status, 2 x Console status, 2
Status LEDs
x Power


SIM 2 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holders


Power 2 x 4 pin DC connector


Antennas 2 x SMA for LTE, 2 x RP-SMA for WiFi


USB 1 x USB A port for external devices


Reset Reboot/User default reset/Factory reset button


Other 1 x Grounding screw, 1 x lock


**PHYSICAL SPECIFICATION**



Casing material


Dimensions (W x H x D)


Weight



Full steel housing


272 x 42.6 x 122.6 mm


1050 g



Mounting options Rack mounting, flat surface placement


**OPERATING ENVIRONMENT**



Operating temperature


Operating humidity



-40°C to +75°C


10 % to 90 % non-condensing



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // RUTXR1

## HARDWARE INSTALLATION


1. Push the SIM holder button with the SIM needle.
2. Pull out the SIM holder.
3. Insert your SIM card into the SIM holder.
4. Slide the SIM holder back into the router.
5. Attach all antennas.
6. Connect the power adapter to the socket on the back of the device. Then plug the other end of the power adapter into a power outlet.
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








|Col1|Col2|
|---|---|
||admin<br>admin01|
|||



TECHNICAL INFORMATION









|Radio specifications|Col2|
|---|---|
|RF technologies|<br>3G, 4G, WiFi|
|Max RF power|24 dBm@WCDMA, 23 dBm@LTE, 23 dBm@WiFi|
|**Bundled accessories speciﬁcations***|**Bundled accessories speciﬁcations***|
|Power adapter|Input: 0.6 A@100-240 VAC, Output: 12 VDC, 1.5 A, 4-pin plug|
|Mobile antenna|<br>699 ~ 868 / 1850 ~ 2690 MHz, 50 Ω, VSWR<3, gain** 1 dBi, omnidirectional, SMA male connector|
|WiFi antenna|2400 ~ 2500 MHz / 4950 ~ 5850 MHz, 50 Ω, VSWR<2, gain** 3 dBi, omnidirectional, RP-SMA male connector|


*Order code dependent.
**Higher gain antenna can be connected to compensate for cable attenuation when a cable is used. The user is responsible for the compliance with the legal regulations.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**7**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*


- RUTXR1

- 18 W PSU

- 2 x LTE antennas (magnetic mount, SMA male, 3 m cable)

- 2 x WiFi antennas (magnetic mount, RP-SMA male, 1.5 m cable)

- Rack - mounting kit

- 4 x Standing pads

- 8 x Screws

- SIM Adapter kit

- Ethernet cable (1.5 m)

- QSG (Quick Start Guide)

- RMS Flyer

- Packaging box









|RUTXR1|18 W PSU|2 X LTE ANTENNAS (MAGNETIC<br>MOUNT, SMA MALE, 3 M CABLE)|
|---|---|---|
|**2 X WIFI ANTENNAS (MAGNETIC**<br>**MOUNT, RP-SMA MALE, 1.5 M CABLE)**|**RACK - MOUNTING KIT**|**4 X STANDING PADS**|
|**8 X SCREWS**|**SIM ADAPTER KIT**|**ETHERNET CABLE (1.5 M)**|



- For all standard order codes standard package contents are the same, execpt for PSU.



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // RUTXR1


## STANDARD ORDER CODES

**PRODUCT CODE** **HS CODE** **HTS CODE** **PACKAGE CONTAINS**



RUTXR1 000000



851762 8517.62.00 Standard package



For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS


**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



4G (LTE-FDD): B1, B3, B5, B7, B8, B20, B28, B32 [1]

4G (LTE-TDD): B38, B40, B41
3G: B1, B3, B5, B8


4G (LTE-FDD): B2, B4, B5, B7, B12, B13, B25, B26,
B29 [1],B30, B66
3G: B2, B4, B5



RUTXR1 0*****



Europe, the Middle East, Africa, Australia,
APAC [2], Brazil, Malaysia



RUTXR1 1***** North America


The price and lead-times for region (operator) specific versions may vary. For more information please contact us.
1 - LTE-FDD B32 Support Rx Only, and in 2×CA it is Only for Secondary Component Carrier.
2 - Excluding Japan and CMCC.



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // RUTXR1


## RUTXR1 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for RUTXR1:



Device housing*:

Box:



272 x 42.6 x 122.6

355 x 175 x 60



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of RUTXR1 and its components as seen from the top:


**RIGHT VIEW**



The figure below depicts the measurements of RUTXR1 and its components as seen from the right side:

|Col1|Col2|Col3|Col4|Col5|
|---|---|---|---|---|
|||||42.6|
||||||



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **10**


DATASHEET // RUTXR1



**FRONT VIEW**


The figure below depicts the measurements of RUTXR1 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUTXR1 and its components as seen from the back panel side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // RUTXR1



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


DATASHEET // RUTXR1



**RACK MOUNT**


The scheme below depicts protrusion measurements of an attached rack mount kit:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**13**


