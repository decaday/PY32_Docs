## PY32F0 series MCU datasheets, packs, tools, reference manuals, etc.



see PY32F0 template project at [decaday/py32f0_cmake_template](https://github.com/decaday/py32f0_cmake_template)

HAL,LL,CMSIS, BSP Drivers [decaday/PY32F0_Drivers](https://github.com/decaday/PY32F0_Drivers)

#### Notice

Please note that the documentation for Puya Semiconductor is in a semi-public state, and I cannot guarantee the completeness and timeliness of the information. If you have updated or additional information, feel free to contribute.

#### About document language

Only the datasheet and some parts of the reference manual have English versions, and the English materials are all suffixed with `_EN`.

It seems that the English versions are also lagging behind the Chinese versions.

### Files

The products in the unified table are actually(maybe) the same die, and the information can be cross-referenced.(However, please also study and discern **on your own**!)

| Folders         | Description                         | PY32F002B         | PY32L020      | PY32C642 |
| --------------- | ----------------------------------- | ----------------- | ------------- | -------- |
| Datasheet       |                                     | CN✔  EN✔          | CN✔           | CN✔      |
| DevelopBoard    | StartKit user huide,schematic       | ✔(only schematic) | CN✔(only sch) | ✖        |
| ReferenceManual |                                     | CN✔  EN✔          | CN✔           | ✖        |
| ApplicationNote |                                     | CN✔  EN✖          | CN✔           | ✖        |
| HAL_LL          | HAL, LL function description manual | ✖                 | .chm          | ✖        |



| Folders         | Description                         | PY32F0xx*     | PY32C613 |
| --------------- | ----------------------------------- | ------------- | -------- |
| Datasheet       |                                     | CN✔ EN✔       | CN✔      |
| DevelopBoard    | StartKit user huide,schematic       | CN✔ EN✔       | ✖        |
| ReferenceManual |                                     | CN✔ EN✔       | CN✔      |
| ApplicationNote |                                     | CN✔  EN✖      | CN✔      |
| HAL_LL          | HAL, LL function description manual | CN✔ (PDF) EN✖ | .chm     |

PY32F0xx*:Including PY32F002A, PY32F003, PY32F030

| Folders         | Description                         | PY32F040 | PY32071_F072 | PY32F070_M070* | PY32F403 |
| --------------- | ----------------------------------- | -------- | ------------ | -------------- | -------- |
| Datasheet       |                                     | CN✔      | CN✔          | CN✔            | CN✔      |
| DevelopBoard    | StartKit user huide,schematic       | CN✔      | CN✔          | ✖              | ✖        |
| ReferenceManual |                                     | CN✔      | CN✔          | ✖              | ✖        |
| ApplicationNote |                                     | CN✔      | CN✔          | ✖              | ✖        |
| HAL_LL          | HAL, LL function description manual | .chm     | .chm         | ✖              | ✖        |

PY32F070_M070*:The chip marking of the chip may be M070, but the data sheet is F070. lacks data

| Folders         | Description                         | PY32F403 |
| --------------- | ----------------------------------- | -------- |
| Datasheet       |                                     | CN✔      |
| DevelopBoard    | StartKit user huide,schematic       | ✖        |
| ReferenceManual |                                     | ✖        |
| ApplicationNote |                                     | ✖        |
| HAL_LL          | HAL, LL function description manual | ✖        |



### Packs

| Files                                | Ver   | Description                                  |
| ------------------------------------ | ----- | -------------------------------------------- |
| Puya.PY32F0xx_DFP.1.1.9.pack         | 1.1.9 | PY32F0 MDK(from Puya)                        |
| Puya.PY32F0xx_DFP.1.2.0.pack         | 1.2.0 | PY32F0 MDK(from keil.arm.com)                |
| Puya.PY32_IAR_DFP.0.0.1.rar          | 0.0.1 | IAR (seems that include other PY32 series)   |
| Puya.PY32F0xx_IAR_DFP.0.0.2.rar      | 0.0.2 | IAR (seems only include PY32F0)              |
| 如何使用IAR开发调试PY32 MCU V1.0.pdf | 1.0   | How to use IAR to develop and debug PY32 MCU |
| PY32F0xx_DFP User Manual Rev.1.0.pdf | 1.0   | Chinese                                      |
| Puya.PY32F4xx_DFP.1.0.0.pack         | 1.0.0 | PY32F4 MDK(from keil.arm.com)                |

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

