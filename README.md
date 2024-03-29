# OPTIGA™ Connect IoT

## Infineon eSIM IoT Solution

<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-VQFN8.png" width="250" title="OPTIGA Connect - VQFN8 package">

OPTIGA™ Connect IoT is an embedded SIM (eUICC) turnkey solution that
enables cellular connectivity at scale for IoT devices.

<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-Logo.png" width="300" title="OPTIGA Connect Iot - Solution Diagram">

OPTIGA™ Connect IoT consists of an eUICC including GSMA compliant
eSIM operating system and pre-loaded bootstrap connectivity.


### Key Features and Benefits
* Remote SIM provisioning compliant with GSMA SGP.02 V3.2
* Compliant with 2G, 3G, 4G (LTE), CDMA, NB-IoT, CAT-M networks
* [Tata Communications](https://www.tatacommunications.com/solutions/mobility-iot/internet-of-things/esim/infineon-partnership) bootstrap - worldwide coverage
* Allows to accommodate multiple MNO profiles
* OTA capable
* 32-bit architecture based on Arm® SecurCore® SC300 enhanced by Infineon Technologies' cache and security technology
* ISO/IEC 7816 UART interface
* Power Supply 1.8/3/5 Volts
* Common Criteria EAL5+ certified hardware
* VQFN-8 package (MFF2)
* Removable SIM and other packages on request
### Application
* IoT end nodes and edge gateways
* Smart Home (security, alarm, light-HVAC-Energy control)
* iHealth monitoring
* Smart City (security, lighting, parking sensor)
* Industry Automation (smart machines, security camera, factory automation, asset tracking)
* Smart Energy (metering, storage, distribution)
* Commercial telematics
* GPS Tracker

## Table of Content
  * [What's new?](#whats-new)
  * [Getting Started](#getting-started)
  * [Documentation](#documentation)
  * [Contributing](#contributing)
  
## What's new?
  01-2024
  * [Modem compatibility list](https://github.com/Infineon/optiga-connect-iot/wiki/Modem-compatibility-list) updated in [Wiki](https://github.com/Infineon/optiga-connect-iot/wiki) section
  * [Modem SIM detection pin](https://github.com/Infineon/optiga-connect-iot/wiki/Modem-SIM-detection-pin) added in [Wiki](https://github.com/Infineon/optiga-connect-iot/wiki) section
  * [Modem troubleshooting guide](https://github.com/Infineon/optiga-connect-iot/wiki/Modem-troubleshooting-guide) added in [Wiki](https://github.com/Infineon/optiga-connect-iot/wiki) section
  * [Modem configuration steps](https://github.com/Infineon/optiga-connect-iot/wiki/Modem-configuration-steps) added in [Wiki](https://github.com/Infineon/optiga-connect-iot/wiki) section
  * [PCB-Design Data](https://github.com/Infineon/optiga-connect-iot/tree/master/support/PCB-Design) for OC2321 and OC2322 added.

## Getting Started
When starting to evaluate Infineons OPTIGA™ Connect IoT solution as a proposal you might want to follow these steps:<br>
1. Download the [DataSheet](https://www.infineon.com/dgdl/Infineon-Datasheet_OPTIGA_Connect_IoT-DataSheet-v01_00-EN.pdf?fileId=5546d462749a7c2d01749b3873b90f57)
2. Order the OPTIGA™ Connect IoT SAMPLE KIT
3. In case you don't have a dedicated `Device` yet, get our OPTIGA™ Connect IoT Evaluation Board
4. Buy a miniPCIe modem of your choice and a LTE antenna. Ensure that the modem is capable to handle eUICCs!
5. If you don't want to solder the VQFN8 package or work with Smart Card readers consider getting our Card Adapter VQFN8 version
6. In case you need adapter that fit in SIM sockets in combination with the Card Adapter VQFN8 we offer a SIM Cable Adapter Kit
7. Download the [Quickstarter Guide](https://www.infineon.com/dgdl/Infineon-Quick_Start_Guide_OPTIGA_Connect_IoT-AdditionalProductInformation-v01_00-EN.pdf?fileId=5546d46274cf54d50174da052db12212)

### OPTIGA™ Connect IoT SAMPLE KIT
The kit comes with 5 pcs of OPTIGA™ Connect IoT with predefined dataplan working out of the box for instant trials.<br>

* 5 pcs VQFN-8/MFF2
* 70 MB of connectivity (*)
* 6 month validity from first network connect on
* 150 countries worldwide coverage (Americas, APAC and EMEA)

(*) For all eSIMs included in the Kit, a combined total of 70 MB is available.<br> 

<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-Samples_Kit_2a.png" height="300" title="OPTIGA Connect IoT - Samples Kit">   <img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-Samples_Kit_3c.png" height="300" title="OPTIGA Connect IoT - Samples Kit Details">

### OPTIGA™ Connect IoT Evaluation Board
Enables customer to verify/operate OPTIGA™ Connect IoT in combination with a cellular modem available as mini PCIe form factor<br>

* LTE modem shield only
* Incl. OPTIGA™ Connect IoT VQFN-8 soldered to the board
* 3FF/Micro-SIM card holder 
* Switch between SIM/eSIM
* Connects to host via 40-pin Raspberry Pi header or Micro-USB
* Optional: Footprint to add OPTIGA™ Trust X/M

<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-LTE_Shield_Bot_V3.png" height="300" title="OPTIGA Connect IoT - Evaluation Board - Bottom">   <img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-LTE_Shield_Top_V3.png" height="300" title="OPTIGA Connect IoT - Evaluation Kit - Top">

### Card Adapter V3.6 VQFN8-1

In this configuration the card adapter is assembled with a<br>

* VQFN-8 Zero Force Insertion (ZIF) test socket
* Jumper and test pins<br>

<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-SP000416068_CardAdaptA3.6VQFN8.1.png" height="230" title="OPTIGA Connect IoT - Card Adapter V3.x VQFN8 version">   
<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-CardAdaptV3.7VQFN8_det.png" height="230" title="OPTIGA Connect IoT - Card Adapter V3.x VQFN8 socket">

### SIM Cable Adapter Kit

Add-on for Card Adapter V3.x <br>
Enables a connection from an OPTIGA™ Connect IoT inserted in the ZIF-socket to a 2FF, 3FF or 4FF SIM card holder<br>

The kit includes 5 variants of SIM adapters to be attached to Card Adapter V3.x via its female 8-pin header<br>
You get:
* Mini-SIM  (2FF, 0 deg)
* Mini-SIM  (2FF, 90 deg)
* Micro-SIM (3FF, 0 deg)
* Micro-SIM (3FF, 180 deg)
* Nano-SIM  (4FF, 0 deg)

Note: The RJ45 and SMB coax cable are not relevant for eSIM


<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA Connect IoT-SIM_Cable_Adapter_Kit.png" height="600" title="OPTIGA Connect IoT - SIM Cable Adapter Kit">

## Documentation

For the Datasheet, Product Brief and a Quickstarter Guide please visit our [OPTIGA™ Connect IoT product website](https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-connect/optiga-connect-iot/#!documents)<br>
Here the direct links to<br>

* [DataSheet](https://www.infineon.com/dgdl/Infineon-Datasheet_OPTIGA_Connect_IoT-DataSheet-v01_00-EN.pdf?fileId=5546d462749a7c2d01749b3873b90f57)
* [Product Brief](https://www.infineon.com/dgdl/Infineon-OPTIGA_Connect_IoT_OC2321-ProductBrief-v01_00-EN.pdf?fileId=5546d46272aa54c00172c1aa70304f10)
* [Quickstarter Guide](https://www.infineon.com/dgdl/Infineon-Quick_Start_Guide_OPTIGA_Connect_IoT-AdditionalProductInformation-v01_00-EN.pdf?fileId=5546d46274cf54d50174da052db12212)

## Contributing

For reporting `technical issues` or proposing `new features`, please create a new [issue](https://github.com/Infineon/optiga-connect-iot/issues).<br>

> Before considering submitting a new issue please check out the [OPTIGA™ Connect IoT - Wiki](https://github.com/Infineon/optiga-connect-iot/wiki)

> When submitting a new issue please be aware that OPTIGA™ Connect IoT is a solution with four major categories and 2 partners involved.

<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA Connect IoT - Solution Architecture.svg" width="250" title="OPTIGA Connect IoT - Solution Architecture">

Fig.: OPTIGA™ Connect IoT - Solution Architecture<br>

Therefore please help us by linking your issues to these four major categories:

* Hardware
* Package
* Software
* Connectivity

Read more in the [Contributing Guide](https://github.com/Infineon/optiga-connect-iot/blob/master/CONTRIBUTING.md)

## License

## Disclaimer
