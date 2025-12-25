"# RUT145 – Industrial RS485 Router

## 1. System Core & Interfaces

| Feature      | Specification                                                 |
| :----------- | :------------------------------------------------------------ |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                 |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB serial NOR        |
| **Ethernet** | 1 x WAN, 1 x LAN (10/100 Mbps, Auto MDI/MDIX)                 |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA) |
| **RS485**    | **1 x 6-pin terminal block** (4-wire or 2-wire interface)     |
| **Antenna**  | 1 x RP-SMA connector (Wi-Fi)                                  |

## 2. Serial & Industrial Protocols

- **RS485 Interface:**
  - _Connector:_ Terminal block (D+, D-, R+, R-, GND, NC)
  - _Modes:_ Console, Serial over IP, Modem, Modbus gateway
- **Supported Protocols:**
  - **Modbus:** TCP/RTU (Master/Slave), MQTT Gateway
  - **MQTT:** Broker, Publisher, Azure MQTT
  - **DNP3:** Station, Outstation (TCP, RTU)
  - **DLMS/COSEM:** Client
  - **BACnet:** Router, Client, Server
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature         | Specification                                          |
| :-------------- | :----------------------------------------------------- | ---------- |
| **Power Input** | **9 – 30 VDC** (Reverse polarity & Surge protection)   |
| **PoE**         | Passive PoE (LAN port, Mode B, 9-30 VDC)               |
| **Consumption** | Idle: < 1 W                                            | Max: < 2 W |
| **Housing**     | Anodized aluminium, IP30 rating                        |
| **Dimensions**  | 113.1 x 25 x 68.6 mm                                   |
| **Mounting**    | **Integrated DIN rail bracket**, Wall mount (optional) |
| **Environment** | Operating Temp: **-40°C to 75°C**                      |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP, EIGRP, Policy based routing
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TP, DMVPN
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA"
  "# RUT276 – Industrial RedCap 5G Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                  |
| :----------- | :--------------------------------------------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                                                  |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 32 MB SPI Flash                                          |
| **Mobile**   | **5G Sub-6Ghz SA:** 223 Mbps DL / 123 Mbps UL <br> **4G LTE Cat 4:** 195 Mbps DL / 105 Mbps UL |
| **Ethernet** | 2 x RJ45 ports (10/100 Mbps)                                                                   |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                                  |
| **Serial**   | **1 x 6-pin terminal block** (RS232, RS485 2-wire)                                             |
| **Storage**  | 1 x Micro SD slot (up to 2 TB)                                                                 |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF)                                                                 |
| **Antenna**  | 2 x SMA (Mobile), 1 x RP-SMA (Wi-Fi)                                                           |

## 2. Serial & Industrial Protocols

- **RS232/RS485 Interface:**
  - _Connector:_ 6-pin terminal block (D+, GND, TX, D-, GND, RX)
  - _Modes:_ Console, Serial over IP, Modem, Modbus gateway, NTRIP Client
- **Supported Protocols:**
  - **Modbus:** TCP/RTU (Server/Client), MQTT Gateway
  - **OPC UA:** Client, Server (TCP)
  - **BACnet:** Router (TCP, RTU RS485)
  - **DNP3:** Station, Outstation (TCP, RTU)
  - **DLMS/COSEM:** Client (TCP, RTU)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature         | Specification                                           |
| :-------------- | :------------------------------------------------------ | ------------ |
| **Power Input** | **9 – 57 VDC** (2-pin industrial DC socket)             |
| **PoE**         | Active PoE (802.3af Class 0) or Passive PoE (16-57 VDC) |
| **Consumption** | Idle: < 2 W                                             | Max: < 3.5 W |
| **Housing**     | Aluminum housing                                        |
| **Dimensions**  | 83 x 25 x 83 mm                                         |
| **Weight**      | 132 g                                                   |
| **Mounting**    | DIN rail, wall mount, flat surface (optional kit)       |
| **Environment** | Operating Temp: **-40°C to 75°C**                       |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP, Stunnel
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, SYN flood)
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **OS:** RutOS (OpenWrt based Linux OS)"
  "# OTD144 – Outdoor 4G LTE Cat 4 Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                     |
| :----------- | :-------------------------------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                                     |
| **Memory**   | **RAM:** 64 MB, DDR2 <br> **Flash:** 16 MB                                        |
| **Mobile**   | **4G LTE Cat 4:** 150 Mbps DL / 50 Mbps UL <br> **3G:** 21 Mbps DL / 5.76 Mbps UL |
| **Ethernet** | 2 x RJ45 ports (10/100 Mbps)                                                      |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                     |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF)                                                    |
| **Antenna**  | 2 x Internal (Mobile), 2 x Internal (Wi-Fi)                                       |
| **LEDs**     | 3 x Connection type, 3 x Signal strength, 4 x ETH status                          |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **BACnet:** Router (RS485, TCP)
  - **DNP3:** TCP Master, Outstation (RS232, RS485, TCP)
  - **DLMS/COSEM:** Client (TCP)
- **MQTT:** Broker, Publisher, Azure MQTT
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity

## 3. Power & Physical

| Feature         | Specification                               |
| :-------------- | :------------------------------------------ | ----------------------------- |
| **Power Input** | **42.5 – 57.0 VDC** (via RJ45 PoE In)       |
| **PoE In**      | 802.3af/at (Port 1)                         |
| **PoE Out**     | 802.3af Alternative B (Port 2, Max 15 W)    |
| **Consumption** | Idle: < 2.5 W                               | Max: < 6 W (PoE Out excluded) |
| **Housing**     | Plastic (PC+ASA), IP55 rating               |
| **Dimensions**  | 110 x 49.3 x 235 mm                         |
| **Mounting**    | **Integrated mounting bracket** (Wall/Pole) |
| **Environment** | Operating Temp: **-40°C to 75°C**           |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP, Stunnel
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Network backup), Load balancing, Captive Portal (Hotspot)"
  "# ATRM50 – High-Performance Industrial 5G Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                 |
| :------------ | :-------------------------------------------------------------------------------------------- |
| **CPU**       | MediaTek Dual-Core, 880 MHz, MIPS1004Kc                                                       |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                                 |
| **Mobile**    | **5G Sub-6 GHz:** 2.4 Gbps DL / 900 Mbps UL <br> **4G LTE Cat 19:** 1.6 Gbps DL / 200 Mbps UL |
| **Ethernet**  | 4 x M12 X-code 8-pin ports (1 x WAN, 3 x LAN, 10/100/1000 Mbps)                               |
| **Wi-Fi**     | 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO, 150 users                                |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF) + **eSIM** (up to 7 profiles)                                  |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                               |
| **Expansion** | 1 x USB 2.0 A-type, 1 x Internal Micro SD (up to 2 TB)                                        |
| **Antenna**   | 4 x SMA (Mobile), 2 x RP-SMA (Wi-Fi), 1 x SMA (GNSS)                                          |

## 2. Serial & Industrial Protocols

- **Industrial Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP)
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature         | Specification                                              |
| :-------------- | :--------------------------------------------------------- | ----------- |
| **Power Input** | **9 – 50 VDC** (M12 A-code 4-pin male connector)           |
| **Protection**  | Reverse polarity, Overvoltage (70V), Surge (>69V)          |
| **I/O**         | 2 x Inputs (**Ignition Detection**, Low Battery Detection) |
| **Consumption** | Idle: < 5.5 W                                              | Max: < 16 W |
| **Housing**     | Anodized aluminum housing and panels, IP30                 |
| **Dimensions**  | 167 x 46.2 x 112.4 mm                                      |
| **Weight**      | 550 g                                                      |
| **Environment** | Operating Temp: **-40°C to 75°C**                          |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN, Tinc
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Certifications:** CE, UKCA, RCM, **E-mark (Vehicle)**, **Railway compliant**
- **OS:** RutOS (OpenWrt based Linux OS)"
  "# RUTM55 – Industrial 5G Cellular Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                 |
| :------------ | :-------------------------------------------------------------------------------------------- |
| **CPU**       | MediaTek Dual-Core, 880 MHz, MIPS1004Kc                                                       |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                                 |
| **Mobile**    | **5G Sub-6 GHz:** 2.4 Gbps DL / 900 Mbps UL <br> **4G LTE Cat 19:** 1.6 Gbps DL / 200 Mbps UL |
| **Ethernet**  | 4 x RJ45 ports (1 x WAN, 3 x LAN, 10/100/1000 Mbps)                                           |
| **Wi-Fi**     | 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO, 150 users                                |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF) + **eSIM** (up to 7 profiles)                                  |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                               |
| **Expansion** | 1 x USB 2.0 A-type (Storage/External devices)                                                 |
| **Antenna**   | 4 x SMA (Mobile), 2 x RP-SMA (Wi-Fi), 1 x SMA (GNSS)                                          |

## 2. Serial & Industrial Protocols

- **Industrial Interfaces:**
  - _RS232:_ TX, RX (Terminal block)
  - _RS485:_ A, B (2-wire interface)
- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** TCP Master, Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP)
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature           | Specification                                                      |
| :---------------- | :----------------------------------------------------------------- | ------------- |
| **Power Input**   | **9 – 50 VDC** (3-pin pluggable terminal block)                    |
| **PoE (Passive)** | Passive PoE (Port 1, 9-50 VDC, Mode B)                             |
| **I/O**           | 2 x Digital Input, 1 x Analog Input, 1 x Digital Output, 1 x Relay |
| **Consumption**   | Idle: < 8.5 W                                                      | Max: < 14.5 W |
| **Housing**       | Anodized aluminum housing and panels, IP30                         |
| **Dimensions**    | 132 x 44.2 x 95 mm                                                 |
| **Weight**        | 430 g                                                              |
| **Environment**   | Operating Temp: **-40°C to 75°C**                                  |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Security:** **TPM 2.0**, Port-based 802.1x, SSL Certificate management
- **OS:** RutOS (OpenWrt based Linux OS)"
  "# RUT951 PoE+ – Industrial LTE Cat 4 PoE Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                     |
| :----------- | :-------------------------------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                                     |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                             |
| **Mobile**   | **4G LTE Cat 4:** 150 Mbps DL / 50 Mbps UL <br> **3G:** 21 Mbps DL / 5.76 Mbps UL |
| **Ethernet** | 4 x RJ45 ports (10/100 Mbps)                                                      |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                     |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF), Auto-switch, eSIM support                         |
| **Antenna**  | 2 x SMA (Mobile), 2 x RP-SMA (Wi-Fi)                                              |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                  |

## 2. Serial & Industrial Protocols

- **Industrial Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP)
  - **DLMS/COSEM:** Client (TCP)
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature         | Specification                                                                                   |
| :-------------- | :---------------------------------------------------------------------------------------------- | ------------------------------- |
| **Power Input** | **9 – 57 VDC** (4-pin industrial DC socket)                                                     |
| **PoE In**      | 802.3af/at compliant (Port 1 / LAN1)                                                            |
| **PoE Out**     | 802.3af/at compliant (Ports 2-4: LAN2, LAN3, WAN) <br> **Max Power:** 30W/port, **Budget:** 90W |
| **Consumption** | Idle: < 5 W                                                                                     | Max: < 6.5 W (PoE Out excluded) |
| **Housing**     | Aluminium housing, plastic panels, IP30                                                         |
| **Dimensions**  | 110 x 50 x 100 mm                                                                               |
| **Weight**      | 287 g                                                                                           |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                               |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Network backup), Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, RCM, EAC, UCRF, WEEE"
  "# RUTM31 – Industrial 5G Cellular Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                      |
| :----------- | :------------------------------------------------------------------------------------------------- |
| **CPU**      | MediaTek, Dual-Core, 880 MHz, MIPS1004Kc                                                           |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                                      |
| **Mobile**   | **5G Sub-6Ghz SA/NSA:** 2 Gbps DL / 1000 Mbps UL <br> **4G LTE Cat 12:** 600 Mbps DL / 150 Mbps UL |
| **Ethernet** | 2 x RJ45 ports (1 x WAN, 1 x LAN, 10/100/1000 Mbps)                                                |
| **Wi-Fi**    | IEEE 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO                                           |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF), Auto-switch, eSIM support                                          |
| **Antenna**  | 4 x SMA (Mobile), 2 x RP-SMA (Wi-Fi)                                                               |
| **I/O**      | 2 x Configurable digital Inputs/Outputs on 4-pin power connector                                   |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP)
  - **DLMS/COSEM:** Client (TCP)
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Security:** **TPM 2.0 standard**, Port-based 802.1x, SSL Certificate management

## 3. Power & Physical

| Feature           | Specification                               |
| :---------------- | :------------------------------------------ | -------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket) |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN port |
| **Consumption**   | Idle: 3.9 W                                 | Max: 9 W |
| **Housing**       | Anodized aluminum housing and panels, IP30  |
| **Dimensions**    | 100 x 30 x 93.7 mm                          |
| **Weight**        | 319 g                                       |
| **Environment**   | Operating Temp: **-40°C to 65°C**           |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Network backup), Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, CB, EAC, UCRF, RCM, WEEE"
  "# RUTM30 – Datasheet (v1.02)

## Table of Contents

1. [Overview](#overview)
2. [Hardware](#hardware)
3. [Mobile Connectivity](#mobile-connectivity)
4. [Wireless (Wi-Fi)](#wireless-wi-fi)
5. [Ethernet](#ethernet)
6. [Network Features](#network-features)
7. [Security Features](#security-features)
8. [VPN Support](#vpn-support)
9. [Industrial Protocols](#industrial-protocols)
10. [Data to Server](#data-to-server)
11. [Monitoring & Management](#monitoring--management)
12. [System Characteristics](#system-characteristics)
13. [Firmware / Configuration](#firmware--configuration)
14. [Input / Output (I/O)](#input--output-io)
15. [Power Specifications](#power-specifications)
16. [Physical Interfaces](#physical-interfaces)
17. [Physical Specification](#physical-specification)
18. [Regulatory & Certifications](#regulatory--certifications)
19. [Ordering Information & Standard Package](#ordering-information--standard-package)
20. [Available Versions](#available-versions)
21. [Spatial Measurements / Diagrams](#spatial-measurements--diagrams)

---

## Overview

**Manufacturer:** TELTONIKA NETWORKS  
**Model:** RUTM30  
**Description:** 5G/4G/3G Industrial Cellular Router with Wi-Fi, Ethernet, and Industrial Interfaces. Made in Lithuania.

---

## Hardware

### Front View

- **Ports:** 4-pin power socket, LAN Ethernet port, WAN Ethernet port
- **Buttons:** Reset button
- **LEDs:**
  - Mobile signal strength LED
  - Power LED
  - Mobile network type LED
  - LAN LEDs
  - WAN LEDs

**LED Behavior:**

- **Mobile Signal Strength:**
  - RED: RSSI between -110 and -82 dBm
  - YELLOW: RSSI between -81 and -52 dBm
  - GREEN: RSSI more than -51 dBm
- **Mobile Network Type:**
  - YELLOW: Connected to a 3G network
  - GREEN: Connected to a 4G network
  - BLUE: Connected to a 5G network

### Back View

- **Antenna Connectors:** 4 x Mobile (SMA), 2 x Wi-Fi (RP-SMA)
- **Arrangement (Left to Right):** MOBILE, WIFI, MOBILE, MOBILE, WIFI, MOBILE

### Power Socket Pinout

- **Pin 1:** Power (Red wire)
- **Pin 2:** Ground (Black wire)
- **Pin 3:** Input (Green wire)
- **Pin 4:** Output (White wire)

---

## Mobile Connectivity

| Parameter                       | Value                                                                                                                                                                                                                                                  |
| :------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Mobile module**               | 5G Sub-6Ghz SA/NSA: 2.4/3.4Gbps DL (4x4 MIMO), 900/550 Mbps UL (2x2); 4G LTE: Cat 19 1.6Gbps DL, Cat 18 200Mbps UL; 3G: 42 Mbps DL, 5.76Mbps UL                                                                                                        |
| **3GPP Release**                | Release 16                                                                                                                                                                                                                                             |
| **eSIM**                        | Consumer type eSIM, profile download and removal operations, up to 7 eSIM profiles; does not include data plans                                                                                                                                        |
| **SIM switch**                  | 2 x 2FF SIM and 1 x eSIM, auto-switch cases: weak signal, data limit, SMS limit, roaming, no network, network denied, data connection fail                                                                                                             |
| **Status**                      | IMSI, ICCID, operator, operator state, data connection state, network type, CA indicator, bandwidth, connected band, signal strength (RSSI), SINR, RSRP, RSRQ, EC/IO, RSCP, data sent/received, LAC, TAC, cell ID, ARFCN, UARFCN, EARFCN, MCC, and MNC |
| **SMS**                         | SMS status, SMS configuration, EMAIL to SMS, SMS to EMAIL, SMS to HTTP, SMS to SMS, scheduled SMS, SMS autoreply, SMPP                                                                                                                                 |
| **USSD**                        | Supports sending and reading Unstructured Supplementary Service Data messages                                                                                                                                                                          |
| **Block/Allow list**            | Operator block/allow list (by country or separate operators)                                                                                                                                                                                           |
| **Multiple PDN**                | Possibility to use different PDNs for multiple network access and services                                                                                                                                                                             |
| **Band management**             | Band lock, Used band status display                                                                                                                                                                                                                    |
| **SIM idle protection service** | Provides the possibility to configure the router to periodically switch to the unused SIM card and establish a data connection in order to prevent the SIM card from being blocked                                                                     |
| **SIM PIN code management**     | SIM PIN code management enables setting, changing, or disabling the SIM card's PIN                                                                                                                                                                     |
| **APN**                         | Auto APN                                                                                                                                                                                                                                               |
| **Bridge**                      | Direct connection (bridge) between mobile ISP and device on LAN                                                                                                                                                                                        |
| **Passthrough**                 | Router assigns its mobile WAN IP address to another device on LAN                                                                                                                                                                                      |
| **Framed routing**              | Framed routing: support an IP network behind 5G UE                                                                                                                                                                                                     |

---

## Wireless (Wi-Fi)

| Parameter                          | Value                                                                                                                                                                                                                                   |
| :--------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Wireless mode**                  | 802.11b/g/n/ac Wave 2 (Wi-Fi 5) with data transmission rates up to 867 Mbps (Dual Band, MU-MIMO), 802.11r fast transition, Access Point (AP), Station (STA)                                                                             |
| **WiFi security**                  | WPA2-Enterprise - PEAP, WPA2-PSK, WPA-EAP, WPA-PSK, WPA3-SAE, WPA3-EAP, OWE; AES-CCMP, TKIP, Auto-cipher modes, client separation, EAP-TLS with PKCS#12 certificates, disable auto-reconnect, 802.11w Protected Management Frames (PMF) |
| **SSID/ESSID**                     | ESSID stealth mode                                                                                                                                                                                                                      |
| **Wi-Fi users**                    | Up to 150 simultaneous connections                                                                                                                                                                                                      |
| **Wireless Connectivity Features** | Wireless mesh (802.11s), fast roaming (802.11r), Relayd, BSS transition management (802.11v), radio resource measurement (802.11k)                                                                                                      |
| **Wireless MAC filter**            | Allowlist, blocklist                                                                                                                                                                                                                    |
| **Wireless QR code generator**     | Once scanned, a user will automatically enter your network without needing to input login information                                                                                                                                   |
| **TravelMate**                     | Forward Wi-Fi hotspot landing page to a subsequent connected device                                                                                                                                                                     |

---

## Ethernet

| Parameter | Value                                                                                                                        |
| :-------- | :--------------------------------------------------------------------------------------------------------------------------- |
| **WAN**   | 1 x WAN port 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX crossover  |
| **LAN**   | 1 x LAN port, 10/100/1000 Mbps, compliance with IEEE 802.3, IEEE 802.3u, 802.3az standards, supports auto MDI/MDIX crossover |

---

## Network Features

| Parameter                    | Value                                                                                                                                                                                                                                                                                                                                                                        |
| :--------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Routing**                  | Static routing, Dynamic routing (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based routing                                                                                                                                                                                                                                                                                 |
| **Network protocols**        | TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP, HTTPS, FTP, SMTP, SSL v3, TLS, ARP, VRRP, PPP, PPPOE, UPNP, SSH, DHCP, Telnet, SMPP, SNMP, MQTT, Wake On Lan (WOL)                                                                                                                                                                                                               |
| **VoIP passthrough support** | H.323 and SIP-alg protocol NAT helpers, allowing proper routing of VoIP packets                                                                                                                                                                                                                                                                                              |
| **Connection monitoring**    | Ping Reboot, Wget Reboot, Periodic Reboot, LCP and ICMP for link inspection                                                                                                                                                                                                                                                                                                  |
| **Firewall**                 | Port forward, traffic rules, custom rules, TTL target customisation                                                                                                                                                                                                                                                                                                          |
| **Firewall status page**     | View all your Firewall statistics, rules, and rule counters                                                                                                                                                                                                                                                                                                                  |
| **Ports management**         | View device ports, enable and disable each of them, turn auto-configuration on or off, change their transmission speed, and so on                                                                                                                                                                                                                                            |
| **Network topology**         | Visual representation of your network, showing which devices are connected to which other devices                                                                                                                                                                                                                                                                            |
| **Hotspot**                  | Captive portal (hotspot), internal/external Radius server, Radius MAC authentication, SMS authorisation, SSO authentication, internal/external landing page, walled garden, user scripts, URL parameters, user groups, individual user or group limitations, user management, 9 default customisable themes and optionality to upload and download customised hotspot themes |
| **Hotspot 2.0**              | Hotspot 2.0 is a Wi-Fi standard that enables seamless, secure, and automatic connection to trusted wireless networks                                                                                                                                                                                                                                                         |
| **DHCP**                     | Static and dynamic IP allocation, DHCP relay, DHCP server configuration, status, static leases: MAC with wildcards                                                                                                                                                                                                                                                           |
| **QoS / SQM**                | Traffic priority queuing by source/destination, service, protocol or port, WMM, 802.11e                                                                                                                                                                                                                                                                                      |
| **DDNS**                     | Supported >25 service providers, others can be configured manually                                                                                                                                                                                                                                                                                                           |
| **DNS over HTTPS**           | DNS over HTTPS proxy enables secure DNS resolution by routing DNS queries over HTTPS                                                                                                                                                                                                                                                                                         |
| **Network backup**           | Wi-Fi WAN, Mobile, VRRP, Wired options, each of which can be used as an automatic Failover                                                                                                                                                                                                                                                                                   |
| **Load balancing**           | Balance Internet traffic over multiple WAN connections                                                                                                                                                                                                                                                                                                                       |
| **SSHFS**                    | Possibility to mount remote file system via SSH protocol                                                                                                                                                                                                                                                                                                                     |
| **VRF support**              | Initial virtual routing and forwarding (VRF) support                                                                                                                                                                                                                                                                                                                         |
| **Traffic Management**       | Real-time monitoring, wireless signal charts, traffic usage history                                                                                                                                                                                                                                                                                                          |

---

## Security Features

| Parameter                      | Value                                                                                                                                                                     |
| :----------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Firewall**                   | Preconfigured firewall rules can be enabled via WebUI, unlimited firewall configuration via CLI, DMZ, NAT, NAT-T, NAT64                                                   |
| **Attack prevention**          | DDOS prevention (SYN flood protection, SSH attack prevention, HTTP/HTTPS attack prevention), port scan prevention (SYN-FIN, SYN-RST, X-mas, NULL flags, FIN scan attacks) |
| **VLAN**                       | Port and tag-based VLAN separation                                                                                                                                        |
| **Mobile quota control**       | Custom data limits for SIM card                                                                                                                                           |
| **WEB filter**                 | Blacklist for blocking out unwanted websites, Whitelist for specifying allowed sites only                                                                                 |
| **Access control**             | Flexible access control of SSH, Web interface, CLI and Telnet                                                                                                             |
| **TPM**                        | Identification and authentication module, TPM 2.0 standard                                                                                                                |
| **SSL certificate generation** | Let's Encrypt and SCEP certificate generation methods                                                                                                                     |
| **802.1x**                     | Port-based network access control client                                                                                                                                  |

---

## VPN Support

| Parameter              | Value                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **OpenVPN**            | Multiple clients and a server can run simultaneously, 27 encryption methods                                                                                                                                                                                                                                                                                                                                                                               |
| **OpenVPN Encryption** | DES-CBC 64, RC2-CBC 128, DES-EDE-CBC 128, DES-EDE3-CBC 192, DESX-CBC 192, BF-CBC 128, RC2-40-CBC 40, CAST5-CBC 128, RC2-64-CBC 64, AES-128-CBC 128, AES128--CFB 128, AES-128-CFB1 128, AES-128-CFB8 128, AES-128-OFB 128, AES-128-GCM 128, AES-192-CFB 192, AES-192-CFB1 192, AES-192-CFB8 192, AES192--OFB 192, AES-192-CBC 192, AES-192GCM -192, AES-256-GCM 256, AES-256-CFB 256, AES-256-CFB1 256, AES-256-CFB8 256, AES-256-OFB 256, AES-256-CBC 256 |
| **IPsec**              | XFRM, IKEV1, IKEv2, with 14 encryption methods for IPsec (3DES, DES, AES128, AES192, AES256, AES128GCM8, AES192GCM8, AES256GCM8, AES128GCM12, AES192GCM12, AES256GCM12, AES128GCM16, AES192GCM16, AES256GCM16)                                                                                                                                                                                                                                            |
| **GRE**                | GRE tunnel, GRE tunnel over IPsec support                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **PPTP, L2TP**         | Client/Server instances can run simultaneously, L2TPv3, L2TP over IPsec support                                                                                                                                                                                                                                                                                                                                                                           |
| **Stunnel**            | Proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the program's code                                                                                                                                                                                                                                                                                                                              |
| **DMVPN**              | Method of building scalable IPsec VPNs, Phase 2 and Phase 3 and Dual Hub support                                                                                                                                                                                                                                                                                                                                                                          |
| **SSTP**               | SSTP client instance support                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **ZeroTier**           | ZeroTier VPN client support                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **WireGuard**          | WireGuard VPN client and server support                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Tinc**               | Tinc offers encryption, authentication and compression in it's tunnels. Client and server support.                                                                                                                                                                                                                                                                                                                                                        |
| **Tailscale**          | Tailscale offers speed, stability, and simplicity over traditional VPNs. Encrypted point-to-point connections using the open source WireGuard protocol                                                                                                                                                                                                                                                                                                    |

---

## Industrial Protocols

| Protocol       | Parameter                  | Value                                                                                                                                              |
| :------------- | :------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| **OPC UA**     | Supported modes            | Client, Server                                                                                                                                     |
|                | Supported connection types | TCP                                                                                                                                                |
| **MODBUS**     | Supported modes            | Server, Client                                                                                                                                     |
|                | Supported connection types | TCP                                                                                                                                                |
|                | Custom registers           | MODBUS TCP custom register block requests, which read/write to a file inside the router, and can be used to extend MODBUS TCP Client functionality |
|                | Supported data formats     | 8bit-: INT, UINT; 16-bit: INT, UINT (MSB or LSB first); 32-bit: float, INT, UINT (ABCD (big-endian), DCBA (little-endian), CDAB, BADC), HEX, ASCII |
| **DNP3**       | Supported modes            | Station, Outstation                                                                                                                                |
|                | Supported connection       | TCP                                                                                                                                                |
| **DLMS/COSEM** | DLMS Support               | DLMS standard protocol for utility meter data exchange                                                                                             |
|                | Supported modes            | Client                                                                                                                                             |
|                | Supported connection types | TCP                                                                                                                                                |

---

## Data to Server

| Parameter          | Value                                                                                                                                                                                         |
| :----------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Protocol**       | HTTP(S), MQTT, Azure MQTT                                                                                                                                                                     |
| **Data to server** | Extract parameters from multiple sources and different protocols, and send them all to a single server; Custom LUA scripting, allowing scripts to utilize the router's Data to server feature |
| **MQTT Gateway**   | Allows sending commands and receiving data from MODBUS Server through MQTT broker                                                                                                             |
| **API**            | Teltonika Networks Web API (beta) support to retrieve or change data.                                                                                                                         |

---

## Monitoring & Management

| Parameter         | Value                                                                                                                                                                                                                                                                                                 |
| :---------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **WEB UI**        | HTTP/HTTPS, status, configuration, FW update, CLI, troubleshoot, multiple event log servers, firmware update availability notifications, event log, system log, kernel log, Internet status                                                                                                           |
| **FOTA**          | Firmware update from server, automatic notification                                                                                                                                                                                                                                                   |
| **SSH**           | SSH (v1, v2)                                                                                                                                                                                                                                                                                          |
| **SMS**           | SMS status, SMS configuration                                                                                                                                                                                                                                                                         |
| **Call**          | Reboot, Status, Mobile data on/off, Output on/off, answer/hang-up with a timer, Wi-Fi on/off                                                                                                                                                                                                          |
| **Email**         | Receive email message status alerts of various services                                                                                                                                                                                                                                               |
| **TR-069**        | OpenACS, EasyCwmp, ACSLite, tGem, LibreACS, GenieACS, FreeACS, LibCWMP, Friendly tech, AVSystem                                                                                                                                                                                                       |
| **MQTT**          | MQTT Broker, MQTT publisher                                                                                                                                                                                                                                                                           |
| **SNMP**          | SNMP (v1, v2, v3), SNMP Trap, Brute force protection                                                                                                                                                                                                                                                  |
| **JSON-RPC**      | Management API over HTTP/HTTPS                                                                                                                                                                                                                                                                        |
| **MODBUS**        | MODBUS TCP status/control                                                                                                                                                                                                                                                                             |
| **RMS**           | Teltonika Remote Management System (RMS)                                                                                                                                                                                                                                                              |
| **ThingWorx**     | Allows monitoring of: WAN Type, WAN IP, Mobile Operator Name, Mobile Signal Strength, Mobile Network Type                                                                                                                                                                                             |
| **Cumulocity**    | Allows monitoring of: Device Model, Revision and Serial Number, WAN Type and IP, Mobile Cell ID, ICCID, IMEI, Connection Type, Operator, Signal Strength. Has reboot and firmware upgrade actions                                                                                                     |
| **Azure IoT Hub** | Can be configured with Data to Server to send all the available parameters to the cloud. Has Direct method support which allows to execute RutOS API calls on the IoT Hub. Also has Plug and Play integration with Device Provisioning Service that allows zero-touch device provisioning to IoT Hubs |
| **AWS IoT Core**  | Utility to interact with the AWS cloud platform. Jobs Support: Call the device's API using AWS Jobs functionality                                                                                                                                                                                     |

---

## System Characteristics

| Parameter         | Value                                            |
| :---------------- | :----------------------------------------------- |
| **CPU**           | MediaTek, Dual-Core, 880 MHz, MIPS1004Kc         |
| **RAM**           | 256 MB, DDR3                                     |
| **FLASH storage** | 16 MB serial NOR flash, 256 MB serial NAND flash |

---

## Firmware / Configuration

| Parameter                  | Value                                                                                                                                                                       |
| :------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **WEB UI**                 | Update FW from file, check FW on server, configuration profiles, configuration backup                                                                                       |
| **FOTA**                   | Update FW                                                                                                                                                                   |
| **RMS**                    | Update FW/configuration for multiple devices at once                                                                                                                        |
| **Keep settings**          | Update FW without losing current configuration                                                                                                                              |
| **Factory settings reset** | A full factory reset restores all system settings, including the IP address, PIN, and user data to the default manufacturer's configuration                                 |
| **Operating system**       | RutOS (OpenWrt based Linux OS)                                                                                                                                              |
| **Supported languages**    | Busybox shell, Lua, C, C++                                                                                                                                                  |
| **Development tools**      | SDK package with build environment provided                                                                                                                                 |
| **GPL customization**      | You can create your own custom, branded firmware and web page application by changing colours, logos, and other elements in our firmware to fit your or your clients' needs |

---

## Input / Output (I/O)

| Parameter            | Value                                                                                                                                                                                                 |
| :------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Configurable I/O** | 2 x Configurable digital Inputs/Outputs on 4-pin power connector. Digital Input, 0-6 V detected as logic low, 8-50 V detected as logic high. Digital Output, Open collector output, max 30 V, 300 mA. |
| **Events**           | Email, RMS, SMS                                                                                                                                                                                       |
| **I/O juggler**      | Allows to set certain I/O conditions to initiate event                                                                                                                                                |

---

## Power Specifications

| Parameter               | Value                                                                                                                      |
| :---------------------- | :------------------------------------------------------------------------------------------------------------------------- |
| **Connector**           | 4-pin industrial DC power socket                                                                                           |
| **Input voltage range** | 9-50 VDC, reverse polarity protection, voltage surge/transient protection                                                  |
| **PoE (passive)**       | Possibility to power up through LAN port, not compatible with IEEE802.3af, 802.3at and 802.3bt standards, Mode B, 9-50 VDC |
| **Power consumption**   | Idle: 3.9 W, Max: 9 W                                                                                                      |

---

## Physical Interfaces

| Parameter       | Value                                                                                            |
| :-------------- | :----------------------------------------------------------------------------------------------- |
| **Ethernet**    | 2 x RJ45 ports, 10/100/1000 Mbps                                                                 |
| **I/O's**       | 2 x Configurable digital I/O on 4-pin power connector                                            |
| **Status LEDs** | 1 x Mobile connection type (RGB), 1 x Mobile connection strength(RGB), 4 x LAN status, 1 x Power |
| **SIM**         | 2 x SIM slots (Mini SIM-2FF), 1.8 V/3 V, internal SIM holders                                    |
| **Power**       | 1 x 4-pin power connector                                                                        |
| **Antennas**    | 4 x SMA for Mobile, 2 x RP-SMA for Wi-Fi                                                         |
| **Reset**       | Reboot/User default reset/Factory reset button                                                   |

---

## Physical Specification

| Parameter                     | Value                                                           |
| :---------------------------- | :-------------------------------------------------------------- |
| **Casing material**           | Anodized aluminum housing and panels                            |
| **Dimensions (W x H x D)**    | 100 x 30 x 93.7 mm                                              |
| **Weight**                    | 319 g                                                           |
| **Mounting options**          | DIN rail, wall mount, flat surface (all require additional kit) |
| **Operating temperature**     | -40°C to 75°C                                                   |
| **Operating humidity**        | 10% to 90% non-condensing                                       |
| **Ingress Protection Rating** | IP30                                                            |

---

## Regulatory & Certifications

| Parameter            | Value                                                                                                                                                                          |
| :------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Regulatory**       | CE, UKCA, CB, EAC, UCRF, RCM, R-NZ, WEEE                                                                                                                                       |
| **EMC Standards**    | EN 55032:2015+ A11:2020 + A1:2020; EN 55035:2017+A11:2020; EN IEC 61000-3-2:2019+A1:2021; EN 301 489-1 V2.2.3; EN 301 489-3 V2.3.2; EN 301 489-17 V3.2.4; EN 301 489-52 V1.2.1 |
| **RF Standards**     | EN 300 328 V2.2.2; EN 300 440 V2.2.1; EN 301 893 V2.1.1; EN 301 908-1 V15.2.1; EN 301 908-2 V13.1.1; EN 301 908-13 V13.2.1; EN 301 908-25 V15.1.1                              |
| **Safety Standards** | CE: EN IEC 62311:2020; RCM: TBD; CB: EN IEC 62368-1:2020+A11:2020                                                                                                              |

---

## Ordering Information & Standard Package

### Classification Codes

- **HS Code:** 851762
- **HTS:** 8517.62.00

### Standard Package Content

- RUTM30 Router
- 18 W PSU
- 4 x 5G Straight compact mobile antennas (SMA male)
- 2 x Wi-Fi antennas (magnetic mount, RP-SMA male, 1.5 m cable)
- Ethernet cable (1.5 m)
- SIM Adapter kit
- 1 x hex key
- QSG (Quick Start Guide)
- Packaging box

---

## Available Versions

### RUTM30 0**\***

**Region:** EMEA, APAC, Brazil¹

| Network Type     | Bands Supported                                                 |
| :--------------- | :-------------------------------------------------------------- |
| **5G NR**        | n1, n3, n5, n7, n8, n20, n28, n38, n40, n41, n75, n76, n77, n78 |
| **4G (LTE-FDD)** | B1, B3, B5, B7, B8, B20, B28, B32, B71                          |
| **4G (LTE-TDD)** | B38, B40, B41, B42, B43                                         |
| **3G**           | B1, B5, B8                                                      |

> ¹ Regional availability excluding Russia, Belarus & Iran

**Order Codes:**

- **RUTM30000000:** Standard package with EU PSU
- **RUTM30000200:** Standard package with UK PSU
- **RUTM30000400:** Standard package with US PSU
- **RUTM30000500:** Standard package with AU PSU

---

## Spatial Measurements / Diagrams

> **Device Housing**
>
> - Dimensions (W x H x D): 100 x 30 x 93.7 mm (excluding antenna connectors)
> - Box Dimensions (W x H x D): 355 x 100 x 175 mm

> **Front View**
>
> - Width: 100.0 mm
> - Height: 30.0 mm
> - Connector/LED positions from left edge:
>   - Power Socket Center: 9.2 mm
>   - Reset Button Center: 25.2 mm
>   - LAN Port Start: 58.2 mm
>   - WAN Port End: 91.9 mm

> **Rear View**
>
> - Antenna Connector Spacing (from left edge):
>   - Mobile: 13.0 mm
>   - Wi-Fi: 27.8 mm
>   - Mobile: 42.6 mm
>   - Mobile: 57.4 mm
>   - Wi-Fi: 72.2 mm
>   - Mobile: 87.0 mm

> **Mounting Space Requirements**
>
> - Width (with antennas): ~182.0 mm
> - Depth (with DIN rail mount): ~123.5 mm (vertical antenna height)
> - Height (device only): 30.0 mm
> - Clearance below DIN rail: 16.20 mm"
>   "# RUTM56 – Industrial Dual-Modem 5G Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                               |
| :----------- | :------------------------------------------------------------------------------------------ |
| **CPU**      | MediaTek, Dual-Core, 880 MHz, MIPS1004Kc                                                    |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                               |
| **Mobile**   | **Modem 1 (5G):** 3.4 Gbps DL / 900 Mbps UL <br> **Modem 2 (4G):** 150 Mbps DL / 50 Mbps UL |
| **Ethernet** | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100/1000 Mbps)                                         |
| **Wi-Fi**    | IEEE 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO                                    |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF) + **eSIM** (up to 7 profiles)                                |
| **GNSS**     | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                             |
| **Antenna**  | 6 x SMA (Mobile), 2 x RP-SMA (Wi-Fi), 1 x SMA (GNSS)                                        |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                            |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP)
  - **DLMS/COSEM:** Client (TCP) với tính năng quét đối tượng tự động
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Security:** **TPM 2.0 standard**, Port-based 802.1x, SSL Certificate management
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | ----------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: 4.5 W                                  | Max: 12.5 W |
| **Housing**       | Anodized aluminum housing and panels, IP30   |
| **Dimensions**    | 132 x 44.2 x 95 mm                           |
| **Weight**        | 515 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** **Dual-Modem Failover**, Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, EAC, EUCRF, WEEE"
  "# OTD500 – Industrial Outdoor 5G Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                        |
| :----------- | :--------------------------------------------------------------------------------------------------- |
| **CPU**      | MediaTek Dual-core, 880 MHz, MIPS1004Kc                                                              |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                                        |
| **Mobile**   | **5G Sub-6 GHz SA/NSA:** 3.4 Gbps DL / 900 Mbps UL <br> **4G LTE Cat 19:** 1.6 Gbps DL / 200 Mbps UL |
| **Ethernet** | 2 x RJ45 ports (10/100/1000 Mbps, WAN/LAN configurable)                                              |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF) + **eSIM** (up to 7 profiles)                                         |
| **Antenna**  | 4 x Internal Omni-directional (4.9 dBi gain)                                                         |
| **LEDs**     | 3 x Connection type, 3 x Signal strength, 4 x ETH status                                             |
| **Security** | **TPM 2.0 standard**, Port-based 802.1x, SSL Certificate management                                  |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP)
  - **DLMS/COSEM:** Client (TCP)
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support
- **OS:** RutOS (OpenWrt based Linux OS)

## 3. Power & Physical

| Feature         | Specification                           |
| :-------------- | :-------------------------------------- | ----------------------------- |
| **Power Input** | **42.5 – 57.0 VDC** (via RJ45 PoE In)   |
| **PoE In**      | 802.3af/at (Port 1)                     |
| **PoE Out**     | 802.3af Alternative B (Port 2, Max 15W) |
| **Consumption** | Idle: < 2.5 W                           | Max: < 9 W (PoE Out excluded) |
| **Housing**     | Plastic (PC+ASA), IP55 rating           |
| **Dimensions**  | 110 x 49.3 x 235 mm                     |
| **Weight**      | 385 g                                   |
| **Environment** | Operating Temp: **-40°C to 55°C**       |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (VRRP, Wired), Load balancing, Captive Portal (Hotspot)
- **Certifications:** CE, UKCA, RCM, CB, EAC, UCRF, WEEE"
  "# RUTM54 – Industrial 5G Cellular Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                        |
| :------------ | :--------------------------------------------------------------------------------------------------- |
| **CPU**       | MediaTek Dual-core, 880 MHz, MIPS1004Kc                                                              |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                                        |
| **Mobile**    | **5G Sub-6 GHz SA/NSA:** 3.4 Gbps DL / 900 Mbps UL <br> **4G LTE Cat 19:** 1.6 Gbps DL / 211 Mbps UL |
| **Ethernet**  | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100/1000 Mbps)                                                  |
| **Wi-Fi**     | IEEE 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO                                             |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF) + **eSIM** (up to 7 profiles)                                         |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                                      |
| **Expansion** | 1 x USB 2.0 A-type (Samba share, USB-to-serial)                                                      |
| **Antenna**   | 4 x SMA (Mobile), 2 x RP-SMA (Wi-Fi), 1 x SMA (GNSS)                                                 |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                                     |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP) với tính năng quét đối tượng tự động
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Security:** Port-based 802.1x, SSL Certificate management, Attack prevention
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | --------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: 4 W                                    | Max: 14 W |
| **Housing**       | Anodized aluminum housing and panels, IP30   |
| **Dimensions**    | 132 x 44.2 x 95 mm                           |
| **Weight**        | 530 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Network backup), Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** FCC, IC, AT&T (Operator), WEEE, RoHS, REACH"
  "# RUT206 – Industrial LTE Cat 4 Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                                   |
| :----------- | :-------------------------------------------------------------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                                                                   |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 32 MB NOR Flash                                                           |
| **Mobile**   | **4G LTE Cat 4:** 150 Mbps DL / 50 Mbps UL <br> **3G:** 21 Mbps DL / 5.76 Mbps UL <br> **2G:** 236.8 kbps DL/UL |
| **Ethernet** | 2 x RJ45 ports (1 x WAN, 1 x LAN, 10/100 Mbps)                                                                  |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                                                   |
| **Serial**   | **1 x 6-pin terminal block** RS232 & RS485                                                                      |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF), Double stacked tray                                                             |
| **Storage**  | 1 x Micro SD slot (Internal, up to 2 TB)                                                                        |
| **Antenna**  | 2 x SMA for Mobile, 1 x RP-SMA for Wi-Fi                                                                        |

## 2. Serial & Industrial Protocols

- **RS232/RS485 Interface:**
  - _Connector:_ 6-pin terminal block (D+, D-, GND, TX, RX, GND)
  - _Serial Functions:_ Console, Serial over IP, Modem, Modbus gateway, NTRIP Client
- **Supported Protocols:**
  - **Modbus:** TCP/RTU (Server/Client), MQTT Gateway
  - **OPC UA:** Client & Server (TCP)
  - **BACnet:** Router (RS485, TCP)
  - **DNP3:** TCP Master, Outstation (RS232, RS485, TCP)
  - **DLMS/COSEM:** Client (TCP), hỗ trợ quét đối tượng COSEM
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature           | Specification                               |
| :---------------- | :------------------------------------------ | ------------ |
| **Power Input**   | **9 – 57 VDC** (2-pin industrial DC socket) |
| **PoE (Active)**  | 802.3af Class 0 (12.94 W) via LAN port      |
| **PoE (Passive)** | 16-57 VDC via spare pairs 4,5 (+) / 7,8 (-) |
| **Consumption**   | Idle: < 2 W                                 | Max: < 3.5 W |
| **Housing**       | Anodized aluminum housing and panels, IP30  |
| **Dimensions**    | 83 x 25 x 83 mm                             |
| **Weight**        | 132 g                                       |
| **Environment**   | Operating Temp: **-40°C to 75°C**           |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Wi-Fi WAN, Mobile, VRRP), Load balancing, Captive Portal
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, CB, RCM, EAC, UCRF"
  "# RUTM59 – Industrial 5G Cellular Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                        |
| :------------ | :--------------------------------------------------------------------------------------------------- |
| **CPU**       | MediaTek Dual-Core, 880 MHz, MIPS1004Kc                                                              |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                                        |
| **Mobile**    | **5G Sub-6 GHz SA/NSA:** 3.4 Gbps DL / 900 Mbps UL <br> **4G LTE Cat 19:** 1.6 Gbps DL / 200 Mbps UL |
| **Ethernet**  | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100/1000 Mbps)                                                  |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF), Auto-switch, SIM idle protection                                     |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                                      |
| **Expansion** | 1 x USB 2.0 A-type (Samba share, USB-to-serial)                                                      |
| **Antenna**   | 4 x SMA (Mobile), 1 x SMA (GNSS)                                                                     |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                                     |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP) với tính năng quét đối tượng tự động
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Security:** Port-based 802.1x, SSL Certificate management, Attack prevention
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | --------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: 5 W                                    | Max: 18 W |
| **Housing**       | Aluminium housing, IP30 rating               |
| **Dimensions**    | 132 x 44.2 x 95 mm                           |
| **Weight**        | 530 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Network backup), Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** FCC, ISED (North America), WEEE"
  "# RUT976 – Industrial 5G Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                  |
| :------------ | :--------------------------------------------------------------------------------------------- |
| **CPU**       | Mediatek, 580 MHz, MIPS 24KEC                                                                  |
| **Memory**    | **RAM:** 128 MB, DDR2 <br> **Flash:** 32 MB NOR Flash                                          |
| **Mobile**    | **5G Sub-6Ghz SA:** 223 Mbps DL / 123 Mbps UL <br> **4G LTE Cat 4:** 195 Mbps DL / 105 Mbps UL |
| **Ethernet**  | 4 x RJ45 ports (1 x WAN, 3 x LAN, 10/100 Mbps)                                                 |
| **Wi-Fi**     | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                                  |
| **Serial**    | 1 x DB9 (RS232), 1 x 6-pin industrial socket (RS485)                                           |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF), Auto-switch, eSIM support                                      |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                                |
| **Expansion** | 1 x USB 2.0 A-type, 1 x Internal Micro SD (up to 2 TB)                                         |
| **I/O**       | 2 x Inputs & 2 x Outputs (10-pin), 1 x Digital In/Out (4-pin Power)                            |

## 2. Industrial Protocols & Software

- **Industrial Interfaces:**
  - _RS232:_ DB9 connector (with RTS, CTS flow control)
  - _RS485:_ Full Duplex (4-wire) & Half Duplex (2-wire)
  - _Serial Functions:_ Console, Serial over IP, Modem, Modbus gateway, NTRIP Client
- **Supported Protocols:**
  - **Modbus:** TCP/RTU (Server/Client), MQTT Gateway
  - **OPC UA:** Client & Server (TCP)
  - **BACnet:** Router (RS485, TCP)
  - **DNP3:** TCP Master, Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP, RS232, RS485) với tính năng quét đối tượng
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT/Kinesis) via Lua scripting

## 3. Power & Physical

| Feature         | Specification                               |
| :-------------- | :------------------------------------------ | ---------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial DC socket) |
| **Consumption** | Idle: < 3 W                                 | Max: < 7 W |
| **Protection**  | Ingress Protection: IP30                    |
| **Housing**     | Aluminum housing, plastic panels            |
| **Dimensions**  | 110 x 50 x 100 mm                           |
| **Weight**      | 295 g                                       |
| **Environment** | Operating Temp: **-40°C to 75°C**           |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Security:** Port-based 802.1x, SSL Certificate management, Web filter
- **Connectivity:** Failover (Network backup), Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)"
  "# RUT271 – Industrial RedCap 5G Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                  |
| :----------- | :--------------------------------------------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                                                  |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 32 MB NOR Flash                                          |
| **Mobile**   | **5G Sub-6Ghz SA:** 223 Mbps DL / 123 Mbps UL <br> **4G LTE Cat 4:** 195 Mbps DL / 105 Mbps UL |
| **Ethernet** | 2 x RJ45 ports (1 x WAN, 1 x LAN, 10/100 Mbps)                                                 |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                                  |
| **SIM**      | 1 x SIM slot (Mini SIM - 2FF)                                                                  |
| **Antenna**  | 2 x SMA for Mobile, 1 x RP-SMA for Wi-Fi                                                       |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                               |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), MQTT Gateway
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP)
  - **DLMS/COSEM:** Client (TCP) với tính năng quét đối tượng tự động
