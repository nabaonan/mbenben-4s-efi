# mbenben-4s-efi

[![macOS](https://img.shields.io/badge/macOS-13.5-yellow)](https://developer.apple.com/documentation/macos-release-notes) [![OpenCore](https://img.shields.io/badge/OpenCore-0.9.3-blue)](https://github.com/acidanthera/OpenCorePkg) [![mbenben](https://img.shields.io/badge/麦本本-小麦4s-lightgrey)](https://github.com/nabaonan/airbook-6200u-efi)

## 介绍
麦本本支持ventura ，所有kext驱动更新最新，完美度95%

## 已知问题

开盖唤醒需要点击键盘才亮屏

## 基本配置

| 名称     | 型号             |
| -------- | ---------------- |
| cpu      | i5 6200u         |
| 内存     | 镁光4g ddr4 2400 |
| 显卡     | hd520（核显）    |
| 无线网卡 | intel AC3165     |
| 声卡     | ALC269           |
| 显示器   | 奇美CMN15CB      |
| 硬盘     | RBU-128g固态     |

## 系统驱动

| 名称                         | 版本                                                         | 描述                       |
| ---------------------------- | ------------------------------------------------------------ | -------------------------- |
| AppleALC                     | ![](https://img.shields.io/badge/version-1.8.3-informational) | 声卡                       |
| IntelBTPatcher.kext          | ![](https://img.shields.io/badge/version-2.3.0-informational) | 蓝牙                       |
| BlueToolFixup                | ![](https://img.shields.io/badge/version-2.6.7-informational) | 蓝牙                       |
| IntelBluetoothFirmware.kext  | ![](https://img.shields.io/badge/version-2.3.0-informational) | 蓝牙                       |
| HibernationFixup             | ![](https://img.shields.io/badge/version-1.4.9-informational) | 修复睡眠                   |
| Lilu                         | ![](https://img.shields.io/badge/version-1.6.6-informational) | 核心                       |
| VoodooPS2Controller          | ![](https://img.shields.io/badge/version-2.3.5-informational) | 触摸板和键盘               |
| WhateverGreen                | ![](https://img.shields.io/badge/version-1.6.5-informational) | 显卡                       |
| VirtualSMC                   | ![](https://img.shields.io/badge/version-1.3.2-informational) | 核心                       |
| SMCProcessor                 | ![](https://img.shields.io/badge/version-1.3.2-informational) | 处理器温度                 |
| SMCBatteryManager            | ![](https://img.shields.io/badge/version-1.3.2-informational) | 电池驱动                   |
| SMCSuperIO                   | ![](https://img.shields.io/badge/version-1.3.0-informational) | 温度检测                   |
| ECEnabler                    | ![](https://img.shields.io/badge/version-1.0.4-informational) | 电池驱动依赖，不用拆字节了 |
| UTBMAP                       |                                                              | usb定制                    |
| USBToolBox.kext              | ![](https://img.shields.io/badge/version-1.1.0-informational) |                            |
| RealtekCardReaderFriend.kext | ![](https://img.shields.io/badge/version-1.0.4-informational) |                            |
| RealtekCardReader.kext       | ![](https://img.shields.io/badge/version-0.9.7-informational) |                            |

## 功能完善度

- [x] 睡眠唤醒

- [x] usb定制

- [x] 电池电量显示

- [x] 音频（内外放）

- [x] Wifi 

- [x] 蓝牙

- [x] cpu睿频

- [x] 开盖唤醒（需要点键盘亮屏）

- [x] 盒盖睡眠

  

## 变更记录

驱动都更新到最新版本，后期如果没有同类型笔记本则不再维护
