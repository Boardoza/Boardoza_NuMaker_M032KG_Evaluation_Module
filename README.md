# Boardoza NuMaker M032KG Evaluation Module Development Board

The **Boardoza NuMaker M032KG Evaluation Module** is a comprehensive development platform based on the **Nuvoton M032KG8AE** Arm® Cortex®-M0 microcontroller. It is designed to help developers quickly prototype, program, and debug embedded applications with minimal setup.

This development board integrates an on-board **Nu-Link2-Me debugger/programmer**, Arduino UNO–compatible headers, and full pin extension connectors, making it suitable for education, rapid prototyping, industrial control, and low-power embedded system development. With flexible power options and built-in current measurement support, it is ideal for evaluating both functionality and power consumption.

## [Click here to purchase!](https://www.ozdisan.com/p/gelistirme-kitleri-ve-aksesuarlari-617/nuvoton-nk-m032kg-621749)

| Front Side | Back Side |
| :---: | :---: |
| ![Front](./assets/B-NuMakerM032KG-EVM%20Front.png) | ![Back](./assets/B-NuMakerM032KG-EVM%20Back.png) |

---

## Key Features

- **Arm® Cortex®-M0 Core:** Based on the Nuvoton M032KG8AE microcontroller, optimized for low-power and cost-sensitive embedded applications.
- **On-Board Debugger & Programmer:** Integrated Nu-Link2-Me enables programming and debugging via SWD without external tools.
- **Arduino UNO Compatible Headers:** Supports rapid prototyping and easy expansion with Arduino-compatible shields.
- **Full Pin Extension Connectors:** Provides access to all MCU pins for advanced and custom hardware development.
- **Flexible Power Options:** Supports VIN input, USB power, and configurable 3.3 V / 5 V target operation.
- **Power Consumption Measurement:** Dedicated ammeter connector allows real-time monitoring of MCU current usage.
- **USB Connectivity:** Separate USB connectors for target MCU and debugger ensure stable development workflow.
- **Virtual COM Port Support:** Enables serial communication with a PC via the on-board debugger.

---

## Technical Specifications

**Model:** M032KG8AE  
**Manufacturer:** Boardoza    
**Manufacturer IC:** Nuvoton Technology  
**Core:** Arm® Cortex®-M0 (32-bit)  
**Maximum Clock Frequency:** Up to 72 MHz  
**Operating Voltage:** 3.3 V / 5 V (configurable)  
**Input Voltage:** Refer to Power Configuration Table  
**Voltage Input Type:** VIN header / USB Type-C  
**Flash Memory:** 256 KB  
**SRAM:** 64 KB  
**GPIO Pins:** Full MCU pin access via extension headers  
**Analog Inputs:** 16 Channel 12-bits ADC channels up to 2 MSPS    
**Interfaces:** UART, SPI, I²C, I²S, PWM, SWD  
**Debug Interface:** SWD (Nu-Link2-Me on-board)  
**Mounting Hole Size:** 4 × M3  
**Operating Temperature:** -40 °C to +85 °C  
**Board Dimensions:** 63 mm × 137.5 mm  

---

## Power Configuration Table

| Configuration | Target Chip Voltage | VIN | J2 (USB) | Nu-Link USB (J5) | SW2 Selection | JP1 Output |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 3.3 V | 7–12 V | X | Ignore | NU1_3VCC | 3.3 V |
| 2 | 3.3 V | X | PC Connection | Ignore | NU1_3VCC | 3.3 V |
| 3 | 5 V* | 7–12 V | X | Ignore | NU1_5VCC | 5 V |
| 4 | 5 V* | X | PC Connection | Ignore | NU1_5VCC | 5 V |
| 5 | 3.3 V | Ignore | Ignore | PC Connection | OFF | 3.3 V |

\* Requires shorting pads of R12 and R4.

---

## Board Pinout


>  **Note:** The complete Arduino mapping, JP3/JP4/JP5/JP6 headers and full multi-function pin descriptions are available in the official board pinout document below:  
>  [NuMaker-M032KG Pinout](./assets/B-NuMakerM032KG-EVM%20Pinout.pdf)

---

## Board Dimensions

<img src="./assets/B-NuMakerM032KG-EVM Dimension.png" alt="Board Dimensions" width="450"/>

---

## Step Files

[Boardoza NuMakerM032KG-EVM.step](./assets/B-NuMakerM032KG-EVM%20Step.step)

---

## Datasheet

[M031/M032 Series Product Brief](./assets/en-us--PB_M031_M032_Series_EN_V1.10%20Datasheet.pdf)  
[M031/M032 Series Technical Reference Manual](./assets/TRM_M031_M032_Series_EN_Rev2.02%20Datasheet.pdf)   
[Nu-Link Debug Adapter User Manual](./assets/UM_Nuvoton_Nu-Link_Debug_Adapter_EN_Rev1.01%20Datasheet.pdf)  

---

## Version History

- **v1.0.0** – Initial Release

---

## Support

If you have any questions or need support, please contact **support@boardoza.com**

---

## **License**
### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