- **MQTT:** Broker, Publisher, MQTT Gateway
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | -------- |
| **Power Input**   | **9 – 30 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-30 VDC) via LAN1 port |
| **Consumption**   | Idle: 1.5 W                                  | Max: 3 W |
| **Housing**       | Aluminum housing, plastic panels, IP30       |
| **Dimensions**    | 83 x 25 x 74 mm                              |
| **Weight**        | 130 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Network backup), Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, FCC, ISED, CB, WEEE"
  "# RUTC50 – High-Speed Industrial 5G Wi-Fi 6 Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                        |
| :------------ | :--------------------------------------------------------------------------------------------------- |
| **CPU**       | Mediatek, Dual-core, 1.3 GHz, ARM Cortex A53                                                         |
| **Memory**    | **RAM:** 512 MB, DDR3 <br> **Flash:** 16 MB NOR + 512 MB NAND                                        |
| **Mobile**    | **5G Sub-6 GHz SA/NSA:** 3.4 Gbps DL / 900 Mbps UL <br> **4G LTE Cat 19:** 1.6 Gbps DL / 200 Mbps UL |
| **Ethernet**  | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100/1000 Mbps)                                                  |
| **Wi-Fi**     | IEEE 802.11b/g/n/ac/ax (Wi-Fi 6), Dual Band, MU-MIMO, 512 users                                      |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF) + **eSIM** support                                                    |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                                      |
| **Expansion** | 1 x USB 2.0 A-type, **Docker Support**                                                               |
| **Antenna**   | 4 x SMA (Mobile), 3 x RP-SMA (Wi-Fi), 1 x SMA (GNSS)                                                 |

## 2. Industrial Protocols & Software

- **Industrial Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP)
  - **DLMS/COSEM:** Client (TCP, USB)
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub (Plug & Play), AWS IoT Core, ThingWorx, Cumulocity
- **Advanced Features:** isolated application deployment via **Docker containers**
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting

## 3. Power & Physical

| Feature           | Specification                                              |
| :---------------- | :--------------------------------------------------------- | ------------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)                |
| **PoE (Passive)** | Passive PoE (Mode B, 9-30 VDC) via LAN1 port               |
| **I/O**           | 1 x Digital Input, 1 x Digital Output (on power connector) |
| **Consumption**   | Idle: < 4.5 W                                              | Max: < 13.5 W |
| **Housing**       | Anodized aluminum housing and panels, IP30                 |
| **Dimensions**    | 130.4 x 42.6 x 103.4 mm                                    |
| **Weight**        | 452 g                                                      |
| **Environment**   | Operating Temp: **-40°C to 75°C**                          |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Wi-Fi WAN, Mobile, VRRP), Load balancing, Captive Portal
- **Certifications:** CE, UKCA, REACH, RoHS, **ECE R118**, **ECE R10 (E-mark)**
- **OS:** RutOS (OpenWrt based Linux OS)"
  "# RUT301 – Industrial Ethernet Router

## 1. System Core & Interfaces

| Feature      | Specification                                              |
| :----------- | :--------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                              |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB serial NOR     |
| **Ethernet** | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100 Mbps)             |
| **USB**      | 1 x USB 2.0 A-type (Samba share, USB-to-serial)            |
| **I/O**      | 2 x Configurable digital I/O pins on 4-pin power connector |
| **LEDs**     | 1 x WAN type, 4 x LAN status, 1 x Power                    |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS:** Client (TCP, USB) - Standard protocol for utility meter data exchange
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **IoT Platforms:** Azure IoT Hub (Direct method & PnP), Cumulocity (Cloud of Things)
- **Security:** Port-based 802.1x, SSL Certificate management, Firewall (Zone-based)
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature           | Specification                               |
| :---------------- | :------------------------------------------ | ---------- |
| **Power Input**   | **9 – 30 VDC** (4-pin industrial DC socket) |
| **PoE (Passive)** | Passive PoE (Optional, Mode B)              |
| **Consumption**   | Idle: 0.8 W                                 | Max: 3.8 W |
| **Housing**       | Aluminium housing, IP30 rating              |
| **Dimensions**    | 100 x 30 x 85 mm                            |
| **Weight**        | 233 g                                       |
| **Environment**   | Operating Temp: **-40°C to 75°C**           |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (VRRP, Wired), Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** Giteki, RoHS, REACH, CE, FCC, IC, RCM, CB"
  "# RUT142 – Industrial RS232 Router

## 1. System Core & Interfaces

| Feature      | Specification                                                 |
| :----------- | :------------------------------------------------------------ |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                 |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB serial NOR        |
| **Ethernet** | 2 x RJ45 ports (1 x WAN, 1 x LAN, 10/100 Mbps)                |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA) |
| **Serial**   | **1 x DB9 (RS232)**                                           |
| **Antenna**  | 1 x RP-SMA connector (Wi-Fi)                                  |
| **LEDs**     | 1 x Power, 1 x WAN status, 1 x LAN status                     |

## 2. Serial & Industrial Protocols

- **RS232 Interface:**
  - _Connector:_ DB9 socket (with RTS, CTS flow control)
  - _Modes:_ Console, Serial over IP, Modem, Modbus gateway, NTRIP Client
- **Supported Protocols:**
  - **Modbus:** TCP/RTU (Server/Client), MQTT Gateway
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, RTU)
  - **DLMS/COSEM:** Client (TCP, RTU)
- **MQTT:** Broker, Publisher, Azure MQTT
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **IoT Platforms:** Azure IoT Hub, Cumulocity (Cloud of Things)

## 3. Power & Physical

| Feature           | Specification                                          |
| :---------------- | :----------------------------------------------------- | ---------- |
| **Power Input**   | **9 – 30 VDC** (3-pin pluggable terminal block)        |
| **PoE (Passive)** | Passive PoE (Mode B, 9-30 VDC) via LAN1 port           |
| **Consumption**   | Idle: < 1 W                                            | Max: < 2 W |
| **Housing**       | Aluminium housing, IP30 rating                         |
| **Dimensions**    | 113.1 x 25 x 68.6 mm                                   |
| **Mounting**      | **Integrated DIN rail bracket**, Wall mount (optional) |
| **Environment**   | Operating Temp: **-40°C to 75°C**                      |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, RCM, FCC, IC, CB, WEEE, RoHS"
  "# RUT140 – Industrial Ethernet Router

## 1. System Core & Interfaces

| Feature      | Specification                                                 |
| :----------- | :------------------------------------------------------------ |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                 |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB serial NOR        |
| **Ethernet** | 2 x RJ45 ports (1 x WAN, 1 x LAN, 10/100 Mbps)                |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA) |
| **Antenna**  | 1 x RP-SMA connector (Wi-Fi)                                  |
| **LEDs**     | 1 x Power, 1 x WAN status, 1 x LAN status                     |
| **Reset**    | Reboot/User default reset/Factory reset button                |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP)
  - **DLMS/COSEM:** Client (TCP)
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **IoT Platforms:** Azure IoT Hub (Direct method & PnP), Cumulocity (Cloud of Things)
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support
- **Security:** Port-based 802.1x, SSL Certificate management, Firewall (Zone-based)

## 3. Power & Physical

| Feature           | Specification                                          |
| :---------------- | :----------------------------------------------------- | ---------- |
| **Power Input**   | **9 – 30 VDC** (3-pin pluggable terminal block)        |
| **PoE (Passive)** | Passive PoE (Mode B, 9-30 VDC) via LAN1 port           |
| **Consumption**   | Idle: < 1 W                                            | Max: < 2 W |
| **Housing**       | Aluminium housing, IP30 rating                         |
| **Dimensions**    | 113.1 x 25 x 68.6 mm                                   |
| **Weight**        | 142.3 g                                                |
| **Mounting**      | **Integrated DIN rail bracket**, Wall mount (optional) |
| **Environment**   | Operating Temp: **-40°C to 75°C**                      |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Wi-Fi WAN, VRRP, Wired), Load balancing, Captive Portal
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, RCM, FCC, IC, CB, WEEE, RoHS"
  "# RUTM51 – Industrial 5G Cellular Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                               |
| :------------ | :------------------------------------------------------------------------------------------ |
| **CPU**       | MediaTek Dual-core, 880 MHz, MIPS1004Kc                                                     |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                               |
| **Mobile**    | **5G Sub-6GHz SA:** 2 Gbps DL / 1 Gbps UL <br> **4G LTE Cat 12:** 600 Mbps DL / 150 Mbps UL |
| **Ethernet**  | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100/1000 Mbps)                                         |
| **Wi-Fi**     | IEEE 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO                                    |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF), Auto-switch, SIM idle protection                            |
| **Expansion** | 1 x USB 2.0 A-type (Storage, USB-to-serial)                                                 |
| **Antenna**   | 4 x SMA (Mobile), 2 x RP-SMA (Wi-Fi)                                                        |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                            |

## 2. Serial & Industrial Protocols

- **Industrial Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP) - Standard utility meter protocol
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | --------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: 5 W                                    | Max: 18 W |
| **Housing**       | Anodized aluminum housing and panels, IP30   |
| **Dimensions**    | 132 x 44.2 x 95 mm                           |
| **Weight**        | 525 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Certifications:** CE, UKCA, EAC, RCM, WEEE, **UN ECE R10 (E-mark)**
- **OS:** RutOS (OpenWrt based Linux OS)"
  "# RUTM10 – Industrial Ethernet Wi-Fi 5 Router

## 1. System Core & Interfaces

| Feature      | Specification                                                    |
| :----------- | :--------------------------------------------------------------- |
| **CPU**      | MediaTek, Dual-Core, 880 MHz, MIPS1004Kc                         |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND    |
| **Ethernet** | 4 x RJ45 ports (1 x WAN, 3 x LAN, 10/100/1000 Mbps)              |
| **Wi-Fi**    | IEEE 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO         |
| **USB**      | 1 x USB A port (USB 2.0)                                         |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector) |
| **Antenna**  | 2 x RP-SMA female connectors for Wi-Fi                           |
| **LEDs**     | 8 x LAN status, 1 x Power, 2 x Wi-Fi band (2.4G/5G)              |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP, USB) - Standard utility meter data exchange
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **IoT Platforms:** Azure IoT Hub (Direct method), Cumulocity (Cloud of Things)
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | ------------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: < 3.51 W                               | Max: < 8.65 W |
| **Housing**       | Anodized aluminum housing and panels, IP30   |
| **Dimensions**    | 115 x 32.2 x 95.2 mm                         |
| **Weight**        | 359 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Security:** Port-based 802.1x, SSL Certificate management, Web filter
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, RCM, CB, **UN ECE R10 (E-mark)**"
  "# RUTM11 – Industrial 4G LTE Cat 6 Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                   |
| :------------ | :------------------------------------------------------------------------------ |
| **CPU**       | MediaTek Dual-core, 880 MHz, MIPS1004Kc                                         |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                   |
| **Mobile**    | **4G LTE Cat 6:** 300 Mbps DL / 50 Mbps UL <br> **3G:** 42 Mbps DL / 11 Mbps UL |
| **Ethernet**  | 4 x RJ45 ports (1 x WAN, 3 x LAN, 10/100/1000 Mbps)                             |
| **Wi-Fi**     | IEEE 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO                        |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF), Auto-switch, SIM idle protection                |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                 |
| **Expansion** | 1 x USB 2.0 A-type (Samba share, USB-to-serial)                                 |
| **Antenna**   | 2 x SMA (Mobile), 2 x RP-SMA (Wi-Fi), 1 x SMA (GNSS)                            |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS:** Client (TCP, USB) - Standard protocol for utility meter
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | ------------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: 3.9 W                                  | Max: < 12.3 W |
| **Housing**       | Anodized aluminum housing and panels, IP30   |
| **Dimensions**    | 115 x 44.2 x 95.1 mm                         |
| **Weight**        | 460 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Wi-Fi WAN, Mobile, VRRP), Load balancing, Captive Portal
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, EAC, RCM, WEEE, **UN ECE R10 (E-mark)**"
  "# RUTM09 – Industrial 4G LTE Cat 6 Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                     |
| :------------ | :-------------------------------------------------------------------------------- |
| **CPU**       | MediaTek Dual-core, 880 MHz, MIPS1004Kc                                           |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                     |
| **Mobile**    | **4G LTE Cat 6:** 300 Mbps DL / 50 Mbps UL <br> **3G:** 42 Mbps DL / 5.76 Mbps UL |
| **Ethernet**  | 4 x RJ45 ports (1 x WAN, 3 x LAN, 10/100/1000 Mbps)                               |
| **SIM**       | 2 x SIM slots (Mini SIM - 2FF), Auto-switch, SIM idle protection                  |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                   |
| **Expansion** | 1 x USB 2.0 A-type (Samba share, USB-to-serial)                                   |
| **Antenna**   | 2 x SMA (Mobile), 1 x SMA (GNSS)                                                  |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                  |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP, USB) với tính năng quét đối tượng tự động
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | ----------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: 2.65 W                                 | Max: 9.82 W |
| **Housing**       | Anodized aluminum housing and panels, IP30   |
| **Dimensions**    | 115 x 44.2 x 95.1 mm                         |
| **Weight**        | 457 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, RCM, CB"
  "# RUTM08 – Industrial Gigabit Ethernet Router

## 1. System Core & Interfaces

| Feature      | Specification                                                    |
| :----------- | :--------------------------------------------------------------- |
| **CPU**      | MediaTek Dual-Core, 880 MHz, MIPS1004Kc                          |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND    |
| **Ethernet** | 4 x RJ45 ports (1 x WAN, 3 x LAN, 10/100/1000 Mbps)              |
| **USB**      | 1 x USB A port (USB 2.0)                                         |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector) |
| **LEDs**     | 8 x LAN status LEDs, 1 x Power LED                               |
| **Reset**    | Reboot/User default reset/Factory reset button                   |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS/COSEM:** Client (TCP, USB) - Standard utility meter protocol
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **IoT Platforms:** Azure IoT Hub (Direct method), Cumulocity (Cloud of Things)
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support
- **Security:** Port-based 802.1x, SSL Certificate management, Firewall (Zone-based)

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | ------------ |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: < 1.8 W                                | Max: < 5.5 W |
| **Housing**       | Anodized aluminum housing and panels, IP30   |
| **Dimensions**    | 115 x 32.2 x 95.2 mm                         |
| **Weight**        | 353 g                                        |
| **Environment**   | Operating Temp: **-40°C to 75°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, RCM, CB, **UN ECE R10 (E-mark)**"
  "# RUTM52 – Industrial Dual-Modem 5G Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                   |
| :----------- | :---------------------------------------------------------------------------------------------- |
| **CPU**      | MediaTek Dual-core, 880 MHz, MIPS1004Kc                                                         |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB NOR + 256 MB NAND                                   |
| **Mobile**   | **Dual 5G Modems:** 3.3 Gbps DL / 600 Mbps UL <br> **4G LTE Cat 20:** 2.0 Gbps DL / 200 Mbps UL |
| **Ethernet** | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100/1000 Mbps)                                             |
| **Wi-Fi**    | IEEE 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO                                        |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF) + **eSIM** (up to 7 profiles)                                    |
| **GNSS**     | GPS, GLONASS, BeiDou, Galileo, QZSS (NMEA 0183)                                                 |
| **Antenna**  | 8 x SMA (Mobile), 2 x RP-SMA (Wi-Fi), 1 x SMA (GNSS)                                            |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                                |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP)
  - **DLMS/COSEM:** Client (TCP) với tính năng quét đối tượng tự động
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **Location Tracking:** Geofencing, NTRIP, Server support (TAVL, RMS)
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | --------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)  |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port |
| **Consumption**   | Idle: 5 W                                    | Max: 13 W |
| **Housing**       | Anodized aluminum housing and panels, IP30   |
| **Dimensions**    | 132 x 44.2 x 95.1 mm                         |
| **Weight**        | 560 g                                        |
| **Environment**   | Operating Temp: **-40°C to 60°C**            |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, VRF
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** **Dual-Modem Failover**, Load balancing, Captive Portal (Hotspot)
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, EAC, RCM, FCC, IC, UCRF, WEEE"
  "# RUT361 – Industrial LTE Cat 6 Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                     |
| :----------- | :-------------------------------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                                     |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB serial NOR                            |
| **Mobile**   | **4G LTE Cat 6:** 300 Mbps DL / 50 Mbps UL <br> **3G:** 42 Mbps DL / 5.76 Mbps UL |
| **Ethernet** | 2 x RJ45 ports (1 x WAN, 1 x LAN, 10/100 Mbps)                                    |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), 2x2 MIMO, AP & STA modes                              |
| **SIM**      | 1 x SIM slot (Mini SIM - 2FF)                                                     |
| **Antenna**  | 2 x SMA for LTE, 2 x RP-SMA for Wi-Fi                                             |
| **I/O**      | 2 x Programmable I/O pins on 4-pin power connector                                |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), Custom register block requests
  - **OPC UA:** Client & Server (TCP)
  - **DNP3:** Station & Outstation (TCP, USB)
  - **DLMS:** Standard protocol for utility meter data exchange
- **MQTT:** Broker, Publisher, Azure MQTT, MQTT Gateway
- **IoT Platforms:** Azure IoT Hub (Direct method), Cumulocity, ThingWorx
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support
- **Monitoring:** Ping Reboot, Wget Reboot, Periodic Reboot, LCP/ICMP inspection

## 3. Power & Physical

| Feature         | Specification                                                                   |
| :-------------- | :------------------------------------------------------------------------------ | ------------ |
| **Power Input** | **9 – 30 VDC** (4-pin industrial DC socket)                                     |
| **I/O Logic**   | **Input:** 0-6V (low), 8-30V (high) <br> **Output:** Open Collector, 30V, 300mA |
| **Consumption** | Idle: < 2.4 W                                                                   | Max: < 4.7 W |
| **Housing**     | Aluminum housing, IP30 rating                                                   |
| **Dimensions**  | 93.2 x 100 x 30 mm                                                              |
| **Weight**      | 243 g                                                                           |
| **Mounting**    | DIN rail, flat surface placement                                                |
| **Environment** | Operating Temp: **-40°C to 75°C**                                               |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing
- **VPN:** OpenVPN (27 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, Tailscale, DMVPN
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Wi-Fi WAN, Mobile, VRRP), Load balancing, Captive Portal
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, RCM, EAC, WEEE, CB"
  "# TCR100 – Consumer-Friendly 4G+ LTE Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                               |
| :----------- | :---------------------------------------------------------------------------------------------------------- |
| **CPU**      | QCA9531, MIPS 24kc, 650 MHz                                                                                 |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                                                       |
| **Mobile**   | **4G+ (LTE-A) Cat 6:** 300 Mbps DL / 50 Mbps UL <br> **3G:** 42 Mbps DL / 5.76 Mbps UL                      |
| **Ethernet** | 2 x RJ45 ports (1 x WAN, 1 x LAN, 10/100 Mbps)                                                              |
| **Wi-Fi**    | **Dual Band:** 2.4 GHz (2x2 MIMO) & 5 GHz (1x1 MIMO) <br> **Security:** WPA3-SAE, WPA2-Enterprise, AP & STA |
| **SIM**      | 1 x SIM slot (Mini SIM - 2FF) với cơ chế kim chọc                                                           |
| **Antenna**  | 2 x SMA for LTE, 3 x Internal for Wi-Fi (2.4G/5G)                                                           |
| **Buttons**  | WPS, Wi-Fi On/Off, Reset                                                                                    |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP Slave (ID filtering, Custom registers), TCP Master
  - **MQTT Gateway:** Send commands/receive data from Modbus Master
  - **DNP3:** Station & Outstation (TCP Master)
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT/Kinesis)
- **IoT Platforms:** Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity
- **Monitoring:** Ping Reboot, Wget reboot, Periodic Reboot, LCP/ICMP inspection
- **Security:** Port forwards, Traffic rules, NAT, DMZ, Attack prevention (DDOS)

## 3. Power & Physical

| Feature         | Specification                                     |
| :-------------- | :------------------------------------------------ | ---------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial DC socket)       |
| **Consumption** | Average: 3.7 W                                    | Max: 9.3 W |
| **Housing**     | Plastic housing with aluminum screws and heatsink |
| **Dimensions**  | 150 x 37 x 105 mm                                 |
| **Weight**      | 376 g                                             |
| **Mounting**    | Flat surface placement                            |
| **Environment** | Operating Temp: **-40°C to 75°C**                 |

## 4. Network & Security Features

- **Routing:** Static routes, Dynamic routes
- **VPN:** OpenVPN (12 methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, DMVPN, PPTP, L2TP
- **Firewall:** Pre-configured rules via WebUI, Unlimited configuration via CLI
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Mobile, Wired, Wi-Fi WAN), Load balancing, Captive Portal
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** TBD (Designed for EMEA, APAC, Brazil, Malaysia markets)"
  "# RUTXR1 – Industrial Enterprise Rack-Mounted Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                     |
| :----------- | :-------------------------------------------------------------------------------- |
| **CPU**      | Quad-core ARM Cortex A7, 717 MHz                                                  |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 256 MB SPI Flash                            |
| **Mobile**   | **4G LTE Cat 6:** 300 Mbps DL / 50 Mbps UL <br> **3G:** 42 Mbps DL / 5.76 Mbps UL |
| **Ethernet** | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100/1000 Mbps)                               |
| **Fiber**    | 1 x SFP port (1 Gbps)                                                             |
| **Wi-Fi**    | IEEE 802.11b/g/n/ac Wave 2 (WiFi 5), MU-MIMO, up to 150 users                     |
| **Serial**   | 1 x RJ45 Console port (Full RS232 with RTS, CTS)                                  |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF), Auto-failover                                     |
| **USB**      | 1 x USB A port (USB 2.0)                                                          |
| **Antenna**  | 2 x SMA for LTE, 2 x RP-SMA for Wi-Fi                                             |

## 2. Serial & Industrial Protocols

- **Supported Protocols:**
  - **Modbus:** TCP Slave/Master, RTU Master Console
  - **MQTT Gateway:** Modbus Master through MQTT broker
  - **Data Collection:** Data to Server (HTTP/HTTPS/MQTT/Kinesis) via Lua scripting
- **IoT Platforms:** Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity
- **Serial Functions:** Console, Modbus gateway, RTU Master, Serial OverIP, Ntrip client
- **Monitoring:** Ping Reboot, Wget reboot, Periodic Reboot, LCP/ICMP inspection

## 3. Power & Physical

| Feature         | Specification                                              |
| :-------------- | :--------------------------------------------------------- | ----------- |
| **Power Input** | **9 – 50 VDC** (Redundant 2 x 4-pin industrial DC sockets) |
| **Consumption** | Idle: < 3 W                                                | Max: < 18 W |
| **Housing**     | Full steel housing                                         |
| **Dimensions**  | 272 x 42.6 x 122.6 mm (1U Rackmount ready)                 |
| **Weight**      | 1050 g                                                     |
| **Environment** | Operating Temp: **-40°C to 75°C**                          |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP
- **VPN:** OpenVPN (12 methods), IPsec (IKEv1/v2), **WireGuard**, Zerotier, DMVPN, SSTP
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Mobile, Wired, Fiber, Wi-Fi WAN), Load balancing
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** CE, UKCA, RCM, EAC, WEEE"
  "# RUTM50 – Industrial 5G Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                        |
| :----------- | :--------------------------------------------------------------------------------------------------- |
| **CPU**      | MediaTek MT7621A, Dual-Core, 880 MHz, MIPS1004Kc                                                     |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB serial NOR + 256 MB serial NAND                          |
| **Mobile**   | **5G Sub-6 GHz SA/NSA:** 3.4 Gbps DL / 900 Mbps UL <br> **4G LTE Cat 19:** 1.6 Gbps DL / 200 Mbps UL |
| **Ethernet** | 5 x RJ45 ports (1 x WAN, 4 x LAN, 10/100/1000 Mbps)                                                  |
| **Wi-Fi**    | IEEE 802.11b/g/n/ac Wave 2 (Wi-Fi 5), MU-MIMO, up to 150 users                                       |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF), Auto-Failover                                                        |
| **GNSS**     | GPS, GLONASS, BeiDou, Galileo, QZSS                                                                  |
| **USB**      | 1 x USB A port (USB 2.0)                                                                             |
| **Antenna**  | 4 x SMA (Mobile), 2 x RP-SMA (Wi-Fi), 1 x SMA (GNSS)                                                 |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Modbus:** TCP (Server/Client), RTU Master (via USB), Custom registers
  - **BACnet:** Router (TCP)
  - **OPC UA:** Client, Server (planned)
  - **DNP3:** Station, Outstation (TCP, USB)
- **MQTT:** Broker, Publisher, Azure MQTT, **Modbus MQTT Gateway**
- **IoT Platforms:** Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity
- **Location Tracking:** GNSS coordinates via WebUI/SMS/TAVL/RMS, Geofencing
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting
- **Network Services:** Teltonika Networks Web API (beta) support

## 3. Power & Physical

| Feature           | Specification                                                  |
| :---------------- | :------------------------------------------------------------- | ----------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket)                    |
| **PoE (Passive)** | Passive PoE (Mode B, 9-50 VDC) via LAN1 port                   |
| **I/O**           | 1 x Digital Input, 1 x Digital Output (Open Collector, 300 mA) |
| **Consumption**   | Idle: < 5 W                                                    | Max: < 18 W |
| **Housing**       | Aluminum housing, IP30 rating                                  |
| **Dimensions**    | 132 x 44.2 x 95.1 mm                                           |
| **Weight**        | 519 g                                                          |
| **Environment**   | Operating Temp: **-40°C to 75°C**                              |

## 4. Network & Security Features

- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing, NHRP
- **VPN:** OpenVPN (27 methods), IPsec, **WireGuard**, ZeroTier, DMVPN, L2TP, PPTP
- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, DMZ, Attack prevention
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), FOTA, TR-069
- **Connectivity:** Failover (Wi-Fi WAN, Mobile, VRRP), Load balancing
- **OS:** RutOS (OpenWrt based Linux OS)
- **Certifications:** FCC, IC, PTCRB, AT&T (Operator)"
  "# RUTX10 – Enterprise Gigabit Ethernet Router

## 1. System Core & Interfaces

| Feature       | Specification                                                       |
| :------------ | :------------------------------------------------------------------ |
| **CPU**       | Quad-core ARM Cortex A7, 717 MHz                                    |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 256 MB, SPI Flash             |
| **Ethernet**  | 1 x WAN, 3 x LAN (10/100/1000 Mbps, Auto MDI/MDIX)                  |
| **Wi-Fi**     | 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO, up to 867 Mbps |
| **Bluetooth** | Bluetooth 4.0 Low Energy (LE)                                       |
| **USB**       | 1 x USB A 2.0 (Samba, USB-to-serial, External HDD/Modem)            |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket)       |
| **Antenna**   | 2 x RP-SMA for Wi-Fi, 1 x RP-SMA for Bluetooth                      |

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID range 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** DNP3 (Master/Outstation), DLMS, MQTT (Broker/Publisher), SNMP (v1/v2/v3)
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP, Policy based routing
- **VPN:** OpenVPN (27 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN, SSTP, Tinc
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH)
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- |
| **Power Input** | **9 – 50 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                        |
| **Consumption** | Max: < 9 W                                                                       |
| **Housing**     | Aluminum housing, IP30 rating                                                    |
| **Dimensions**  | 115 x 32.2 x 95.2 mm                                                             |
| **Weight**      | 355 g                                                                            |
| **Mounting**    | DIN rail, Flat surface placement                                                 |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                |

## 4. Security & Safety

- **Firewall:** Port forward, Traffic rules, Custom rules, NAT, NAT-T, DMZ
- **Attack Prevention:** DDOS prevention (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **Authentication:** Pre-shared key, Digital certificates, X.509, TACACS+, Radius
- **VLAN:** Port and tag-based VLAN separation
- **Web Filter:** Blacklist/Whitelist (sites/URLs)
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control"
  "# RUT951 – Industrial 4G LTE Router

## 1. System Core & Interfaces

| Feature      | Specification                                                 |
| :----------- | :------------------------------------------------------------ |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEc                                 |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB, SPI Flash        |
| **Mobile**   | **4G LTE Cat 4** (Up to 150 Mbps), 3G, 2G                     |
| **SIM**      | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch cases         |
| **Ethernet** | 1 x WAN 10/100 Mbps, 3 x LAN 10/100 Mbps (Auto MDI/MDIX)      |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP), Station (STA)  |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket) |
| **Antenna**  | 2 x SMA for LTE, 2 x RP-SMA for Wi-Fi                         |

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** DNP3 (TCP Master, Outstation), MQTT (Broker/Publisher), SNMP (v1/v2/v3)
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP, Policy based routing
- **VPN:** OpenVPN (27 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, DMVPN, SSTP, Tinc
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH), SMS/Call utilities
- **IoT Platforms:** Clouds of things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- | ---------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                        |
| **Consumption** | Idle: < 2 W                                                                      | Max: < 7 W |
| **Housing**     | Aluminium housing with plastic panels, IP30 rating                               |
| **Dimensions**  | 110 x 50 x 100 mm                                                                |
| **Weight**      | 287 g                                                                            |
| **Mounting**    | **DIN rail** (two-sided mounting), Flat surface                                  |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                |

