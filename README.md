# OPTIGA™ Connect IoT OC2321

## Infineon eSIM IoT Solution

<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-VQFN8.png" width="200" title="OPTIGA Connect - VQFN8 package">

OPTIGA™ Connect IoT is an embedded SIM (eUICC) turnkey solution that
enables cellular connectivity at scale for IoT devices.

<img src="https://github.com/Infineon/Assets/blob/master/Pictures/OPTIGA_Connect_IoT/OPTIGA_Connect_IoT-Logo.png" width="300" title="OPTIGA Connect Iot - Solution Diagram">

OPTIGA™ Connect IoT consists of an eUICC including GSMA compliant
eSIM operating system and pre-loaded bootstrap connectivity.


### Key Features and Benefits
* Remote SIM provisioning compliant with GSMA SGP.02 V3.2
* Compliant with 2G, 3G, 4G (LTE), CDMA, NB-IoT, CAT-M networks
* [Tata Communications](https://www.tatacommunications.com/solutions/mobility-iot/internet-ofthings/esim/infineon-partnership/connectivity) bootstrap - worldwide coverage
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
  * [Getting Started](#getting-started)
  * [Samples Kit](#samples-kit)
  * [Documentation](#documentation)
  * [Contributing](#contributing)

## Getting Started

### OPTIGA™ Connect IoT evaluation kit

### Examples

#### How to read out EID

The EID or eUICC-ID is the unique identifier of an embedded Universal Integrated Circuit Card (eUICC)<br> 
One option to get the EID is to read it electronically by means of Command-APDUs (Application Protocol Data Unit)<br> 
via the ISO/IEC 7816-UART: 
``` markdown
1) SELECT ECASD: A0 00 00 05 59 10 10 FF FF FF FF 89 00 00 02 00
-> 00 A4 04 00 10 A0 00 00 05 59 10 10 FF FF FF FF 89 00 00 02 00 
<- 90 00

2) GET DATA Tag 5A, EID example= 89034011560010000000000000000121
-> 80 CA 00 5A 12
<- 5A 10 89 03 40 11 56 00 10 00 00 00 00 00 00 00 01 21 90 00
```

## Documentation

For the Datasheet, Product Brief and the Quickstarter Guide please visit our [OPTIGA™ Connect IoT OC2321 product website](https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-connect/optiga-connect-iot/)<br>

* [DataSheet](https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-connect/optiga-connect-iot/#!documents)
* [Product Brief](https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-connect/optiga-connect-iot/#!documents)
* [Quickstarter Guide](https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-connect/optiga-connect-iot/)

## Contributing

For reporting technical issues or proposing new features, please create a new issue.<br>

Read more in the [Contributing Guide](https://github.com/Infineon/optiga-connect-iot/blob/master/CONTRIBUTING.md)

## License

## Disclaimer
