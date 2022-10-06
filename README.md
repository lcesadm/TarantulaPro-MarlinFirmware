<h1 align="center">TarantulaPro-MarlinFirmware</h1>
<p align="center">
    <img src="logo.avif" alt="logo" width="400"><br>
    <a href="https://github.com/MarlinFirmware/Marlin/releases/tag/2.1.1" target="_blank">
        <img src="https://img.shields.io/badge/marlin-2.1.1-blue?style=for-the-badge" alt="Marlin Version">
    </a>
    <img src="https://img.shields.io/badge/STATUS-WORKING-orange?style=for-the-badge" alt="Status">
</p>

### Topics :large_blue_diamond:

**:small_blue_diamond: [Tarantula Pro :spider:](#tarantula-pro-spider)**  
**:small_blue_diamond: [About :book:](#about-book)**  
**:small_blue_diamond: [Features :wrench:](#features-wrench)**  
**:small_blue_diamond: [Contributors :handshake:](#contributors-handshake)**

## Tarantula Pro :spider:

<p align="justify">
  I've owned this printer for a few years and lately I've been updating it with some hardware improvements, adding several features to ensure better efficiency during prints.<br>
  I created this repository to be able to save all the changes made to the firmware based on the 3D printer hardware implementations (TMC drivers, auto-leveling, runout sensor...).
</p>

## About :book:

<p align="justify">
    This is my configs and upgrades of my Tarantula Pro 3D printer.I only added the changed <strong><a href="https://github.com/MarlinFirmware/Marlin" target="_blank">Marlin Firmware</a></strong> source code files:
</p>

- `Configuration.h`
- `Configuration_adv.h`
- `_Bootscreen.h`
- `_Statusscreen.h`

> **:warning: All settings were made for the Tarantula Pro printer with my modifications, check your printer's compatibility first.**

<p align="center">
    <a href="https://www.arduino.cc/" target="_blank">
        <img src="https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white" alt="Arduino">
    </a>
    <a href="https://www.w3schools.com/cpp/" target="_blank">
        <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++">
    </a>
    <a href="https://code.visualstudio.com" target="_blank">
        <img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="VSCode">
    </a>
</p>

## Features :wrench:

- [x] Basic Configuration
  > - Added default configuration using the **[examples](https://github.com/MarlinFirmware/Configurations)** provide by the Marlin Firmware.
  > - Added Status Screen configuration.
- [x] TMC2208 Drivers Configuration
  > - Added TMC2208 V3.0 by BTT Standalone drivers configuration.
  > - Changed steppers calibration and X axis min position.
- [x] Auto-Leveling Configuration
  > - Added auto-leveling 3DTouch Configuration.
  > - Enabled Z probe homing with safe home.
- [x] Runout Sensor Configuration
  > - Added runout sensor configuration.
  > - Reused Z axis endstope (replaced by Z probe homing) on X_MAX_PIN pins.
- [ ] Dual Z Configuration
- [ ] Others Configs

## Contributors :handshake:

| [<img src="https://avatars.githubusercontent.com/u/60631170" width=115><br><sub>Leonardo Cesar</sub>](https://github.com/LeoLCM) |
| :---:

<p align="center">
    <a href="./LICENSE" target="_blank">
        <img src="https://img.shields.io/github/license/leolcm/tarantulapro-marlinfirmware?style=for-the-badge" alt="MIT LICENSE">
    </a>
</p>