## 4. Security & Safety

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **Mobile Control:** Data limit/Quota control, SMS limit, Roaming protection
- **VLAN:** Port and tag-based separation
- **Web Filter:** Blacklist/Whitelist for websites
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control"
  "# RUT901 – Industrial 4G LTE Router

## 1. System Core & Interfaces

| Feature      | Specification                                                 |
| :----------- | :------------------------------------------------------------ |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEc                                 |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB, SPI Flash        |
| **Mobile**   | **4G LTE Cat 4** (Up to 150 Mbps), 3G, 2G                     |
| **SIM**      | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch               |
| **Ethernet** | 1 x WAN 10/100 Mbps, 3 x LAN 10/100 Mbps (Auto MDI/MDIX)      |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP), Station (STA)  |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket) |
| **Antenna**  | 2 x SMA for LTE, 2 x RP-SMA for Wi-Fi                         |

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** DNP3 (TCP Master, Outstation), MQTT (Broker/Publisher), SNMP (v1/v2/v3)
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP, Policy based routing
- **VPN:** OpenVPN (27 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, DMVPN, SSTP, Tinc
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH), SMS/Call utilities
- **IoT Platforms:** Clouds of things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- | ---------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                        |
| **Consumption** | Idle: < 2 W                                                                      | Max: < 7 W |
| **Housing**     | Aluminium housing with plastic panels, IP30 rating                               |
| **Dimensions**  | 110 x 50 x 100 mm                                                                |
| **Weight**      | 297 g                                                                            |
| **Mounting**    | **DIN rail** (two-sided mounting), Flat surface                                  |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                |

## 4. Security & Safety

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **Mobile Control:** Data limit/Quota control, SMS limit, Roaming protection
- **Wi-Fi Security:** WPA3-SAE, WPA2-EAP, WPA3-EAP, OWE, AES-CCMP, TKIP
- **VLAN:** Port and tag-based separation
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control"
  "# RUT300 – Industrial Ethernet Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                           |
| :------------ | :-------------------------------------------------------------------------------------- |
| **CPU**       | QCA9531, MIPS 24kc, 650 MHz                                                             |
| **Memory**    | **RAM:** 64 MB, DDR2 <br> **Flash:** 16 MB, SPI Flash                                   |
| **Ethernet**  | 1 x WAN, 4 x LAN (10/100 Mbps, Auto MDI/MDIX)                                           |
| **USB**       | 1 x USB A 2.0 (Samba, USB-to-serial, External HDD/Modem)                                |
| **I/O**       | 2 x Configurable Digital Input/Output (on 4-pin power socket)                           |
| **I/O Specs** | **Output:** Open collector, max 30 V, 300 mA <br> **Input:** 0-6 V (Low), 8-30 V (High) |

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** DNP3 (TCP Master, Outstation), MQTT (Broker/Publisher), SNMP (v1/v2/v3)
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP, Policy based routing
- **VPN:** OpenVPN (27 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, DMVPN, SSTP, Tinc
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH)
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- | -------- |
| **Power Input** | **7 – 30 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                        |
| **Consumption** | Idle: 1.3 W                                                                      | Max: 3 W |
| **Housing**     | Aluminum housing, IP30 rating                                                    |
| **Dimensions**  | 100 x 30 x 85 mm                                                                 |
| **Weight**      | 229 g                                                                            |
| **Mounting**    | DIN rail, Flat surface placement                                                 |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                |

## 4. Security & Management

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **Authentication:** Pre-shared key, Digital certificates, X.509, TACACS+, Radius
- **VLAN:** Port and tag-based VLAN separation
- **Web Filter:** Blacklist/Whitelist (sites/URLs)
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control
- **OS:** RutOS (OpenWrt based Linux OS)"
  "# RUT260 – Compact Industrial 4G LTE Cat 6 Router

## 1. System Core & Interfaces

| Feature      | Specification                                                 |
| :----------- | :------------------------------------------------------------ |
| **CPU**      | Mediatek, 580 MHz, MIPS 24Kc                                  |
| **Memory**   | **RAM:** 128 MB, DDR3 <br> **Flash:** 16 MB, SPI Flash        |
| **Mobile**   | **4G LTE Cat 6** (Up to 300 Mbps), 3G                         |
| **SIM**      | 1 x SIM slot (Mini SIM - 2FF), eSIM (Optional)                |
| **Ethernet** | 1 x WAN 10/100 Mbps, 1 x LAN 10/100 Mbps (Auto MDI/MDIX)      |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP), Station (STA)  |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket) |
| **Antenna**  | 2 x SMA for LTE, 1 x RP-SMA for Wi-Fi                         |

## 2. Network & Industrial Protocols

- **Modbus:** TCP Server/Client, MQTT Gateway, Custom registers
- **Supported Protocols:** OPC UA (Client/Server), DNP3 (Station/Outstation), MQTT, SNMP (v1/v2/v3)
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP, Policy based routing
- **VPN:** OpenVPN (27 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, DMVPN, SSTP, Tinc
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH), SMS/Call utilities
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- | ------------ |
| **Power Input** | **9 – 30 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (LAN port, Mode B, 9-30 VDC)                                         |
| **Consumption** | Idle: < 2 W                                                                      | Max: < 6.5 W |
| **Housing**     | Aluminium housing with plastic panels, IP30 rating                               |
| **Dimensions**  | 83 x 25 x 74 mm                                                                  |
| **Weight**      | 130 g                                                                            |
| **Mounting**    | DIN rail, Flat surface placement                                                 |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                |

## 4. Security & Safety

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **Wi-Fi Security:** WPA3-SAE, WPA3-EAP, WPA2-Enterprise-PEAP, WPA2-PSK, OWE
- **Mobile Control:** Data limit/Quota control, SMS limit, Roaming protection
- **VLAN:** Port and tag-based VLAN separation
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control"
  "# RUTX14 – Industrial 4G LTE Cat 12 Router

## 1. System Core & Interfaces

| Feature       | Specification                                                 |
| :------------ | :------------------------------------------------------------ |
| **CPU**       | Quad-core ARM Cortex A7, 717 MHz                              |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 256 MB, SPI Flash       |
| **Mobile**    | **4G LTE Cat 12** (Up to 600 Mbps), 3G                        |
| **SIM**       | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch               |
| **Ethernet**  | 1 x WAN, 4 x LAN (10/100/1000 Mbps, Auto MDI/MDIX)            |
| **Wi-Fi**     | 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO, 867 Mbps |
| **Bluetooth** | Bluetooth 4.0 Low Energy (LE)                                 |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS                           |
| **USB**       | 1 x USB A 2.0 (Samba, USB-to-serial, External HDD/Modem)      |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket) |

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** MQTT (Broker/Publisher), SNMP (v1/v2/v3), DNP3, DLNA
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP
- **VPN:** OpenVPN (12 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN, SSTP
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH), SMS/Call utilities
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- | ----------- |
| **Power Input** | **9 – 50 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (LAN1 port, Mode B, Not IEEE 802.3af/at/bt compatible)               |
| **Consumption** | Idle: < 4 W                                                                      | Max: < 22 W |
| **Housing**     | Full aluminium housing, IP30 rating                                              |
| **Dimensions**  | 132 x 44 x 95 mm                                                                 |
| **Weight**      | 515 g                                                                            |
| **Mounting**    | **DIN rail** (two-sided), Flat surface placement                                 |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                |

## 4. Security & Location Tracking

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **Wi-Fi Security:** WPA3-SAE, WPA3-EAP, WPA2-Enterprise-PEAP, WPA2-PSK, OWE
- **VLAN:** Port and tag-based VLAN separation
- **Tracking:** GNSS coordinates via WebUI, SMS, TAVL, RMS; Geofencing
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control"
  "# RUTX12 – Industrial Dual 4G LTE Cat 6 Router

## 1. System Core & Interfaces

| Feature       | Specification                                                 |
| :------------ | :------------------------------------------------------------ |
| **CPU**       | Quad-core ARM Cortex A7, 717 MHz                              |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 256 MB, SPI Flash       |
| **Mobile**    | **2 x 4G LTE Cat 6 modems** (Up to 300 Mbps each), 3G         |
| **SIM**       | **2 x SIM slots** (Mini SIM - 2FF), Dual simultaneous modems  |
| **Ethernet**  | 1 x WAN, 4 x LAN (10/100/1000 Mbps, Auto MDI/MDIX)            |
| **Wi-Fi**     | 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO, 867 Mbps |
| **Bluetooth** | Bluetooth 4.0 Low Energy (LE)                                 |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS                           |
| **USB**       | 1 x USB A 2.0 (Samba, USB-to-serial, External HDD/Modem)      |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket) |

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** MQTT (Broker/Publisher), SNMP (v1/v2/v3), DNP3 (Master/Outstation), NTRIP
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, NHRP
- **VPN:** OpenVPN (27 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN, SSTP, Tinc
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH), SMS/Call utilities
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- | ----------- |
| **Power Input** | **9 – 50 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-50 VDC)                                        |
| **Consumption** | Idle: < 4 W                                                                      | Max: < 22 W |
| **Housing**     | Full aluminium housing, IP30 rating                                              |
| **Dimensions**  | 132 x 44.2 x 95.1 mm                                                             |
| **Weight**      | 540 g                                                                            |
| **Mounting**    | **DIN rail** (two-sided), Flat surface placement                                 |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                |

## 4. Security & Location Tracking

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **Wi-Fi Security:** WPA2-Enterprise (PEAP), WPA2-PSK, WEP, client separation
- **VLAN:** Port and tag-based VLAN separation
- **Tracking:** GNSS coordinates via WebUI, SMS, TAVL, RMS; Geofencing; NMEA 0183
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control, IP/Login block"
  "# RUTX11 – Industrial 4G LTE Cat 6 Router

## 1. System Core & Interfaces

| Feature       | Specification                                                        |
| :------------ | :------------------------------------------------------------------- |
| **CPU**       | Quad-core ARM Cortex A7, 717 MHz                                     |
| **Memory**    | **RAM:** 256 MB, DDR3 <br> **Flash:** 256 MB, SPI Flash              |
| **Mobile**    | **4G LTE Cat 6** (Up to 300 Mbps), 3G                                |
| **SIM**       | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch, SIM idle protection |
| **Ethernet**  | 1 x WAN, 3 x LAN (10/100/1000 Mbps, Auto MDI/MDIX)                   |
| **Wi-Fi**     | 802.11b/g/n/ac Wave 2 (Wi-Fi 5), Dual Band, MU-MIMO, 867 Mbps        |
| **Bluetooth** | Bluetooth 4.0 Low Energy (LE)                                        |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS                                  |
| **USB**       | 1 x USB A 2.0 (Samba, USB-to-serial, External HDD/Modem)             |
| **I/O**       | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket)        |

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** MQTT (Broker/Publisher), SNMP (v1/v2/v3), DNP3, DLMS, NTRIP
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP, Policy based routing
- **VPN:** OpenVPN (27 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN, SSTP, Tinc
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH), SMS/Call utilities
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature           | Specification                                                                    |
| :---------------- | :------------------------------------------------------------------------------- |
| **Power Input**   | **9 – 50 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **Special Power** | **Railway version:** 24-36 VDC (RUTX11 020G00)                                   |
| **PoE**           | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                        |
| **Consumption**   | Max: < 16 W                                                                      |
| **Housing**       | Aluminum housing, IP30 rating                                                    |
| **Dimensions**    | 115 x 44.2 x 95.1 mm                                                             |
| **Weight**        | 456 g                                                                            |
| **Mounting**      | DIN rail, Flat surface placement                                                 |
| **Environment**   | Operating Temp: **-40°C to 75°C**                                                |

## 4. Security & Location Tracking

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **Wi-Fi Security:** WPA2-Enterprise (PEAP), WPA2-PSK, WEP, client separation
- **VLAN:** Port and tag-based VLAN separation
- **Tracking:** GNSS coordinates via WebUI, SMS, TAVL, RMS; Geofencing; NMEA 0183
- **Certifications:** Railway (EN 50155, EN 50121), CE/RED, FCC, IC, PTCRB, UL/CSA"
  "# RUTX09 – Industrial 4G LTE Cat 6 Router

## 1. System Core & Interfaces

| Feature      | Specification                                                 |
| :----------- | :------------------------------------------------------------ |
| **CPU**      | Quad-core ARM Cortex A7, 717 MHz                              |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 256 MB, SPI Flash       |
| **Mobile**   | **4G LTE Cat 6** (Up to 300 Mbps), 3G                         |
| **SIM**      | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch               |
| **Ethernet** | 1 x WAN, 3 x LAN (10/100/1000 Mbps, Auto MDI/MDIX)            |
| **GNSS**     | GPS, GLONASS, BeiDou, Galileo, QZSS                           |
| **USB**      | 1 x USB A 2.0 (Samba, USB-to-serial, External HDD/Modem)      |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket) |
| **Antenna**  | 2 x SMA for LTE, 1 x SMA for GNSS                             |

[Image of RUTX09 industrial cellular router front and back panels showing interfaces]

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** MQTT (Broker/Publisher), SNMP (v1/v2/v3), DNP3, NTRIP, HTTP(S)
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP, Policy based routing
- **VPN:** OpenVPN (12 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN, SSTP
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH), SMS/Call utilities
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- |
| **Power Input** | **9 – 50 VDC** (4-pin industrial DC socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (LAN port, Mode B, Not IEEE 802.3af/at/bt compatible)                |
| **Consumption** | Max: < 9 W                                                                       |
| **Housing**     | Aluminium housing, IP30 rating                                                   |
| **Dimensions**  | 115 x 44.2 x 95.1 mm                                                             |
| **Weight**      | 455 g                                                                            |
| **Mounting**    | **DIN rail**, Flat surface placement                                             |
| **Environment** | Operating Temp: **-40°C to 75°C**                                                |

[Image of RUTX09 4-pin industrial DC power socket pinout]

## 4. Security & Location Tracking

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **VLAN:** Port and tag-based VLAN separation
- **Tracking:** GNSS coordinates via WebUI, SMS, TAVL, RMS; Geofencing; NMEA 0183
- **Mobile Control:** Data limit/Quota control for both SIMs, Black/White list
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control"
  "# RUTX08 – Industrial Gigabit Ethernet Router

## 1. System Core & Interfaces

| Feature          | Specification                                                 |
| :--------------- | :------------------------------------------------------------ |
| **CPU**          | Quad-core ARM Cortex A7, 717 MHz                              |
| **Memory**       | **RAM:** 256 MB, DDR3 <br> **Flash:** 256 MB, SPI Flash       |
| **Ethernet**     | 1 x WAN, 3 x LAN (10/100/1000 Mbps, Auto MDI/MDIX)            |
| **USB**          | 1 x USB A 2.0 (Samba, USB-to-serial, External HDD/Modem)      |
| **I/O**          | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket) |
| **Power Socket** | 4-pin industrial DC power socket                              |

[Image of RUTX08 industrial gigabit router front and back panels showing interfaces]

## 2. Network & Industrial Protocols

- **Modbus:** TCP Slave (ID 1-255), TCP Master (01-06, 15, 16 functions), MQTT Gateway
- **Supported Protocols:** MQTT (Broker/Publisher), SNMP (v1/v2/v3), DLNA, HTTP(S)
- **Routing:** Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP, Policy based routing
- **VPN:** OpenVPN (12 encryption methods), IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN, SSTP
- **Monitoring:** Teltonika RMS, FOTA, TR-069, JSON-RPC, Web UI, CLI (SSH), Troubleshoot
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                     |
| :-------------- | :---------------------------------------------------------------- |
| **Power Input** | **9 – 50 VDC** (Reverse polarity & Surge protection)              |
| **PoE**         | Passive PoE (LAN port, Mode B, Not IEEE 802.3af/at/bt compatible) |
| **Consumption** | Max: < 6 W                                                        |
| **Housing**     | Aluminium housing, IP30 rating                                    |
| **Dimensions**  | 115 x 32.2 x 95.2 mm                                              |
| **Weight**      | 345 g                                                             |
| **Mounting**    | **DIN rail**, Flat surface placement                              |
| **Environment** | Operating Temp: **-40°C to 75°C**                                 |

[Image of RUTX08 4-pin industrial DC power socket pinout]

## 4. Security & Safety

- **Firewall:** Port forward, Traffic rules, Custom rules, DMZ, NAT, NAT-T
- **Attack Prevention:** DDOS (SYN flood, SSH/HTTP/HTTPS), Port scan prevention
- **VLAN:** Port and tag-based VLAN separation
- **Web Filter:** Blacklist/Whitelist for websites
- **Access Control:** MAC address filter, TCP/UDP/ICMP packet control
- **Authentication:** Pre-shared key, digital certificates, X.509 certificates"
  "# RUT956 – Industrial 4G (LTE) Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                                                                        |
| :------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CPU**       | Mediatek, 580 MHz, MIPS 24KEC                                                                                                                        |
| **Memory**    | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                                                                                                |
| **Ethernet**  | 1 x WAN, 3 x LAN (10/100 Mbps, Auto MDI/MDIX)                                                                                                        |
| **Wi-Fi**     | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                                                                                        |
| **Mobile**    | 4G (LTE) Cat 4 up to 150 Mbps, 3G, 2G                                                                                                                |
| **SIM Slots** | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch                                                                                                      |
| **Serial**    | 1 x RS232 (DB9), 1 x RS485 (6-pin terminal block)                                                                                                    |
| **I/O**       | **10-pin socket:** 1 x Dry Input, 1 x Isolated Input, 1 x Analog Input, 1 x Relay Output, 1 x OC Output <br> **4-pin socket:** 1 x Input, 1 x Output |
| **USB**       | 1 x USB A port (USB 2.0)                                                                                                                             |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS                                                                                                                  |

## 2. Serial & Industrial Protocols

- **Serial Modes:** Console, Serial over IP, Modem, MODBUS gateway, NTRIP Client
- **Modbus:** TCP/RTU (Master/Slave), Custom registers, MQTT Gateway
- **MQTT:** Broker, Publisher, Azure MQTT, Kinesis
- **DNP3:** TCP Master, Outstation, RTU Master
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                     |
| **Consumption** | Idle: < 2 W                                                                   | Max: < 7 W           |
| **Housing**     | Aluminium housing, plastic panels, IP30 rating                                |
| **Dimensions**  | 110 x 50 x 100 mm                                                             |
| **Weight**      | 287 g                                                                         |
| **Mounting**    | **DIN rail** (two-side mounting), Flat surface                                |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Connectivity:** Failover (Network backup), Load balancing, Connection monitoring (Ping/Periodic Reboot)

## 5. Frequency Bands (Version Specific)

- **Global:** LTE-FDD (B1-B5, B7, B8, B12, B13, B18-B20, B25, B26, B28), LTE-TDD (B38-B41), 3G, 2G
- **Europe/EMEA:** LTE-FDD (B1, B3, B5, B7, B8, B20, B28A), LTE-TDD (B38, B40, B41), 3G, 2G
- **North America:** LTE-FDD (B2, B4, B5, B12-B14, B66, B71), 3G"
  "# RUT906 – Industrial Cellular Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                                                                        |
| :------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CPU**       | Mediatek, 580 MHz, MIPS 24KEC                                                                                                                        |
| **Memory**    | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                                                                                                |
| **Ethernet**  | 1 x WAN, 3 x LAN (10/100 Mbps, Auto MDI/MDIX)                                                                                                        |
| **Wi-Fi**     | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                                                                                        |
| **Mobile**    | 4G (LTE) Cat 4 up to 150 Mbps, 3G, 2G                                                                                                                |
| **SIM Slots** | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch                                                                                                      |
| **Serial**    | 1 x RS232 (DB9), 1 x RS485 (6-pin terminal block)                                                                                                    |
| **I/O**       | **10-pin socket:** 1 x Dry Input, 1 x Isolated Input, 1 x Analog Input, 1 x Relay Output, 1 x OC Output <br> **4-pin socket:** 1 x Input, 1 x Output |
| **USB**       | 1 x USB A port (USB 2.0)                                                                                                                             |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS                                                                                                                  |

## 2. Serial & Industrial Protocols

- **Serial Modes:** Console, Serial over IP, Modem, Modbus gateway
- **Supported Protocols:**
  - **Modbus:** TCP/RTU (Client/Server), Custom registers, MQTT Gateway
  - **BACnet:** Router (RS485, TCP)
  - **OPC UA:** Client, Server (planned)
  - **DNP3:** TCP Station, Outstation (RS232, RS485, TCP, USB)
  - **MQTT:** Broker, Publisher, Azure MQTT
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                     |
| **Consumption** | Idle: < 2 W                                                                   | Max: < 7 W           |
| **Housing**     | Aluminium housing, plastic panels, IP30 rating                                |
| **Dimensions**  | 109.5 x 50 x 100 mm                                                           |
| **Weight**      | 295 g                                                                         |
| **Mounting**    | **DIN rail** (two-side mounting), Flat surface                                |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Connectivity:** Failover (Network backup), Load balancing, Connection monitoring (Ping/Periodic Reboot)

## 5. Frequency Bands & Regional

- **Region:** Europe, the Middle East, Africa, Thailand
- **4G (LTE-FDD):** B1, B3, B7, B8, B20, B28
- **4G (LTE-TDD):** B38, B40, B41
- **3G:** B1, B8
- **2G:** B2, B8"
  "# RUT360 – Industrial Cellular Router

## 1. System Core & Interfaces

| Feature      | Specification                                                                                                        |
| :----------- | :------------------------------------------------------------------------------------------------------------------- |
| **CPU**      | QCA9531, MIPS 24kc, 650 MHz                                                                                          |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                                                                |
| **Ethernet** | 1 x WAN, 1 x LAN (10/100 Mbps, Auto MDI/MDIX)                                                                        |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), 2x2 MIMO, AP/STA                                                                         |
| **Mobile**   | 4G (LTE) Cat 6 up to 300 Mbps, 3G up to 42 Mbps                                                                      |
| **SIM Slot** | **1 x SIM slot** (Mini SIM - 2FF)                                                                                    |
| **I/O**      | 2 x Programmable I/O (on 4-pin power socket): <br> - Digital Input (0-30V) <br> - Open Collector Output (30V, 300mA) |

## 2. Industrial Protocols & Software

- **Modbus:** TCP Master/Slave, Custom registers, MQTT Gateway
- **DNP3:** TCP Master, Outstation
- **MQTT:** Broker, Publisher, Azure MQTT, Kinesis
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub
- **OS:** RutOS (OpenWrt based Linux OS)

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **Consumption** | Max: < 10.5 W                                                                 |
| **Housing**     | Full Aluminum housing, IP30 rating                                            |
| **Dimensions**  | 100 x 30 x 85 mm                                                              |
| **Weight**      | 247 g                                                                         |
| **Mounting**    | **DIN rail**, Flat surface placement                                          |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Connectivity:** Failover (Network backup), Load balancing, Wireless Mesh (802.11s), Fast roaming (802.11r)

## 5. Frequency Bands & Regional

- **Europe, MEA, APAC, Brazil:**
  - **4G (LTE-FDD):** B1, B3, B5, B7, B8, B20, B28, B32
  - **4G (LTE-TDD):** B38, B40, B41
  - **3G:** B1, B3, B5, B8
- **North America:**
  _ **4G (LTE-FDD):** B2, B4, B5, B7, B12, B13, B25, B26, B29, B30, B66
  _ **3G:** B2, B4, B5"
  "# RUT241 – Industrial Cellular Router

## 1. System Core & Interfaces

| Feature      | Specification                                                              |
| :----------- | :------------------------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                              |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                      |
| **Ethernet** | 1 x WAN, 1 x LAN (10/100 Mbps, Auto MDI/MDIX)                              |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)              |
| **Mobile**   | 4G (LTE) Cat 4 up to 150 Mbps, 3G, 2G                                      |
| **SIM Slot** | **1 x SIM slot** (Mini SIM - 2FF), External holder                         |
| **I/O**      | 1 x Digital Input (0-30V), 1 x Digital Output (Open collector, 30V, 300mA) |
| **Antennas** | 2 x SMA for LTE, 1 x RP-SMA for Wi-Fi                                      |

## 2. Industrial Protocols & Software

- **Modbus:** TCP Master/Slave, Custom registers, MQTT Gateway
- **DNP3:** TCP Master, Outstation
- **MQTT:** Broker, Publisher, Azure MQTT, Kinesis
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub
- **OS:** RutOS (OpenWrt based Linux OS)

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                     |
| **Consumption** | Max: < 6.5 W                                                                  |
| **Housing**     | Aluminium housing, plastic panels, IP30 rating                                |
| **Dimensions**  | 83 x 25 x 74 mm                                                               |
| **Weight**      | 125 g                                                                         |
| **Mounting**    | **DIN rail** (Bottom/Sideways), Flat surface                                  |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Connectivity:** Failover (Network backup), Load balancing, Fast roaming (802.11r), Relayd

## 5. Frequency Bands & Regional (Typical)

- **Europe, MEA, Thailand:**
  - **4G (LTE-FDD):** B1, B3, B7, B8, B20, B28A
  - **3G:** B1, B8 | **2G:** B3, B8
- **Global Version:**
  - **4G (LTE-FDD):** B1, B2, B3, B4, B5, B7, B8, B12, B13, B18, B19, B20, B25, B26, B28
  - **4G (LTE-TDD):** B38, B39, B40, B41
  - **3G:** B1, B2, B4, B5, B6, B8, B19 | **2G:** B2, B3, B5, B8
- **North America:**
  _ **4G (LTE-FDD):** B2, B4, B5, B12, B13, B14, B66, B71
  _ **3G:** B2, B4, B5"
  "# RUT200 – Industrial Cellular Router

## 1. System Core & Interfaces

| Feature      | Specification                                                              |
| :----------- | :------------------------------------------------------------------------- |
| **CPU**      | Mediatek, 580 MHz, MIPS 24KEC                                              |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                      |
| **Ethernet** | 1 x WAN, 1 x LAN (10/100 Mbps, Auto MDI/MDIX)                              |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)              |
| **Mobile**   | 4G (LTE) Cat 4 up to 150 Mbps, 3G, 2G                                      |
| **SIM Slot** | **1 x SIM slot** (Mini SIM - 2FF)                                          |
| **I/O**      | 1 x Digital Input (0-30V), 1 x Digital Output (Open collector, 30V, 300mA) |

## 2. Industrial Protocols & Software

- **Modbus:** TCP Master/Slave, Custom registers, MQTT Gateway
- **DNP3:** TCP Master, Outstation
- **MQTT:** Broker, Publisher, Azure MQTT, Kinesis
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub
- **OS:** RutOS (OpenWrt based Linux OS)

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                     |
| **Consumption** | Max: < 6.5 W                                                                  |
| **Housing**     | Aluminium housing, plastic panels, IP30 rating                                |
| **Dimensions**  | 83 x 25 x 74 mm                                                               |
| **Weight**      | 125 g                                                                         |
| **Mounting**    | **DIN rail** (Bottom/Sideways), Flat surface                                  |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Connectivity:** Failover (Network backup), Load balancing, Fast roaming (802.11r), Relayd

"
"# RUT955 – Industrial Cellular Router with GNSS & Serial

## 1. System Core & Interfaces

| Feature       | Specification                                                                                                                                        |
| :------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CPU**       | Atheros Wasp, MIPS 74Kc, 550 MHz                                                                                                                     |
| **Memory**    | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                                                                                                |
| **Ethernet**  | 1 x WAN (configurable to LAN), 3 x LAN (10/100 Mbps)                                                                                                 |
| **Wi-Fi**     | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)                                                                                        |
| **Mobile**    | 4G (LTE) Cat 4 up to 150 Mbps, 3G, 2G                                                                                                                |
| **SIM Slots** | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch                                                                                                      |
| **Serial**    | 1 x RS232 (DB9), 1 x RS485 (6-pin terminal block)                                                                                                    |
| **I/O**       | **10-pin socket:** 1 x Dry Input, 1 x Isolated Input, 1 x Analog Input, 1 x Relay Output, 1 x OC Output <br> **4-pin socket:** 1 x Input, 1 x Output |
| **Storage**   | 1 x USB A 2.0, 1 x Micro SD slot (up to 64 GB)                                                                                                       |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS                                                                                                                  |

## 2. Serial & Industrial Protocols

- **Serial Modes:** Console, Serial over IP, Modem, Modbus gateway, NTRIP Client
- **Supported Protocols:**
  - **Modbus:** TCP/RTU (Master/Slave), Custom registers, MQTT Gateway
  - **MQTT:** Broker, Publisher, Azure MQTT
  - **NTRIP:** Client for high-precision GNSS
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **PoE**         | Passive PoE (LAN port, Mode B, 9-30 VDC)                                      |
| **Consumption** | Idle: < 2 W                                                                   | Max: < 7 W           |
| **Housing**     | Aluminium housing, plastic panels, IP30 rating                                |
| **Dimensions**  | 110 x 50 x 100 mm                                                             |
| **Weight**      | 287 g                                                                         |
| **Mounting**    | **DIN rail** (two-side mounting), Flat surface                                |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2)
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TP, DMVPN, SSTP, Stunnel
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (X.509)
- **Connectivity:** Failover (Network backup), Load balancing, Connection monitoring (Ping/Wget Reboot)

"
"# RUT950 – Industrial 4G LTE Wi-Fi Router

## 1. System Core & Interfaces

| Feature       | Specification                                                              |
| :------------ | :------------------------------------------------------------------------- |
| **CPU**       | Atheros Wasp, MIPS 74Kc, 550 MHz                                           |
| **Memory**    | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                      |
| **Ethernet**  | 1 x WAN, 3 x LAN (10/100 Mbps, Auto MDI/MDIX)                              |
| **Wi-Fi**     | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)              |
| **Mobile**    | 4G (LTE) Cat 4 up to 150 Mbps, 3G, 2G                                      |
| **SIM Slots** | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch                            |
| **I/O**       | 1 x Digital Input (0-30V), 1 x Digital Output (Open collector, 30V, 300mA) |
| **Antennas**  | 2 x SMA for LTE, 2 x RP-SMA for Wi-Fi                                      |

## 2. Industrial Protocols & Software

- **Modbus:** TCP Master/Slave, Custom registers, MQTT Gateway
- **DNP3:** TCP Master, Outstation
- **MQTT:** Broker, Publisher, Azure MQTT, Kinesis
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub
- **Connectivity:** Wireless Mesh (802.11s), Fast roaming (802.11r), Relayd

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                     |
| **Consumption** | Idle: < 2 W                                                                   | Max: < 7 W           |
| **Housing**     | Aluminium housing, plastic panels, IP30 rating                                |
| **Dimensions**  | 110 x 50 x 100 mm                                                             |
| **Weight**      | 280 g                                                                         |
| **Mounting**    | **DIN rail** (two-side mounting), Flat surface placement                      |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Redundancy:** Dual SIM (Failover), VRRP, Connection monitoring (Ping/Wget Reboot)
  "
  "# RUT850 – Automotive Router Datasheet

## Table of Contents

