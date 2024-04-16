# Lilygo TTGO T-Beam LoRa V1.2 (TBeam-AXP2101-V1.2)

## Introduction

This repository has been created to address the fragmentation of information and frequent misidentification of components related to the Lilygo TTGO T-Beam LoRa V1.2 board. It aims to provide a detailed resource covering the components used in my unit, instructions on how to control them, and an overview of their capabilities.

## Components

Here is a detailed list of components included on the Lilygo TTGO T-Beam LoRa V1.2:

| Component            | Model / Specification                                          | Image                                                                                                                        |
|----------------------|----------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Power Management** | AXP2101                                                        | ![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/19901be8-0966-4945-9a5f-20a95e9222c2)|
| **USB-UART Converter** | CH9102F                                                      |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/8b9187c8-b851-4f2d-8dc4-8512e3ea656b)|
| **Additional FLASH** | 25Q32JVSIQ (W25Q32JV)                                          |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/82142d90-f1b8-4bac-abb7-32ea806ee841)       |
| **Additional PSRAM** | APS6404L-3SQR (APS6404L-3SQR QSPI PSRAM)                       | ![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/7fd6b1fb-a30d-4301-bda7-35a142bf4a6e)      |
| **System on Chip (SoC)** | ESP32-D0WDQ6-V3                                             |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/bb0f027d-7781-4a3d-bb46-1142eafdaf45)     |
| **GPS Module**       | NEO-6M-0-001 (IPEX connected antenna)                           |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/6987e2af-3f7d-4b80-96b6-a4243fffe04a)        |
| **GPS Flash**        | 24AA32A                                                        |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/07592282-7e65-43e0-bd46-ae4148658ce7)       |
| **LoRa Module**      | Lilygo 433/470-MHz LORA32 <br> HPDTeK HPD14A V1.2 (SX1278 433MHz)   |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/06727c8d-ba6d-4614-a508-1ca691e0a568) ![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/c6b1cc36-8943-4ab7-9c34-9ea8feeebcdb)|
| **Main Battery**     | 18650 (+ NCE3401AY MOSFET)                                     |                                                                                           |
| **Backup Battery**   | MS412FE (MS Lithium Rechargeable Battery MS412FE)              |                                                                                           |



## External Libraries and Repositories

The following external libraries and repositories are used in this project:

- [XPowersLib](https://github.com/lewisxhe/XPowersLib) - Library for interfacing with power management components.
- [LilyGo-LoRa-Series](https://github.com/Xinyuan-LilyGO/LilyGo-LoRa-Series) - Library for managing the LoRa functionalities.
