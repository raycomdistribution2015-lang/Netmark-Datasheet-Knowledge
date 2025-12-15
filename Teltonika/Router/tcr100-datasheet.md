# TCR100

Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.


DATASHEET // TCR100


## HARDWARE

FRONT VIEW


BACK VIEW


POWER SOCKET PINOUT



**Network status icons**


**Wi-fi** **WPS**
**button** **button**


**Reset**
**button**



**Power**
**socket**





**LAN Ethernet**
**port**



**SIM**
**holder**



**Power / Red wire** **Ground / Black wire**

**Not connected** **Not connected**


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**2**


DATASHEET // TCR100


## FEATURES

**MOBILE**


Mobile module



4G+ (LTE-A) – Cat 6 up to 300 Mbps, 3G – Up to 42 Mbps



Status Signal strength, SINR, RSRP, RSRQ, Bytes sent/received, connected band, carrier aggregation, IMSI, ICCID



SMS


USSD


Black/White list


Multiple PDN


Band management



SMS status, SMS configuration, send/read SMS via HTTP POST/GET, Email to SMS, SMS to Email, SMS to HTTP, SMS to SMS, SMS
auto reply


Supports sending and reading Unstructured Supplementary Service Data messages


Operator black/white list


Possibility to use different PDNs for multiple network access and services


Band lock, Used band status display



APN Auto APN

Bridge mode Direct connection (bridge) between mobile ISP and device on LAN


**WIRELESS**


Wireless mode 2.4 GHz (802.11 b/g/n, 2x2 MIMO), 5 GHz (802.11 ac, 1x1 MIMO), Access Point (AP), Station (STA)



WiFi security


ESSID



WPA3-EAP, WPA3-SAE, WPA2-Enterprise-PEAP, WPA2-PSK, WEP; AES-CCMP, TKIP, Auto Cipher modes, client separation


ESSID stealth mode



Wireless Hotspot Captive portal (Hotspot), internal/external Radius server, SMS OTP, MAC auth, built in customizable landing page, walled garden


Wireless mesh/roaming Wireless mesh (802.11s), fast roaming (802.11r)


**ETHERNET**


1 x WAN port (can be configured as LAN) 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u standards, supports auto
WAN
MDI/MDIX crossover



LAN


**NETWORK**


Routing


Network protocols


Connection monitoring


Firewall



1 x LAN port, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u standards, supports auto MDI/MDIX crossover


Static routes, Dynamic routes


TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SMTP, SSL v3, TLS, ARP, VRRP, PPP, PPPoE, UPNP, SSH, DHCP, Telnet,
SNMP, MQTT, Wake on LAN (WOL)


Ping Reboot, Wget reboot, Periodic Reboot, LCP and ICMP for link inspection


Port forwards, traffic rules, NAT rules, custom rules



DHCP Static and dynamic IP allocation, DHCP Relay, Relayd



QoS / Smart Queue
Management (SQM)


DDNS


Network backup



Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e


Supported >25 service providers, others can be configured manually


Mobile, Wired and Wi-Fi WAN options, each of which can be used as an automatic Failover



Load balancing Balance Internet traffic over multiple WAN connections


SSHFS Possibility to mount remote file system via SSH protocol


**SECURITY**



Authetication


Firewall


Attack prevention


VLAN



Pre-shared key, digital certificates, X.509 certificates


Pre-configured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI; DMZ; NAT; NAT-T


DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN,
SYN-RST, X-mas, NULL flags, FIN scan attacks)


Tag based VLAN separation



Mobile quota control Option to set custom data limit



WEB filter


Access control



Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only


Flexible access control of TCP, UDP, ICMP packets, MAC address filter



Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**3**


DATASHEET // TCR100



**VPN**


OpenVPN



Multiple clients and a server can run simultaneously, 12 encryption methods



DES-CBC, RC2-CBC, DES-EDE-CBC, DES-EDE3-CBC, DESX-CBC, BF-CBC, RC2-40-CBC, CAST5-CBC, RC2-64-CBC, AES-128-CBC,
OpenVPN Encryption
AES-192-CBC, AES-256-CBC



IPSec


GRE


PPTP, L2TP


Stunnel


DMVPN


SSTP


ZeroTier


WireGuard


**MODBUS TCP SLAVE**


ID filtering



IKEv1, IKEv2, with 5 encryption methods for IPsec (DES, 3DES, AES128, AES192, AES256)


GRE tunnel


Client/Server instances can run simultaneously, L2TPv3 support


Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program’s code


Method of building scalable IPsec VPNs


SSTP client instance support


ZeroTier VPN client support


WireGuard VPN client and server support


Respond to one ID in range [1;255] or any



