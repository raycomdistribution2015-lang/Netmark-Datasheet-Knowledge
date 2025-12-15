# NTP001
## v1.01

Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.


### DATASHEET - NTP001



**HARDWARE**


**FRONT VIEW**


**BACK VIEW**


**16-PIN TERMINAL BLOCK**


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



2


### DATASHEET - NTP001

**FEATURES**


**Ethernet**


**LAN** 1 x LAN port, 10/100 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az

standards, supports auto MDI/MDIX crossover


**Network**


**Network protocols** TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, SSL/TLS, ARP, SSH, DHCP,

SNMP, MQTT


**Connection monitoring** Ping Reboot, Wget Reboot, Periodic Reboot


**Network topology** Visual representation of your network, showing which devices are connected to which

other devices


**DDNS** Supported >25 service providers, others can be configured manually


**Security**


**Authentication** Pre-shared key, digital certificates, X.509 certificates, TACACS+, Internal & External

RADIUS users authentication, IP & login attempts block, time-based login blocking,

built-in random password generator


**WEB filter** Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites

only


**Access control** Flexible access control of SSH, Web interface, CLI and Telnet


**802.1x** Port-based network access control client


**NTP**


**Supported modes** Server - Receive time from GPS and act as a NTP server to broadcast time for other

devices (Stratum 1). Broadcast time through UDP or over Serial (RS232, RS485)


**Daytime Protocol** TCP/UDP


**Date over Serial** RS232/RS485


**NTP** NTPv4, NTP authentication (MD5/SHA1), Unicast/Multicast/Broadcast mode


**Protocol** NTP Stratum 1 Time Server (NTPv4)


**NTP Accuracy** Ethernet NTP ±1ms overall


**NTP Performance** >300 NTP requests per second (wire speed)


**Synchronization Accuracy** LAN synchronization typically 1–10ms


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



3


### DATASHEET - NTP001

**MODBUS**


**Supported modes** Server, Client


**Supported connection types** RTU (RS232, RS485), TCP


**Custom registers** MODBUS TCP custom register block requests, which read/write to a file inside the

router, and can be used to extend MODBUS TCP Client functionality


**Supported data formats** 8-bit: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD

(big-endian), DCBA (little-endian), CDAB, BADC), HEX, ASCII


**MQTT Gateway**


**Modbus MQTT Gateway** Allows sending commands and receiving data from MODBUS Server through MQTT

broker


**API**



**Teltonika Networks Web API (beta)**

**support**


**Monitoring & Management**



Expand your device's possibilities by using a set of configurable API endpoints to

retrieve or change data. For more information, please refer to this documentation:

[https://developers.teltonika-networks.com](https://developers.teltonika-networks.com)



**WEB UI** HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, multiple event log

servers, firmware update availability notifications, event log, system log, kernel log,

Internet status


**SSH** SSH (v1, v2)


**SNMP** SNMP (v1, v2, v3), SNMP Trap, Brute force protection


**JSON-RPC** Management API over HTTP/HTTPS


**MODBUS** MODBUS TCP status/control


**System Characteristics**


**CPU** Mediatek, 580 MHz, MIPS 24KEc


**RAM** 128 MB, DDR2


**FLASH storage** 16 MB, NOR Flash


**Firmware / Configuration**


**WEB UI** Update FW from file, check FW on server, configuration profiles, configuration

backup


**Keep settings** Update FW without losing current configuration


**Factory settings reset** A full factory reset restores all system settings, including the IP address, PIN, and user

data to the default manufacturer's configuration


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB



TELTONIKA NETWORKS without prior notice.



4


### DATASHEET - NTP001



**FIRMWARE CUSTOMISATION**


**Operating system** RutOS (OpenWrt based Linux OS)


**Supported languages** Busybox shell (ash), Lua 5.1, C, C++


**Development tools** SDK package with build environment provided


**GPL customization** You can create your own custom, branded firmware and web page application by

changing colours, logos, and other elements in our firmware to fit your or your clients’

needs


**Location Tracking**


**GNSS** GPS, GLONASS, BeiDou, Galileo and QZSS


**Acquisition Sensitivity** Acquisition Sensitivity -146 dBm, Reacquisition Sensitivity -157 dBm, Tracking

Sensitivity -157 dBm


**Accuracy** CEP-50 open sky 2.5 m


**Time Source** GPS 1575.42 ±1.023 MHz, GLONASS 1597.5–1605.8 MHz, Galileo 1575.42 ±2.046

MHz, BDS 1561.098 ±2.046 MHz


**Startup** Cold GPS acquisition in 120 seconds


**Serial**


**RS232** Terminal block connector: TX, RX, RTS, CTS


**RS485** Terminal block connector: D+, D-, R+, R- (2 or 4 wire interface)


**Input / Output**


**Input** 3 x Digital Input, 0 - 6 V detected as logic low, 8 - 30 V detected as logic high


**Output** 3 x Digital Output, Open collector output, max output 30 V, 300 mA


**Power**


**Connector** 2-pin in 16-pin industrial terminal block


**Input voltage range** 9 - 30 VDC, Overvoltage protection, Reverse polarity protection, Surge protection +/
1kV 50 uS Max


**Power consumption** Idle: < 2 W, Max: < 3.5 W


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



5


### DATASHEET - NTP001



**Physical Interfaces**


**Ethernet** 1 x RJ45 ports, 10/100 Mbps


**I/O’s** 3 x Configurable I/O, 1 x Analog input in 16-pin terminal block


**Status LEDs** 1 x Power, 2x GNSS status LEDs, 1x NTP Server status LED, 3 x IO status LEDs


**Power** 1 x 16-pin terminal block


**Antennas** 1 x SMA for GNSS


**RS232** 4-pin in 16-pin terminal block (TX, RX, RTS, CTS)


**RS485** 4-pin in 16-pin terminal block (D+, D-, R+, R-)


**Reset** Reboot/User default reset/Factory reset button


**Physical Specification**


**Casing material** Anodized aluminum housing and panels


**Dimensions (W x H x D)** 82.6 x 25 x 83 mm


**Weight** 180 g


**Mounting options** DIN rail, wall mount, flat surface (all require additional kit)


**Operating Environment**


**Operating temperature** -40 °C to 75 °C


**Operating humidity** 10% to 90% non-condensing


**Ingress Protection Rating** IP30


**Regulatory & Type Approvals**


**Regulatory** CE, UKCA, CB, UCRF, EAC, WEEE


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



6


### DATASHEET - NTP001



**ORDERING**


**STANDARD PACKAGE***


**NTP001** **2X8PIN CONNECTOR** **QSG (QUICK START GUIDE)**


NTP001 GNSS NTP Time Server

[16-pin terminal block](https://teltonika-networks.com/products/accessories/other-2/2x8pin-connector)

QSG (Quick Start Guide)

Packaging box


*Standard package contents may differ based on standard order codes.


[For more information on all available packaging options – please contact us](https://teltonika-networks.com/about-us/contacts/) directly.


**CLASSIFICATION CODES**


**HS Code:** 851762

**HTS:** 8517.62.00


**AVAILABLE VERSIONS**


NTP001 **0** ***** N/A NTP001000000 / Standard package


**NTP001 SPATIAL MEASUREMENTS**


**PHYSICAL SPECIFICATION**


**Device housing (W x H x D):** 82.6 x 25 x 83 mm


**Box (W x H x D):** 97 x 31 x 106.5 mm


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



7


### DATASHEET - NTP001



**TOP VIEW**

The figure below depicts the measurements of device and its components as seen from the top:


**RIGHT VIEW**

The figure below depicts the measurements of device and its components as seen from the right:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



8


### DATASHEET - NTP001



**REAR VIEW**

The figure below depicts the measurements of device and its components as seen from the back panel side:


**FRONT VIEW**

The figure below depicts the measurements of device and its components as seen from the front panel side:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



9


### DATASHEET - NTP001



**MOUNTING SPACE REQUIREMENTS**

The figure below depicts an approximation of the device's dimensions when cables and antennas are attached:


Copyright © 2025, UAB TELTONIKA NETWORKS. Specifications and information given in this document are subject to change by UAB

TELTONIKA NETWORKS without prior notice.



10