- [Overview / Introduction](#overview--introduction)
- [Key Features](#key-features)
- [Hardware Specifications](#hardware-specifications)
- [Software Features](#software-features)
- [Electrical, Mechanical & Environmental](#electrical-mechanical--environmental)
- [Certifications](#certifications)

## Overview / Introduction

**RUT850** is a compact, slim design LTE wireless router dedicated to automotive applications. It supports the latest IEEE802.11n and 802.11b/g WLAN standards, providing wireless receiving and transmitting rates of up to 150 Mbps. LTE speeds reach up to 150 Mbps DL and 50 Mbps UL.

Whether for a long family trip, a camping spot, or a need to access a backend office, the RUT850 is a perfect choice. It connects multiple devices, allowing users to watch movies, video streams, or connect to remote surveillance equipment with ease.

The device is designed for use in light vehicles, buses, trucks, and other heavy transport utilizing 24V batteries, achieved through a wide input voltage range (7-30 VDC) and voltage surge protection.

## Key Features

- **LTE Cat 4:** High-speed LTE providing speeds of up to 150 Mbps.
- **WiFi:** Internal WiFi antenna supporting IEEE802.11n and 802.11b/g standards.
- **Ignition Detection:** Power supply socket connector has an Ignition digital input to control the router's sleep mode status.
- **RMS Support:** Full support for the centralized Teltonika Remote Management System for remote access, control, and monitoring.
- **Easy Setup:** Set up internet connectivity in minutes via smartphone.

## Hardware Specifications

### LTE

| Parameter          | Value                                                             |
| :----------------- | :---------------------------------------------------------------- |
| **FDD Bands**      | 2100(B1) / 1800(B3) / 850(B5) / 2600(B7) / 900(B8) / 800(B20) MHz |
| **TDD Bands**      | 2600(B38) / 2300(B40) / 2500(B40) MHz                             |
| **Downlink Speed** | Up to 150/130 Mbps (FDD/TDD)                                      |
| **Uplink Speed**   | Up to 50/35 Mbps (FDD/TDD)                                        |
| **Diversity**      | All bands with diversity                                          |

### UMTS

| Parameter           | Value                               |
| :------------------ | :---------------------------------- |
| **Bands**           | 2100(B1) / 850(B5) / 900(B8) MHz    |
| **DC-HSPA+ Speed**  | 42 Mbps downlink / 5.76 Mbps uplink |
| **UMTS Mode Speed** | 384 kbps DL / 384 kbps UL           |
| **Antenna**         | RX diversity antenna                |

### GSM/GPRS/EDGE

| Parameter       | Value                                                                                                                                                                               |
| :-------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Bands**       | 1800(B3) / 900(B8) MHz                                                                                                                                                              |
| **Power Class** | Class 4 (33dBm ±2dB) for GSM 850/900MHz<br>Class 1 (30dBm ±2dB) for GSM 1800/1900MHz<br>Class E2 (27dBm ±3dB) for EDGE 850/900MHz<br>Class E2 (26dBm +3/-4dB) for EDGE 1800/1900MHz |
| **GPRS Speed**  | 85.6 kbps DL / 85.6 kbps UL                                                                                                                                                         |
| **EDGE Speed**  | 236.8 kbps DL / 236.8 kbps UL                                                                                                                                                       |

### WiFi

| Parameter             | Value                                                     |
| :-------------------- | :-------------------------------------------------------- |
| **Standards**         | IEEE 802.11b/g/n                                          |
| **Modes**             | AP and STA modes                                          |
| **Encryption**        | 64/128-bit WEP, WPA, WPA2, WPA&WPA2 encryption methods    |
| **Frequency Range**   | 2.401 - 2.495 GHz                                         |
| **Max TX Power**      | 20dBm                                                     |
| **Security Features** | SSID stealth mode and access control based on MAC address |
| **Hardware**          | Internal WiFi antenna                                     |

### Other Hardware Interfaces

- **SIM:** SIM card drawer
- **Ignition:** Input for Ignition

## Software Features

- **Dynamic DNS**
- **Periodic Reboot**
- **SMS Control / Gateway**
- **Mobile on Demand**
- **Hotspot**
- **Mobile Quota Control**
- **Backup WAN**
- **NTP**
- **Ping Reboot**
- **Web Filter**
- **Sleep Mode**

## Electrical, Mechanical & Environmental

| Parameter                  | Value                     |
| :------------------------- | :------------------------ |
| **Input Voltage Range**    | 7 - 30 VDC                |
| **Overvoltage Protection** | Up to continuous 60 VDC   |
| **Power Consumption**      | < 5 W                     |
| **Dimensions (H x W x D)** | 131 mm x 79 mm x 17 mm    |
| **Weight**                 | 107 g                     |
| **Operating Temperature**  | -40°C to 75°C             |
| **Storage Temperature**    | -45°C to 80°C             |
| **Operating Humidity**     | 10% to 90% non-condensing |
| **Storage Humidity**       | 5% to 95% non-condensing  |

## Certifications

- **Quality System:** ISO 9001
- **Other:** DNV GL, RoHS Compliant

---

_Note: Supported frequency bands are dependent on geographical location and may not be available in all markets. Teltonika reserves a right to modify the functionality of the device without any prior notice._"
"# RUT240 – Industrial Cellular Router

## 1. System Core & Interfaces

| Feature      | Specification                                                              |
| :----------- | :------------------------------------------------------------------------- |
| **CPU**      | Atheros Hornet, MIPS 24Kc, 400 MHz                                         |
| **Memory**   | **RAM:** 64 MB, DDR2 <br> **Flash:** 16 MB SPI Flash                       |
| **Ethernet** | 1 x WAN, 1 x LAN (10/100 Mbps, Auto MDI/MDIX)                              |
| **Wi-Fi**    | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA)              |
| **Mobile**   | 4G (LTE) Cat 4 up to 150 Mbps, 3G, 2G                                      |
| **SIM Slot** | **1 x SIM slot** (Mini SIM - 2FF), External holder                         |
| **I/O**      | 1 x Digital Input (0-30V), 1 x Digital Output (Open collector, 30V, 300mA) |
| **Antennas** | 2 x SMA for LTE, 1 x RP-SMA for Wi-Fi                                      |

## 2. Industrial Protocols & Software

- **Modbus:** TCP Master/Slave, Custom registers, MQTT Gateway
- **DNP3:** TCP Master, Outstation
- **MQTT:** Broker, Publisher, Azure MQTT, Kinesis
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub
- **Connectivity:** Wireless Mesh (802.11s), Fast roaming (802.11r), Relayd
- **OS:** RutOS (OpenWrt based Linux OS)

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                     |
| **Consumption** | Max: < 6.5 W                                                                  |
| **Housing**     | Aluminium housing, plastic panels, IP30 rating                                |
| **Dimensions**  | 83 x 25 x 74 mm                                                               |
| **Weight**      | 125 g                                                                         |
| **Mounting**    | **DIN rail** (Bottom/Sideways), Flat surface                                  |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Connectivity:** Failover (Network backup), Load balancing, Connection monitoring (Ping/Wget Reboot)
  "
  "# OTD140 – Industrial Outdoor 4G Router

## 1. System Core & Interfaces

| Feature       | Specification                                   |
| :------------ | :---------------------------------------------- |
| **CPU**       | Mediatek, 580 MHz, MIPS 24KEC                   |
| **Memory**    | **RAM:** 128 MB <br> **Flash:** 16 MB           |
| **Ethernet**  | 2 x 10/100 Mbps ports (PoE IN & PoE OUT)        |
| **Mobile**    | 4G (LTE) Cat 4 (150 Mbps DL), 3G, 2G            |
| **SIM Slots** | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch |
| **Antennas**  | Internal antennas for Mobile connectivity       |
| **PoE In**    | 802.3af/at (42.5 - 57.0 VDC)                    |
| **PoE Out**   | 802.3af (Max 15W, yêu cầu nguồn vào 802.3at)    |

## 2. Industrial Protocols & Software

- **Industrial Protocols:** \* **OPC UA:** Client, Server (planned)
  - **Modbus:** TCP Server/Client, Custom registers, MQTT Gateway
  - **DNP3:** Station, Outstation (TCP)
  - **DLMS:** Support for utility meter data exchange
- **MQTT:** Broker, Publisher, Azure MQTT
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub
- **OS:** RutOS (OpenWrt based Linux OS)

## 3. Power & Physical

| Feature         | Specification                           |
| :-------------- | :-------------------------------------- | ------------------------------- |
| **Power Input** | PoE (42.5 - 57.0 VDC) qua cổng RJ45     |
| **Consumption** | Idle: < 2.5 W                           | Max: < 6 W (không tính PoE Out) |
| **Housing**     | Plastic (PC+ASA), IP55 rating           |
| **Dimensions**  | 110 x 49.30 x 235 mm                    |
| **Weight**      | 855 g                                   |
| **Mounting**    | Mounting Bracket (Pole hoặc Wall mount) |
| **Environment** | Operating Temp: **-40°C to 75°C**       | Humidity: 10% to 90%            |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN separation, WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Redundancy:** Dual SIM (Failover), VRRP, Connection monitoring (Ping/Wget Reboot)
  "
  "# RUTX50 – Industrial 5G Router

## 1. System Core & Interfaces

| Feature       | Specification                                                                                          |
| :------------ | :----------------------------------------------------------------------------------------------------- |
| **CPU**       | Quad-core ARM Cortex A7, 717 MHz                                                                       |
| **Memory**    | **RAM:** 256 MB <br> **Flash:** 256 MB SPI Flash                                                       |
| **Ethernet**  | 1 x WAN, 4 x LAN (10/100/1000 Mbps)                                                                    |
| **Wi-Fi**     | 802.11ac Wave 2 (WiFi 5), MU-MIMO, lên đến 867 Mbps                                                    |
| **Mobile**    | **5G Sub-6Ghz** SA/NSA (3.3Gbps DL, 900Mbps UL) <br> 4G (LTE) Cat 20 (2.0Gbps DL) <br> 3G (42 Mbps DL) |
| **SIM Slots** | **2 x SIM slots** (Mini SIM - 2FF), Auto-switch                                                        |
| **I/O**       | 1 x Digital Input (0-30V), 1 x Digital Output (Open collector, 30V, 300mA)                             |
| **USB**       | 1 x USB A 2.0 (Samba share, USB-to-serial, External HDD)                                               |
| **GNSS**      | GPS, GLONASS, BeiDou, Galileo, QZSS                                                                    |

## 2. Industrial Protocols & Software

- **Industrial Protocols:**
  - **Modbus:** TCP Master/Slave, Custom registers, MQTT Gateway
  - **DNP3:** TCP Master, Outstation
  - **MQTT:** Broker, Publisher, Azure MQTT, Kinesis
- **Monitoring:** Teltonika RMS, Web UI, CLI, SSH, SNMP (v1/v2/v3), TR-069, JSON-RPC
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub
- **Location Tracking:** NTRIP Client, NMEA 0183, Geofencing
- **OS:** RutOS (OpenWrt based Linux OS)

## 3. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 50 VDC** (4-pin industrial socket), Reverse polarity & Surge protection |
| **PoE**         | Passive PoE (LAN1 port, Mode B, 9-30 VDC)                                     |
| **Consumption** | Idle: < 4 W                                                                   | Max: < 18 W          |
| **Housing**     | Full Aluminum housing, IP30 rating                                            |
| **Dimensions**  | 132 x 44.2 x 95.1 mm                                                          |
| **Weight**      | 533 g                                                                         |
| **Mounting**    | **DIN rail** (two-side mounting), Flat surface placement                      |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 4. Network & Security Features

- **Routing:** Static, Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy based
- **VPN:** OpenVPN, IPsec (IKEv1/v2), **WireGuard**, ZeroTier, PPTP, L2TPv3, DMVPN, SSTP, Stunnel, Tinc
- **Firewall:** Port forward, Traffic rules, NAT, DMZ, Attack prevention (DDOS, Port scan)
- **Security:** VLAN (Port/Tag-based), WEB filter (White/Blacklist), MAC filter, Authentication (TACACS+, Radius, X.509)
- **Connectivity:** Failover (Network backup), Load balancing, Wireless Mesh (802.11s), Fast roaming (802.11r)
  "
  "# SWM280 – L2+ Managed PoE+ Switch

## 1. System Core & Interfaces

| Feature        | Specification                                            |
| :------------- | :------------------------------------------------------- |
| **CPU**        | Realtek, Single Core, 500 MHz, MIPS-4KEC                 |
| **Memory**     | **RAM:** 128 MB, DDR3 <br> **Flash:** 16 MB Serial Flash |
| **Ethernet**   | 24 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX        |
| **Fiber**      | 4 x SFP ports cho kết nối quang học                      |
| **PoE Out**    | **Ports 1-12** hỗ trợ PoE/PoE+ (802.3af/at)              |
| **PoE Budget** | Tổng công suất **300 W** (Tối đa 30 W mỗi cổng)          |
| **Management** | L2+ Managed Switch                                       |

## 2. Industrial Protocols & Diagnostics

- **Industrial Protocols:**
  - **Profinet:** Class B conformance (tùy chọn mã đặt hàng)
  - **EtherNet/IP:** Hỗ trợ sẵn
  - **SNMP:** V2, V3
  - **LLDP:** Hỗ trợ sẵn
- **MRP:** MRP client role, MRP manager role
- **Diagnostics:** Cable diagnostic, Ping, Traceroute, Nslookup
- **PoE Management:** Enable/disable, Ping reboot (tự động khởi động lại cổng PoE)

## 3. Performance & Network Features

| Feature             | Specification                                            |
| :------------------ | :------------------------------------------------------- |
| **Bandwidth**       | 56 Gbps (Non-blocking)                                   |
| **Forwarding Rate** | 83.33 Mpps                                               |
| **MAC Table**       | 8K entries                                               |
| **Jumbo Frame**     | 10000 bytes                                              |
| **L2 Features**     | Loop protection, STP/RSTP, VLAN (802.1Q), Port isolation |
| **L3 Features**     | Static IPv4/IPv6 routing, DHCPv6 client                  |
| **QoS**             | 802.1p priority, DSCP, TOS, Scheduling (SP/WFQ/WRR)      |

## 4. Power & Physical

| Feature         | Specification                               |
| :-------------- | :------------------------------------------ | -------------------- |
| **Power Input** | **100 – 240 VAC**, 50/60 Hz (C14 connector) |
| **Consumption** | Idle: 7.5 W                                 | Max: 325 W           |
| **Housing**     | Anodized aluminum housing, IP30 rating      |
| **Dimensions**  | 483 x 44 x 234 mm (Chuẩn Rack 1U)           |
| **Weight**      | 1842 g                                      |
| **Mounting**    | Rack mounting kit tích hợp                  |
| **Environment** | Operating Temp: **0°C to 50°C**             | Humidity: 10% to 90% |

## 5. Security & Management

- **Authentication:** Radius & TACACS+, PAM preshared key
- **Access Control:** 802.1x port-based control, MAC filtering
- **Management Interfaces:** WEB UI, CLI, FOTA, RMS, Teltonika Networks Web API
- **OS:** TSWOS (OpenWrt based Linux OS)
- **Redundancy:** VRRP, MRP"
  "# SWM281 – L2+ Managed Industrial Switch

## 1. System Core & Interfaces

| Feature        | Specification                                            |
| :------------- | :------------------------------------------------------- |
| **CPU**        | Realtek, Single Core, 500 MHz, MIPS-4KEC                 |
| **Memory**     | **RAM:** 128 MB, DDR3 <br> **Flash:** 16 MB Serial Flash |
| **Ethernet**   | 24 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX        |
| **Fiber**      | 4 x SFP ports cho kết nối quang học                      |
| **Management** | L2+ Managed Switch                                       |
| **Standards**  | IEEE 802.3i, 802.3u, 802.3ab, 802.3x, 802.3az            |

## 2. Industrial Protocols & Software

- **Industrial Protocols:**
  - **Profinet:** Class B conformance (tùy chọn mã đặt hàng)
  - **EtherNet/IP:** Hỗ trợ sẵn
  - **SNMP:** V2, V3
  - **LLDP:** Hỗ trợ sẵn
- **Redundancy:** MRP (client/manager role), STP/RSTP, Loop protection
- **Monitoring:** WEB UI, CLI, FOTA, RMS, Teltonika Networks Web API
- **OS:** TSWOS (OpenWrt based Linux OS)
- **Diagnostics:** Cable diagnostic, Ping, Traceroute, Nslookup

## 3. Performance & Network Features

| Feature             | Specification                                        |
| :------------------ | :--------------------------------------------------- |
| **Bandwidth**       | 56 Gbps (Non-blocking)                               |
| **Forwarding Rate** | 83.33 Mpps                                           |
| **MAC Table**       | 8K entries                                           |
| **Jumbo Frame**     | 10000 bytes                                          |
| **L3 Features**     | Static IPv4/IPv6 routing, DHCPv6 client              |
| **VLAN**            | 802.1Q VLAN, Port VLAN separation                    |
| **QoS**             | Port priority, DSCP, 802.1p, Scheduling (SP/WFQ/WRR) |

## 4. Power & Physical

| Feature         | Specification                                     |
| :-------------- | :------------------------------------------------ | -------------------- |
| **Power Input** | **100 – 240 VAC**, 50/60 Hz (C14 connector)       |
| **Consumption** | Idle: 5.5 W                                       | Max: 20 W            |
| **Housing**     | Anodized aluminum housing and panels, IP30 rating |
| **Dimensions**  | 483 x 44 x 234 mm (Chuẩn Rack 1U)                 |
| **Weight**      | 1853 g                                            |
| **Mounting**    | Rack mounting kit tích hợp                        |
| **Environment** | Operating Temp: **0°C to 50°C**                   | Humidity: 10% to 90% |

## 5. Security Features

- **Authentication:** Radius & TACACS+, PAM preshared key
- **Access Control:** 802.1x port-based network access control (client/server)
- **MAC Filtering:** Allow specific MACs, ignore or disable port upon unauthorized access
- **Port Settings:** Enable/disable, link speed control, port isolation, Port Mirroring
- **Attack Prevention:** IP & login attempts block"
  "# SWM282 – L2+ Managed PoE+ Industrial Switch

## 1. System Core & Interfaces

| Feature        | Specification                                            |
| :------------- | :------------------------------------------------------- |
| **CPU**        | Realtek, Single Core, 500 MHz, MIPS-4KEC                 |
| **Memory**     | **RAM:** 128 MB, DDR3 <br> **Flash:** 16 MB Serial Flash |
| **Ethernet**   | 24 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX        |
| **Fiber**      | 4 x SFP ports cho kết nối quang học                      |
| **PoE Out**    | **Cả 24 cổng** đều hỗ trợ PoE/PoE+ (802.3af/at)          |
| **PoE Budget** | Tổng công suất **300 W** (Tối đa 30 W mỗi cổng)          |
| **Management** | L2+ Managed Switch                                       |

## 2. Industrial Protocols & Software

- **Industrial Protocols:**
  - **Profinet:** Class B conformance (tùy chọn mã đặt hàng)
  - **EtherNet/IP:** Hỗ trợ sẵn
  - **SNMP:** V2, V3
  - **LLDP:** Hỗ trợ sẵn
- **Redundancy:** MRP (client/manager role), STP/RSTP, Loop protection
- **Diagnostics:** Cable diagnostic, Ping, Traceroute, Nslookup
- **PoE Management:** Port-based PoE control, **Ping reboot** (tự khởi động lại thiết bị PD khi mất kết nối)
- **OS:** TSWOS (OpenWrt based Linux OS)

## 3. Performance & Network Features

| Feature             | Specification                                       |
| :------------------ | :-------------------------------------------------- |
| **Bandwidth**       | 56 Gbps (Non-blocking)                              |
| **Forwarding Rate** | 83.33 Mpps                                          |
| **MAC Table**       | 8K entries                                          |
| **Jumbo Frame**     | 10000 bytes                                         |
| **L3 Features**     | Static IPv4/IPv6 routing, DHCPv6 client             |
| **VLAN**            | 802.1Q VLAN, Port VLAN separation                   |
| **QoS**             | SP/WFQ/WRR scheduling, Rate limiting, Storm control |

## 4. Power & Physical

| Feature         | Specification                                     |
| :-------------- | :------------------------------------------------ | ------------------------ |
| **Power Input** | **100 – 240 VAC**, 50/60 Hz (C14 connector)       |
| **Consumption** | Idle: 9 W                                         | Max: 330 W (bao gồm PoE) |
| **Housing**     | Anodized aluminum housing and panels, IP30 rating |
| **Dimensions**  | 483 x 44 x 234 mm (Chuẩn Rack 1U)                 |
| **Weight**      | 2291 g                                            |
| **Mounting**    | Rack mounting kit tích hợp                        |
| **Environment** | Operating Temp: **0°C to 50°C**                   | Humidity: 10% to 90%     |

## 5. Security Features

- **Authentication:** Radius & TACACS+, PAM preshared key
- **Access Control:** 802.1x port-based network access control
- **MAC Filtering:** Whitelist/Blacklist theo từng cổng
- **Management Security:** IP & login attempts block
- **API:** Teltonika Networks Web API (beta) hỗ trợ truy xuất/thay đổi dữ liệu cấu hình"
  "# TSF010 – Flat Industrial Unmanaged Switch

## 1. System Core & Interfaces

| Feature            | Specification                                         |
| :----------------- | :---------------------------------------------------- |
| **Type**           | Unmanaged Industrial Switch                           |
| **Ethernet**       | 5 x RJ45 ports (10/100 Mbps), Auto MDI/MDIX crossover |
| **Standards**      | IEEE 802.3i, 802.3u, 802.3ab, 802.3x, 802.3az         |
| **Power Socket**   | 3-pin industrial DC power socket (+, -, Chassis)      |
| **LED Indicators** | 1 x Power LED, 10 x ETH status LEDs                   |

## 2. Industrial Features & Performance

- **Industrial Protocols:** Profinet Class A conformance (tùy chọn mã đặt hàng).
- **Bandwidth:** 10 Gbps (Non-blocking).
- **Packet Buffer:** 128 KB.
- **MAC Table:** 2K entries.
- **Jumbo Frame:** 9216 bytes.
- **Rugged Design:** Vỏ nhôm Anodized, chuẩn bảo vệ IP30.

## 3. Power Specifications

| Feature                    | Specification                                  |
| :------------------------- | :--------------------------------------------- | ---------- |
| **Input Voltage**          | **7 – 57 VDC**                                 |
| **Consumption**            | Idle: 1 W                                      | Max: 1.5 W |
| **Overvoltage Protection** | 60 Vmax                                        |
| **Reverse Polarity**       | 80 Vmax                                        |
| **Surge Protection**       | Min 64.4V / Max 71.2V breakdown voltage        |
| **Grounding**              | Grounding terminal tích hợp trên đầu nối nguồn |

## 4. Physical Specification

| Feature                | Specification                                                |
| :--------------------- | :----------------------------------------------------------- |
| **Dimensions**         | 113 x 28 x 50 mm (Thiết kế dạng dẹt ""Flat"")                |
| **Weight**             | 142 g                                                        |
| **Mounting**           | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Operating Temp**     | **-40°C to 75°C**                                            |
| **Operating Humidity** | 5% to 95% non-condensing                                     |

## 5. Ordering Information

| Model Code        | Description                  | Standard Package                    |
| :---------------- | :--------------------------- | :---------------------------------- |
| **TSF010 000000** | Standard version             | Switch TSF010, 3-pin connector, QSG |
| **TSF010 000001** | Profinet Class A conformance | Switch TSF010, 3-pin connector, QSG |

_Lưu ý: Gói tiêu chuẩn không bao gồm bộ nguồn (PSU)._"
"# TSW030 – 8-Port Industrial Unmanaged Switch

## 1. System Core & Interfaces

| Feature            | Specification                                         |
| :----------------- | :---------------------------------------------------- |
| **Type**           | Unmanaged Industrial Switch                           |
| **Ethernet**       | 8 x RJ45 ports (10/100 Mbps), Auto MDI/MDIX crossover |
| **Standards**      | IEEE 802.3i, 802.3u, 802.3ab, 802.3x, 802.3az         |
| **Power Socket**   | 2-pin industrial DC power socket (7-57 VDC)           |
| **LED Indicators** | 1 x Power LED, 16 x ETH status LEDs                   |

## 2. Industrial Features & Performance

- **Industrial Protocols:** Profinet Class A conformance (tùy chọn mã đặt hàng).
- **Bandwidth:** 20 Gbps (Non-blocking).
- **Packet Buffer:** 128 KB.
- **MAC Table:** 2K entries.
- **Jumbo Frame:** 9216 bytes.
- **Rugged Design:** Vỏ nhôm Anodized, chuẩn bảo vệ IP30.

## 3. Power Specifications

| Feature                    | Specification                           |
| :------------------------- | :-------------------------------------- | ---------- |
| **Input Voltage**          | **7 – 57 VDC**                          |
| **Consumption**            | Idle: 0.5 W                             | Max: 1.5 W |
| **Overvoltage Protection** | 60 Vmax                                 |
| **Reverse Polarity**       | 80 Vmax                                 |
| **Surge Protection**       | Min 64.4V / Max 71.2V breakdown voltage |
| **Pinout**                 | 1- Vin, 2-PGND                          |

## 4. Physical Specification

| Feature                | Specification                                                |
| :--------------------- | :----------------------------------------------------------- |
| **Dimensions**         | 113.1 x 41.2 x 74.6 mm                                       |
| **Weight**             | 256 g                                                        |
| **Mounting**           | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Alternative Mount**  | Wall mount and flat surface (cần bộ kit bổ sung)             |
| **Operating Temp**     | **-40°C to 75°C**                                            |
| **Operating Humidity** | 5% to 95% non-condensing                                     |

## 5. Ordering Information

| Model Code        | Description                  | Standard Package                  |
| :---------------- | :--------------------------- | :-------------------------------- |
| **TSW030 000000** | Standard version             | Switch TSW030, QSG, Packaging box |
| **TSW030 000001** | Profinet Class A conformance | Switch TSW030, QSG, Packaging box |

_Lưu ý: Gói tiêu chuẩn không bao gồm bộ nguồn (PSU)._"
"# TSW040 – 8-Port Industrial Unmanaged PoE+ Switch

## 1. System Core & Interfaces

| Feature            | Specification                                         |
| :----------------- | :---------------------------------------------------- |
| **Type**           | Unmanaged Industrial PoE+ Switch                      |
| **Ethernet**       | 8 x RJ45 ports (10/100 Mbps), Auto MDI/MDIX crossover |
| **Standards**      | IEEE 802.3i, 802.3u, 802.3ab, 802.3x, 802.3az         |
| **Power Socket**   | 2-pin industrial DC power socket                      |
| **LED Indicators** | 1 x Power LED, 16 x ETH status LEDs                   |

## 2. Power over Ethernet (PoE)

| Feature                | Specification                              |
| :--------------------- | :----------------------------------------- |
| **PoE Ports**          | **Port 1 – 8**                             |
| **PoE Standards**      | 802.3af and 802.3at compliant PSE (Mode B) |
| **Max Power per Port** | 30 W                                       |
| **Total PoE Budget**   | **240 W** (Yêu cầu nguồn đầu vào phù hợp)  |

## 3. Industrial Features & Performance

- **Industrial Protocols:** Profinet Class A conformance (tùy chọn mã đặt hàng).
- **Bandwidth:** 20 Gbps (Non-blocking).
- **Packet Buffer:** 128 KB.
- **MAC Table:** 2K entries.
- **Jumbo Frame:** 9216 bytes.
- **Rugged Design:** Vỏ nhôm Anodized, chuẩn bảo vệ IP30.

## 4. Power Specifications

| Feature           | Specification                                               |
| :---------------- | :---------------------------------------------------------- | ------------------------ | -------------- |
| **Input Voltage** | **7 – 57 VDC** (Sử dụng 44 – 57 VDC để cấp nguồn PoE Out)   |
| **Consumption**   | Idle: 1 W                                                   | Max: 2 W (chưa tính PoE) | PoE Max: 246 W |
| **Protections**   | Overvoltage (60V), Reverse polarity (80V), Surge protection |
| **Pinout**        | 1- Vin, 2-PGND                                              |

## 5. Physical Specification

| Feature                | Specification                                                |
| :--------------------- | :----------------------------------------------------------- |
| **Dimensions**         | 113.1 x 41.2 x 74.6 mm                                       |
| **Weight**             | 280 g                                                        |
| **Mounting**           | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Operating Temp**     | **-40°C to 75°C**                                            |
| **Operating Humidity** | 5% to 95% non-condensing                                     |

## 6. Ordering Information

| Model Code        | Description                  | Standard Package   |
| :---------------- | :--------------------------- | :----------------- |
| **TSW040 000000** | Standard version             | Switch TSW040, QSG |
| **TSW040 000001** | Profinet Class A conformance | Switch TSW040, QSG |

_Lưu ý: Gói tiêu chuẩn mặc định không bao gồm bộ nguồn (PSU)._"
"# TSW304 – 4-Port Gigabit Industrial Unmanaged Switch

## 1. System Core & Interfaces

| Feature            | Specification                                              |
| :----------------- | :--------------------------------------------------------- |
| **Type**           | Unmanaged Industrial Switch                                |
| **Ethernet**       | 4 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX crossover |
| **Standards**      | IEEE 802.3i, 802.3u, 802.3ab, 802.3x, 802.3az              |
| **Power Socket**   | 2-pin industrial DC power socket                           |
| **LED Indicators** | 1 x Power LED, 8 x LAN status LEDs (Orange/Green)          |

## 2. Performance Specifications

| Feature               | Specification                            |
| :-------------------- | :--------------------------------------- |
| **Bandwidth**         | 8 Gbps (Non-blocking)                    |
| **Packet Buffer**     | 128 KB                                   |
| **MAC Table**         | 2K entries                               |
| **Jumbo Frame**       | 9216 bytes                               |
| **Energy Efficiency** | IEEE 802.3az (Energy Efficient Ethernet) |

## 3. Power Specifications

| Feature           | Specification                                                                            |
| :---------------- | :--------------------------------------------------------------------------------------- | ----------- |
| **Input Voltage** | **7 – 57 VDC** hoặc **9 – 40 VAC**                                                       |
| **Passive PoE**   | Hỗ trợ cấp nguồn qua cổng ETH1 (Mode B, 9-30 VDC), không tương thích chuẩn 802.3af/at/bt |
| **Consumption**   | Idle: 0.26 W                                                                             | Max: 1.44 W |
| **Protections**   | Grounding screw tích hợp để bảo vệ tĩnh điện                                             |

## 4. Physical Specification

| Feature                | Specification                                                |
| :--------------------- | :----------------------------------------------------------- |
| **Housing**            | Aluminum housing, IP30 rating                                |
| **Dimensions**         | 102 x 25 x 81.5 mm                                           |
| **Weight**             | 210 g                                                        |
| **Mounting**           | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Alternative Mount**  | Hỗ trợ treo tường (Wall mounting)                            |
| **Operating Temp**     | **-40 °C to 75 °C**                                          |
| **Operating Humidity** | 10% to 90% non-condensing                                    |

## 5. Regulatory & Safety

- **Regulatory:** CE/RED, UKCA, CB, EAC, RoHS, REACH, FCC, IC, RCM, GITEKI.
- **Safety Standard:** EN IEC 62368-1:2020+A11:2020.
- **HS Code:** 851762 | **HTS:** 8517.62.00.

## 6. What's in the Box

- Switch TSW304
- QSG (Quick Start Guide)
- Packaging box

_Lưu ý: Gói tiêu chuẩn mặc định không bao gồm bộ nguồn (PSU)._"
"# TSW212 – L2 Managed Industrial Switch

## 1. System Core & Interfaces

| Feature        | Specification                                    |
| :------------- | :----------------------------------------------- |
| **Type**       | L2 Managed Industrial Switch                     |
| **Ethernet**   | 8 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX |
| **Fiber**      | 2 x SFP ports cho kết nối quang học Gigabit      |
| **Management** | Managed L2 với hệ điều hành TSWOS                |
| **Default IP** | 192.168.1.2                                      |
| **Standards**  | IEEE 802.1p, IEEE 802.1Q, 802.3az                |

## 2. Industrial Protocols & Software

- **Supported Protocols:**
  - **Profinet:** Class B conformance
  - **EtherNet/IP:** Hỗ trợ sẵn
  - **SNMP:** V2, V3
  - **LLDP:** Hỗ trợ sẵn
- **Redundancy:** MRP (client/manager role), STP/RSTP, Loop protection
- **Diagnostics:** Cable diagnostic, Ping, Traceroute, Nslookup
- **OS:** TSWOS (OpenWrt based Linux OS)
- **Monitoring:** WEB UI, FOTA, RMS (Remote Management System)

## 3. Performance & Network Features

| Feature           | Specification                                            |
| :---------------- | :------------------------------------------------------- |
| **Bandwidth**     | 20 Gbps (Non-blocking)                                   |
| **MAC Table**     | 8K entries                                               |
| **Packet Buffer** | 512 KB                                                   |
| **Jumbo Frame**   | 10000 bytes                                              |
| **L3 Features**   | Static IPv4/IPv6 routing, DHCPv6 client                  |
| **VLAN**          | Port-based and Tag-based VLAN separation                 |
| **QoS**           | Port priority, DSCP, 802.1p, TOS (SP/WFQ/WRR scheduling) |

## 4. Power & Physical

| Feature         | Specification                                                |
| :-------------- | :----------------------------------------------------------- | -------------------- |
| **Power Input** | **7 – 57 VDC** (2-pin industrial socket)                     |
| **Consumption** | Idle: < 2.5 W                                                | Max: 6 W             |
| **Housing**     | Anodized aluminum housing and panels, IP30 rating            |
| **Dimensions**  | 132 x 44.2 x 122.2 mm                                        |
| **Weight**      | 615 g                                                        |
| **Mounting**    | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Environment** | Operating Temp: **-40 °C to 75 °C**                          | Humidity: 10% to 90% |

## 5. Security & Diagnostic Tools

- **Authentication:** Radius & TACACS+, IP & login attempts block
- **Port Settings:** Port isolation, Link speed control, Port Mirroring
- **Energy Savings:** EEE (802.3az) management
- **Regulatory:** CE, CB, RCM, FCC, IC, EAC, UCRF
- **Safety Standard:** IEC 62368-1:2018

## 6. Ordering Information

| Product Code      | Description      | Standard Package                  |
| :---------------- | :--------------- | :-------------------------------- |
| **TSW212 000000** | Standard version | Switch TSW212, QSG, Packaging box |

_Lưu ý: Gói tiêu chuẩn không bao gồm bộ nguồn (PSU)._"
"# TSW210 – Industrial Unmanaged Gigabit Switch

## 1. System Core & Interfaces

| Feature            | Specification                                              |
| :----------------- | :--------------------------------------------------------- |
| **Type**           | Unmanaged Industrial Switch                                |
| **Ethernet**       | 8 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX crossover |
| **Fiber**          | 2 x SFP ports cho kết nối quang học tầm xa                 |
| **Standards**      | IEEE 802.3i, 802.3u, 802.3ab, 802.3x, 802.3az              |
| **Power Socket**   | 2-pin industrial DC power socket (7-57 VDC)                |
| **LED Indicators** | 1 x Power LED, 16 x ETH status LEDs, 2 x SFP status LEDs   |

## 2. Performance Specifications

| Feature               | Specification                            |
| :-------------------- | :--------------------------------------- |
| **Bandwidth**         | 20 Gbps (Non-blocking)                   |
| **Packet Buffer**     | 128 KB                                   |
| **MAC Table**         | 2K entries                               |
| **Jumbo Frame**       | 9216 bytes                               |
| **Energy Efficiency** | IEEE 802.3az (Energy Efficient Ethernet) |

## 3. Power Specifications

| Feature           | Specification                               |
| :---------------- | :------------------------------------------ | ----------- |
| **Input Voltage** | **7 – 57 VDC**                              |
| **Consumption**   | Idle: 1.03 W                                | Max: 3.71 W |
| **Protections**   | Grounding screw tích hợp để bảo vệ thiết bị |
| **Pinout**        | Đỏ (Power / Input), Đen (Ground)            |

## 4. Physical Specification

| Feature                | Specification                                                |
| :--------------------- | :----------------------------------------------------------- |
| **Housing**            | Full Aluminum housing, IP30 rating                           |
| **Dimensions**         | 132 x 44.2 x 122.2 mm                                        |
| **Weight**             | 456 g                                                        |
| **Mounting**           | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Alternative Mount**  | Treo tường (Wall mounting) hoặc đặt trên bề mặt phẳng        |
| **Operating Temp**     | **-40°C to 75°C**                                            |
| **Operating Humidity** | 10% to 90% non-condensing                                    |

## 5. Regulatory & Ordering

- **Regulatory:** CE, UKCA, CB, EAC, RCM, FCC, IC.
- **HS Code:** 851762 | **HTS:** 8517.62.00.
- **Standard Package:** Switch TSW210, QSG, Packaging box.

_Lưu ý: Gói tiêu chuẩn mặc định không bao gồm bộ nguồn (PSU)._"
"# TSW202 – L2 Managed PoE+ Industrial Switch

## 1. System Core & Interfaces

| Feature        | Specification                                    |
| :------------- | :----------------------------------------------- |
| **Type**       | Managed Industrial PoE+ Switch                   |
| **Ethernet**   | 8 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX |
| **Fiber**      | 2 x SFP ports cho kết nối quang học Gigabit      |
| **Management** | Managed L2 với hệ điều hành TSWOS                |
| **Default IP** | 192.168.1.2                                      |
| **Standards**  | IEEE 802.1p, IEEE 802.1Q, 802.3az                |

## 2. Power over Ethernet (PoE)

| Feature                | Specification          |
| :--------------------- | :--------------------- |
| **PoE Ports**          | **Port 1 – 8**         |
| **PoE Standards**      | IEEE 802.3af/at (PoE+) |
| **Max Power per Port** | 30 W                   |
| **Total PoE Budget**   | **240 W**              |

## 3. Industrial Protocols & Software

- **Industrial Protocols:**
  - **Profinet:** Class B conformance
  - **EtherNet/IP:** Hỗ trợ sẵn
  - **SNMP:** V2, V3
  - **LLDP:** Hỗ trợ sẵn
- **Redundancy:** MRP (client/manager role), STP/RSTP, Loop protection
- **Diagnostics:** Cable diagnostic, Ping, Traceroute, Nslookup
- **OS:** TSWOS (OpenWrt based Linux OS)
- **Management:** WEB UI, FOTA, RMS (Remote Management System)

## 4. Performance & Network Features

| Feature           | Specification                                            |
| :---------------- | :------------------------------------------------------- |
| **Bandwidth**     | 20 Gbps (Non-blocking)                                   |
| **MAC Table**     | 8K entries                                               |
| **Packet Buffer** | 512 KB                                                   |
| **Jumbo Frame**   | 10000 bytes                                              |
| **L3 Features**   | Static IPv4/IPv6 routing, DHCPv6 client                  |
| **QoS**           | Port priority, DSCP, 802.1p, TOS (SP/WFQ/WRR scheduling) |

## 5. Power & Physical

| Feature         | Specification                                                |
| :-------------- | :----------------------------------------------------------- | ------------------------ | -------------- |
| **Power Input** | **44 – 57 VDC** (2-pin industrial socket)                    |
| **Consumption** | Idle: < 2.5 W                                                | Max: 6 W (chưa tính PoE) | PoE Max: 246 W |
| **Housing**     | Anodized aluminum housing and panels, IP30 rating            |
| **Dimensions**  | 132 x 44.2 x 122.2 mm                                        |
| **Weight**      | 610 g                                                        |
| **Mounting**    | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Environment** | Operating Temp: **-40 °C to 75 °C**                          | Humidity: 10% to 90%     |

## 6. Ordering Information

| Product Code      | Description      | Standard Package                  |
| :---------------- | :--------------- | :-------------------------------- |
| **TSW202 000000** | Standard version | Switch TSW202, QSG, Packaging box |

_Lưu ý: Gói tiêu chuẩn mặc định không bao gồm bộ nguồn (PSU)._"
"# TSW200 – Industrial Unmanaged PoE+ Switch

## 1. System Core & Interfaces

| Feature            | Specification                                    |
| :----------------- | :----------------------------------------------- |
| **Type**           | Unmanaged Industrial Switch                      |
| **Ethernet**       | 8 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX |
| **Fiber**          | 2 x SFP ports cho kết nối quang học tầm xa       |
| **PoE Out**        | **8 x PoE+ ports** (IEEE 802.3af/at)             |
| **Standards**      | IEEE 802.3i, 802.3u, 802.3ab, 802.3x, 802.3az    |
| **LED Indicators** | 1 x Power LED, 16 x ETH status, 2 x SFP status   |

## 2. Power over Ethernet (PoE)

| Feature                | Specification                              |
| :--------------------- | :----------------------------------------- |
| **PoE Ports**          | **Port 1 – 8**                             |
| **PoE Standards**      | 802.3af and 802.3at compliant PSE (Mode B) |
| **Max Power per Port** | 30 W                                       |
| **Total PoE Budget**   | **240 W** (Tại PSE)                        |

## 3. Performance Specifications

| Feature               | Specification                            |
| :-------------------- | :--------------------------------------- |
| **Bandwidth**         | 20 Gbps (Non-blocking)                   |
| **Packet Buffer**     | 128 KB                                   |
| **MAC Table**         | 2K entries                               |
| **Jumbo Frame**       | 9216 bytes                               |
| **Energy Efficiency** | IEEE 802.3az (Energy Efficient Ethernet) |

## 4. Power & Physical

| Feature           | Specification                                                |
| :---------------- | :----------------------------------------------------------- | -------------------- | ---------------- |
| **Input Voltage** | **44 – 57 VDC** (2-pin industrial socket)                    |
| **Consumption**   | Idle: 1.8 W                                                  | Max: 5.5 W           | PoE Max: 245.5 W |
| **Housing**       | Full Aluminum housing, IP30 rating                           |
| **Dimensions**    | 132 x 44.2 x 122.2 mm                                        |
| **Weight**        | 456 g                                                        |
| **Mounting**      | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Environment**   | Operating Temp: **-40°C to 75°C**                            | Humidity: 10% to 90% |

## 5. Regulatory & Ordering

- **Regulatory:** CE, UKCA, CB, EAC, RCM, FCC, IC, UCRF.
- **HS Code:** 851762 | **HTS:** 8517.62.00.
- **Standard Package:** Switch TSW200, QSG, Packaging box.

_Lưu ý: Gói tiêu chuẩn mặc định không bao gồm bộ nguồn (PSU)._"
"# TSW114 – 5-Port Gigabit Industrial Unmanaged Switch

## 1. System Core & Interfaces

| Feature            | Specification                                    |
| :----------------- | :----------------------------------------------- |
| **Type**           | Unmanaged Industrial Switch                      |
| **Ethernet**       | 5 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX |
| **Standards**      | IEEE 802.3, 802.3u, 802.3ab, 802.3x, 802.3az     |
| **Power Socket**   | 2-pin industrial DC power socket                 |
| **LED Indicators** | 1 x Power LED, 10 x LAN status LEDs              |

## 2. Performance Specifications

| Feature               | Specification                            |
| :-------------------- | :--------------------------------------- |
| **Bandwidth**         | 10 Gbps (Non-blocking)                   |
| **Packet Buffer**     | 128 KB                                   |
| **MAC Table**         | 2K entries                               |
| **Jumbo Frame**       | 9216 bytes                               |
| **Energy Efficiency** | IEEE 802.3az (Energy Efficient Ethernet) |

## 3. Power Specifications

| Feature           | Specification                                |
| :---------------- | :------------------------------------------- | ---------- |
| **Input Voltage** | **9 – 30 VDC**                               |
| **Consumption**   | Idle: 0.6 W                                  | Max: 1.5 W |
| **Pinout**        | Đỏ (Power / Input), Đen (Ground)             |
| **Protections**   | Grounding screw tích hợp để bảo vệ tĩnh điện |

## 4. Physical Specification

| Feature                | Specification                                                |
| :--------------------- | :----------------------------------------------------------- |
| **Housing**            | Anodized aluminum housing and panels, IP30 rating            |
| **Dimensions**         | 113.1 x 27.4 x 80.5 mm (Thiết kế siêu mỏng)                  |
| **Weight**             | 174 g                                                        |
| **Mounting**           | **Integrated DIN rail bracket** (Ngàm DIN rail tích hợp sẵn) |
| **Operating Temp**     | **-40°C to 75°C**                                            |
| **Operating Humidity** | 10% to 90% non-condensing                                    |

## 5. Regulatory & Ordering

- **Regulatory:** CE, UKCA, CB, EAC, RCM, FCC, IC.
- **HS Code:** 851762 | **HTS:** 8517.62.00.
- **Standard Package:** Switch TSW114, QSG, Packaging box.

_Lưu ý: Gói tiêu chuẩn mặc định không bao gồm bộ nguồn (PSU)._"
"# TSW101 – Automotive Dedicated Gigabit Unmanaged PoE+ Switch

## 1. System Core & Interfaces

| Feature            | Specification                                      |
| :----------------- | :------------------------------------------------- |
| **Type**           | Unmanaged Industrial Switch (Automotive dedicated) |
| **Ethernet**       | 5 x RJ45 ports (10/100/1000 Mbps), Auto MDI/MDIX   |
| **PoE Out**        | **4 x PoE+ ports** (IEEE 802.3af/at)               |
| **Standards**      | IEEE 802.3, 802.3u, 802.3ab, 802.3x, 802.3az       |
| **Power Socket**   | 2-pin industrial DC power socket (9-30 VDC)        |
| **LED Indicators** | 1 x Power LED, 10 x LAN status LEDs                |

## 2. Power over Ethernet (PoE)

| Feature                | Specification                                        |
| :--------------------- | :--------------------------------------------------- |
| **PoE Ports**          | **Port 1 – 4**                                       |
| **PoE Standards**      | 802.3af/at compliant PSE (Mode B - over spare pairs) |
| **Max Power per Port** | 30 W                                                 |
| **Total PoE Budget**   | **60 W** (tại 12 VDC) / **120 W** (tại 24 VDC)       |

## 3. Performance Specifications

| Feature               | Specification                            |
| :-------------------- | :--------------------------------------- |
| **Bandwidth**         | 10 Gbps (Non-blocking)                   |
| **Packet Buffer**     | 128 KB                                   |
| **MAC Table**         | 2K entries                               |
| **Jumbo Frame**       | 9216 bytes                               |
| **Energy Efficiency** | IEEE 802.3az (Energy Efficient Ethernet) |

## 4. Power & Physical

| Feature           | Specification                                                            |
| :---------------- | :----------------------------------------------------------------------- | -------------------- | ---------------- |
| **Input Voltage** | **9 – 30 VDC** (Phù hợp với điện áp xe 12V/24V)                          |
| **Consumption**   | Idle: 0.6 W                                                              | Max: 1.5 W           | PoE Max: 121.5 W |
| **Housing**       | Aluminum housing, IP30 rating                                            |
| **Dimensions**    | 115 x 32 x 95 mm                                                         |
| **Weight**        | 354 g                                                                    |
| **Mounting**      | **Integrated DIN rail bracket**, Wall mount (tùy chọn kit), Flat surface |
| **Environment**   | Operating Temp: **-40°C to 75°C**                                        | Humidity: 10% to 90% |

## 5. Regulatory & Ordering

- **Regulatory:** CE, UKCA, **E-mark (Vehicle Certification)**, EAC, RCM, FCC, IC, CB.
- **HS Code:** 851762 | **HTS:** 8517.62.00.
- **Standard Package:** Switch TSW101, QSG, Packaging box.

_Lưu ý: Gói tiêu chuẩn mặc định không bao gồm bộ nguồn (PSU)._"
"# TSW010 – Industrial Unmanaged Switch

## 1. Hardware Overview & Interfaces

| Feature          | Specification                                             |
| :--------------- | :-------------------------------------------------------- |
| **Ethernet**     | 5 x RJ45 ports, 10/100 Mbps, Auto MDI/MDIX                |
| **Standards**    | IEEE 802.3i, 802.3u, 802.3x, 802.3az                      |
| **Power Socket** | 1 x 2-pin industrial DC power socket                      |
| **LEDs**         | 1 x Power LED, 10 x LAN status LEDs (Orange: Link/Active) |
| **Other**        | 1 x Grounding screw                                       |

## 2. Performance Specifications

| Parameter             | Value                 |
| :-------------------- | :-------------------- |
| **Bandwidth**         | 1 Gbps (Non-blocking) |
| **Packet Buffer**     | 128 KB                |
| **MAC Address Table** | 2K entries            |
| **Jumbo Frame**       | 2048 bytes            |

## 3. Power Specifications

| Feature           | Specification                                                             |
| :---------------- | :------------------------------------------------------------------------ | ---------- |
| **Input Voltage** | **9 – 30 VDC** (Reverse polarity & Surge protection)                      |
| **Passive PoE**   | Supported on ETH1 (Mode B, 9-30 VDC), _Not IEEE 802.3af/at/bt compatible_ |
| **Consumption**   | Idle: 0.3 W                                                               | Max: 0.9 W |

## 4. Physical & Environmental

| Feature                | Specification                                                            |
| :--------------------- | :----------------------------------------------------------------------- |
| **Casing**             | Full aluminum housing, IP30 rating                                       |
| **Dimensions**         | 113.1 x 27.4 x 80.5 mm                                                   |
| **Weight**             | 146.5 g                                                                  |
| **Mounting**           | **Integrated DIN rail bracket**, Wall mount (optional kit), Flat surface |
| **Operating Temp**     | **-40 °C to 75 °C**                                                      |
| **Operating Humidity** | 10% to 90% non-condensing                                                |

## 5. Regulatory & Safety

- **Regulatory:** CE, REACH, ROHS, WEEE, UKCA, FCC, IC, CB, RCM, GITEKI
- **Safety Standard:** EN IEC 62368-1:2020+A11:2020

## 6. Package Contents

- TSW010 Switch
- QSG (Quick Start Guide)
- Packaging box"
  "# TSW100 – Industrial Unmanaged PoE+ Switch

## 1. System Core & Interfaces

| Feature          | Specification                                        |
| :--------------- | :--------------------------------------------------- |
| **Ethernet**     | 5 x RJ45 ports, 10/100/1000 Mbps, Auto MDI/MDIX      |
| **PoE Out**      | 4 x PoE+ ports (Ports 1-4), IEEE 802.3af/at (Mode B) |
| **Power Socket** | 1 x 4-pin industrial DC power socket                 |
| **Status LEDs**  | 1 x Power LED, 10 x LAN status LEDs                  |
| **Other**        | 1 x Grounding screw                                  |

## 2. PoE & Power Specifications

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ | ----------------- | -------------- |
| **Input Voltage**      | **7 – 57 VDC** (PoE operation requires 44-57 VDC) |
| **PoE Standards**      | 802.3af/at compliant PSE                          |
| **PoE Max Power/Port** | 30 W (at PSE)                                     |
| **Total PoE Budget**   | **120 W** (at PSE)                                |
| **Consumption**        | Idle: 2 W                                         | Max: 9 W (no PoE) | PoE Max: 129 W |

## 3. Performance Specifications

| Parameter             | Value                  |
| :-------------------- | :--------------------- |
| **Bandwidth**         | 10 Gbps (Non-blocking) |
| **Packet Buffer**     | 128 KB                 |
| **MAC Address Table** | 2K entries             |
| **Jumbo Frame**       | 9216 bytes             |

## 4. Physical & Environmental

| Feature                | Specification                                              |
| :--------------------- | :--------------------------------------------------------- |
| **Housing**            | Aluminum housing, IP30 rating                              |
| **Dimensions**         | 115 x 32 x 95 mm                                           |
| **Weight**             | 350 g                                                      |
| **Mounting**           | **Integrated DIN rail bracket**, Wall mount (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                                        |
| **Operating Humidity** | 10% to 90% non-condensing                                  |

## 5. Regulatory & Safety

- **Regulatory:** CE, REACH, ROHS, WEEE, UKCA, FCC, IC, CB, RCM
- **Safety:** EN IEC 62368-1:2020+A11:2020

## 6. Package Contents

- TSW100 Switch
- QSG (Quick Start Guide)
- Packaging box"
  "# TSW110 – Industrial Unmanaged Gigabit Switch

## 1. Hardware Overview & Interfaces

| Feature          | Specification                                   |
| :--------------- | :---------------------------------------------- |
| **Ethernet**     | 5 x RJ45 ports, 10/100/1000 Mbps, Auto MDI/MDIX |
| **Standards**    | IEEE 802.3, 802.3u, 802.3ab, 802.3x, 802.3az    |
| **Power Socket** | 1 x 4-pin industrial DC power socket            |
| **Status LEDs**  | 1 x Power LED, 10 x LAN status LEDs             |
| **Other**        | 1 x Grounding screw                             |

## 2. Performance Specifications

| Parameter             | Value                  |
| :-------------------- | :--------------------- |
| **Bandwidth**         | 10 Gbps (Non-blocking) |
| **Packet Buffer**     | 128 KB                 |
| **MAC Address Table** | 2K entries             |
| **Jumbo Frame**       | 9216 bytes             |

## 3. Power Specifications

| Feature                 | Specification                       |
| :---------------------- | :---------------------------------- | ---------- |
| **Input Voltage**       | **9 – 30 VDC**                      |
| **Power Socket Pinout** | Pin 1: V+ (Red), Pin 2: GND (Black) |
| **Consumption**         | Idle: 0.4 W                         | Max: 1.8 W |

## 4. Physical & Environmental

| Feature                | Specification                                                            |
| :--------------------- | :----------------------------------------------------------------------- |
| **Housing**            | Full aluminum housing, IP30 rating                                       |
| **Dimensions**         | 115 x 32 x 95 mm                                                         |
| **Weight**             | 345 g                                                                    |
| **Mounting**           | **Integrated DIN rail bracket**, Wall mount (optional kit), Flat surface |
| **Operating Temp**     | **-40 °C to 75 °C**                                                      |
| **Operating Humidity** | 10% to 90% non-condensing                                                |

## 5. Regulatory & Certification

- **Regulatory:** CE, UKCA, EAC, RCM, FCC, IC, CB
- **HS Code:** 851762
- **HTS Code:** 8517.62.00

## 6. Package Contents

- TSW110 Switch
- QSG (Quick Start Guide)
- Packaging box"
  "# TRB501 – Industrial 5G Gateway

## 1. Hardware Overview & Interfaces

| Feature         | Specification                                                    |
| :-------------- | :--------------------------------------------------------------- |
| **Mobile**      | 5G Sub-6GHz SA/NSA (3GPP Release 16); 4G LTE Cat 19; 3G          |
| **Ethernet**    | 1 x RJ45 port, **10/100/1000/2500 Mbps**                         |
| **USB**         | 1 x Micro USB (Virtual network interface)                        |
| **I/O**         | 2 x Configurable digital Inputs/Outputs on 4-pin power connector |
| **SIM**         | 1 x Mini SIM slot (2FF)                                          |
| **Antennas**    | 4 x SMA connectors for Mobile                                    |
| **Status LEDs** | Connection type, Signal strength, ETH status, Power              |

## 2. System Core & Software

| Feature                  | Specification                                                   |
| :----------------------- | :-------------------------------------------------------------- | ----------------- |
| **CPU**                  | Qualcomm Single-Core, 1.5 GHz, ARM Cortex-A7                    |
| **Memory**               | **RAM:** 512 MB                                                 | **Flash:** 512 MB |
| **OS**                   | RutOS (OpenWrt based Linux OS)                                  |
| **Industrial Protocols** | Modbus TCP (Server/Client), MQTT Gateway, OPC UA, DNP3, DLMS    |
| **Security**             | Firewall, DDOS prevention, VLAN, WEB filter, Access Control     |
| **VPN**                  | OpenVPN, IPsec, WireGuard, ZeroTier, Tailscale, GRE, L2TP, PPTP |
| **Management**           | Web UI, RMS, CLI, SSH, SMS, SNMP, JSON-RPC, TR-069              |

## 3. Power Specifications

| Feature           | Specification                                   |
| :---------------- | :---------------------------------------------- | ---------- |
| **Power Input**   | **9 – 30 VDC** (4-pin industrial socket)        |
| **PoE (Passive)** | Passive PoE via ETH port (Mode B, 9-30 VDC)     |
| **Protection**    | Overvoltage, Reverse polarity, Surge protection |
| **Consumption**   | Idle: < 1.5 W                                   | Max: < 5 W |

## 4. Physical & Environmental

| Feature                | Specification                                               |
| :--------------------- | :---------------------------------------------------------- |
| **Housing**            | Anodized aluminum housing and panels, IP30 rating           |
| **Dimensions**         | 100 x 30 x 93.4 mm                                          |
| **Weight**             | 241 g                                                       |
| **Mounting**           | DIN rail, wall mount, or flat surface (via additional kits) |
| **Operating Temp**     | **-40 °C to 75 °C**                                         |
| **Operating Humidity** | 10% to 90% non-condensing                                   |

## 5. Regulatory & Certification

- **Regulatory:** CE, UKCA, RCM, CB, EAC, UCRF, WEEE, E-mark (Vehicle)
- **Safety:** EN IEC 62311:2020, EN IEC 62368-1:2020+A11:2020
  "
  "# TRB247 – Industrial LTE Cat 1 Gateway

## 1. System Core & Interfaces

| Feature      | Specification                                            |
| :----------- | :------------------------------------------------------- |
| **Mobile**   | 4G LTE Cat 1 bis (Up to 10 Mbps DL, 5 Mbps UL)           |
| **SIM**      | 2 x SIM slots (Mini SIM - 2FF), Dual SIM auto-switch     |
| **Ethernet** | 1 x RJ45 port, 10/100 Mbps                               |
| **GNSS**     | GPS, GLONASS, BeiDou, Galileo, QZSS                      |
| **Serial**   | 1 x RS232 (TX, RX, RTS, CTS); 1 x RS485 (D+, D-, R+, R-) |
| **I/O**      | 3 x Configurable digital Input/Output, 1 x Analog Input  |
| **Antennas** | 1 x SMA for LTE, 1 x SMA for GNSS                        |

## 2. Industrial & Network Features

| Feature        | Specification                                               |
| :------------- | :---------------------------------------------------------- |
| **Protocols**  | Modbus (TCP/RTU), DNP3, DLMS, BACnet (Router), OPC UA, MQTT |
| **VPN**        | OpenVPN, IPsec, WireGuard, ZeroTier, Tailscale, L2TP, PPTP  |
| **Routing**    | Static, BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP                |
| **Security**   | Firewall, DDOS prevention, VLAN, 802.1x, WEB filter         |
| **Management** | Teltonika RMS, Web UI, CLI, SSH, SMS, SNMP, TR-069          |
| **Location**   | NMEA 0183, NTRIP, Geofencing, Server (TAVL, RMS)            |

## 3. System Characteristics

| Parameter | Value                          |
| :-------- | :----------------------------- |
| **CPU**   | Mediatek, 580 MHz, MIPS 24KEC  |
| **RAM**   | 128 MB, DDR2                   |
| **FLASH** | 16 MB, SPI Flash               |
| **OS**    | RutOS (OpenWrt based Linux OS) |

## 4. Power Specifications

| Feature           | Specification                                        |
| :---------------- | :--------------------------------------------------- | ------------ |
| **Input Voltage** | **9 – 30 VDC** (Reverse polarity & Surge protection) |
| **Connector**     | 2-pin (integrated in 16-pin terminal block)          |
| **Consumption**   | Idle: < 1.7 W                                        | Max: < 2.6 W |

## 5. Physical & Environmental

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ |
| **Housing**            | Anodized aluminum housing and panels, IP30 rating |
| **Dimensions**         | 83 x 25 x 82.6 mm                                 |
| **Weight**             | 181 g                                             |
| **Mounting**           | DIN rail, wall mount, flat surface (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                               |
| **Operating Humidity** | 10% to 90% non-condensing                         |

## 6. Regulatory & Safety

- **Regulatory:** FCC, ISED, WEEE, FCC/IC
- **RF Standards:** 47 CFR Part 15 Subpart B, ICES-003
- **HS Code:** 851762
  "
  "# NTP001 – GNSS NTP Time Server

## 1. Hardware Overview & Interfaces

| Feature         | Specification                                            |
| :-------------- | :------------------------------------------------------- |
| **NTP Role**    | Stratum 1 Time Server (NTPv4)                            |
| **GNSS**        | GPS, GLONASS, BeiDou, Galileo, QZSS                      |
| **Ethernet**    | 1 x RJ45 port, 10/100 Mbps                               |
| **Serial**      | 1 x RS232 (TX, RX, RTS, CTS); 1 x RS485 (D+, D-, R+, R-) |
| **I/O**         | 3 x Configurable digital I/O, 1 x Analog Input           |
| **Antenna**     | 1 x SMA for GNSS                                         |
| **Status LEDs** | 1x Power, 2x GNSS, 1x NTP Server, 3x IO status           |

## 2. NTP & Network Performance

| Parameter           | Value                                                             |
| :------------------ | :---------------------------------------------------------------- |
| **NTP Accuracy**    | Ethernet NTP ±1ms overall                                         |
| **NTP Performance** | >300 NTP requests per second (wire speed)                         |
| **Sync Accuracy**   | LAN synchronization typically 1-10ms                              |
| **NTP Modes**       | Unicast, Multicast, Broadcast                                     |
| **Protocols**       | NTPv4, Daytime Protocol (TCP/UDP), Date over Serial               |
| **Security**        | NTP Authentication (MD5/SHA1), 802.1x, Web Filter, Access Control |

## 3. Industrial Protocols & Management

| Feature        | Specification                                               |
| :------------- | :---------------------------------------------------------- |
| **Modbus**     | Modbus TCP & RTU (Server/Client)                            |
| **MQTT**       | MQTT Gateway (Modbus MQTT Gateway), MQTT Publisher          |
| **Management** | Web UI, SSH, SNMP (v1, v2, v3), JSON-RPC, Modbus TCP status |
| **Monitoring** | Ping Reboot, Wget Reboot, Periodic Reboot                   |
| **API**        | Teltonika Networks Web API support                          |

## 4. System Characteristics

| Parameter  | Value                          |
| :--------- | :----------------------------- | --------------------------- |
| **CPU**    | Mediatek, 580 MHz, MIPS 24KEC  |
| **Memory** | **RAM:** 128 MB, DDR2          | **Flash:** 16 MB, NOR Flash |
| **OS**     | RutOS (OpenWrt based Linux OS) |

## 5. Power Specifications

| Feature           | Specification                                   |
| :---------------- | :---------------------------------------------- | ------------ |
| **Input Voltage** | **9 – 30 VDC** (2-pin in 16-pin terminal block) |
| **Protection**    | Overvoltage, Reverse polarity, Surge protection |
| **Consumption**   | Idle: < 2 W                                     | Max: < 3.5 W |

## 6. Physical & Environmental

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ |
| **Housing**            | Anodized aluminum housing and panels, IP30 rating |
| **Dimensions**         | 82.6 x 25 x 83 mm                                 |
| **Weight**             | 180 g                                             |
| **Mounting**           | DIN rail, wall mount, flat surface (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                               |
| **Operating Humidity** | 10% to 90% non-condensing                         |

## 7. Regulatory & Safety

- **Regulatory:** CE, UKCA, CB, UCRF, EAC, WEEE
- **HS Code:** 851762 | **HTS:** 8517.62.00
  "
  "# TRB160 – Industrial 4G LTE Cat 6 Gateway

## 1. System Core & Interfaces

| Feature         | Specification                                           |
| :-------------- | :------------------------------------------------------ |
| **Mobile**      | 4G LTE Cat 6 (Up to 300 Mbps DL / 50 Mbps UL); 3G       |
| **Ethernet**    | 1 x RJ45 port, 10/100/1000 Mbps                         |
| **USB**         | 1 x USB Type-C (Power, Network data, Virtual interface) |
| **I/O**         | 2 x Configurable digital I/O on 4-pin power connector   |
| **SIM**         | 1 x Internal SIM slot (Mini SIM-2FF), eSIM (Optional)   |
| **Antennas**    | 2 x SMA for Mobile                                      |
| **Status LEDs** | Connection type, Signal strength, ETH status, Power     |

## 2. Software & Network Features

| Feature                  | Specification                                                         |
| :----------------------- | :-------------------------------------------------------------------- |
| **Industrial Protocols** | Modbus TCP (Server/Client), MQTT Gateway, OPC UA (Client), DNP3, DLMS |
| **Security**             | Firewall, DDOS prevention, VLAN, MAC address filter, Web Filter       |
| **VPN**                  | OpenVPN, IPsec, WireGuard, ZeroTier, GRE, L2TP, PPTP, Stunnel, DMVPN  |
| **Management**           | Web UI, Teltonika RMS, FOTA, SSH, SMS, SNMP, JSON-RPC, TR-069         |
| **IoT Platforms**        | Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity                    |
| **Routing**              | Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing          |

## 3. System Characteristics

| Parameter | Value                            |
| :-------- | :------------------------------- |
| **CPU**   | Qualcomm, 1.2 GHz, ARM Cortex-A7 |
| **RAM**   | 128 MB                           |
| **FLASH** | 256 MB                           |
| **OS**    | RutOS (OpenWrt based Linux OS)   |

## 4. Power Specifications

| Feature           | Specification                                                      |
| :---------------- | :----------------------------------------------------------------- | ------------ |
| **Power Inputs**  | 4-pin Industrial socket (**9 – 30 VDC**) or USB Type-C (**5 VDC**) |
| **PoE (Passive)** | Passive PoE via ETH port (Mode B, 9-30 VDC)                        |
| **Protection**    | Overvoltage, Reverse polarity, Surge protection                    |
| **Consumption**   | Idle: < 0.25 W                                                     | Max: < 3.3 W |

## 5. Physical & Environmental

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ |
| **Housing**            | Anodized aluminum housing and panels, IP30 rating |
| **Dimensions**         | 83 x 25 x 74.2 mm                                 |
| **Weight**             | 172 g                                             |
| **Mounting**           | DIN rail, wall mount, flat surface (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                               |
| **Operating Humidity** | 10% to 90% non-condensing                         |

## 6. Regulatory & Safety

- **Regulatory:** CE, UKCA, CB
- **EMC/RF:** EN 301 489-1, EN 301 489-52, EN 301 908-1/2/13
- **Safety:** EN IEC 62368-1, EN IEC 62311
  "
  "# TRB246 – Industrial LTE Cat 4 Gateway

## 1. System Core & Interfaces

| Feature         | Specification                                                  |
| :-------------- | :------------------------------------------------------------- |
| **Mobile**      | 4G LTE Cat 4 (Up to 150 Mbps DL / 50 Mbps UL); 3G; 2G          |
| **SIM**         | 2 x SIM slots (Mini SIM - 2FF), Dual SIM auto-switch           |
| **Ethernet**    | 1 x RJ45 port, 10/100 Mbps                                     |
| **GNSS**        | GPS, GLONASS, BeiDou, Galileo, QZSS                            |
| **Serial**      | 1 x RS232 (TX, RX, RTS, CTS); 1 x RS485 (D+, D-, R+, R-)       |
| **I/O**         | 3 x Configurable digital I/O, 1 x Analog Input (0-30 V)        |
| **Antennas**    | 1 x SMA for LTE, 1 x SMA for GNSS                              |
| **Status LEDs** | 3 x Connection status, 3 x Signal strength, 1 x Power, 1 x ETH |

## 2. Industrial & Network Features

| Feature           | Specification                                                   |
| :---------------- | :-------------------------------------------------------------- |
| **Protocols**     | Modbus (TCP/RTU), DNP3, DLMS, BACnet (Router), OPC UA, MQTT     |
| **VPN**           | OpenVPN, IPsec, WireGuard, ZeroTier, Tailscale, GRE, L2TP, PPTP |
| **Management**    | Web UI, Teltonika RMS, FOTA, SSH, SMS, SNMP (v1/v2/v3), TR-069  |
| **Location**      | NMEA 0183, NTRIP, Geofencing, Accuracy 2.5m CEP                 |
| **IoT Platforms** | Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity              |
| **Routing**       | Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing    |

## 3. System Characteristics

| Parameter | Value                          |
| :-------- | :----------------------------- |
| **CPU**   | Mediatek, 580 MHz, MIPS 24KEC  |
| **RAM**   | 128 MB                         |
| **FLASH** | 16 MB                          |
| **OS**    | RutOS (OpenWrt based Linux OS) |

## 4. Power Specifications

| Feature           | Specification                                        |
| :---------------- | :--------------------------------------------------- | ------------ |
| **Input Voltage** | **9 – 30 VDC** (2-pin in 16-pin terminal block)      |
| **Protection**    | Reverse polarity, Surge protection +/-1 kV 50 µs max |
| **Consumption**   | Idle: < 1.5 W                                        | Max: < 3.5 W |

## 5. Physical & Environmental

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ |
| **Housing**            | Aluminum housing, IP30 rating                     |
| **Dimensions**         | 83 x 25 x 74.2 mm                                 |
| **Weight**             | 165 g                                             |
| **Mounting**           | DIN rail, wall mount, flat surface (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                               |
| **Operating Humidity** | 10% to 90% non-condensing                         |

## 6. Regulatory & Safety

- **Regulatory:** CE, UKCA, EAC, RCM, FCC, IC, CB, WEEE
- **EMC:** EN 55032, EN 55035, EN 301 489-1/19/52
- **Safety:** EN IEC 62368-1, EN IEC 62311

## 7. Package Contents

- Gateway TRB246
- 16-pin terminal block
- 1 x Hex key
- QSG (Quick Start Guide)
- Packaging box
  _(Lưu ý: Anten và PSU tùy thuộc vào mã đặt hàng cụ thể)_"
  "# TRB256 – Industrial NB-IoT/LTE Cat M1 Gateway

## 1. System Core & Interfaces

| Feature         | Specification                                             |
| :-------------- | :-------------------------------------------------------- |
| **Mobile**      | 4G LTE Cat M1 (588 DL/1119 UL kbps); NB-IoT (Cat NB1/NB2) |
| **SIM**         | 2 x SIM slots (Mini SIM - 2FF), Dual SIM auto-switch      |
| **Ethernet**    | 1 x RJ45 port, 10/100 Mbps                                |
| **GNSS**        | GPS (GLONASS, BeiDou, Galileo, QZSS under development)    |
| **Serial**      | 1 x RS232 (TX, RX, RTS, CTS); 1 x RS485 (D+, D-, R+, R-)  |
| **I/O**         | 3 x Configurable digital I/O, 1 x Analog Input (0-30 V)   |
| **Antennas**    | 1 x SMA for LTE, 1 x SMA for GNSS                         |
| **Status LEDs** | Network type (2G/NB/M1), Signal strength, Power, ETH      |

## 2. Industrial & Network Features

| Feature           | Specification                                                 |
| :---------------- | :------------------------------------------------------------ |
| **Protocols**     | Modbus (TCP/RTU), DNP3, DLMS, BACnet (Router), OPC UA, MQTT   |
| **VPN**           | OpenVPN, IPsec, WireGuard, ZeroTier, GRE, L2TP, PPTP, Stunnel |
| **Management**    | Web UI, Teltonika RMS, FOTA, SSH, SMS, SNMP, JSON-RPC, TR-069 |
| **Location**      | NMEA 0183, NTRIP, Geofencing, Server (TAVL, RMS)              |
| **IoT Platforms** | Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity            |
| **Routing**       | Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing  |

## 3. System Characteristics

| Parameter | Value                          |
| :-------- | :----------------------------- |
| **CPU**   | Mediatek, 580 MHz, MIPS 24KEC  |
| **RAM**   | 128 MB                         |
| **FLASH** | 16 MB                          |
| **OS**    | RutOS (OpenWrt based Linux OS) |

## 4. Power Specifications

| Feature           | Specification                                        |
| :---------------- | :--------------------------------------------------- | ---------- |
| **Input Voltage** | **9 – 30 VDC** (2-pin in 16-pin terminal block)      |
| **Protection**    | Reverse polarity, Surge protection +/-1 kV 50 µs max |
| **Consumption**   | Idle: 2 W                                            | Max: 3.5 W |

## 5. Physical & Environmental

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ |
| **Housing**            | Aluminum housing, IP30 rating                     |
| **Dimensions**         | 83 x 25 x 74.2 mm                                 |
| **Weight**             | 165 g                                             |
| **Mounting**           | DIN rail, wall mount, flat surface (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                               |
| **Operating Humidity** | 10% to 90% non-condensing                         |

## 6. Regulatory & Safety

- **Regulatory:** CE, UKCA, EAC, RCM, CB, WEEE
- **EMC:** EN 55032, EN 55035, EN 301 489-1/19/52
- **Safety:** EN IEC 62368-1, EN IEC 62311

## 7. Package Contents

- Gateway TRB256
- 16-pin terminal block
- 1 x Hex key
- QSG (Quick Start Guide)
- Packaging box
  _(Lưu ý: Anten và PSU tùy thuộc vào mã đặt hàng cụ thể)_"
  "# TRB145 – Industrial RS485 LTE Gateway

## 1. System Core & Interfaces

| Feature         | Specification                                         |
| :-------------- | :---------------------------------------------------- |
| **Mobile**      | 4G LTE Cat 1 (Up to 10 Mbps); 3G; 2G                  |
| **RS485**       | 1 x 6-pin terminal block (2-wire or 4-wire interface) |
| **USB**         | 1 x Micro USB (Virtual network interface)             |
| **I/O**         | 2 x Configurable digital I/O on 4-pin power connector |
| **SIM**         | 1 x SIM slot (Mini SIM - 2FF)                         |
| **Antenna**     | 1 x SMA connector for LTE                             |
| **Status LEDs** | 3 x connection type, 5 x signal strength, 1 x Power   |

[Image of Teltonika TRB145 front and rear panel layout]

## 2. Industrial & Software Features

| Feature           | Specification                                                     |
| :---------------- | :---------------------------------------------------------------- |
| **Serial Modes**  | Console, OverIP, Modem, Modbus RTU Master, Modbus Gateway         |
| **Modbus**        | Modbus TCP (Master/Slave), Modbus RTU (Master)                    |
| **Protocols**     | TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP(S), MQTT, SNMP         |
| **VPN**           | OpenVPN (12 encryption methods), IPsec, WireGuard, ZeroTier, GRE  |
| **Security**      | Firewall, DDOS prevention, VLAN, Port scan prevention, Web Filter |
| **Management**    | Web UI, Teltonika RMS, FOTA, SSH, SMS, JSON-RPC, TR-069           |
| **IoT Platforms** | Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity             |

## 3. System Characteristics

| Parameter | Value                                   |
| :-------- | :-------------------------------------- |
| **CPU**   | ARM Cortex-A7, 1.2 GHz                  |
| **RAM**   | 128 MB (50 MB available for userspace)  |
| **FLASH** | 512 MB (200 MB available for userspace) |
| **OS**    | RutOS (OpenWrt based Linux OS)          |

## 4. Power Specifications

| Feature           | Specification                                         |
| :---------------- | :---------------------------------------------------- |
| **Input Voltage** | **9 – 30 VDC** (4-pin industrial socket)              |
| **Protection**    | Reverse polarity protection, Surge protection >33 VDC |
| **Consumption**   | < 5 W                                                 |

[Image of Teltonika TRB145 4-pin power socket pinout and RS485 terminal block]

## 5. Physical & Environmental

| Feature                | Specification                            |
| :--------------------- | :--------------------------------------- |
| **Housing**            | Aluminum housing, IP30 rating            |
| **Dimensions**         | 74.5 x 25 x 64.4 mm                      |
| **Weight**             | 130 g                                    |
| **Mounting**           | DIN rail (bottom/sideways), Flat surface |
| **Operating Temp**     | **-40 °C to 75 °C**                      |
| **Operating Humidity** | 10% to 90% non-condensing                |

[Image of Teltonika TRB145 physical dimensions and spatial measurements]

## 6. Regulatory & Safety

- **Regulatory:** CE/RED, EAC, ROHS, WEEE
- **Safety:** IEC 62368-1, EN 62368-1, EN 50385, EN 62232
- **EMI:** EN 301 489-1/19/52, EN 61000-4-2/3/4/5/6/11

## 7. Package Contents

- TRB145 Gateway
- 4.5 W PSU
- 1 x LTE antenna (magnetic mount, SMA male, 3 m cable)
- Micro-USB cable (0.8 m)
- RS485 connector & Hex key
- QSG (Quick Start Guide)"
  "# TRB255 – Industrial LPWAN Gateway

## 1. System Core & Interfaces

| Feature         | Specification                                                |
| :-------------- | :----------------------------------------------------------- |
| **Mobile**      | LTE Cat M1 / NB-IoT / EGPRS                                  |
| **SIM**         | 2 x SIM slots (Mini SIM - 2FF), Dual SIM auto-switch         |
| **Ethernet**    | 1 x RJ45 port, 10/100 Mbps                                   |
| **GNSS**        | GPS, GLONASS, BeiDou, Galileo, QZSS                          |
| **Serial**      | 1 x RS232 (TX, RX, RTS, CTS); 1 x RS485 (D+, D-, R+, R-)     |
| **I/O**         | 3 x Configurable digital I/O, 1 x Analog Input (0-30 V)      |
| **Antennas**    | 1 x SMA for LTE, 1 x SMA for GNSS                            |
| **Status LEDs** | 3 x Connection type, 3 x Signal strength, 1 x Power, 1 x ETH |

## 2. Industrial & Network Features

| Feature           | Specification                                                  |
| :---------------- | :------------------------------------------------------------- |
| **Protocols**     | Modbus (TCP/RTU), DNP3 (Master/Outstation), MQTT Gateway       |
| **VPN**           | OpenVPN, IPsec, WireGuard, ZeroTier, GRE, L2TP, PPTP, Stunnel  |
| **Management**    | Web UI, Teltonika RMS, FOTA, SSH, SMS, SNMP (v1/v2/v3), TR-069 |
| **Location**      | NMEA 0183, NTRIP, Geofencing, Server (TAVL, RMS)               |
| **Security**      | Firewall, DDOS prevention, VLAN, MAC filter, Web Filter        |
| **IoT Platforms** | Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity          |

## 3. System Characteristics

| Parameter | Value                                |
| :-------- | :----------------------------------- |
| **CPU**   | Qualcomm QCA9531, MIPS 24kc, 650 MHz |
| **RAM**   | 64 MB, DDR2                          |
| **FLASH** | 16 MB, SPI Flash                     |
| **OS**    | RutOS (OpenWrt based Linux OS)       |

## 4. Power Specifications

| Feature           | Specification                                        |
| :---------------- | :--------------------------------------------------- | ---------- |
| **Input Voltage** | **9 – 30 VDC** (2-pin in 16-pin terminal block)      |
| **Protection**    | Reverse polarity, Surge protection +/-1 kV 50 µs max |
| **Consumption**   | Idle: < 1.2 W                                        | Max: < 5 W |

## 5. Physical & Environmental

| Feature                | Specification                      |
| :--------------------- | :--------------------------------- |
| **Housing**            | Aluminum housing, IP30 rating      |
| **Dimensions**         | 83 x 25 x 74.2 mm                  |
| **Weight**             | 165 g                              |
| **Mounting**           | DIN rail (two sides), Flat surface |
| **Operating Temp**     | **-40 °C to 75 °C**                |
| **Operating Humidity** | 10% to 90% non-condensing          |

## 6. Regulatory & Safety

- **Regulatory:** CE/RED, UKCA, EAC, UCRF, ROHS, REACH, CITC, ICASA, GITEKI, NTC, FCC, IC, NOM
- **Safety:** EN IEC 62368-1, EN IEC 62311
  "
  "# TRB245 – Industrial LTE Cat 4 Gateway

## 1. Hardware Overview & Interfaces

| Feature         | Specification                                                  |
| :-------------- | :------------------------------------------------------------- |
| **Mobile**      | 4G LTE Cat 4 (Up to 150 Mbps DL / 50 Mbps UL); 3G; 2G          |
| **SIM**         | 2 x SIM slots (Mini SIM - 2FF), Dual SIM auto-switch           |
| **Ethernet**    | 1 x RJ45 port, 10/100 Mbps                                     |
| **GNSS**        | GPS, GLONASS, BeiDou, Galileo, QZSS                            |
| **Serial**      | 1 x RS232 (TX, RX, RTS, CTS); 1 x RS485 (D+, D-, R+, R-)       |
| **I/O**         | 3 x Configurable digital I/O, 1 x Analog Input (0-30 V)        |
| **Antennas**    | 1 x SMA for LTE, 1 x SMA for GNSS                              |
| **Status LEDs** | 3 x Connection status, 3 x Signal strength, 1 x Power, 1 x ETH |

[Image of Teltonika TRB245 front and rear panel layout]

## 2. Industrial & Network Features

| Feature           | Specification                                                  |
| :---------------- | :------------------------------------------------------------- |
| **Protocols**     | Modbus (TCP/RTU), DNP3 (Master/Outstation), MQTT Gateway       |
| **VPN**           | OpenVPN, IPsec, WireGuard, ZeroTier, GRE, L2TP, PPTP, Stunnel  |
| **Management**    | Web UI, Teltonika RMS, FOTA, SSH, SMS, SNMP (v1/v2/v3), TR-069 |
| **Location**      | NMEA 0183, NTRIP, Geofencing, Server (TAVL, RMS)               |
| **Security**      | Firewall, DDOS prevention, VLAN, MAC filter, Web Filter        |
| **IoT Platforms** | Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity          |

## 3. System Characteristics

| Parameter | Value                                |
| :-------- | :----------------------------------- |
| **CPU**   | Qualcomm QCA9531, MIPS 24kc, 650 MHz |
| **RAM**   | 64 MB, DDR2                          |
| **FLASH** | 16 MB, SPI Flash                     |
| **OS**    | RutOS (OpenWrt based Linux OS)       |

## 4. Power Specifications

| Feature           | Specification                                        |
| :---------------- | :--------------------------------------------------- | ---------- |
| **Input Voltage** | **9 – 30 VDC** (2-pin in 16-pin terminal block)      |
| **Protection**    | Reverse polarity, Surge protection +/-1 kV 50 µs max |
| **Consumption**   | Idle: < 1.2 W                                        | Max: < 5 W |

[Image of Teltonika TRB245 16-pin terminal block pinout]

## 5. Physical & Environmental

| Feature                | Specification                      |
| :--------------------- | :--------------------------------- |
| **Housing**            | Aluminum housing, IP30 rating      |
| **Dimensions**         | 83 x 25 x 74.2 mm                  |
| **Weight**             | 165 g                              |
| **Mounting**           | DIN rail (two sides), Flat surface |
| **Operating Temp**     | **-40 °C to 75 °C**                |
| **Operating Humidity** | 10% to 90% non-condensing          |

[Image of Teltonika TRB245 physical dimensions and spatial measurements]

## 6. Regulatory & Safety

- **Regulatory:** CE/RED, UKCA, EAC, RCM, FCC, IC, CB, NOM
- **Safety:** EN IEC 62368-1, EN IEC 62311
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 7. Package Contents

- Gateway TRB245
- 9 W PSU (EU/US/AU/JP tùy mã)
- 1 x LTE antenna (swivel, SMA male)
- 1 x GNSS antenna (adhesive, SMA male, 3 m cable)
- 16-pin terminal block
- Ethernet cable (1.5 m) & Hex key
- QSG (Quick Start Guide)"
  "# TRB143 – Industrial M-Bus Gateway

## 1. System Core & Interfaces

| Feature      | Specification                                                       |
| :----------- | :------------------------------------------------------------------ |
| **CPU**      | ARM Cortex-A7, 1.3 GHz                                              |
| **Memory**   | **RAM:** 256 MB, DDR3 <br> **Flash:** 512 MB, SPI Flash             |
| **Ethernet** | 1 x RJ45 port, 10/100/1000 Mbps                                     |
| **M-Bus**    | **1 x M-Bus Interface** (Supports up to 250 slaves, powers up to 6) |
| **SIM**      | 1 x Mini SIM slot (2FF), 1.8 V/3 V                                  |
| **I/O**      | 1 x Digital Input, 1 x Digital Output on 4-pin power connector      |
| **Antenna**  | 1 x SMA connector for LTE                                           |

## 2. Mobile & Networking

| Feature              | Specification                                                                                                         |
| :------------------- | :-------------------------------------------------------------------------------------------------------------------- |
| **Mobile Module**    | 4G (LTE) Cat 4 (150 Mbps DL), 3G, 2G                                                                                  |
| **Protocols**        | TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP(S), SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, SSH, DHCP, SNMP, MQTT |
| **Network Features** | Static routing, Failover (Wired/Mobile), Load balancing, Bridge, Passthrough                                          |
| **Security**         | Firewall (Port forward, NAT), DDOS prevention, Port scan prevention, VLAN, Web filter                                 |

## 3. Industrial Protocols & VPN

- **Industrial Protocols:**
  - **M-Bus:** Master interface for utility meter data exchange
  - **Modbus:** TCP Master/Slave (with custom registers)
  - **Data to Server:** HTTP(S), MQTT, Azure MQTT, Kinesis
  - **MQTT Gateway:** Modbus Master to MQTT Broker
  - **DNP3:** TCP Master, Outstation
- **VPN Support:**
  - OpenVPN (27 encryption methods), IPsec (IKEv1, IKEv2), WireGuard, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN, Tailscale

## 4. Power & Physical

| Feature         | Specification                                 |
| :-------------- | :-------------------------------------------- | -------- |
| **Power Input** | **12 – 30 VDC** (4-pin industrial DC socket)  |
| **PoE**         | Passive PoE (via LAN port, Mode B, 12-30 VDC) |
| **Consumption** | Idle: 3 W                                     | Max: 6 W |
| **Housing**     | Aluminum housing, IP30 rating                 |
| **Dimensions**  | 74.5 x 25 x 73 mm                             |
| **Weight**      | 145 g                                         |
| **Environment** | Operating Temp: **-40°C to 75°C**             |

## 5. Management & Software

- **Operating System:** RUTOS (OpenWrt based Linux OS)
- **Management Tools:** Teltonika RMS, Web UI, CLI (SSH), SMS Control, TR-069, JSON-RPC, FOTA
- **Cloud Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub, AWS IoT Core

## 6. Package Contents

- TRB143 Gateway
- 18 W PSU
- 1 x LTE antenna (magnetic mount, SMA male, 3 m cable)
- Ethernet cable & Hex key
- QSG (Quick Start Guide)"
  "# TRB142 – Industrial RS232 LTE Gateway

## 1. System Core & Interfaces

| Feature     | Specification                                           |
| :---------- | :------------------------------------------------------ |
| **Mobile**  | 4G LTE Cat 1 (Up to 10 Mbps); 3G; 2G                    |
| **RS232**   | **1 x DB9 Female socket** (Full RS232 pinout supported) |
| **CPU**     | ARM Cortex-A7, 1.2 GHz                                  |
| **Memory**  | **RAM:** 128 MB, DDR2 <br> **Flash:** 512 MB, SPI Flash |
| **USB**     | 1 x Micro USB (Virtual network interface)               |
| **I/O**     | 2 x Configurable digital I/O on 4-pin power connector   |
| **SIM**     | 1 x SIM slot (Mini SIM - 2FF)                           |
| **Antenna** | 1 x SMA connector for LTE                               |

## 2. Serial & Industrial Protocols

- **RS232 Interface:**
  - Baud rates: 300 to 115200 bps
  - Functions: Console, OverIP, Modem, Modbus gateway, NTRIP Client
- **Supported Protocols:**
  - **Modbus:** TCP Master/Slave, RTU Master (via RS232)
  - **MQTT:** MQTT Broker, MQTT Publisher, MQTT Gateway
  - **DNP3:** TCP Master, Outstation, RTU Master
  - **Data to Server:** HTTP(S), MQTT, Azure MQTT, Kinesis
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SMS Control, TR-069, JSON-RPC, FOTA

## 3. Power & Physical

| Feature         | Specification                                        |
| :-------------- | :--------------------------------------------------- |
| **Power Input** | **9 – 30 VDC** (Reverse polarity & Surge protection) |
| **Consumption** | < 5 W                                                |
| **Housing**     | Aluminum housing, IP30 rating                        |
| **Dimensions**  | 74.5 x 25 x 64.4 mm                                  |
| **Weight**      | 135 g                                                |
| **Mounting**    | DIN rail (bottom/sideways), Flat surface             |
| **Environment** | Operating Temp: **-40 °C to 75 °C**                  |

## 4. Network & Security Features

- **Routing:** Static routing, VRRP, Mobile failover
- **VPN:** OpenVPN (27 encryption methods), IPsec (IKEv1/v2), WireGuard, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN
- **Firewall:** Port forward, Traffic rules, NAT, Attack prevention (DDOS, Port scan)
- **IoT Platforms:** Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity

## 5. Package Contents

- TRB142 Gateway
- 9 W PSU
- 1 x LTE antenna (magnetic mount, SMA male, 3 m cable)
- Micro-USB cable (0.8 m) & Hex key
- QSG (Quick Start Guide)"
  "# TRB141 – Industrial I/O LTE Gateway

## 1. System Core & Interfaces

| Feature           | Specification                                                      |
| :---------------- | :----------------------------------------------------------------- |
| **Mobile**        | 4G LTE Cat 1 (Up to 10 Mbps); 3G; 2G                               |
| **CPU**           | ARM Cortex-A7, 1.2 GHz                                             |
| **Memory**        | **RAM:** 128 MB, DDR2 <br> **Flash:** 512 MB, SPI Flash            |
| **Ethernet**      | Virtual network interface via Micro-USB                            |
| **I/O Connector** | **16-pin terminal block** (Relays, DI, AI, Isolated Input, 1-Wire) |
| **Antenna**       | 1 x SMA connector for LTE                                          |
| **SIM**           | 1 x Mini SIM slot (2FF), 1.8 V/3 V                                 |

## 2. Advanced Input/Output Features

- **Relay Outputs:**
  - 1 x Non-latching relay (0.5A @ 60VDC)
  - 1 x Latching relay (0.8A @ 70VDC)
- **Analog Input:** 0-30V DC range, configurable for 4-20mA sensors
- **Digital Inputs:**
  - 2 x Configurable (Dry/Wet)
  - 1 x Isolated input (Up to 71V)
- **1-Wire Interface:** Supports 1-Wire protocol for temperature/humidity sensors
- **Power Output:** 3.8V and direct Vin output pins for powering external sensors

## 3. Networking & Software

| Feature               | Specification                                                                                                         |
| :-------------------- | :-------------------------------------------------------------------------------------------------------------------- |
| **Protocols**         | TCP, UDP, IPv4, IPv6, ICMP, NTP, DNS, HTTP(S), SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, SSH, DHCP, SNMP, MQTT |
| **VPN**               | OpenVPN (27 encryption methods), IPsec (IKEv1/v2), WireGuard, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN             |
| **Industrial**        | Modbus TCP Master/Slave, Modbus RTU Master, DNP3, MQTT Gateway                                                        |
| **Management**        | Web UI, Teltonika RMS, FOTA, SSH, SMS Control, TR-069, JSON-RPC                                                       |
| **Cloud Integration** | Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity                                                                 |

## 4. Power & Physical

| Feature         | Specification                               |
| :-------------- | :------------------------------------------ |
| **Power Input** | **9 – 30 VDC** (4-pin industrial DC socket) |
| **Consumption** | < 5 W                                       |
| **Housing**     | Aluminum housing, IP30 rating               |
| **Dimensions**  | 74.5 x 25 x 64.4 mm                         |
| **Weight**      | 136 g                                       |
| **Environment** | Operating Temp: **-40 °C to 75 °C**         |
| **Mounting**    | DIN rail (bottom/sideways), Flat surface    |

## 5. Regulatory & Safety

- **Regulatory:** CE/RED, EAC, ROHS, WEEE
- **EMC:** EN 301 489-1/19/52, EN 61000-4-2/3/4/5/6/11
- **Safety:** IEC 62368-1, EN 50385, EN 62232

## 6. Package Contents

- TRB141 Gateway
- 9 W PSU
- 1 x LTE antenna (magnetic mount, SMA male, 3 m cable)
- Micro-USB cable (0.8 m)
- 16-pin I/O connector & Hex key
- QSG (Quick Start Guide)"
  "# TRB500 – Industrial 5G Gateway

## 1. System Core & Interfaces

| Feature         | Specification                                                                    |
| :-------------- | :------------------------------------------------------------------------------- |
| **Mobile**      | **5G Sub-6GHz SA/NSA** (DL up to 3.3 Gbps, UL up to 600 Mbps); 4G LTE Cat 20; 3G |
| **Ethernet**    | 1 x RJ45 port, **10/100/1000 Mbps**                                              |
| **USB**         | 1 x Micro USB (Virtual network interface)                                        |
| **SIM**         | 1 x SIM slot (Mini SIM - 2FF)                                                    |
| **I/O**         | 1 x Digital Input, 1 x Digital Output (on 4-pin power connector)                 |
| **Antennas**    | 4 x SMA connectors for Mobile                                                    |
| **Status LEDs** | Network type, Signal strength, LAN status, Power                                 |

[Image of Teltonika TRB500 front and rear panel layout]

## 2. Industrial & Software Features

| Feature           | Specification                                                            |
| :---------------- | :----------------------------------------------------------------------- |
| **Protocols**     | Modbus TCP (Master/Slave), MQTT Gateway, DNP3 (Master/Outstation)        |
| **VPN**           | OpenVPN, IPsec, WireGuard, ZeroTier, GRE, L2TP, PPTP, Stunnel, Tailscale |
| **Management**    | Web UI, Teltonika RMS, FOTA, SSH, SMS Control, TR-069, JSON-RPC          |
| **Security**      | Firewall, DDOS prevention, VLAN, Port scan prevention, Web Filter        |
| **IoT Platforms** | Azure IoT Hub, Cloud of Things, ThingWorx, Cumulocity                    |
| **Routing**       | Static, BGP, OSPF v2, RIP v1/v2, EIGRP, Policy based routing             |

## 3. System Characteristics

| Parameter         | Value                                                 |
| :---------------- | :---------------------------------------------------- | ----------------- |
| **CPU**           | Single core ARM Cortex A7, 1.5 GHz                    |
| **Memory**        | **RAM:** 256 MB                                       | **Flash:** 512 MB |
| **OS**            | RutOS (OpenWrt based Linux OS)                        |
| **Customization** | SDK, Busybox shell, Lua, C, C++, Python, Java support |

## 4. Power Specifications

| Feature           | Specification                                        |
| :---------------- | :--------------------------------------------------- | ---------- |
| **Input Voltage** | **9 – 30 VDC** (4-pin industrial socket)             |
| **Protection**    | Reverse polarity, Surge protection +/-1 kV 50 µs max |
| **Consumption**   | Idle: < 3 W                                          | Max: < 6 W |

[Image of Teltonika TRB500 4-pin power socket pinout]

## 5. Physical & Environmental

| Feature                | Specification                 |
| :--------------------- | :---------------------------- |
| **Housing**            | Aluminum housing, IP30 rating |
| **Dimensions**         | 100 x 30 x 93.4 mm            |
| **Weight**             | 241 g                         |
| **Mounting**           | DIN rail, Flat surface        |
| **Operating Temp**     | **-40 °C to 75 °C**           |
| **Operating Humidity** | 10% to 90% non-condensing     |

[Image of Teltonika TRB500 spatial measurements and mounting requirements]

## 6. Regulatory & Safety

- **Regulatory:** CE, UKCA, Brazil (Anatel), Thailand (NBTC)
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 7. Package Contents

- TRB500 Gateway
- 9 W PSU
- 4 x Mobile antennas (swivel, SMA male)
- Micro-USB cable (0.8 m)
- Ethernet cable
- SIM Adapter kit
- QSG (Quick Start Guide)"
  "# TRB140 – Industrial LTE Gateway

## 1. System Core & Interfaces

| Feature      | Specification                                                 |
| :----------- | :------------------------------------------------------------ |
| **CPU**      | ARM Cortex-A7, 1.2 GHz                                        |
| **Memory**   | **RAM:** 128 MB, DDR2 <br> **Flash:** 512 MB, SPI Flash       |
| **Ethernet** | 1 x RJ45 port, 10/100/1000 Mbps (Auto MDI/MDIX)               |
| **Mobile**   | 4G/LTE (Cat 4), 3G, 2G                                        |
| **SIM**      | 1 x Mini SIM slot (2FF), 1.8 V/3 V                            |
| **USB**      | 1 x Micro USB (Virtual network interface)                     |
| **I/O**      | 1 x Digital Input, 1 x Digital Output (on 4-pin power socket) |
| **Antenna**  | 1 x SMA connector for LTE                                     |

## 2. Mobile & Networking

- **Mobile Performance:** LTE Cat 4 (up to 150 Mbps), 3G (up to 42 Mbps), 2G (up to 236.8 kbps)
- **Status Monitoring:** RSSI, SINR, RSRP, RSRQ, Bytes sent/received, connected band, IMSI, ICCID
- **Network Features:** TCP, UDP, IPv4/IPv6, ICMP, NTP, DNS, HTTP/HTTPS, SFTP, FTP, SMTP, SSL/TLS, ARP, VRRP, PPP, PPPoE, UPnP, SSH, DHCP, Telnet, SNMP, MQTT, WOL
- **Connection Monitoring:** Ping Reboot, Wget Reboot, Periodic Reboot, LCP/ICMP link inspection
- **Security:** Pre-shared key, X.509 certificates, TACACS+, Radius, IP & Login attempts block, VLAN (Port/Tag-based)
- **Firewall:** Port forward, traffic rules, custom rules, DMZ, NAT, NAT-T, DDoS prevention, Port scan prevention

## 3. VPN & Industrial Protocols

- **VPN Support:**
  - **OpenVPN:** Multiple clients/server, 27 encryption methods
  - **IPsec:** IKEv1, IKEv2, 14 encryption methods
  - **Others:** WireGuard, ZeroTier, PPTP, L2TPv3, GRE, Stunnel, DMVPN, SSTP, Tinc
- **Industrial Protocols:**
  - **Modbus TCP:** Master (Functions 01-06, 15, 16), Slave (Custom registers, Remote access)
  - **DNP3:** TCP Master, Outstation
  - **MQTT Gateway:** Modbus Master to MQTT Broker
  - **Data to Server:** HTTP(S), MQTT, Azure MQTT, Kinesis

## 4. Power & Physical

| Feature         | Specification                                                                 |
| :-------------- | :---------------------------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (4-pin industrial socket, Reverse polarity & Surge protection) |
| **PoE**         | Passive PoE (Mode B, 9-30 VDC, via LAN port)                                  |
| **Consumption** | < 5 W                                                                         |
| **Housing**     | Aluminum housing, IP30 rating                                                 |
| **Dimensions**  | 74.5 x 25 x 64.4 mm                                                           |
| **Weight**      | 134 g                                                                         |
| **Mounting**    | DIN rail (Bottom and sideways), Flat surface                                  |
| **Environment** | Operating Temp: **-40°C to 75°C**                                             | Humidity: 10% to 90% |

## 5. Management & Software

- **Operating System:** RutOS (OpenWrt based Linux OS)
- **Management:** Web UI, CLI (SSH), SMS, TR-069, SNMP, JSON-RPC, Modbus TCP, Teltonika RMS
- **IoT Platforms:** Cloud of Things, ThingWorx, Cumulocity, Azure IoT Hub
- **Development:** SDK package, Supported languages: Busybox shell, Lua, C, C++

---

### Power Socket Pinout

| Pin   | Description        | Wire Color |
| :---- | :----------------- | :--------- | --- |
| **1** | Power (+)          | Red        |
| **2** | Ground (-)         | Black      |
| **3** | I/O (Input/Output) | Green      |
| **4** | I/O (Input/Output) | White      | "   |

"# TRM142 – Industrial RS232 LTE Modem

## 1. System Core & Interfaces

| Feature         | Specification                                             |
| :-------------- | :-------------------------------------------------------- |
| **Mobile**      | 4G LTE Cat 4 (Up to 150 Mbps DL); 3G; 2G                  |
| **RS232**       | **1 x DB9 Female connector** (With RTS, CTS flow control) |
| **USB**         | 1 x Micro USB (Virtual network interface)                 |
| **SIM**         | 1 x SIM slot (Mini SIM - 2FF), 1.8 V/3 V                  |
| **Antenna**     | 1 x SMA connector for Mobile                              |
| **Status LEDs** | 1 x Power, 1 x Network, 1 x Mobile status                 |
| **Reset**       | Reboot/User default reset/Factory reset button            |

## 2. Mobile Connectivity & Performance

| Parameter        | Value                               |
| :--------------- | :---------------------------------- |
| **4G LTE (FDD)** | Up to 150 Mbps DL / 50 Mbps UL      |
| **4G LTE (TDD)** | Up to 130 Mbps DL / 30 Mbps UL      |
| **3G (HSPA+)**   | Up to 21 Mbps DL / 5.76 Mbps UL     |
| **2G (EDGE)**    | Up to 236.8 kbps DL / 236.8 kbps UL |
| **3GPP Release** | Release 9                           |

## 3. Power Specifications

| Feature           | Specification                                   |
| :---------------- | :---------------------------------------------- | ---------- |
| **Input Voltage** | **9 – 30 VDC** (4-pin industrial socket)        |
| **Protection**    | Overvoltage, reverse polarity, surge protection |
| **Consumption**   | Idle: < 1 W                                     | Max: < 5 W |

## 4. Physical & Environmental

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ |
| **Housing**            | Aluminum housing, IP30 rating                     |
| **Dimensions**         | 74.5 x 25 x 64.5 mm (housing only)                |
| **Weight**             | 135 g                                             |
| **Mounting**           | DIN rail, wall mount, flat surface (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                               |
| **Operating Humidity** | 10% to 90% non-condensing                         |

## 5. Software & Drivers

- **Management:** Windows Connection Manager, Modem Manager (Linux)
- **USB Serial Driver:** Windows 7/8/10/11, Linux 2.6~6.3, Android 4.x~13
- **NDIS Driver:** Windows 7/8/10
- **Other Drivers:** GNSS and RIL (Android 4.x~13)

## 6. Regulatory & Safety

- **Regulatory:** CE, UKCA, CB, RCM, EAC, UCRF, WEEE
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 7. Package Contents

- TRM142 Modem
- 9 W PSU
- 1 x Mobile antenna (swivel, SMA male)
- Micro-USB cable (0.8 m)
- 1 x Hex key
- QSG (Quick Start Guide)"
  "# TRM500 – Industrial 5G Modem

## 1. System Core & Interfaces

| Feature          | Specification                                                                    |
| :--------------- | :------------------------------------------------------------------------------- |
| **Mobile**       | **5G Sub-6GHz SA/NSA** (DL up to 3.4 Gbps, UL up to 900 Mbps); 4G LTE Cat 19; 3G |
| **USB**          | 1 x USB Type-C (For power and network data/virtual interface)                    |
| **Power Socket** | 1 x 4-pin industrial DC power socket                                             |
| **SIM**          | 1 x SIM slot (Mini SIM - 2FF), 1.8 V/3 V                                         |
| **Antennas**     | 4 x SMA connectors for Mobile                                                    |
| **Status LEDs**  | 1 x Power, 1 x 5G, 1 x Network, 1 x Mobile status                                |

## 2. Mobile Connectivity & Performance

| Parameter         | Value                         |
| :---------------- | :---------------------------- |
| **5G SA**         | 2.4 Gbps (DL) / 900 Mbps (UL) |
| **5G NSA**        | 3.4 Gbps (DL) / 550 Mbps (UL) |
| **4G LTE Cat 19** | 1.6 Gbps (DL) / 200 Mbps (UL) |
| **3G**            | 42 Mbps (DL) / 5.76 Mbps (UL) |
| **3GPP Release**  | Release 16                    |

## 3. Power Specifications

| Feature           | Specification                                             |
| :---------------- | :-------------------------------------------------------- | ----------- |
| **Input Voltage** | **9 – 30 VDC** (4-pin socket) or **5 VDC** (USB Type-C)   |
| **USB Power**     | USB host must provide 5V @ 3A                             |
| **Protection**    | Overvoltage, reverse polarity, surge protection (>35 VDC) |
| **Consumption**   | Idle: < 5 W                                               | Max: < 12 W |

## 4. Physical & Environmental

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ |
| **Housing**            | Anodized aluminum housing and panels, IP30 rating |
| **Dimensions**         | 83 x 25 x 85.4 mm                                 |
| **Weight**             | 94.5 g                                            |
| **Mounting**           | DIN rail, wall mount, flat surface (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                               |
| **Operating Humidity** | 10% to 90% non-condensing                         |

## 5. Software & Drivers

- **Management:** Windows Connection Manager, Modem Manager (Linux)
- **USB Serial/NDIS:** Windows 7/8/10/11, Linux, Android
- **MBIM Driver:** Windows 8/10/11, Linux 3.18~6.3
- **Protocol Drivers:** Gobinet, QMI_WWAN, RIL (Android)

## 6. Regulatory & Safety

- **Regulatory:** CE, UKCA, RCM, CB, WEEE
- **Safety:** EN IEC 62368-1:2020+A11:2020, EN IEC 62311:2020
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 7. Package Contents

- TRM500 Modem
- 9 W PSU (EU/UK/AU tùy mã)
- 4 x 5G Mobile antennas (swivel, SMA male)
- USB Type-C cable (0.8 m)
- SIM Adapter kit & Hex key
- QSG (Quick Start Guide)"
  "# TRM200 – Industrial LTE Cat 4 Modem

## 1. Hardware Overview & Interfaces

| Feature             | Specification                                        |
| :------------------ | :--------------------------------------------------- |
| **Mobile**          | 4G LTE Cat 4 (Up to 75 Mbps DL / 50 Mbps UL); 3G; 2G |
| **Interface/Power** | 1 x Micro-USB (Power and network data)               |
| **SIM**             | 1 x SIM slot (Mini SIM - 2FF), 1.8 V/3 V             |
| **Antenna**         | 1 x SMA connector for Mobile                         |
| **Status LEDs**     | 1 x Power, 1 x Network, 1 x Mobile status            |

[Image of Teltonika TRM200 front and rear panel layout]

## 2. Mobile Connectivity & Performance

| Parameter        | Value                               |
| :--------------- | :---------------------------------- |
| **4G LTE (FDD)** | Up to 75 Mbps DL / 50 Mbps UL       |
| **3G (HSPA+)**   | Up to 42 Mbps DL / 5.76 Mbps UL     |
| **2G (EDGE)**    | Up to 236.8 kbps DL / 236.8 kbps UL |
| **3GPP Release** | Release 9                           |

## 3. Power Specifications

| Feature           | Specification                     |
| :---------------- | :-------------------------------- | ---------- |
| **Connector**     | Micro-USB                         |
| **Input Voltage** | **5 VDC** (Powered via Micro-USB) |
| **Consumption**   | Idle: 0.9 W                       | Max: 3.2 W |

## 4. Physical & Environmental

| Feature                | Specification                                     |
| :--------------------- | :------------------------------------------------ |
| **Housing**            | Aluminum housing, IP30 rating                     |
| **Dimensions**         | 74.5 x 25 x 64.5 mm                               |
| **Weight**             | 274 g                                             |
| **Mounting**           | DIN rail, wall mount, flat surface (optional kit) |
| **Operating Temp**     | **-40 °C to 75 °C**                               |
| **Operating Humidity** | 10% to 90% non-condensing                         |

[Image of Teltonika TRM200 physical dimensions and spatial measurements]

## 5. Software & Drivers

- **USB Serial Driver:** Windows 7/8/10, Linux 2.6+, Android 2.3+
- **NDIS Driver:** Windows 7/8/10

## 6. Regulatory & Safety

- **Regulatory:** CE, UKCA, CB, EAC, UCRF, WEEE
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 7. Package Contents

- TRM200 Modem
- 1 x Mobile antenna (swivel, SMA male)
- Micro-USB cable (0.8 m)
- 1 x Hex key
- QSG (Quick Start Guide)
- Packaging box"
  "# TRM250 – Industrial LPWAN LTE Modem

## 1. Hardware Overview & Interfaces

| Feature             | Specification                            |
| :------------------ | :--------------------------------------- |
| **Mobile**          | **LTE Cat M1 / NB-IoT / EGPRS**          |
| **Interface/Power** | 1 x Micro-USB (Power and network data)   |
| **SIM**             | 1 x SIM slot (Mini SIM - 2FF), 1.8 V/3 V |
| **Antenna**         | 1 x SMA connector for LTE                |
| **Status LEDs**     | 1 x Power, 1 x Network, 1 x LTE status   |

## 2. Mobile Connectivity & Performance

| Parameter            | Value                                                                                                                |
| :------------------- | :------------------------------------------------------------------------------------------------------------------- |
| **Technologies**     | 4G (LTE-FDD), 4G (LTE-TDD), 2G                                                                                       |
| **Bands (Global)**   | FDD: B1, B2, B3, B4, B5, B8, B12, B13, B18, B19, B20, B26, B28 <br> TDD: B39 (Cat M1) <br> 2G: 850/900/1800/1900 MHz |
| **Regional Version** | Global (Excluding Russia & Belarus)                                                                                  |

## 3. Power Specifications

| Feature           | Specification                     |
| :---------------- | :-------------------------------- |
| **Connector**     | Micro-USB                         |
| **Input Voltage** | **5 VDC** (Powered via Micro-USB) |
| **Consumption**   | 3.6 W Max                         |

## 4. Physical & Environmental

| Feature                | Specification                 |
| :--------------------- | :---------------------------- |
| **Housing**            | Aluminum housing, IP30 rating |
| **Dimensions**         | 74.5 x 25 x 64.5 mm           |
| **Weight**             | 130 g                         |
| **Mounting**           | DIN rail, Flat surface        |
| **Operating Temp**     | **-40 °C to 75 °C**           |
| **Operating Humidity** | 10% to 90% non-condensing     |

## 5. Software & Drivers

- **Management:** Windows Connection Manager (NDIS driver)
- **USB Driver:** Windows 7/8/10, Windows CE 5.0/6.0, Linux 2.6+, Android 4.x+
- **Drivers Supported:** RIL (Android), NDIS (Windows), Gobinet (Linux)

## 6. Regulatory & Safety

- **Regulatory:** CE, UKCA, CB, EAC, UCRF, WEEE
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 7. Package Contents

- TRM250 Modem
- 1 x LTE antenna (swivel, SMA male)
- Micro-USB cable (0.8 m)
- 1 x Hex key
- QSG (Quick Start Guide)
- Packaging box"
  "# TRM240 – Industrial LTE Cat 1 Modem

## 1. Hardware Overview & Interfaces

| Feature             | Specification                            |
| :------------------ | :--------------------------------------- |
| **Mobile**          | 4G LTE Cat 1 (Up to 10 Mbps); 3G; 2G     |
| **Interface/Power** | 1 x Micro-USB (Power and network data)   |
| **SIM**             | 1 x SIM slot (Mini SIM - 2FF), 1.8 V/3 V |
| **Antenna**         | 1 x SMA connector for LTE                |
| **Status LEDs**     | 1 x Power, 1 x Network, 1 x LTE status   |

## 2. Mobile Connectivity & Performance

| Parameter            | Value                                               |
| :------------------- | :-------------------------------------------------- |
| **4G LTE (Cat 1)**   | Up to 10 Mbps DL / 5 Mbps UL                        |
| **3G (HSPA+)**       | Up to 42 Mbps DL / 5.76 Mbps UL                     |
| **2G (EDGE)**        | Up to 236.8 kbps DL / 236.8 kbps UL                 |
| **Available Region** | Europe, Middle East, Africa, Korea, Thailand, India |

## 3. Power Specifications

| Feature           | Specification                     |
| :---------------- | :-------------------------------- |
| **Connector**     | Micro-USB                         |
| **Input Voltage** | **5 VDC** (Powered via Micro-USB) |
| **Consumption**   | 3.2 W Max                         |

## 4. Physical & Environmental

| Feature                | Specification                 |
| :--------------------- | :---------------------------- |
| **Housing**            | Aluminum housing, IP30 rating |
| **Dimensions**         | 74.5 x 25 x 64.5 mm           |
| **Weight**             | 131 g                         |
| **Mounting**           | DIN rail, Flat surface        |
| **Operating Temp**     | **-40 °C to 75 °C**           |
| **Operating Humidity** | 10% to 90% non-condensing     |

## 5. Software & Drivers

- **Management:** Windows Connection Manager (NDIS driver)
- **USB Driver:** Windows 7/8/10, Windows CE 5.0/6.0, Linux 2.6+, Android 4.x+
- **Supported Protocols:** RIL (Android), NDIS (Windows), Gobinet (Linux), QMI_WWAN

## 6. Regulatory & Safety

- **Regulatory:** CE/RED, EAC, ROHS, WEEE
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 7. Package Contents

- TRM240 Modem
- 1 x LTE antenna (swivel, SMA male)
- Micro-USB cable (0.8 m)
- 1 x Hex key
- QSG (Quick Start Guide)
- Packaging box"
  "# DAP145 – Industrial Wireless Access Point with RS485

## 1. System Core & Interfaces

| Feature           | Specification                                                 |
| :---------------- | :------------------------------------------------------------ |
| **CPU**           | Mediatek, 580 MHz, MIPS 24KEC                                 |
| **Memory**        | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB serial NOR flash  |
| **Ethernet**      | 2 x RJ45 ports, 10/100 Mbps (IEEE 802.3 series compliant)     |
| **Wi-Fi**         | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA) |
| **RS485**         | **1 x 6-pin terminal block** (2-wire or 4-wire interface)     |
| **Antenna**       | 1 x RP-SMA connector for Wi-Fi                                |
| **I/O & Sensors** | Integrated RS485 for Serial-to-IP bridging                    |

[Image of Teltonika DAP145 front panel interfaces]

## 2. Wireless & Networking Features

- **Wi-Fi Performance:** Up to 50 simultaneous connections, WPA3 security, Mesh (802.11s), Fast Roaming (802.11r).
- **Connectivity Features:** Relayd, BSS transition management (802.11v), Radio resource measurement (802.11k).
- **Routing:** Static & Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy-based routing.
- **Security:** Firewall (Port forward, NAT), VLAN separation, DDOS & Port scan prevention, 802.1x client.
- **VPN Support:** OpenVPN, IPsec, WireGuard, ZeroTier, GRE, PPTP, L2TPv3, Stunnel, DMVPN, SSTP, Tailscale.

## 3. Industrial Protocols & Management

- **Industrial Protocols:**
  - **Modbus:** TCP/RTU (Master/Slave), MQTT Gateway
  - **BacNET:** Router (RTU RS485)
  - **DNP3:** Station/Outstation (TCP/RTU)
  - **DLMS/COSEM:** Client (TCP/RTU)
  - **OPC UA:** Client/Server (TCP)
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting.
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), TR-069, JSON-RPC, FOTA.

## 4. Power & Physical

| Feature         | Specification                                              |
| :-------------- | :--------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (3-pin pluggable terminal block)            |
| **PoE**         | Passive PoE (via LAN1 port, Mode B, 9-30 VDC)              |
| **Consumption** | Idle: < 1 W                                                | Max: < 2 W           |
| **Housing**     | Anodized aluminum housing and panels, IP30 rating          |
| **Dimensions**  | 113.10 x 25 x 68.6 mm                                      |
| **Weight**      | 149.2 g                                                    |
| **Mounting**    | **Integrated DIN rail bracket**, Wall mount (optional kit) |
| **Environment** | Operating Temp: **-40°C to 75°C**                          | Humidity: 10% to 90% |

[Image of Teltonika DAP145 3-pin power and 6-pin RS485 terminal block pinout]

## 5. Regulatory & Certification

- **Regulatory:** CE/RED, UKCA, CB, RCM, FCC, IC, EAC, UCRF, WEEE
- **Safety:** EN IEC 62368-1:2020+A11:2020, EN IEC 62311:2020
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 6. Package Contents

- DAP145 Access Point
- 3-Pin Power Connector
- 2 x 3-Pin Connectors (for RS485)
- Quick Start Guide (QSG)"
  "# DAP142 – Industrial Wireless Access Point with RS232

## 1. System Core & Interfaces

| Feature           | Specification                                                 |
| :---------------- | :------------------------------------------------------------ |
| **CPU**           | Mediatek, 580 MHz, MIPS 24KEC                                 |
| **Memory**        | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB serial NOR flash  |
| **Ethernet**      | 2 x RJ45 ports, 10/100 Mbps (IEEE 802.3 series compliant)     |
| **Wi-Fi**         | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA) |
| **RS232**         | **1 x DB9 socket** (Full RS232 pinout support)                |
| **Antenna**       | 1 x RP-SMA female connector for Wi-Fi                         |
| **I/O & Sensors** | Integrated RS232 for Serial-to-IP bridging & NTRIP            |

## 2. Wireless & Networking Features

- **Wi-Fi Performance:** Up to 50 simultaneous connections, WPA3-SAE, Mesh (802.11s), Fast Roaming (802.11r).
- **Wireless Connectivity:** Relayd, BSS transition management (802.11v), Radio resource measurement (802.11k), Hotspot 2.0.
- **Routing:** Static & Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy-based routing, VRF support.
- **Security:** Firewall (Port forward, NAT), VLAN separation, DDOS & Port scan prevention, 802.1x client.
- **VPN Support:** OpenVPN, IPsec, WireGuard, ZeroTier, GRE, PPTP, L2TPv3, Stunnel, DMVPN, SSTP, Tailscale.

## 3. Industrial Protocols & Management

- **Industrial Protocols:**
  - **Modbus:** TCP Master/Slave, RTU Master (via RS232), MQTT Gateway
  - **DNP3:** Station/Outstation (TCP/RTU)
  - **DLMS/COSEM:** Client (TCP/RTU) with automatic meter discovery
  - **OPC UA:** Client/Server (TCP)
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting.
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), TR-069, JSON-RPC, FOTA.
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity.

## 4. Power & Physical

| Feature         | Specification                                              |
| :-------------- | :--------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (3-pos pluggable terminal block)            |
| **PoE**         | Passive PoE (via LAN2 port, Mode B, 9-30 VDC)              |
| **Consumption** | Idle: 1 W                                                  | Max: 2 W             |
| **Housing**     | Anodized aluminum housing and panels, IP30 rating          |
| **Dimensions**  | 113.10 x 25 x 68.6 mm                                      |
| **Weight**      | 149.2 g                                                    |
| **Mounting**    | **Integrated DIN rail bracket**, Wall mount (optional kit) |
| **Environment** | Operating Temp: **-40°C to 75°C**                          | Humidity: 10% to 90% |

## 5. Regulatory & Certification

- **Regulatory:** CE, UKCA, CB
- **Safety:** EN IEC 62368-1:2020+A11:2020, EN IEC 62311:2020
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 6. Package Contents

- DAP142 Access Point
- 3-pin power connector
- Quick Start Guide (QSG)
- Packaging box"
  "# DAP142 – Industrial Wireless Access Point with RS232

## 1. System Core & Interfaces

| Feature           | Specification                                                 |
| :---------------- | :------------------------------------------------------------ |
| **CPU**           | Mediatek, 580 MHz, MIPS 24KEC                                 |
| **Memory**        | **RAM:** 128 MB, DDR2 <br> **Flash:** 16 MB serial NOR flash  |
| **Ethernet**      | 2 x RJ45 ports, 10/100 Mbps (IEEE 802.3 series compliant)     |
| **Wi-Fi**         | IEEE 802.11b/g/n (Wi-Fi 4), Access Point (AP) & Station (STA) |
| **RS232**         | **1 x DB9 socket** (Full RS232 pinout support)                |
| **Antenna**       | 1 x RP-SMA female connector for Wi-Fi                         |
| **I/O & Sensors** | Integrated RS232 for Serial-to-IP bridging & NTRIP            |

## 2. Wireless & Networking Features

- **Wi-Fi Performance:** Up to 50 simultaneous connections, WPA3-SAE, Mesh (802.11s), Fast Roaming (802.11r).
- **Wireless Connectivity:** Relayd, BSS transition management (802.11v), Radio resource measurement (802.11k), Hotspot 2.0.
- **Routing:** Static & Dynamic (BGP, OSPF v2, RIP v1/v2, EIGRP, NHRP), Policy-based routing, VRF support.
- **Security:** Firewall (Port forward, NAT), VLAN separation, DDOS & Port scan prevention, 802.1x client.
- **VPN Support:** OpenVPN, IPsec, WireGuard, ZeroTier, GRE, PPTP, L2TPv3, Stunnel, DMVPN, SSTP, Tailscale.

## 3. Industrial Protocols & Management

- **Industrial Protocols:**
  - **Modbus:** TCP Master/Slave, RTU Master (via RS232), MQTT Gateway
  - **DNP3:** Station/Outstation (TCP/RTU)
  - **DLMS/COSEM:** Client (TCP/RTU) with automatic meter discovery
  - **OPC UA:** Client/Server (TCP)
- **Data Collection:** Data to Server (HTTP/HTTPS/MQTT) via Lua scripting.
- **Management:** Teltonika RMS, Web UI, CLI (SSH), SNMP (v1/v2/v3), TR-069, JSON-RPC, FOTA.
- **IoT Platforms:** Azure IoT Hub, AWS IoT Core, ThingWorx, Cumulocity.

## 4. Power & Physical

| Feature         | Specification                                              |
| :-------------- | :--------------------------------------------------------- | -------------------- |
| **Power Input** | **9 – 30 VDC** (3-pos pluggable terminal block)            |
| **PoE**         | Passive PoE (via LAN2 port, Mode B, 9-30 VDC)              |
| **Consumption** | Idle: 1 W                                                  | Max: 2 W             |
| **Housing**     | Anodized aluminum housing and panels, IP30 rating          |
| **Dimensions**  | 113.10 x 25 x 68.6 mm                                      |
| **Weight**      | 149.2 g                                                    |
| **Mounting**    | **Integrated DIN rail bracket**, Wall mount (optional kit) |
| **Environment** | Operating Temp: **-40°C to 75°C**                          | Humidity: 10% to 90% |

## 5. Regulatory & Certification

- **Regulatory:** CE, UKCA, CB
- **Safety:** EN IEC 62368-1:2020+A11:2020, EN IEC 62311:2020
- **HS Code:** 851762 | **HTS Code:** 8517.62.00

## 6. Package Contents

- DAP142 Access Point
- 3-pin power connector
- Quick Start Guide (QSG)
- Packaging box"
  "# TAP200 – Industrial Wi-Fi 5 Wireless Access Point

## 1. System Core & Interfaces

| Feature         | Specification                                              |
| :-------------- | :--------------------------------------------------------- |
| **CPU**         | MediaTek Dual-Core, 880 MHz, MIPS 1004Kc                   |
| **Memory**      | **RAM:** 256 MB, DDR3 <br> **Flash:** 16 MB SPI NOR Flash  |
| **Ethernet**    | 1 x RJ45 port, **10/100/1000 Mbps** (IEEE 802.3 compliant) |
| **Wi-Fi**       | **802.11b/g/n/ac Wave 2 (Wi-Fi 5)**, Dual Band, MU-MIMO    |
| **Antennas**    | 2 x Internal 2.4 GHz, 2 x Internal 5 GHz                   |
| **Status LEDs** | 1 x Power LED (via Web-UI control), RJ45 status LEDs       |

[Image of Teltonika TAP200 bottom view interfaces and RJ45 port]

## 2. Wireless & Network Features

| Feature            | Specification                                         |
| :----------------- | :---------------------------------------------------- |
| **Wi-Fi Speed**    | Up to 867 Mbps                                        |
| **Wi-Fi Users**    | Up to **100 simultaneous connections**                |
| **Wi-Fi Security** | WPA3-EAP/SAE, WPA2-PSK/EAP, OWE, Client isolation     |
| **Connectivity**   | Fast roaming (802.11r), SSID stealth mode, MAC filter |
| **Network**        | IPv4/IPv6, SSH, SNMP, DHCP client, VLAN (Tag-based)   |
| **Management**     | Teltonika RMS, Web UI, CLI, FOTA, JSON-RPC            |

## 3. Power Specifications

| Feature           | Specification                                 |
| :---------------- | :-------------------------------------------- | ------------ |
| **Power Input**   | **PoE (Power over Ethernet)** via RJ45 socket |
| **PoE Standard**  | 802.3af PoE Class 1                           |
| **Input Voltage** | 44.0 – 57.0 V                                 |
| **Consumption**   | Idle: < 4 W                                   | Max: < 5.5 W |

## 4. Physical & Environmental

| Feature                | Specification                                            |
| :--------------------- | :------------------------------------------------------- |
| **Casing**             | UV stabilized plastic, IP30 rating                       |
| **Dimensions**         | **Ø 158 mm x 30 mm**                                     |
| **Weight**             | 190 g                                                    |
| **Mounting**           | AP Mounting Bracket (specifically for **ceiling mount**) |
| **Operating Temp**     | **-40 °C to 75 °C**                                      |
| **Operating Humidity** | 10% to 90% non-condensing                                |

[Image of Teltonika TAP200 spatial measurements and side view]

## 5. Regulatory & Certification

- **Regulatory:** CE, UKCA, FCC, IC, RCM, CB, EAC, UCRF, WEEE
- **Safety:** IEC 62368-1, EN IEC 62311
- **EMI:** EN 55032, EN 55035, EN 301 489-1/17

## 6. Package Contents

- TAP200 Access Point
- AP Mounting Bracket
- Wi-Fi Information sticker
- Quick Start Guide (QSG)
  _(Lưu ý: Có phiên bản kèm PoE Injector 15W tùy mã đặt hàng)_"
  "# TAP100 – Industrial Wi-Fi 4 Wireless Access Point

## 1. System Core & Interfaces

| Feature         | Specification                                         |
| :-------------- | :---------------------------------------------------- |
| **CPU**         | Mediatek, 580 MHz, MIPS 24KEC                         |
| **Memory**      | **RAM:** 64 MB, DDR2 <br> **Flash:** 16 MB, SPI Flash |
| **Ethernet**    | 1 x RJ45 port, 10/100 Mbps (IEEE 802.3 compliant)     |
| **Wi-Fi**       | **802.11b/g/n (Wi-Fi 4)**                             |
| **Antennas**    | 2 x Internal for 2.4 GHz Wi-Fi                        |
| **Status LEDs** | 1 x Power LED (via Web-UI control), RJ45 status LEDs  |

[Image of Teltonika TAP100 bottom view interfaces and RJ45 port]

## 2. Wireless & Network Features

| Feature            | Specification                                                  |
| :----------------- | :------------------------------------------------------------- |
| **Wi-Fi Users**    | Up to **100 simultaneous connections**                         |
| **Wi-Fi Security** | WPA3-EAP/SAE, WPA2-PSK/EAP, OWE, Client separation             |
| **Connectivity**   | Fast roaming (802.11r), SSID stealth mode, MAC filter          |
| **Network**        | IPv4/IPv6, SSH, SNMP (v1/v2/v3), DHCP client, VLAN (Tag-based) |
| **Management**     | Teltonika RMS, Web UI, CLI, FOTA, JSON-RPC                     |

## 3. Power Specifications

| Feature           | Specification                                 |
| :---------------- | :-------------------------------------------- |
| **Power Input**   | **PoE (Power over Ethernet)** via RJ45 socket |
| **PoE Standard**  | 802.3af PoE Class 1                           |
| **Input Voltage** | 44.0 – 57.0 V                                 |
| **Consumption**   | < 2 W Max                                     |

## 4. Physical & Environmental

| Feature                | Specification                                            |
| :--------------------- | :------------------------------------------------------- |
| **Casing**             | UV stabilized plastic, IP30 rating                       |
| **Dimensions**         | **Ø 158 mm x 30 mm**                                     |
| **Weight**             | 190 g                                                    |
| **Mounting**           | AP Mounting Bracket (specifically for **ceiling mount**) |
| **Operating Temp**     | **-40 °C to 75 °C**                                      |
| **Operating Humidity** | 10% to 90% non-condensing                                |

[Image of Teltonika TAP100 spatial measurements and side view]

## 5. Regulatory & Certification

- **Regulatory:** CE, UKCA, CB, FCC, IC, WEEE, ANRT
- **Safety:** IEC 62368-1:2018, EN IEC 62311
- **EMC:** EN 55032, EN 55035, EN 301 489-1/17

## 6. Package Contents

- TAP100 Access Point
- AP Mounting Bracket
- Wi-Fi Information sticker
- Quick Start Guide (QSG)
  _(Lưu ý: Có phiên bản kèm PoE Injector 15W tùy mã đặt hàng)_"

"# Edgecore EWS5204 – Enterprise Wireless LAN Controller

## 1. Hardware Specifications

| Feature              | Specification                                            |
| :------------------- | :------------------------------------------------------- |
| **Form Factor**      | 19"" (1U) Rack Mount (Mounting bracket included)         |
| **Dimensions**       | 43.8 cm x 30.0 cm x 4.4 cm                               |
| **Weight**           | 5.2 kg (11.46 lbs)                                       |
| **Power Input**      | 100-240 VAC, 50/60 Hz                                    |
| **Interfaces (WAN)** | 2 x 10/100/1000Base-T Ethernet (RJ-45), 2 x 100/1000 SFP |
| **Interfaces (LAN)** | 6 x 10/100/1000Base-T Ethernet (RJ-45), 2 x 100/1000 SFP |
| **Other Ports**      | 2 x USB 3.0, 1 x Console (RJ-45), 1 x micro USB          |
| **Display & LED**    | LCD Display, Power LED, HDD LED                          |
| **Environment**      | Operating Temp: 0°C to 40°C; Humidity: 10% to 90%        |

## 2. System Capacity

| Parameter              | Value            |
| :--------------------- | :--------------- |
| **Managed APs**        | Up to **1,000**  |
| **Managed Switches**   | Up to **250**    |
| **Max. Online Users**  | Up to **10,000** |
| **Local Accounts**     | 30,000           |
| **On-Demand Accounts** | 30,000           |

## 3. Wireless & Mobility Features

- **Roaming:** Fast Roaming (L2/L3), Cross Gateway Roaming.
- **Smart Login:** WISPr Smart Client, QR Code Automatic Login, On-Demand Smart Login.
- **Device Recognition:** Mobile Device Recognition for optimized Captive Portal.
- **AP Management:** Automatic Discovery/Provisioning, Template-based config, Batch Upgrade, Load Balancing.
- **Connectivity:** Device Plug-and-Play, Multiple device logins per account.

## 4. Security & Authentication

- **Network Isolation:** Intra-VLAN/Port, Inter-VLAN/Port, Rogue AP Detection.
- **VPN & Tunneling:** Remote/Site-to-Site VPN, IPSec, PPTP, CAPWAP.
- **Authentication Types:** 802.1X, UAM (Web-based), IP/MAC-based, Social Media Login.
- **Auth Databases:** Local, On-Demand, Guest, RADIUS, LDAP, NT Domain, SIP, POP3.
- **Guest Access:** E-mail registration, SMS registration, PayPal billing, Hotel PMS integration (Opera, IDS Next).

## 5. Network & Management Features

- **Network Services:** DHCP Server/Relay, NAT, WAN Load Balancing, Dynamic Routing, Local DNS.
- **Traffic Control:** Bandwidth Limitation (User/Group), Traffic Classification (802.1p/DSCP), Concurrent Session Limit.
- **Firewall:** Stateful Firewall with individual enforcement schedules.
- **High Availability:** N+1 Redundancy with automatic synchronization.
- **Management Tools:** Browser-Based GUI, SNMP v2c, System Backup/Restore, Built-in Packet Capture.
- **Reporting:** System Dashboard, Traffic Volume Reports, Syslog, SMTP Notifications, User Event Logs."
  "# Edgecore EWS101 – Entry-Level Wireless LAN Controller

## 1. System Core & Interfaces

| Feature            | Specification                                     |
| :----------------- | :------------------------------------------------ |
| **Form Factor**    | Desktop                                           |
| **Ethernet (WAN)** | 1 x 10/100/1000Base-T Ethernet (Auto-MDIX, RJ-45) |
| **Ethernet (LAN)** | 4 x 10/100/1000Base-T Ethernet (Auto-MDIX, RJ-45) |
| **USB**            | 1 x USB 3.0                                       |
| **Console**        | 1 x RJ-45                                         |
| **Indicators**     | Power, Status LEDs                                |
| **Buttons**        | Reset button                                      |

## 2. System Capacity

| Parameter              | Value         |
| :--------------------- | :------------ |
| **Managed APs**        | Up to **50**  |
| **Concurrent Users**   | Up to **200** |
| **Local Accounts**     | Up to 2,000   |
| **On-Demand Accounts** | Up to 2,000   |

## 3. Mobility & Wireless Management

- **Roaming:** Fast Roaming (between APs), Cross Gateway Roaming.
- **AP Discovery:** Automatic AP Discovery & Provisioning (Template-based).
- **AP Management:** Firmware Batch Upgrade, Load Balancing, Tunneled Management (L2/L3).
- **User Authentication:** \* WISPr Smart Client, QR Code Auto-login.
  - Captive Portal (Customizable, Mobile-optimized).
  - Social Media Login, SMS registration.
- **On-Demand Login:** Smart Login without Re-Authentication.

## 4. Security & Network Features

- **VPN & Tunneling:** IPSec, IKEv2 (Remote & Site-to-Site).
- **Network Isolation:** Intra-VLAN/Port, Inter-VLAN/Port isolation.
- **Detection:** Rogue AP Detection.
- **Authentication Servers:** RADIUS, LDAP, NT Domain, SIP, POP3.
- **Network Services:** DHCP Server/Relay, NAT, Dynamic Routing, Local DNS, HTTP Proxy.
- **Hotel PMS Integration:** Micros Opera PMS, Innkey PMS, IDS Next.
- **Traffic Management:** Bandwidth throttling (User/Group), Stateful Firewall, 802.1p/DSCP.

## 5. Power & Physical

| Feature         | Specification                            |
| :-------------- | :--------------------------------------- |
| **Power Input** | **DC 12V / 1A** (Power adapter included) |
| **Dimensions**  | 19.0 x 13.3 x 3.3 cm                     |
| **Weight**      | 0.56 kg (1.23 lbs)                       |
| **Environment** | Operating Temp: **0°C to 40°C**          |
| **Humidity**    | 5% to 95% (non-condensing)               |

## 6. Monitoring & Reporting

- **System Dashboard:** Real-time system status & graphical performance.
- **Traffic Analysis:** Volume reports, active sessions list, online device monitoring.
- **Logging:** Syslog, CAPWAP log, Firewall log, User HTTP Web log.
- **Notifications:** SMTP (E-mail) with multiple concurrent receivers.
- **Utilities:** Built-in packet capture, SNMP v2c."
  "# Edgecore EWS100 – Enterprise-Grade Wireless LAN Controller

## 1. System Core & Interfaces

| Feature              | Specification                                          |
| :------------------- | :----------------------------------------------------- |
| **Form Factor**      | Desktop                                                |
| **Interfaces (WAN)** | 1 or 2 x 10/100/1000Base-T Ethernet (Auto-MDIX, RJ-45) |
| **Interfaces (LAN)** | 4 or 3 x 10/100/1000Base-T Ethernet (Auto-MDIX, RJ-45) |
| **USB**              | 1 x USB 3.0                                            |
| **LED Indicators**   | Power, Status                                          |
| **Buttons**          | Power, Reset                                           |

## 2. System Capacity

| Parameter              | Value        |
| :--------------------- | :----------- |
| **Managed APs**        | Up to **10** |
| **Local Accounts**     | Up to 2,000  |
| **On-Demand Accounts** | Up to 2,000  |

## 3. Security & Authentication

- **Network Security:** \* VPN (Remote, Local, Site-to-Site), IPSec, PPTP.
  - Rogue AP Detection, Built-in Root CA.
  - Network Isolation (Intra/Inter-VLAN or Port).
- **Authentication Types:** 802.1X, UAM (Browser-based), IP/MAC-based, Guest, Social Media Login.
- **Authentication Servers:** RADIUS, LDAP, NT Domain, SIP, POP3.
- **Captive Portal:** Customizable with Wild Card Walled Garden, User Blacklisting.
- **Account Generation:** SMS registration, PayPal integration, Hotel PMS integration, Ticket Printer support.

## 4. Mobility & AP Management

- **Mobility:** Fast Roaming (L2/L3), Cross Gateway Roaming, WISPr Smart Client, QR Code Auto-login.
- **Optimization:** Mobile Device Recognition, Multiple device logins per account, Plug-and-Play.
- **AP Management:** \* Automatic Discovery & Provisioning (Template-based).
  - AP Firmware Batch Upgrade, Configuration Backup/Restore.
  - Tunneled Management (L2 & L3 APs), AP Load Balancing.

## 5. Network & User Management

- **Network Services:** DHCP Server/Relay, NAT, Dynamic Routing, Built-in HTTP Proxy, Local DNS, WAN Load Balancing/Failover.
- **User Policies:** Role-based (Time & Location dependent), Bandwidth Limitation, Concurrent Session Limit.
- **Traffic Control:** Stateful Firewall (Individual schedules), Traffic Classification (802.1p/DSCP).
- **Service Zones:** Multiple virtual controller segments.
- **Hotel PMS:** Direct interface with Micros Opera PMS.

## 6. Power & Physical

| Feature         | Specification                            |
| :-------------- | :--------------------------------------- |
| **Power Input** | **DC 12V / 1A** (Power adapter included) |
| **Dimensions**  | 19.0 x 13.3 x 3.3 cm                     |
| **Weight**      | 0.82 kg (1.81 lbs)                       |
| **Environment** | Operating Temp: **0°C to 40°C**          |
| **Humidity**    | 5% to 95% (non-condensing)               |

## 7. Reporting & Monitoring

- **Dashboard:** Real-time system status, Graphical performance & traffic volume reports.
- **Monitoring:** Online Device Monitoring, Active Sessions List, System Process Monitor.
- **Logging:** Syslog (Configurable severity), CAPWAP log, RADIUS log, Firewall log, User HTTP Web log.
- **Notifications:** SMTP (E-mail) with multiple concurrent receivers.
- **Utilities:** Built-in packet capture, SNMP v2c."
  "# ET4202-LX – 1G 10km SFP Transceiver

## 1. System Core & Interfaces

| Feature               | Specification                                                |
| :-------------------- | :----------------------------------------------------------- |
| **Form Factor**       | Small Form-factor Pluggable (SFP)                            |
| **Data Rate**         | Up to 1.25 Gbps                                              |
| **Optical Interface** | Duplex LC receptacle                                         |
| **Fiber Type**        | Single-Mode Fiber (SMF) 9/125 µm                             |
| **Max Reach**         | 10 km                                                        |
| **Compliance**        | SFP MSA, SFF-8472, RoHS                                      |
| **Features**          | Hot pluggable, DDM (Digital Diagnostic Monitoring) available |

## 2. Optical Specifications

- **Transmitter:**
  - _Type:_ 1310 nm FP Laser
  - _Launch Optical Power:_ -9 to -3 dBm
  - _Center Wavelength:_ 1260 nm to 1360 nm (Typical: 1310 nm)
  - _Extinction Ratio:_ Min 9 dB
- **Receiver:**
  - _Type:_ PIN photo-detector
  - _Receiver Sensitivity:_ Max -23 dBm
  - _Center Wavelength:_ 1260 nm to 1620 nm

## 3. Electrical & Power

| Feature                | Specification                               |
| :--------------------- | :------------------------------------------ |
| **Supply Voltage**     | Typical: **3.3 V** (Range: 3.135 – 3.465 V) |
| **Max Supply Voltage** | 3.6 V                                       |
| **Input Impedance**    | 90 – 110 $\Omega$ (Differential)            |
| **Data Input Swing**   | 250 – 1000 mV (Single Ended)                |

## 4. Physical & Environmental

| Feature                    | Specification                               |
| :------------------------- | :------------------------------------------ |
| **Operating Temp**         | **0°C to 70°C** (Commercial)                |
| **Storage Temp**           | -40°C to 85°C                               |
| **Humidity**               | 0% to 95% (Relative, non-condensing)        |
| **Dimensions (L x W x H)** | **56.6 x 13.7 x 9.2 mm** (Total with latch) |
| **Body Length**            | 55.5 mm                                     |
| **Weight**                 | Not specified (Standard SFP weight)         |

## 5. Pin Definitions

| Pin           | Name      | Description                          |
| :------------ | :-------- | :----------------------------------- | --- |
| 1, 17, 20     | VeeT      | Transmitter Ground                   |
| 2             | TxFault   | Transmitter Fault Indication         |
| 3             | TxDisable | Transmitter Disable                  |
| 4, 5, 6       | MOD-DEF   | Module Definition (SDA, SCL, Ground) |
| 8             | LOS       | Loss of Signal                       |
| 9, 10, 11, 14 | VeeR      | Receiver Ground                      |
| 12, 13        | RD-/+     | Received Data Out (Inverted/Normal)  |
| 15            | VccR      | Receiver Power                       |
| 16            | VccT      | Transmitter Power                    |
| 18, 19        | TD+/-     | Transmit Data In (Normal/Inverted)   | "   |

"# ECW5410-L – TIP Open Indoor Access Point

## 1. Hardware Specifications

| Feature            | Specification                                                                                                    |
| :----------------- | :--------------------------------------------------------------------------------------------------------------- |
| **CPU**            | IPQ8068                                                                                                          |
| **Memory**         | 512 MB                                                                                                           |
| **Flash**          | **NOR:** 32 MB, **NAND:** 256 MB                                                                                 |
| **Interfaces**     | 1 x 10/100/1000Base-T (802.3at PoE) <br> 1 x 10/100/1000Base-T <br> 1 x RJ-45 Console Port <br> 1 x USB 2.0 Port |
| **Bluetooth**      | Built-in Bluetooth Low Energy (BLE) beacon                                                                       |
| **Antenna**        | 5 x Built-in PIFA (4 x WiFi, 1 x BLE) <br> **Gain:** 3 dBi (2.4 GHz), 5 dBi (5 GHz), 3 dBi (BLE)                 |
| **LED Indicators** | Power, 2.4G-WiFi, 5G-WiFi, ETH 1 (PoE), ETH 2                                                                    |
| **Buttons**        | Restart / Reset                                                                                                  |

## 2. Wi-Fi Specifications

- **Standards:** 802.11ac Wave 2 (a/b/g/n compliant), Concurrent Dual-Band.
- **MIMO & Streams:** **4x4 MU-MIMO** with 4 spatial streams.
- **Frequency Bands:** 2.412 – 2.472 GHz, 5.180 – 5.825 GHz.
- **Physical Data Rate:** \* **2.4 GHz:** Up to **800 Mbps**
  - **5 GHz:** Up to **1733 Mbps**
- **Channelization:** 20 MHz, 40 MHz, 80 MHz.
- **RF Output Power:** Up to 24 dBm (Aggregated).
- **ESSIDs:** Up to 16 per radio (**32 total**).
- **Security:** Enterprise-Grade Wireless Security.

## 3. Power & Physical

| Feature               | Specification                                                             |
| :-------------------- | :------------------------------------------------------------------------ |
| **Power Input**       | **DC:** 12V/2A (Adapter included) <br> **PoE:** 802.3at compliant         |
| **Power Consumption** | Max. 25.5 W                                                               |
| **Dimensions**        | 19.5 x 19.1 x 3.9 cm                                                      |
| **Weight**            | 0.62 kg (1.37 lbs)                                                        |
| **Mounting**          | Wall, T-bar, or Ceiling mount (Mounting kit included)                     |
| **Environment**       | Operating Temp: **0°C to 50°C** <br> Humidity: 5% to 95% (non-condensing) |
| **ESD Protection**    | IEC-61000-4-2: +/-4KV contact, +/-8KV air                                 |

## 4. Software & Compliance

- **Software Platform:** **TIP Open WiFi Ready** (Pre-installed).
- **Certifications:** FCC (US), CE (Europe), TELEC, VCCI, NCC, BSMI."
  "# ECW5211-L – Indoor Access Point

## 1. Hardware Specifications

| Feature                | Specification                                      |
| :--------------------- | :------------------------------------------------- |
| **Uplink Interface**   | 1 x 10/100/1000BASE-T (RJ-45) with **802.3af PoE** |
| **LAN Interface**      | 1 x 10/100/1000BASE-T (RJ-45)                      |
| **USB**                | 1 x USB 2.0 port                                   |
| **Bluetooth**          | Integrated **Bluetooth Low Energy (BLE)**          |
| **Antenna Type**       | 3 x Built-in PIFA (2 x Dual-band WiFi, 1 x BLE)    |
| **Antenna Gain**       | 3 dBi (2.4 GHz), 5 dBi (5 GHz), 3 dBi (BLE)        |
| **Indicators/Buttons** | Power, 2G-WiFi, 5G-WiFi, LAN / Reset, Restart      |

## 2. Wi-Fi Specifications

- **Standards:** 802.11a/b/g/n/ac Wave 2.
- **Radios:** Concurrent Dual-band 2.4 GHz & 5 GHz.
- **MIMO & Streams:** **2x2:2 MU-MIMO** (2 Radio chains, 2 Spatial streams).
- **Physical Data Rate:** \* **2.4 GHz:** Up to **300 Mbps**.
  - **5 GHz:** Up to **867 Mbps**.
  - **Aggregate:** 1.2 Gbps.
- **Channelization:** 20 MHz, 40 MHz, 80 MHz.
- **RF Output Power:** Up to 22 dBm (Aggregated).
- **ESSIDs:** Up to 16 per radio (**32 total**).

## 3. Performance & Capacity

| Parameter              | Value                                                                      |
| :--------------------- | :------------------------------------------------------------------------- |
| **Concurrent Users**   | Up to **256** (128 per radio)                                              |
| **Roaming**            | Layer 2 / Layer 3 Fast Roaming                                             |
| **Quality of Service** | Wireless QoS (802.11e/WMM), DSCP (802.1p), Airtime fairness, Band steering |
| **Advanced Features**  | Multicast to unicast conversion, Optimal client filtering                  |

## 4. Security & Management

- **Encryption/Auth:** WEP, WPA/WPA2 Mixed, WPA2-Personal (AES), WPA2-Enterprise (AES).
- **Network Security:** VLAN tagging (802.1Q), Station isolation, DHCP snooping, Layer-2 firewall.
- **Deployment Modes:** Standalone or Tunneled management by controller.
- **Management:** Web UI (HTTP/HTTPS), SNMP v1, v2c, v3.
- **Controller Features:** Captive portal, Guest provisioning, Wi-Fi monetization (when used with Edgecore controller).

## 5. Power & Physical

| Feature                    | Specification                                        |
| :------------------------- | :--------------------------------------------------- |
| **PoE Input**              | **802.3af compliant**                                |
| **DC Input**               | 12 V / 1.0 A (Power adapter optional)                |
| **Power Consumption**      | Max. **9.0 W**                                       |
| **Dimensions (L x W x H)** | 14.7 x 14.7 x 3.5 cm                                 |
| **Weight**                 | 0.36 kg (0.78 lb)                                    |
| **Mounting**               | Wall or Ceiling mount (Kit included)                 |
| **Environment**            | Operating Temp: **0°C to 50°C**; Humidity: 5% to 95% |

## 6. Receive Sensitivity (Typical)

| Standard             | Data Rate | Sensitivity   |
| :------------------- | :-------- | :------------ | --- |
| **802.11b**          | 11 Mbps   | -86 dBm       |
| **802.11a/g**        | 54 Mbps   | -70 / -72 dBm |
| **802.11n (HT40)**   | MCS15     | -66 dBm       |
| **802.11ac (VHT80)** | MCS9      | -57 dBm       | "   |

"# ECW100 – Indoor In-Wall Access Point

## 1. System Core & Interfaces

| Feature              | Specification                                         |
| :------------------- | :---------------------------------------------------- |
| **Uplink Interface** | 1 x 10/100/1000Base-T (RJ-45) with **802.3af PoE**    |
| **LAN Interface**    | 1 x 10/100/1000Base-T (RJ-45)                         |
| **Bypass Port**      | **1 x RJ-11 (Front) & 1 x RJ-11 (Back)** pass-through |
| **Antenna Type**     | 2 x Built-in (Dual-band)                              |
| **Antenna Gain**     | 2 dBi (2.4 GHz), 3.5 dBi (5 GHz)                      |
| **LED Indicators**   | LAN Status (100 Mbps / 1 Gbps)                        |
| **Buttons**          | Restart / Reset                                       |

## 2. Wireless (Wi-Fi) Specifications

- **Standards:** IEEE 802.11a/b/g/n/ac Wave 1.
- **Radios:** Concurrent Dual-band 2.4 GHz & 5 GHz.
- **MIMO & Streams:** **2x2 MIMO** with 2 Spatial Streams.
- **Data Rates:** \* **2.4 GHz:** Up to **300 Mbps**
  - **5 GHz:** Up to **867 Mbps**
  - **Aggregate:** 1.2 Gbps
- **Channelization:** 20 MHz, 40 MHz, 80 MHz.
- **RF Output Power:** Up to 10 dBm (Aggregated).
- **ESSIDs:** Up to 8 per radio (**16 total**).

## 3. Performance & Capacity

| Parameter              | Value                                                        |
| :--------------------- | :----------------------------------------------------------- |
| **Concurrent Users**   | Up to **200** (100 per radio)                                |
| **Quality of Service** | 802.11e/WMM, DSCP (802.1p), Multicast to Unicast Conversion  |
| **Roaming**            | Layer 2 / Layer 3 Fast Roaming, 802.1X Preauthentication     |
| **Deployment**         | Standalone or Tunneled management by Edgecore EWS Controller |

## 4. Security & Management

- **Wireless Security:** WEP, WPA/WPA2 Mixed, WPA2-Personal (AES), WPA2-Enterprise (AES).
- **Network Security:** VLAN tagging (802.1Q), Station isolation, DHCP snooping, Layer-2 firewall.
- **Management:** Web UI (HTTP/HTTPS), SNMP v1/v2c/v3, LLDP.
- **Controller Features:** Captive portal, Guest provisioning, Bandwidth control, Wi-Fi monetization (with EWS Controller).

## 5. Power & Physical

| Feature               | Specification                                      |
| :-------------------- | :------------------------------------------------- |
| **Power Input**       | **PoE 802.3af compliant**                          |
| **Power Consumption** | Max. **8.0 W**                                     |
| **Dimensions (US)**   | 4.0 x 7.0 x 11.5 cm                                |
| **Dimensions (EU)**   | 4.0 x 8.5 x 8.5 cm                                 |
| **Weight**            | 125 g (0.275 lbs)                                  |
| **Mounting**          | In-Wall (Plate included) with Tamperproof Kit Lock |
| **Environment**       | Operating Temp: 0°C to 40°C; Humidity: 0% to 90%   |

## 6. Receive Sensitivity (Typical)

| Standard             | Data Rate | Sensitivity |
| :------------------- | :-------- | :---------- | --- |
| **802.11b**          | 11 Mbps   | -84 dBm     |
| **802.11a/g**        | 54 Mbps   | -69 dBm     |
| **802.11n (HT40)**   | MCS15     | -63 dBm     |
| **802.11ac (VHT80)** | MCS9      | -54 dBm     | "   |

"# ECS5550 Series – L3 10G Ethernet Aggregation Switch

## 1. System Performance & Capacity

| Parameter               | ECS5550-30X   | ECS5550-54X   |
| :---------------------- | :------------ | :------------ |
| **Switching Capacity**  | **1.68 Tbps** | **2.16 Tbps** |
| **Forwarding Rate**     | 600 Mpps      | 600 Mpps      |
| **Flash Memory (eMMC)** | 8 GB          | 8 GB          |
| **DRAM**                | 4 GB          | 4 GB          |
| **Packet Buffer Size**  | 6 MB          | 6 MB          |
| **MAC Address Table**   | 32 K          | 32 K          |
| **Jumbo Frames**        | 10 KB         | 10 KB         |

## 2. Hardware Interfaces

| Port Type               | ECS5550-30X                                   | ECS5550-54X                                   |
| :---------------------- | :-------------------------------------------- | :-------------------------------------------- |
| **10G SFP+ Ports**      | 24 (Supports 1G/2.5G/10G)                     | 48 (Supports 1G/2.5G/10G)                     |
| **100G QSFP28 Uplinks** | 6 (Supports 40G/100G)                         | 6 (Supports 40G/100G)                         |
| **Management Ports**    | 1 x RJ-45 Console, 1 x RJ-45 OOB, 1 x USB 2.0 | 1 x RJ-45 Console, 1 x RJ-45 OOB, 1 x USB 2.0 |
| **Fans**                | 3+1 Redundant fans                            | 3+1 Redundant fans                            |
| **Power Supply**        | Dual CRPS slots (Hot-swappable)               | Dual CRPS slots (Hot-swappable)               |

## 3. Key Software Features

- **Layer 2 Features:**
  - **High Availability:** ITU-T G.8032 ERPS (Convergence <50 ms), Multi-chassis Link Aggregation (MC-LAG).
  - **VLANs:** 802.1Q (4K), Q-in-Q (Selective), GVRP, Protocol/MAC/Subnet-based VLAN.
  - **L2 Protocols:** IGMP Snooping v1/v2/v3, MVR, 802.1D/w/s (STP/RSTP/MSTP).
- **Layer 3 Features:**
  - **Standard:** IPv4/IPv6 Unicast Routing, Static Routes (1K), RIP v1/v2, ECMP.
  - **Advanced (Requires License):** OSPF v2/v3, BGP4+, VRRP, PIM-SM/SSM, Policy Based Routing (PBR).
- **Security:** ACLs (L2/L3/L4), Port Security, 802.1X (Port/MAC based), RADIUS/TACACS+, DoS Protection, DHCP Snooping, Dynamic ARP Inspection (DAI).
- **Management:** ecCLOUD support, OpenLAN Switching (OLS), Web UI, CLI (SSH), SNMP v1/v2c/v3, sFlow, ZTP.

## 4. Power & Physical Specifications

| Feature                    | Specification                  |
| :------------------------- | :----------------------------- | ---------- |
| **Power Consumption**      | Max 200W (30X) / 230W (54X)    |
| **Input Voltage**          | AC: 100-240V                   | DC: 36-72V |
| **Dimensions (W x D x H)** | 44.2 x 42 x 4.36 cm (1U)       |
| **Weight**                 | 3.85 kg (30X) / 4.7 kg (54X)   |
| **Operating Temperature**  | **-5°C to 50°C**               |
| **MTBF**                   | > 500,000 hours (at 25°C)      |
| **Reliability**            | Redundant CRPS, Redundant Fans |

## 5. Supported Modules (Quick Reference)

- **1G/2.5G SFP:** ET4202 Series (SX, LX, EX, ZX, RJ45), ET4251 Series (LX, EX).
- **10G SFP+:** ET5402 Series (SR, LR, ER, RJ45), DAC/AOC cables.
- **40G/100G QSFP:** ET6401/ET6402 (40G), ET7402 (100G SR4, LR4, CWDM4).
- **License:** **LIC-ECS5550-LAYER3** (For OSPF, BGP, PIM, PBR)."
  "# ECS4620 Series – L3 Gigabit Ethernet Stackable Switch

## 1. System Performance & Capacity

| Feature                | Specification                                              |
| :--------------------- | :--------------------------------------------------------- |
| **Switching Capacity** | 128 Gbps (28-port models) / 176 Gbps (52-port models)      |
| **Forwarding Rate**    | 95.23 Mpps (28-port models) / 130.94 Mpps (52-port models) |
| **Memory**             | **RAM:** 256 MB <br> **Flash:** 128 MB                     |
| **MAC Address Table**  | 16 K entries                                               |
| **Jumbo Frames**       | 10 K                                                       |
| **Stacking**           | Hardware Stacking support                                  |

## 2. Hardware Interface & Models

| Model                  | 10/100/1000BASE-T | SFP (1G) | SFP+ (10G) | Expansion Slot (10G) | PoE Support        |
| :--------------------- | :---------------: | :------: | :--------: | :------------------: | :----------------- |
| **ECS4620-28T/DC**     |        24         |    0     |     2      |          1           | No                 |
| **ECS4620-28P**        |        24         |    0     |     2      |          1           | 802.3af/at (410 W) |
| **ECS4620-28F/DC/2AC** |     2 (Combo)     |    22    |     2      |          1           | No                 |
| **ECS4620-52T**        |        48         |    0     |     2      |          1           | No                 |
| **ECS4620-52P**        |        48         |    0     |     2      |          1           | 802.3af/at (780 W) |

## 3. Software & Network Features

- **Layer 2 Features:**
  - _Spanning Tree:_ IEEE 802.1D (STP), 802.1w (RSTP), 802.1s (MSTP), BPDU Guard, Root Guard.
  - _VLANs:_ 4K VLANs, Port-based, Private VLAN, GVRP, Voice VLAN, Q-in-Q.
  - _Multicast:_ IGMP Snooping v1/v2/v3, MVR, MLD Snooping v1/v2.
  - _Reliability:_ G.8032 ERPS (recovery < 50ms).
- **Layer 3 Features:**
  - _Unicast Routing:_ Static routes, RIP v1/v2, OSPF v2/v3, BGP4+, ECMP.
  - _Multicast Routing:_ PIM-DM, PIM-SM, PIM-DM6, PIM-SM6.
  - _Redundancy:_ VRRP, Proxy ARP, UDP Helper.
- **QoS & Security:**
  - _QoS:_ 8 egress queues per port, Strict Priority, WRR, DiffServ, Rate Limiting (64 Kbps ~ 1000 Mbps).
  - _Security:_ IEEE 802.1X, MAC/Web authentication, ACL (L2/L3/L4), DHCP Snooping, IP Source Guard, DAI, SSH/SSL.

## 4. Power & Physical

| Feature              | Specification                                                 |
| :------------------- | :------------------------------------------------------------ |
| **Power Input (AC)** | 100 – 240 VAC, 50/60 Hz                                       |
| **Power Input (DC)** | 36 – 75 VDC (Available for DC models)                         |
| **Power Supply**     | Dual AC PSU (Model 28F-2AC), RPS900W support                  |
| **Operating Temp**   | 0°C to 45°C                                                   |
| **Storage Temp**     | -40°C to 70°C                                                 |
| **Housing**          | Rack-mountable (1U)                                           |
| **Dimensions**       | 44 x 31.5 x 4.4 cm (28 ports) / 44 x 39.1 x 4.4 cm (52 ports) |

## 5. Management & Compliance

- **Management:** Industry-standard CLI, Web UI, SNMP v1/v2c/v3, RMON (1, 2, 3, 9), sFlow, Dual Image, LLDP/LLDP-MED.
- **OAM:** IEEE 802.3ah Link, IEEE 802.1ag CFM, ITU-T Y.1731.
- **Regulatory:** CE Mark, FCC Class A, EN 61000, UL/cUL, CB, RoHS, WEEE."
  "# ECS4210 Series – L2 Gigabit Ethernet Access Switch

## 1. System Performance & Capacity

| Feature                | Specification                                           |
| :--------------------- | :------------------------------------------------------ |
| **Switching Capacity** | 24 Gbps (12-port models) / 56 Gbps (28-port models)     |
| **Forwarding Rate**    | 17.9 Mpps (12-port models) / 41.7 Mpps (28-port models) |
| **Memory**             | **RAM:** 128 MB <br> **Flash:** 32 MB                   |
| **MAC Address Table**  | 16 K entries                                            |
| **Jumbo Frames**       | 13 K                                                    |

## 2. Hardware Interface & Models Comparison

| Model           | 10/100/1000BASE-T |    Uplink Ports     |  PoE Support  | PoE Budget | Max Consumption |
| :-------------- | :---------------: | :-----------------: | :-----------: | :--------: | :-------------: |
| **ECS4210-12T** |         8         |       4 x SFP       |      No       |    N/A     |      9.1 W      |
| **ECS4210-12P** |         8         | 2 x RJ-45 + 2 x SFP | Yes (802.3at) |   150 W    |      189 W      |
| **ECS4210-28T** |        24         |       4 x SFP       |      No       |    N/A     |     17.2 W      |
| **ECS4210-28P** |        24         |       4 x SFP       | Yes (802.3at) |   400 W    |      460 W      |

## 3. Software Features

- **Layer 2 Features:**
  - **Spanning Tree:** IEEE 802.1D (STP), 802.1w (RSTP), 802.1s (MSTP), Root Guard, Loopback detection.
  - **VLANs:** 4K VLANs, Port-based, 802.1Q, Q-in-Q, Voice VLAN, Private VLAN, GVRP.
  - **Link Aggregation:** Static trunk, IEEE 802.3ad LACP (8 groups, 8 ports/group).
  - **Multicast:** IGMP Snooping v1/v2/v3, MVR (Multicast VLAN Registration).
- **QoS (Quality of Service):**
  - **Queues:** 8 hardware queues per port.
  - **Scheduling:** Strict Priority, Weighted Round Robin (WRR).
  - **Traffic Management:** Rate limiting (64 Kbps resolution), trTCM, Ingress policing, Egress shaping.
- **Security Features:**
  - **Access Control:** IEEE 802.1X (Port/MAC based), MAC/Web Authentication, RADIUS, TACACS+.
  - **Network Protection:** DHCP Snooping (Option 82), IP Source Guard, Dynamic ARP Inspection (DAI), IPv6 ACL.
  - **Management Security:** HTTPS/SSL, SSH v1.5/v2.0.

## 4. Physical & Environmental

| Feature                   | Specification                                               |
| :------------------------ | :---------------------------------------------------------- |
| **Power Input**           | 100 – 240 VAC, 50 – 60 Hz                                   |
| **Operating Temperature** | **0°C to 50°C**                                             |
| **Storage Temperature**   | -40°C to 70°C                                               |
| **Operating Humidity**    | 10% to 90% (non-condensing)                                 |
| **Rack Space**            | 19"" standard (1U)                                          |
| **Weight**                | 0.7 kg (12T) / 2.3 kg (12P) / 2.16 kg (28T) / 3.13 kg (28P) |

## 5. Management & Compliance

- **Management Interfaces:** CLI (Console/Telnet), Web UI, SNMP v1/v2c/v3.
- **Monitoring:** RMON (groups 1, 2, 3, 9), Syslog, Port Mirroring (VLAN/MAC based, RSPAN), LLDP (802.1ab).
- **IPv6 Features:** IPv4/IPv6 dual stack, Neighbor Discovery, SNMP/HTTP over IPv6.
- **Regulatory Compliance:** _ **EMC:** CE Mark, FCC Class A.
  _ **Safety:** UL, CB (IEC60950-1). \* **Protection:** 4KV surge protection, 8KV/15KV ESD protection."
  "# ECS4155 Series – L2+/Lite L3 2.5G Multi-Gigabit Ethernet Switch

## 1. System Performance & Capacity

| Feature                | Specification                                            |
| :--------------------- | :------------------------------------------------------- |
| **Switching Capacity** | 420 Gbps                                                 |
| **Forwarding Rate**    | 310 Mpps                                                 |
| **Memory**             | **DRAM:** 4 GB <br> **Flash:** 8 MB (NOR) + 16 GB (eMMC) |
| **Packet Buffer**      | 3 MB                                                     |
| **MAC Address Table**  | 32 K entries                                             |
| **Jumbo Frames**       | 10 KB                                                    |
| **MTBF**               | > 500,000 hours                                          |

## 2. Hardware Interface

| Model           | 1G/2.5G BASE-T Ports | SFP28 (1G/10G/25G) Uplinks | PoE Support |
| :-------------- | :------------------: | :------------------------: | :---------- |
| **ECS4155-30T** |          24          |             6              | No          |
| **ECS4155-30P** |          24          |             6              | Yes (PoE++) |

- **Management Interfaces:** 1 x RJ-45 Console, 1 x Out-of-Band (OOB) Management, 1 x USB (Type A).
- **Surge Protection:** 6KV (RJ-45 ports), 4KV (Power).

## 3. Power over Ethernet (Model 30P)

| Feature                | Specification                                           |
| :--------------------- | :------------------------------------------------------ |
| **PoE Standards**      | IEEE 802.3af/at, IEEE 802.3bt (PoE++)                   |
| **Max Power per Port** | **Up to 90 W**                                          |
| **Total PoE Budget**   | **750 W**                                               |
| **PoE Management**     | Dynamic Power Allocation, Auto Disable Exceeding Budget |

## 4. Software Features

### Layer 2 & Resilience

- **Spanning Tree:** STP/RSTP/MSTP (64 instances), BPDU Guard, Root Guard, Loopback detection.
- **VLANs:** 4K VLANs, Port-based, 802.1Q, Q-in-Q (Selective), GVRP, Voice VLAN, Private VLAN.
- **Resilience:** ITU-T G.8032 ERPS (Convergence < 50ms).
- **Link Aggregation:** LACP (802.3ad) - 16 groups, Multi-chassis Link Aggregation (MC-LAG).
- **Multicast:** IGMP Snooping v1/v2/v3, MVR (5 Multicast VLANs), MLD Snooping v1/v2.

### Layer 3 & Routing

- **IPv4/IPv6 Routing:** Static Routing.
- **Dynamic Routing:** RIP v1/v2.

### QoS & Security

- **QoS:** 8 hardware queues per port, Strict Priority, WRR, Ingress/Egress Rate Limiting (64 Kbps resolution).
- **Security:** Port Security, IEEE 802.1X, MAC/Web Authentication, ACLs (L2/L3/L4/IPv6), DHCP Snooping, IP Source Guard, DAI, SSH v2, SSL/HTTPS.

### OAM & Management

- **Management:** CLI (Console/Telnet), Web UI, SNMP v1/v2c/v3, ecCLOUD, sFlow v4/v5.
- **OAM:** IEEE 802.3ah EFM, IEEE 802.1ag CFM, ITU-T Y.1731 Performance Monitor.
- **Diagnostics:** DDM (Digital Diagnostic Monitoring) on SFP28 ports.

## 5. Physical & Environmental

| Feature             | Specification                 |
| :------------------ | :---------------------------- |
| **Power Input**     | 100 – 240 VAC, 50/60 Hz       |
| **Max Consumption** | 88 W (30T) / 950 W (30P)      |
| **Operating Temp**  | **-5°C to 50°C**              |
| **Storage Temp**    | -40°C to 70°C                 |
| **Humidity**        | 5% to 95% (non-condensing)    |
| **Dimensions**      | 44 x 28 x 4.4 cm (1U)         |
| **Weight**          | 3.85 kg (30T) / 4.79 kg (30P) |

## 6. Compliance & Safety

- **Safety:** UL/cUL (62368-1), CB (IEC62368-1), BSMI.
- **EMC:** CE Mark, FCC Class A, VCCI, CISPR Class A.
- **Green Tech:** IEEE 802.3az Energy-Efficient Ethernet (EEE)."
  "# ECS4150 Series – L2+/Lite L3 Gigabit Ethernet Switch

## 1. System Performance & Capacity

| Feature                | Specification                                |
| :--------------------- | :------------------------------------------- |
| **Switching Capacity** | 128 Gbps                                     |
| **Forwarding Rate**    | 95 Mpps                                      |
| **Memory**             | **DRAM:** 1 GB <br> **Flash:** 256 MB (NAND) |
| **Packet Buffer**      | 1.5 MB                                       |
| **MAC Address Table**  | 16 K entries                                 |
| **Jumbo Frames**       | 10 KB                                        |
| **MTBF**               | 655,028 hrs (28T) / 449,388 hrs (28P)        |

## 2. Hardware Interface & PoE Matrix

| Model           | 10/100/1000BASE-T | SFP+ (10G) Uplinks | PoE Support | PoE Budget |
| :-------------- | :---------------: | :----------------: | :---------: | :--------: |
| **ECS4150-28T** |        24         |         4          |     No      |    N/A     |
| **ECS4150-28P** |        24         |         4          | Yes (PoE+)  |   370 W    |

- **Management Ports:** 1 x RJ-45 Console, 1 x Out-of-Band (OOB) Management, 1 x USB.
- **PoE Features:** IEEE 802.3af/at (Max 30W/port), Dynamic Power Allocation.

## 3. Software & Networking Features

### Layer 2 & Resilience

- **Spanning Tree:** STP, RSTP, MSTP (64 instances), BPDU Guard/Root Guard, Loopback detection.
- **VLANs:** 4K VLANs, Port-based, IEEE 802.1Q, GVRP, Q-in-Q, Selective Q-in-Q, Voice/Guest VLAN.
- **Resilience:** ITU-T G.8032 ERPS (Convergence time < 50ms).
- **Link Aggregation:** LACP (802.3ad) - 16 groups, Multi-chassis Link Aggregation (MC-LAG).
- **Multicast:** IGMP Snooping v1/v2/v3, MVR (5 Multicast VLANs), MLD Snooping v1/v2.

### Lite Layer 3 & Routing

- **IPv4/IPv6 Routing:** Static Routing.
- **Dynamic Routing:** RIP v1/v2.

### QoS & Security

- **QoS:** 8 hardware queues per port, Strict Priority, WRR, Ingress/Egress Rate Limiting.
- **Security:** Port Security, IEEE 802.1X (Port/MAC based), ACLs (L2/L3/L4/IPv6), DHCP Snooping, IP Source Guard, DAI, SSH v2, SSL/HTTPS.

### OAM & Management

- **OAM:** IEEE 802.3ah EFM, IEEE 802.1ag CFM, ITU-T Y.1731, Dying Gasp.
- **Management:** CLI (Console/Telnet), Web UI, SNMP v1/v2c/v3, ecCLOUD support, sFlow.

## 4. Power & Physical

| Feature                    | Specification                                   |
| :------------------------- | :---------------------------------------------- |
| **Power Input**            | 100 – 240 VAC, 50/60 Hz                         |
| **Max Power Consumption**  | 25 W (28T) / 450 W (28P)                        |
| **Surge Protection**       | 6KV (RJ-45 & Power)                             |
| **Operating Temperature**  | **-5°C to 45°C**                                |
| **Acoustic Noise**         | 0 dBA (28T - Fanless) / < 40 dBA (28P)          |
| **Dimensions (W x D x H)** | 44 x 22 x 4.4 cm (28T) / 44 x 28 x 4.4 cm (28P) |
| **Weight**                 | 3.05 kg (28T) / 4.75 kg (28P)                   |

## 5. Compliance & Regulatory

- **Safety:** UL (CSA 22.2 NO 62368-1), CB (IEC/EN 62368-1), BSMI.
- **EMC:** CE Mark, FCC Class A, CISPR Class A, VCCI.
- **Green Ethernet:** IEEE 802.3az Energy-Efficient Ethernet (EEE)."
  "# ECS4120 Series – L2+/L3 Lite Gigabit Ethernet Access Switch

## 1. System Performance & Capacity

| Feature                | Specification                                             |
| :--------------------- | :-------------------------------------------------------- |
| **Switching Capacity** | 128 Gbps (28-port models) / 176 Gbps (52-port models)     |
| **Forwarding Rate**    | 95 Mpps (28-port models) / 130 Mpps (52-port models)      |
| **Memory**             | **RAM:** 512 MB <br> **Flash:** 256 MB                    |
| **MAC Address Table**  | 16 K entries                                              |
| **Jumbo Frames**       | 9 KB                                                      |
| **Stacking**           | Hardware Stacking (Available on models with ""S"" suffix) |

## 2. Hardware Interface Matrix

| Model               | 10/100/1000BASE-T | SFP (1G) Ports | SFP+ (10G) Uplinks | PoE Support | Note                    |
| :------------------ | :---------------: | :------------: | :----------------: | :---------: | :---------------------- |
| **ECS4120-28T/TS**  |        24         |       0        |         4          |     No      | Fanless (28T)           |
| **ECS4120-28P/PS**  |        24         |       0        |         4          | Yes (370W)  | 802.3at PoE+            |
| **ECS4120-28F/v2**  |     4 (Combo)     |       20       |         4          |     No      | DC Power support        |
| **ECS4120-52T/TS**  |        48         |       0        |         4          |     No      | High Density            |
| **ECS4120-28Fv2-1** |     4 (Combo)     |       20       |         4          |     No      | **Temp: -10°C to 65°C** |

- **Console Port:** 1 x RJ-45 console port.
- **OOB Management:** 1 x GE port (Available on 28F models).

## 3. PoE Specifications (PoE Models)

| Feature                | Specification                                       |
| :--------------------- | :-------------------------------------------------- |
| **PoE Standards**      | IEEE 802.3af (PoE), IEEE 802.3at (PoE+)             |
| **PoE Power Budget**   | **370 W** (ECS4120-28P / 28PS)                      |
| **Max Power per Port** | 30 W                                                |
| **PoE Management**     | Dynamic Allocation, Scheduling, Port Prioritization |

## 4. Software Features

### Layer 2 & Resilience

- **Resilience:** **ITU-T G.8032 ERPS** (Convergence < 50ms).
- **Spanning Tree:** STP, RSTP (802.1w), MSTP (802.1s - 64 instances).
- **VLANs:** 4K VLANs, Port-based, 802.1Q, **Q-in-Q (Double Tagging)**, VLAN Translation, Voice VLAN.
- **Link Aggregation:** LACP (802.3ad) - Up to 26 groups (8 ports/group).
- **Multicast:** IGMP Snooping v1/v2/v3, MVR (Multicast VLAN Registration).

### L3 Lite & Routing

- **IP Routing:** IPv4/IPv6 Static Routes.
- **IPv6 Support:** Dual stack, Neighbor Discovery, DHCPv6 Snooping, IPv6 ACL, RA Guard.

### QoS & Security

- **QoS:** 8 hardware queues/port, Strict Priority, WRR, Ingress/Egress Rate Limiting (64Kbps resolution).
- **Security:** Port Security, IEEE 802.1X (Port/MAC), ACLs (L2/L3/L4/IPv6), DHCP Snooping, DAI, IP Source Guard, SSH v2.0, SSL/HTTPS.

### OAM & Management

- **OAM:** IEEE 802.3ah Link, **IEEE 802.1ag CFM**, **ITU-T Y.1731** (SLA verification).
- **Management:** CLI (Console/Telnet), Web UI, SNMP v1/v2c/v3, RMON, sFlow.

## 5. Physical & Environmental

| Feature                   | Specification                                              |
| :------------------------ | :--------------------------------------------------------- | --- |
| **Power Input (AC)**      | 100 – 240 VAC, 50/60 Hz                                    |
| **Power Input (DC)**      | 48 – 60 VDC (Available on 28F models)                      |
| **Operating Temperature** | 0°C to 50°C (Standard) / **-10°C to 65°C** (Model 28Fv2-1) |
| **Humidity**              | 10% to 90% (non-condensing)                                |
| **Dimensions**            | 1U Rackmount (Width: 44 cm)                                |
| **Compliance**            | CE, FCC Class A, UL, CB, RoHS, WEEE                        | "   |

"# ECS2100 Series – Gigabit Web-Smart Pro Switches

## 1. Hardware Performance & Capacity (Non-PoE Models)

| Feature                | ECS2100-10T     | ECS2100-28T      | ECS2110-26T      | ECS2100-52T      |
| :--------------------- | :-------------- | :--------------- | :--------------- | :--------------- |
| **RJ-45 Ports**        | 8 x 10/100/1000 | 24 x 10/100/1000 | 24 x 10/100/1000 | 48 x 10/100/1000 |
| **Uplink Ports**       | 2 x 1G SFP      | 4 x 1G SFP       | **2 x 10G SFP+** | 4 x 1G SFP       |
| **Switching Capacity** | 20 Gbps         | 56 Gbps          | 88 Gbps          | 104 Gbps         |
| **Forwarding Rate**    | 14.9 Mpps       | 41.7 Mpps        | 65.5 Mpps        | 77.4 Mpps        |
| **Flash / DRAM**       | 32 MB / 256 MB  | 32 MB / 256 MB   | 32 MB / 256 MB   | 32 MB / 256 MB   |
| **MAC Address**        | 8 K             | 8 K              | 16 K             | 16 K             |
| **Acoustics**          | Fanless (0 dB)  | Fanless (0 dB)   | Fanless (0 dB)   | Fanless (0 dB)   |

## 2. Hardware Performance & Capacity (PoE Models)

| Feature                | ECS2100-10PE   | ECS2100-10P    | ECS2100-28P | ECS2100-28PP        |
| :--------------------- | :------------- | :------------- | :---------- | :------------------ |
| **RJ-45 PoE Ports**    | 8              | 8              | 24          | 24                  |
| **Uplink Ports**       | 2 x 1G SFP     | 2 x 1G SFP     | 4 x 1G SFP  | 4 x 1G SFP          |
| **PoE Budget**         | **65 W**       | **125 W**      | **200 W**   | **370 W (740 W\*)** |
| **PoE Standard**       | 802.3af/at     | 802.3af/at     | 802.3af/at  | 802.3af/at          |
| **Switching Capacity** | 20 Gbps        | 20 Gbps        | 56 Gbps     | 56 Gbps             |
| **Acoustics**          | Fanless (0 dB) | Fanless (0 dB) | 46.1 dB     | 49.7 dB             |

_\*740 W khi sử dụng thêm phụ kiện PS3000 + EPS460W._

## 3. L2 & L3 Software Features

- **L2 Features:**
  - **Spanning Tree:** 802.1D (STP), 802.1w (RSTP), 802.1s (MSTP - 64 instances).
  - **VLANs:** 4K IEEE 802.1Q, Port-based, MAC-based, Auto Voice VLAN, Guest VLAN.
  - **Link Aggregation:** Static Trunk, IEEE 802.3ad (LACP).
  - **Multicast:** IGMP v1/v2/v3 Snooping, MLD Snooping, IGMP Queries.
  - **Other:** LLDP/LLDP-MED, Q-in-Q, Loopback Detection, Jumbo Frame 10K.
- **L3 Features:**
  - **Static Routing:** Hỗ trợ định tuyến tĩnh Layer 3.
  - **RIP:** Hỗ trợ trên các model 10T/10P/10PE/28T/28P/28PP.
- **Quality of Service (QoS):**
  - 8 HW Queues per port.
  - Priority Queues (WRR/Strict Priority/Hybrid).
  - Rate Limiting: 64 Kbps ~ 1000 Mbps.
  - IPv4/IPv6 DSCP, DiffServ.

## 4. Security & Management

- **Security:**
  - **Access Control:** L2/L3/L4 ACL (512 entries), IEEE 802.1X, MAC Filter.
  - **Network Guard:** IP Source Guard, DHCP Snooping, Dynamic ARP Inspection (DAI).
  - **Protection:** DDOS Protection, CPU Guard, Storm Control.
  - **Encryption:** SSH v1.5/v2.0, SSL v1/v2/v3.
- **Management:**
  - **Interface:** Console port, Web UI, CLI, Telnet, SNMP v1/v2c/v3.
  - **Features:** Dual Firmware/Configuration, DHCP Client/Relay, sFlow.
  - **Cloud/Software:** Hỗ trợ ECView Pro (SNMP Management).

## 5. Physical & Environmental

| Feature                | Specification                                        |
| :--------------------- | :--------------------------------------------------- | --- |
| **Power Input**        | 100-240 VAC, 50-60 Hz                                |
| **Operating Temp**     | 0°C to 50°C (Hầu hết các model)                      |
| **Storage Temp**       | -40°C to 70°C                                        |
| **Operating Humidity** | 10% to 90% (non-condensing)                          |
| **Mounting**           | Rackmount (19""/10""/13""), Wallmount (ECS2100-10PE) |
| **Compliance**         | CE Mark, FCC Class A, RoHS, CB (IEC/EN60950-1)       | "   |

"# ECS2020 Series – Gigabit Web-Smart Ethernet Switches

## 1. System Hardware & Interfaces

| Feature                | ECS2020-10T    | ECS2020-28T    | ECS2020-10P (PoE) | ECS2020-28P (PoE) |
| :--------------------- | :------------- | :------------- | :---------------- | :---------------- |
| **10/100/1000 Ports**  | 8 x RJ-45      | 24 x RJ-45     | 8 x RJ-45         | 24 x RJ-45        |
| **SFP Uplink Ports**   | 2 x 1G SFP     | 4 x 1G SFP     | 2 x 1G SFP        | 4 x 1G SFP        |
| **Console Port**       | No             | No             | No                | No                |
| **PoE Budget**         | N/A            | N/A            | **70 W**          | **190 W**         |
| **Switching Capacity** | 20 Gbps        | 56 Gbps        | 20 Gbps           | 56 Gbps           |
| **Forwarding Rate**    | 14.9 Mpps      | 41.7 Mpps      | 14.9 Mpps         | 41.7 Mpps         |
| **Flash / DRAM**       | 16 MB / 128 MB | 16 MB / 128 MB | 16 MB / 128 MB    | 16 MB / 128 MB    |
| **MAC Address Table**  | 8 K            | 8 K            | 8 K               | 8 K               |

## 2. Layer 2 & Technical Features

- **Spanning Tree:** IEEE 802.1D (STP), 802.1w (RSTP), 802.1s (MSTP), Root Guard, Loopback Detection.
- **VLAN Features:** \* 4K IEEE 802.1Q VLANs.
  - **Voice/Surveillance VLAN** (Auto optimization for VoIP/IP Cameras).
  - Guest VLAN, Port-Based VLAN.
- **Link Aggregation:** Static Trunk, IEEE 802.3ad (LACP).
- **Multicast:** IGMP v2/v3 Snooping, MLD Snooping, IGMP Queries/Immediate Leave.
- **Green Technology:** IEEE 802.3az Energy Efficient Ethernet, Cable Length detection.
- **Advanced Features:** LLDP/LLDP-MED, Jumbo Frame (10K), Cable Diagnostics.

## 3. Quality of Service (QoS) & Security

- **QoS Management:**
  - 8 Hardware Queues per port.
  - Scheduling: Strict Priority (SPQ), WRR, Hybrid.
  - Rate Limiting (Ingress/Egress), IPv4/IPv6 DSCP, DiffServ.
- **Security Features:**
  - **Network Protection:** DDOS Protection, CPU Guard, Port Isolation.
  - **Access Control:** IEEE 802.1X, MAC Filter, Port Security, AAA (RADIUS/TACACS+).
  - **ACL:** L2/L3/L4 (Ingress only, 256 entries), IPv4/IPv6 support.
  - **Monitoring:** Port Mirror (1:1, 1:Many), Storm Control (Broadcast/Multicast).
  - **Encryption:** SSH v1.5/v2.0, SSL v1/v2/v3.

## 4. Power & Physical Specifications

| Feature              | Specification                                      |
| :------------------- | :------------------------------------------------- | --------------------------- |
| **Power Input**      | 100-240 VAC, 50-60 Hz                              |
| **PoE Support**      | IEEE 802.3af/at (Auto Power Allocation, PoE Timer) |
| **Surge Protection** | **4 KV**                                           |
| **Acoustics**        | **Fanless:** 10T, 10P, 28T                         | **Smart Fan:** 28P (<40 dB) |
| **Operating Temp**   | **0°C to 50°C**                                    |
| **Housing / Mount**  | Rackmount (9""/13""/19"" depending on model)       |
| **Certifications**   | CE/FCC, UL/BSMI, CB (IEC/EN60950-1)                |

## 5. Management & IPv6

- **Management Interfaces:** Web-based (Multi-language), Telnet CLI (Cisco-like), SNMP v1/v2c/v3.
- **IPv6 Support:** Dual Stack (IPv4/IPv6), IPv6 Management, Neighbor Discovery, Ping/Trace, Syslog.
- **Configuration:** Dual Configuration files, Software/Config upgrade via HTTP/TFTP.
- **Monitoring:** Syslog, RMON1 (groups 1, 2, 3, 9), Event/Error Log."
  "# ECS1020 Series – Gigabit Unmanaged Switches

## 1. Hardware Performance & Capacity

| Feature                | ECS1020-16T | ECS1020-24T | ECS1020-10P | ECS1020-16P |
| :--------------------- | :---------- | :---------- | :---------- | :---------- |
| **10/100/1000 Ports**  | 16 x RJ-45  | 24 x RJ-45  | 9 x RJ-45   | 16 x RJ-45  |
| **SFP Uplink Ports**   | No          | No          | 1 (1G/100M) | No          |
| **Switching Capacity** | 32 Gbps     | 48 Gbps     | 20 Gbps     | 32 Gbps     |
| **Forwarding Rate**    | 23.8 Mpps   | 35.7 Mpps   | 14.9 Mpps   | 23.8 Mpps   |
| **Packet Buffer**      | 2 Mbit      | 4.1 Mbit    | 1.5 Mbit    | 2 Mbit      |
| **MAC Address Table**  | 8 K         | 8 K         | 4 K         | 8 K         |
| **Jumbo Frames**       | 9 K         | 9 K         | 9 K         | 9 K         |
| **Surge Protection**   | **4 KV**    | **4 KV**    | **6 KV**    | **6 KV**    |

[Image of unmanaged gigabit switch network topology]

## 2. PoE & Power Efficiency

- **PoE Standards:** IEEE 802.3af/802.3at (PoE+).
- **PoE Power Budget:**
  - **ECS1020-10P:** 140 W (8 ports PoE).
  - **ECS1020-16P:** 300 W (16 ports PoE).
- **Energy Efficiency:** \* Support **IEEE 802.3az** (Energy Efficient Ethernet).
  - Power saving up to 69% (model dependent).
- **Acoustics:**
  - Fanless (0 dB): ECS1020-16T, ECS1020-24T.
  - With Fan: ECS1020-10P (49 dB), ECS1020-16P (51 dB).

[Image of PoE application with IP Cameras and Wireless Access Points]

## 3. Specialized Modes (ECS1020-16T Only)

- **Dumb Switch Mode:** No VLAN, standard unmanaged operation.
- **VLAN Mode (Port Isolation):** \* Port 16 (Uplink) communicates with ports 1-15.
  - Ports 1-15 isolated from each other.
- **VLAN Monitor Mode:** \* Port 16 (Uplink) 10/100/1000 Mbps.
  - Ports 1-15 fixed at **10 Mbps** (Extended distance up to 250M).
  - Isolation between ports 1-15 enabled.

## 4. Physical & Environmental

| Feature                | ECS1020-16T/24T/10P         | ECS1020-16P                 |
| :--------------------- | :-------------------------- | :-------------------------- |
| **Dimensions (WxDxH)** | 280 x 180 x 44 mm           | 440 x 208 x 44 mm           |
| **Weight**             | 1.35 kg - 1.70 kg           | 2.70 kg                     |
| **Rack Space**         | 13"" (Rackmount)            | 19"" (Rackmount)            |
| **Power Input**        | 100-240 VAC, 50-60 Hz       | 100-240 VAC, 50-60 Hz       |
| **Operating Temp**     | 0°C to 40°C                 | 0°C to 40°C                 |
| **Operating Humidity** | 10% to 90% (non-condensing) | 10% to 90% (non-condensing) |

## 5. Compliance & Safety

- **Safety:** LVD.
- **EMC:** CE Mark, FCC Class A, BSMI.
- **Environment:** WEEE, RoHS compliant."
  "# ECIS4500 Series – Industrial Managed Gigabit Ethernet Switches

## 1. System Core & Performance

| Feature                       | ECIS4500-6T2F                         | ECIS4500-6T4F  | ECIS4500-8T2F  |
| :---------------------------- | :------------------------------------ | :------------- | :------------- |
| **RJ-45 Ports (10/100/1000)** | 6                                     | 6              | 8              |
| **SFP Slots (100/1000)**      | 2                                     | 4              | 2              |
| **Console Port**              | 1 x RJ-45                             | 1 x RJ-45      | 1 x RJ-45      |
| **Switching Capacity**        | 16 Gbps                               | 20 Gbps        | 20 Gbps        |
| **Forwarding Rate**           | 17.9 Mpps                             | 17.9 Mpps      | 17.9 Mpps      |
| **Memory**                    | **RAM:** 128 MB <br> **Flash:** 16 MB | 128 MB / 16 MB | 128 MB / 16 MB |
| **MAC Address Table**         | 8 K                                   | 8 K            | 8 K            |
| **Jumbo Frames**              | 9 K Bytes                             | 9 K Bytes      | 9 K Bytes      |

## 2. Industrial Redundancy & L2 Features

- **Ring Technology:** **E-Ring Technology** (Fast ring fail-over protection **< 20 ms**).
- **Redundancy Protocols:** IEEE 802.1D STP, 802.1w RSTP, 802.1s MSTP, LACP (Dynamic & Static).
- **VLAN Support:** \* 4096 VLAN IDs.
  - Port-based, Tag-based (802.1Q), Double Tagging (**Q-in-Q**).
  - GVRP, RADIUS-assigned VLAN.
- **Multicast:** IGMP v1/v2 Snooping, Querying, Filtering/Throttling (255 groups).
- **QoS:** 8 priority queues, SPQ/WRR scheduling, 802.1p CoS, Port-based shaping.

## 3. Power & Physical Specifications

| Feature              | Specification                                                    |
| :------------------- | :--------------------------------------------------------------- |
| **Power Input**      | **12 – 58 VDC**, Redundant Input Terminals                       |
| **Power Protection** | Reverse Power Protection & Transient Protection (> 15,000W peak) |
| **Consumption**      | ~10 W (Max)                                                      |
| **Housing**          | **IP30** metal case                                              |
| **Dimensions**       | 60 x 109 x 154 mm                                                |
| **Mounting**         | **DIN-rail** (clip included) or Wall mount                       |
| **Operating Temp**   | **-40°C to 75°C**                                                |
| **Alarm Relay**      | 1 output (Max 0.5A @ 24 VDC) for System Alarms                   |

## 4. Security & Management

- **Security:** \* IEEE 802.1X (IP/MAC-based), Port Security, ACL.
  - Authentication: RADIUS, TACACS+, Local Database.
  - Encrypted sessions: **HTTPS, SSL, SSH**.
- **Management:** \* CLI (Cisco-like), Web UI, SNMP v1/v2c/v3.
  - DHCP: Client, Relay, Server, Snooping, Option 82.
  - Monitoring: Port Mirroring (Per VLAN), LLDP, Syslog, RMON (groups 1, 2, 3, 9).
  - Diagnostics: Ethernet Copper diagnostic tool, Remote Ping.

## 5. Regulatory & Industry Compliance

- **Railway:** **EN 50121-4** compliance.
- **EMC/Safety:** CE/FCC Class A, UL-60950.
- **Environmental Tests:** \* Shock (IEC 60068-2-27).
  - Vibration (IEC 60068-2-6).
  - Freefall (IEC 60068-2-32).
- **MTBF:** > 25 years."
  "# EAP102 – TIP Open Indoor Access Point

## 1. System Core & Interfaces

| Feature          | Specification                                            |
| :--------------- | :------------------------------------------------------- |
| **CPU**          | Qualcomm IPQ8071A                                        |
| **Memory**       | **RAM:** 1 GB <br> **Flash:** 32 MB NOR / 256 MB NAND    |
| **Uplink Port**  | 1 x 10/100/1000/2.5GBase-T Ethernet (RJ-45, 802.3at PoE) |
| **LAN Port**     | 1 x 10/100/1000/2.5GBase-T Ethernet (RJ-45)              |
| **Console Port** | 1 x RJ-45                                                |
| **USB**          | 2 x USB 2.0 Port (Hoạt động luân phiên từng cổng)        |
| **Bluetooth**    | Bluetooth Low Energy (BLE) radio tích hợp                |

## 2. Wi-Fi Performance & Radio

- **Standard:** IEEE 802.11ax (Wi-Fi 6), Concurrent Dual-Band.
- **Radio Chains / Spatial Streams:**
  - **2.4 GHz:** 2 x 2 MU-MIMO; 2 Spatial Streams.
  - **5 GHz:** 4 x 4 MU-MIMO; 4 Spatial Streams.
- **Physical Data Rate:**
  - **2.4 GHz:** Lên đến 574 Mbps.
  - **5 GHz:** Lên đến 2,400 Mbps.
  - **Tổng băng thông:** ~2.9 Gbps.
- **Antenna (Tích hợp):**
  - **Loại:** 4 x Built-in antenna.
  - **Gain:** 5.5 dBi (2.4 GHz & BLE), 7.6 dBi (5 GHz).
- **Băng tần & Kênh:**
  - 2.400 - 2.483 GHz (20/40 MHz).
  - 5.150 - 5.850 GHz (20/40/80 MHz).
- **ESSIDs:** Hỗ trợ tối đa **32 ESSIDs** (16 mỗi radio).

## 3. Power & Physical Specifications

| Feature               | Specification                                             |
| :-------------------- | :-------------------------------------------------------- |
| **Power Input**       | **DC:** 12V / 2A <br> **PoE:** 802.3at compliant          |
| **Power Consumption** | Tối đa 25W                                                |
| **Dimensions**        | 195 x 201 x 39.8 mm                                       |
| **Weight**            | 0.7 kg (1.54 lbs)                                         |
| **Mounting**          | Wall / Ceiling / T-bar mount (Kèm bộ kit)                 |
| **Environment**       | Nhiệt độ hoạt động: **0°C đến 45°C** <br> Độ ẩm: 5% - 95% |
| **Protection (ESD)**  | IEC-61000-4-2 (+/-4KV contact, +/-8KV air)                |

## 4. Software & Compliance

- **Platform:** **TIP Open WiFi Ready** (Phần mềm cài đặt sẵn, linh hoạt tùy chỉnh).
- **Security:** Enterprise-grade wireless security.
- **Certifications:** FCC, CE, LVD, NCC, BSMI, VCCI, JATE, IC, C-Tick.
- **Ordering Information:** _ **Part Number:** EAP102_T
  _ **Description:** FI2EC7616401S-C"
  "# EAP101 – Indoor Wi-Fi 6 Access Point

## 1. System Core & Interfaces

| Feature               | Specification                                     |
| :-------------------- | :------------------------------------------------ |
| **Wireless Standard** | IEEE 802.11ax (Wi-Fi 6), Concurrent Dual-Band     |
| **Uplink Port**       | 1 x 10/100/1000/2.5GBase-T Ethernet (802.3at PoE) |
| **LAN Ports**         | 2 x 10/100/1000Base-T Ethernet                    |
| **Console Port**      | 1 x RJ-45 Port                                    |
| **USB**               | 1 x USB 2.0 Port                                  |
| **Additional Radios** | **Bluetooth Low Energy (BLE) 5.2** & **ZigBee**   |
| **Buttons**           | Restart / Reset                                   |

[Image of EAP101 Wi-Fi 6 Access Point interfaces and hardware layout]

## 2. Wi-Fi & Radio Performance

- **Radio Chains / Spatial Streams:** 2 x 2 MU-MIMO; 2 Spatial Streams.
- **Aggregated Data Rate:** Up to **1.7 Gbps**.
  - **5 GHz:** Up to 1200 Mbps (HE80).
  - **2.4 GHz:** Up to 574 Mbps (HE40).
- **Antenna (Built-in):**
  - 2.4 GHz: 4.8 dBi
  - 5 GHz: 6 dBi
  - BLE: 4.6 dBi
- **Advanced Wireless Features:**
  - **OFDMA** & BSS Coloring.
  - Target Wake Time (TWT).
  - 802.11 k/v/r (Fast Roaming).
  - Support up to **32 ESSIDs** (16 per radio).

[Image of MU-MIMO and OFDMA technology in Wi-Fi 6]

## 3. Security & Network Features

- **Wireless Security:**
  - **WPA3-Personal/Enterprise** & Transition modes.
  - Wi-Fi Enhanced Open (OWE).
  - Multi/Dynamic Pre-Shared Key (MPSK/DPSK).
- **Network Features:**
  - IPv6 Compatible.
  - Access Control List (ACL) & L3 Firewall.
  - DHCP Snooping & ARP Inspection.
  - Open Mesh & Band Steering.
- **Mobility:** OpenRoaming (Hotspot 2.0 R1).

## 4. Management & AI Intelligence

- **Management Options:**
  - **ecCLOUD:** Cloud-based management.
  - **Standalone:** Local configuration.
  - **EWS-Series Controller:** Hardware controller management.
- **AI-Enabled Detection (via ecCLOUD):**
  - Performance detection (Throughput, Latency, Packet Drops).
  - Wi-Fi Experience monitoring (EAP failures, Radio Congestion, Hogging Airtime).
  - Roaming analysis (Sticky Client, Slow Roaming detection).
- **Deployment:** Zero Touch Provisioning (ZTP), QR Code Onboarding.

[Image of Edgecore ecCLOUD management dashboard showing AI-enabled performance detection]

## 5. Power & Physical Specifications

| Feature                | Specification                                      |
| :--------------------- | :------------------------------------------------- |
| **Power Input**        | **DC:** 12V / 2.0A <br> **PoE:** 802.3at compliant |
| **Power Consumption**  | Max. 22.4 W                                        |
| **Operating Temp**     | **0°C to 50°C** (32°F to 122°F)                    |
| **Operating Humidity** | 5% to 95% (non-condensing)                         |
| **Dimensions**         | 19.5 x 19.5 x 3.9 cm                               |
| **Weight**             | 0.65 kg (1.44 lb)                                  |
| **Mounting**           | Wall / Ceiling / T-bar mount (Kit included)        |
| **Security Slot**      | 1 x Kensington lock slot                           |

## 6. Regulatory & Certifications

- **Certifications:** FCC, CE, LVD, NCC, BSMI, VCCI, JATE, TELEC, IC, C-Tick."
  "# AS5710-54X / AS5712-54X – 10GbE Data Center Switch

## 1. System Core & Interfaces

| Feature              | Specification                                                             |
| :------------------- | :------------------------------------------------------------------------ |
| **Switch Silicon**   | Broadcom BCM56854 Trident II 720Gbps                                      |
| **CPU (AS5710-54X)** | **Freescale P2041** quad-core 1.5GHz <br> 2 GB DDR3 RAM, 8 GB NAND Flash  |
| **CPU (AS5712-54X)** | **Intel Atom C2538** quad-core 2.4GHz <br> 8 GB DDR3 RAM, 8 GB NAND Flash |
| **10G Ports**        | 48 x SFP+ (Supporting 10GbE or 1GbE)                                      |
| **40G Ports**        | 6 x QSFP (Supporting 40GbE or 4 x 10GbE breakout)                         |
| **Management**       | 1 x RJ-45 Console, 1 x RJ-45 10/100/1000M, 1 x USB Type A                 |

## 2. Performance & Network Virtualization

- **Switching Capacity:** 1.44 Tbps full duplex
- **Forwarding Rate:** 1 Bpps (Billion packets per second)
- **Packet Buffer:** 12 MB integrated
- **Jumbo Frames:** Up to 9216 Bytes
- **MAC Address Table:** 32 K min / 288 K max (Tùy thuộc vào NOS)
- **Hardware Virtualization:** Hỗ trợ VXLAN và NVGRE tunneling
- **Forwarding Mode:** Full line-rate Layer 2 và Layer 3

## 3. Power & Physical

| Feature            | Specification                                                    |
| :----------------- | :--------------------------------------------------------------- |
| **Power Input**    | 90 – 264 VAC / -48 to -72 VDC / 12 VDC option                    |
| **Redundancy**     | 2 x Hot-swappable, load-sharing PSUs                             |
| **Max Power**      | **282 W** (Không bao gồm Module quang)                           |
| **Fans**           | 4+1 redundant fan modules, hot-swappable                         |
| **Airflow**        | Port-to-power (Front-to-Back) hoặc Power-to-port (Back-to-Front) |
| **Dimensions**     | 44.3 x 47.3 x 4.34 cm (Chuẩn 1U)                                 |
| **Operating Temp** | 0°C to 40°C (32°F to 104°F)                                      |

## 4. Software & Management

- **Boot Loader:** Pre-loaded với **Open Network Install Environment (ONIE)**
- **Hệ điều hành tương thích (AS5712):** Cumulus Linux, Open Network Linux (ONL), PicOS, Big Monitoring Fabric, Netvisor OS, FlexSwitch.
- **Hệ điều hành tương thích (AS5710):** Open Network Linux (ONL), Big Monitoring Fabric.
- **Monitoring:** Hệ thống LED hiển thị trạng thái Port (Link/Activity), PSU, Quạt và Chẩn đoán hệ thống.
- **Compliance:** CE, FCC Part 15 Class A, RoHS-6, TAA Compliant."
