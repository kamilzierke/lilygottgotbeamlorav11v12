# Lilygo TTGO T-Beam LoRa V1.2 (TBeam-AXP2101-V1.2)

## Introduction

This repository has been created to address the fragmentation of information and frequent misidentification of components related to the Lilygo TTGO T-Beam LoRa V1.2 board. It aims to provide a detailed resource covering the components used in my unit, instructions on how to control them, and an overview of their capabilities.

## Components

Here is a detailed list of components included on the Lilygo TTGO T-Beam LoRa V1.2:

| Component            | Model / Specification                                          | Image                                                                                                                        |
|----------------------|----------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Power Management** | AXP2101                                                        | ![AXP2101](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/a5136ea7-2379-4551-95cc-fb42595513b3)   |
| **USB-UART Converter** | CH9102F                                                      |  ![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/848ba108-04f1-4a04-b5bf-2fd15cf001b3)    |
| **Additional FLASH** | 25Q32JVSIQ (W25Q32JV)                                          |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/82142d90-f1b8-4bac-abb7-32ea806ee841)       |
| **Additional PSRAM** | APS6404L-3SQR (APS6404L-3SQR QSPI PSRAM)                       | ![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/7fd6b1fb-a30d-4301-bda7-35a142bf4a6e)      |
| **System on Chip (SoC)** | ESP32-D0WDQ6-V3                                             |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/bb0f027d-7781-4a3d-bb46-1142eafdaf45)     |
| **GPS Module**       | NEO-6M-0-001 (IPEX connected antenna)                           |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/6987e2af-3f7d-4b80-96b6-a4243fffe04a)        |
| **GPS Flash**        | 24AA32A                                                        |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/07592282-7e65-43e0-bd46-ae4148658ce7)       |
| **LoRa Module**      | Lilygo 433/470-MHz Model: LORA32                               |![obraz](https://github.com/kamilzierke/lilygottgotbeamlorav11v12/assets/67487992/89bad018-498a-4dc5-b4c3-77323839dbb4)       |
| **Main Battery**     | 18650 (+ NCE3401AY MOSFET)                                     |                                                                                           |
| **Backup Battery**   | MS412FE (MS Lithium Rechargeable Battery MS412FE)              |                                                                                           |



## External Libraries and Repositories

The following external libraries and repositories are used in this project:

- [XPowersLib](https://github.com/lewisxhe/XPowersLib) - Library for interfacing with power management components.
- [LilyGo-LoRa-Series](https://github.com/Xinyuan-LilyGO/LilyGo-LoRa-Series) - Library for managing the LoRa functionalities.
