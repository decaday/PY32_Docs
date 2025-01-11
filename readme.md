## PY32F0 series MCU datasheets, packs, firmwares, tools, reference manuals, etc.

Repositories related to py32:

CSDK:

- [OpenPuya](https://github.com/OpenPuya) Docs, Firmwares for py32
- [decaday/py32f0-cmake](https://github.com/decaday/py32f0-cmake) PY32F0 cmake template project
- [decaday/PY32F0_Drivers](https://github.com/decaday/PY32F0_Drivers) HAL,LL,CMSIS, BSP Drivers
- [IOsetting/py32f0-template](https://github.com/IOsetting/py32f0-template) PY32F0 makefile(linux) template
- [SoCXin/PY32F002](https://github.com/SoCXin/PY32F002)
- [OS-Q/platform-puya](https://github.com/OS-Q/platform-puya) OS-Q platform for PY32F0xx

Rust:

- [py32-rs/py32-hal](https://github.com/py32-rs/py32-hal) Rust HAL implementation and Embassy support for py32
- [py32-rs/py32-data](https://github.com/py32-rs/py32-data) metapac auto-generating for py32
- [creatoy/py32f0xx-hal](https://github.com/creatoy/py32f0xx-hal) A Rust `embedded-hal` implementation
- [decaday/py32csdk-hal-sys](https://github.com/decaday/py32csdk-hal-sys) PY32F0 MCU cSDK bindings

Arduino:

- [py32duino/Arduino-PY32](https://github.com/py32duino/Arduino-PY32) Arduino core for py32

PCB Symbols:

- [dreamcmi/Kicad-MCU-Puya](https://github.com/dreamcmi/Kicad-MCU-Puya) Puya PY32 Series KICAD7 Symbol
- [HalfSweet/KiCad Symbols · GitLab](https://gitlab.com/HalfSweet1/kicad-symbols/-/tree/PY32) PY32 Symbols in Halfsweet's fork

PCB, Devboards:

- [HalfSweet/PY32F030K28U_Arduino_Nano](https://github.com/HalfSweet/PY32F030K28U_Arduino_Nano): An Arduino Nano-like PY32F030K28 Development Board
- [wagiminator/Development-Boards](https://github.com/wagiminator/Development-Boards): Collection of various development boards
- [gpgreen/py32_dev](https://github.com/gpgreen/py32_dev) : puya py32 cortex m0 development board

Puya PY32 based projects:

- [ArcaneNibble/puya-spinner](https://github.com/ArcaneNibble/puya-spinner) : PY32F002AL15 based 'fidget spinner' project. PCB and firmware.

- [grahamwhaley/py32c642_vape](https://github.com/grahamwhaley/py32c642_vape) : Reverse engineer schematic and test firmware of PY32C642F15 based e-cigarette 'vape' board.

- [radex/puya-experiments](https://github.com/radex/puya-experiments) : PY32 F002 and F003 PCB breakout board designs.

# Notice

**After July 2024, [the puyasemi official website](https://www.puyasemi.com) provides downloads of most materials. You can download official materials [here](https://www.puyasemi.com/download.html).**

--------------------

--------------------

Please note that the documentation for Puya Semiconductor is in a semi-public state, and I cannot guarantee the completeness and timeliness of the information. If you have updated or additional information, feel free to contribute.

### About document language

Only the datasheet and some parts of the reference manual have English versions, and the English materials are all suffixed with `_EN`.

It seems that the English versions are also lagging behind the Chinese versions.

### Files

The products in the unified table are actually(maybe) the same die, and the information can be cross-referenced.(However, please also study and discern **on your own**!)

| Folders         | Description                         | PY32F002B         | PY32L020    | PY32C642/C641 |
| --------------- | ----------------------------------- | ----------------- | ----------- | ------------- |
| Datasheet       |                                     | CN✔  EN✔          | CN✔         | CN✔           |
| DevelopBoard    | StartKit user huide,schematic       | ✔(only schematic) | ✔(only sch) | ✔             |
| ReferenceManual |                                     | CN✔  EN✔          | CN✔         | ✖             |
| ApplicationNote |                                     | CN✔  EN✖          | CN✔         | ✖             |
| HAL_LL          | HAL, LL function description manual | ✖                 | .chm        | ✖             |
| Firmware        |                                     | ✔0.0.4            | ✔1.0.0      | ✔0.0.1        |

| Folders         | Description                         | PY32F030/F003/F002A | PY32C613 |
| --------------- | ----------------------------------- | ------------------- | -------- |
| Datasheet       |                                     | CN✔ EN✔             | CN✔      |
| DevelopBoard    | StartKit user huide,schematic       | CN✔ EN✔             | ✖        |
| ReferenceManual |                                     | CN✔ EN✔             | CN✔      |
| ApplicationNote |                                     | CN✔  EN✖            | CN✔      |
| HAL_LL          | HAL, LL function description manual | CN✔ (PDF) EN✖       | .chm     |

| Folders         | Description                         | PY32F040 | PY32F071_072 | PY32F070_M070* |
| --------------- | ----------------------------------- | -------- | ------------ | -------------- |
| Datasheet       |                                     | CN✔      | CN✔          | CN✔            |
| DevelopBoard    | StartKit user huide,schematic       | CN✔      | CN✔          | ✖              |
| ReferenceManual |                                     | CN✔      | CN✔          | ✖              |
| ApplicationNote |                                     | CN✔      | CN✔          | ✖              |
| HAL_LL          | HAL, LL function description manual | .chm     | .chm         | ✖              |
| Firmware        |                                     | ✔1.0.1   | ✔1.0.1       |                |

PY32F070_M070*:The chip marking of the chip may be M070, but the data sheet is F070. lacks data

| Folders         | Description                         | PY32F403 |
| --------------- | ----------------------------------- | -------- |
| Datasheet       |                                     | CN✔      |
| DevelopBoard    | StartKit user huide,schematic       | CN✔      |
| ReferenceManual |                                     | CN✔      |
| ApplicationNote |                                     | CN✔      |
| HAL_LL          | HAL, LL function description manual | .chm     |
| Firmware        |                                     | 1.0.1    |

### Packs

| Files                                | Ver   | Description                                  |
| ------------------------------------ | ----- | -------------------------------------------- |
| Puya.PY32F0xx_DFP.1.1.9.pack         | 1.1.9 | PY32F0 MDK(from Puya)                        |
| Puya.PY32F0xx_DFP.1.2.0.pack         | 1.2.0 | PY32F0 MDK(from keil.arm.com)                |
| Puya.PY32_IAR_DFP.0.0.3.zip          | 0.0.3 | IAR (seems that include other PY32 series)   |
| Puya.PY32F0xx_IAR_DFP.0.0.2.rar      | 0.0.2 | IAR (seems only include PY32F0)              |
| 如何使用IAR开发调试PY32 MCU V1.0.pdf         | 1.0   | How to use IAR to develop and debug PY32 MCU |
| PY32F0xx_DFP User Manual Rev.1.0.pdf | 1.0   | Chinese                                      |
| Puya.PY32F4xx_DFP.1.0.0.pack         | 1.0.0 | PY32F4 MDK                                   |

### More

These files come from :

```
PY32F002B_230807
PY32F002B_231026
PY32L020_231018

PY32F030 & PY32F003 &PY32F002A_230410

PY32F040_230807
PY32F040_231018
PY32F040_231115

PY32F072&PY32F071&PY32F070_230703
PY32F072&PY32F071&PY32F070_231115
```

https://www.keil.arm.com/packs/py32f0xx_dfp-puya/

You can also check out this project (https://github.com/OpenPuya/data/) and website (https://py32.org/).

 I have not compared the differences between this website and my repo. The latest versions of some files may be found in this repo or on that website.
