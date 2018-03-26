## Table of Contents

* [Introduction](#introduction)
* [Navigating the Repository](#navigating-the-repository)
* [Required Tools](#required-tools)
* [Code Examples List](#code-examples-list)
* [References](#references)

# Introduction

This repository contains examples and demos for [PSoC 4 MCU](http://www.cypress.com/products/32-bit-arm-cortex-m0-psoc-4) family of devices, world's Most Flexible 32-bit ARM Cortex-M0 One-Chip Solution. Cypress provides a wealth of data at [www.cypress.com](http://www.cypress.com/) to help you select the right PSoC device and effectively integrate it into your design. Visit our [PSoC 4 MCU](http://www.cypress.com/products/32-bit-arm-cortex-m0-psoc-4) webpage to explore more about PSoC 4 MCU family of device.

Feel free to explore through the code example source files and Let us innovate together!

# Navigating the Repository

This repository provides examples that demonstrates how to develop capacitive touch sensing applications with PSoC 4 MCU using the Cypress’ CapSense feature. The CapSense feature offers unprecedented signal-to-noise ratio, best-in-class liquid tolerance, and a wide variety of sensors such as buttons, sliders, trackpads and proximity sensors.

If you are new to developing projects with PSoC 4 MCU, we recommend you to refer the [PSoC 4 Getting Started](https://github.com/cypresssemiconductorco/PSoC4-MCU-Getting-Started) GitHub page which can help you familiarize with device features and guides you to create a simple PSoC 4 design with PSoC Creator IDE. For other block specific designs please refer to the following GitHub repositories:

#### 1. [Analog Designs](https://github.com/cypresssemiconductorco/PSoC4-MCU-Analog-Designs)
#### 2. [Digital Designs](https://github.com/cypresssemiconductorco/PSoC4-MCU-Digital-Designs)
#### 3. [BLE Connectivity Designs](https://github.com/cypresssemiconductorco/PSoC4-MCU-BLE-Connectivity-Designs)
#### 4. [USB Connectivity Designs](https://github.com/cypresssemiconductorco/PSoC4-MCU-USB-Connectivity-Designs)
#### 5. [Device Related Designs](https://github.com/cypresssemiconductorco/PSoC4-MCU-Device-Related-Designs)
#### 6. [PSoC 4 Pioneer Kit](https://github.com/cypresssemiconductorco/PSoC4-MCU-Pioneer-Kits)
#### 7. [System Designs](https://github.com/cypresssemiconductorco/PSoC4-MCU-System-Designs)

You can use these block level examples to guide you through the development of a system-level design. All the code examples in this repository comes with well documented design guidelines to help you understand the design and how to develop it. The code examples and their associated documentation are in the Code Example folder in the repository.

# Required Tools

## Software
### Integrated Development Environment (IDE)
To use the code examples in this repository, please download and install
[PSoC Creator](http://www.cypress.com/products/psoc-creator)

## Hardware
### PSoC 4 MCU Development Kits
* [CY8CKIT-042-BLE-A Bluetooth® Low Energy 4.2 Compliant Pioneer Kit](http://www.cypress.com/documentation/development-kitsboards/cy8ckit-042-ble-bluetooth-low-energy-42-compliant-pioneer-kit).

* [CY8CKIT-041-41XX PSoC 4100S CapSense Pioneer Kit](http://www.cypress.com/documentation/development-kitsboards/cy8ckit-041-41xx-psoc-4100s-capsense-pioneer-kit). 

* [CY8CKIT-046 PSoC 4 L-Series Pioneer Kit](http://www.cypress.com/documentation/development-kitsboards/cy8ckit-046-psoc-4-l-series-pioneer-kit)

* [CY8CKIT-044 PSoC Analog Coprocessor Pioneer Kit](http://www.cypress.com/documentation/development-kitsboards/cy8ckit-048-psoc-analog-coprocessor-pioneer-kit)

* [CY8CKIT-049-4xxx PSoC 4 Prototyping Kit](http://www.cypress.com/documentation/development-kitsboards/psoc-4-cy8ckit-049-4xxx-prototyping-kits)

* [CY8CKIT-042 PSoC 4 Pioneer Kit](http://www.cypress.com/documentation/development-kitsboards/cy8ckit-042-psoc-4-pioneer-kit) 

**Note** Please refer to the code example documnetation for selecting the appropriate kit for testing the project

## Code Example List
#### 1. CE95285 - CapSense CSD with PSoC 4
This CapSense_CSD_P4_Design code example demonstrates operation of the CapSense CSD component with the PSoC Creator Software and PSoC 4 Pioneer Kit (CY8CKIT-042) or PSoC 4 S0 Kit (CY8CKIT-040) hardware. The component is configured with a linear slider. Visual feedback of a Slider touch can be observed via LEDs.
#### 2. CE95286 - PSoC® 4 CapSense_CSD Slider and Tuner
This CapSense_CSD_P4 Tuner Design code example demonstrates operation of the CapSense CSD component with the PSoC Creator software, CapSense Tuner software and PSoC 4 Pioneer Kit hardware (CY8CKIT-042). The component is configured with a linear slider. The CapSense Tuner software is used for displaying scanning results. Visual feedback of a Slider touch can be observed via LEDs.
#### 3. CE95288 - CapSense Low Power with PSoC 4
For PSoC 4000 devices only, this code example demonstrates a low power CapSense system. Any battery driven equipment requires very low system power consumption, while maintaining the required performance. The PSoC 4000 family supports a capacitive touch sensing known as CapSense® and two device low power modes: Sleep and Deep-Sleep. These low power modes enable PSoC 4 to achieve the required performance while operating at very low system power consumption.
#### 4. CE95289 - CapSense Proximity with PSoC 4
For PSoC 4000 devices only, this project demonstrates a CapSense based proximity sensing design to control brightness of a LED. It will help user learn how to design a proximity sensor in their design using a PSoC 4 (4000 family) device and see how an approaching hand controls the intensity of a LED. It will employ the CapSense auto tuning ability, SmartSense®, to tune the proximity sensor of any wire/trace length. The project will also help user understand and design a simple Sleep-scan routine using the proximity sensor where the device will enter a periodic scan mode at a configurable rate and sleep once the sensor scan is complete to save power.

## References
#### 1. PSoC 4 MCU
PSoC 4 is the world's Most Flexible 32-bit ARM Cortex-M0 One-Chip Solution. PSoC 4 has tackled some of the complex portions of embedded system design making it easier for you to get your product to market. Functions such as analog sensor integration, capacitive touch, and wireless connectivity have been integrated and optimized in PSoC 4 to “just work” so you don’t have to. To learn more on the device. Learn more: [PSoC 4 MCU](http://www.cypress.com/products/32-bit-arm-cortex-m0-psoc-4)

####  2. PSoC 4 MCU Learning resource list
##### 2.1 PSoC 4 MCU Datasheets
Device datasheets list the features and electrical specifications of PSoC 4 families of devices: [PSoC 4 MCU Datasheets](http://www.cypress.com/search/all?f%5b0%5d=meta_type%3Atechnical_documents&f%5b1%5d=field_related_products%3A1297&f%5b2%5d=resource_meta_type%3A575)
##### 2.2 PSoC 4 MCU Application Notes
Application notes are available on the Cypress website to assist you with designing your PSoC application: [A list of PSoC 4 MCU ANs](https://community.cypress.com/external-link.jspa?url=http%3A%2F%2Fwww.cypress.com%2Fsearch%2Fall%3Ff%255b0%255d%3Dmeta_type%253Atechnical_documents%26f%255b1%255d%3Dfield_related_products%253A1297%26f%255b2%255d%3Dresource_meta_type%253A574)
##### 2.3 PSoC 4 MCU Component Datasheets
PSoC Creator utilizes "components" as interfaces to functional Hardware (HW). Each component in PSoC Creator has an associated datasheet that describes the functionality, APIs, and electrical specifications for the HW. You can access component datasheets in PSoC Creator by right-clicking a component on the schematic page or by going through the component library listing. You can also access component datasheets from the Cypress website: [PSoC 4 Component Datasheets](https://community.cypress.com/external-link.jspa?url=http%3A%2F%2Fwww.cypress.com%2Fsearch%2Fall%3Ff%255b0%255d%3Dmeta_type%253Asoftware_tools%26f%255b1%255d%3Dfield_related_products%253A1297%26f%255b2%255d%3Dsoftware_tools_meta_type%253A532)
##### 2.4 PSoC 4 MCU Technical Reference Manuals (TRM)
The TRM provides detailed descriptions of the internal architecture of PSoC 4 devices:[PSoC 4 MCU TRMs](https://community.cypress.com/external-link.jspa?url=http%3A%2F%2Fwww.cypress.com%2Fsearch%2Fall%3Ff%255b0%255d%3Dmeta_type%253Atechnical_documents%26f%255b1%255d%3Dfield_related_products%253A1297%26f%255b2%255d%3Dresource_meta_type%253A583)

## FAQ

### Technical Support
If you have any queries or questions, our technical support team would be happy to assist you. You can create a support request at [This link](https://secure.cypress.com/myaccount/?id=25&techSupport=1), or if you are in the United States, you can talk to our technical support team by calling our toll-free number +1-800-541-4736 and then selecting option 8 at the IVR prompt. 

You can also use the following support resources if you need quick assistance: 
Self-help: [http://www.cypress.com/support] (http://www.cypress.com/support)
Local Sales office locations: [http://www.cypress.com/about-us/sales-offices] (http://www.cypress.com/about-us/sales-offices)