Allow remote access Allow access through WAN


MODBUS TCP custom register block, which allows to read/write to a file inside the router, and can be used to extend MODBUS
Custom registers
TCP slave functionality


**MODBUS TCP MASTER**



Supported functions



01, 02, 03, 04, 05, 06, 15, 16



Supported data formats 8 bit: INT, UINT; 16 bit: INT, UINT (MSB or LSB first); 32 bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB,
BADC), HEX, ASCII


**MQTT GATEWAY**



Gateway


**DNP3**


Supported modes


**DATA TO SERVER (PLANNED)**


Protocols



Allows sending commands and receiving data from MODBUS Master trough MQTT broker


TCP Master, DNP3 Outstation


HTTP(S), MQTT, Azure MQTT, Kinesis



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


MODBUS MODBUS TCP status/control


RMS Teltonika Remote Management System (RMS)


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**4**


DATASHEET // TCR100



**IoT PLATFORMS**


Clouds of things



Allows monitoring of: Device data, Mobile data, Network info, Availability



ThingWorx Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type


Allows monitoring of: Device Model, Revision and Serial Number, Mobile Cell ID, ICCID, IMEI, Connection Type, Operator, Signal
Cumulocity
Strength, WAN Type and IP


Can send device IP, Number of bytes send/received, Mobile connection state, Network link state, IMEI, ICCID, Model, ManufacAzure IoT Hub turer, Serial, Revision, IMSI, SIM State, PIN state, GSM signal, WCDMA RSCP, WCDMA EC/IO, LTE RSRP, LTE SINR, LTE RSRQ, CELL
ID, Operator, Operator number, Connection type, Temperature, PIN count to Azure IoT Hub server


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



Update FW/configuration from server


Update FW/configuration for multiple devices at once



Keep settings Update FW without losing current configuration


**POWER**


Connector 4 pin industrial DC power socket


Input voltage range 9 - 30 VDC, reverse polarity protection, voltage surge/transient protection


Power consumption 3.7 W average, 9.3 W max


**PHYSICAL INTERFACES (PORTS, LEDS, ANTENNAS, BUTTONS, SIM)**


Ethernet 2 x RJ45 ports, 10/100 Mbps



Status LEDs


SIM



1 x Internet, 1 x Wi-Fi, 3 x Mobile connection strength, 2 x Ethernet status


1 x SIM slots (Mini SIM - 2FF), 1.8 V/3 V, external SIM holder (Embedded SIM variant available)



Antenna 2 x SMA for LTE, 2 x Internal for 2.4 GHz Wi-Fi, 1 x Internal for 5 GHz Wi-Fi



Power


WPS



1 x 4 pin DC connector


WPS activation button



Wi-Fi On/Off Wi-Fi enable/disable button

Reset Reboot/User default reset/Factory reset button


**PHYSICAL SPECIFICATION**


Casing material Plastic housing with aluminum screws and heatsink



Dimensions (W x H x D)


Weight



150 x 37 x 105 mm


376 g



Mounting options Flat surface placement


**OPERATING ENVIRONMENT**


Operating temperature -40 C to 75 C


Operating humidity 10 % to 90 % non-condensing


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**5**


DATASHEET // TCR100

## HARDWARE INSTALLATION


1. Pull out the SIM needle from SIM adapter kit.
2. Push the SIM holder button with the SIM needle.
3. Pull out the SIM holder.
4. Insert your SIM card into the SIM holder.
5. Slide the SIM holder back into the router.
6. You may store the SIM needle in the designated holder for future use.
7. Attach all antennas.
8. Connect the power adapter to the 4 pin socket and then plug the other end of the power adapter into a power outlet.
9. Connect to the device’s WiFi interface by using SSID and password or scaning QR code provided on the device information label or use
an Ethernet cable connected to LAN port.


## NETWORK STATUS ICONS

**WiFi** button – Enables/Disables Wi-Fi radio.



Buttons Network status icons



**WPS** button – Activates WPS authentication for 120 seconds.


Wi-Fi indication LED. When LED is lit – WiFi is enabled.


Internet connection LED. When LED is lit – the router has an internet connection, when LED is blinking – internet connection has
been lost.


Mobile signal strength LEDs. Signal strength indicated by number of lit bars.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**6**


DATASHEET // TCR100

## LOGIN TO DEVICE


1. To enter the router's Web interface (WebUI), type http://192.168.1.1 into the URL field of your Internet browser*.
2. To access router’s WebUI use admin as username and password given in the information label on the bottom side of the router (image A),
when prompted for authentication.
3. After you log in, you will be prompted to change your password for security reasons. The new password must contain at least 8 characters,
including at least one uppercase letter, one lowercase letter, and one digit. This step is mandatory, and you will not be able to interact with the
router's WebUI before you change the password.
4. When you change the router's password, the Setup wizard will start. The Setup wizard is a tool used to set up some of the router's main
operating parameters.
5. Go to the Overview page and pay attention to the Signal Strength indication (image B). To maximize the cellular performance try adjusting
the antennas or changing the location of your device to achieve the best signal conditions.











TECHNICAL INFORMATION




|Radio specifications|Col2|
|---|---|
|RF technologies|3G, 4G (LTE) Cat6, IEEE 802.11 b/g/n 2.4 GHz, IEEE 802.11 a/n/ac 5 GHz|
|Max RF power|24 dBm@WCDMA, 23 dBm@LTE, 20 dBm@Wi-Fi 2.4G, 23 dBm@Wi-Fi 5G|
||**Integrated antennas speciﬁcations**|
|Wi-Fi antenna|1. 2.4 GHz antenna: 2.4-2.5 GHz, VSWR<2, peak gain 1.62 dB, omnidirectional<br>2. 2.4 GHz antenna: 2.4-2.5 GHz, VSWR<2, peak gain 3.97 dB, omnidirectional<br>3. 5 GHz antenna: 5.1-5.85 GHz, VSWR<2, peak gain 5.02 dB, omnidirectional|
|**Bundled accessories speciﬁcations****|**Bundled accessories speciﬁcations****|
|Power adapter|Input: 0.6 A@100-240 VAC, Output: 12 VDC, 1 A, 4 pin plug|
|Mobile antenna|698~960/1710~2690 MHz, 50 Ω, VSWR<3, gain*** 4 dBi, omnidirectional, SMA male connector|



*To ensure maximum compatibility please use following latest internet browsing applications: Chrome, Firefox, Edge, Opera, Safari, Android Chrome, Android Firefox
**Order code dependent.
***Higher gain antenna can be connected to compensate for cable attenuation when a cable is used. The user is responsible for the compliance with the legal regulations.


In all EU member states, operation of 5150-5250 MHz is restricted to indoor use only.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice. **7**


## WHAT'S IN THE BOX?

STANDARD PACKAGE CONTAINS*

- Router TCR100

- 18 W PSU

- 2 x LTE antennas (swivel, SMA male)

- Ethernet cable (1.5 m)

- SIM Adapter kit

- QSG (Quick Start Guide)

- RMS Flyer

- Packaging box





|TCR100|18 W PSU|2 X LTE ANTENNAS (SWIVEL, SMA<br>MALE)|
|---|---|---|
|**ETHERNET CABLE (1.5 M)**|**SIM ADAPTER KIT**||



- For all standard order codes standard package contents are the same, execpt for PSU.





Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**8**


DATASHEET // TCR100

## STANDARD ORDER CODES


**PRODUCT CODE** **PACKAGE CONTAINS**



TCR100 000000


For more information on all available packaging options – please contact us directly.

## AVAILABLE VERSIONS



Standard package with Euro PSU



**PRODUCT CODE** **REGION (OPERATOR)** **FREQUENCY**



4G (LTE-FDD): B1, B3, B5, B7, B8, B20, B28, B32 [1]

4G (LTE-TDD): B38, B40, B41
3G: B1, B3, B5, B8



TCR100 0*****



Europe, the Middle East, Africa,
Australia, APAC [2], Brazil, Malaysia



The price and lead-times for region (operator) specific versions may vary. For more information please contact us.


1 - LTE-FDD B32 Support Rx Only, and in 2×CA it is Only for Secondary Component Carrier.

2 - Excluding Japan and CMCC.


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**9**


DATASHEET // TCR100


## TCR100 SPATIAL MEASUREMENTS & WEIGHT

**MAIN MEASUREMENTS**


W x H x D dimensions for TCR100:



Device housing*:

Box:



150 x 37 x 105

173 x 71 x 148



*Housing measurements are presented without antenna connectors and screws; for measurements of other device elements look to the sections below.


**TOP VIEW**


The figure below depicts the measurements of TCR100 and its components as seen from the top:


**RIGHT VIEW**


The figure below depicts the measurements of TCR100 and its components as seen from the right side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**10**


DATASHEET // TCR100



**FRONT VIEW**


The figure below depicts the measurements of TCR100 and its components as seen from the front panel side:


**REAR VIEW**


The figure below depicts the measurements of RUT360 and its components as seen from the back panel side:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**11**


DATASHEET // TCR100



**MOUNTING SPACE REQUIREMENTS**


The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2022, TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by TELTONIKA NETWORKS without prior notice.



**12**


