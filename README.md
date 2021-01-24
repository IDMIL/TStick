![Logo of the project](https://raw.githubusercontent.com/IDMIL/TStick/master/Sopranino/2GW/FW19101/Docs/images/IDMIL-logo.png)

# T-Stick
> Digital Musical Instrument (DMI)

The T-Stick is a DMI conceived by Joseph Malloch and D. Andrew Stewart at the [Input Devices and Music Interaction Laboratory (IDMIL)](http://www.idmil.org/) at McGill University. It has been in development since 2006, has a relatively long history for a DMI, has multiple versions, several expert performers, and has an associated repertoire. More than 20 copies have been built unintended for commercial use. Nevertheless, it has been adopted by expert performers and composers as part of their musical practice including D. Andrew Stewart (Soprano user) and Fernando Rocha (Tenor user). It has appeared in dozens of public appearances in countries such as Canada, USA, Brazil, Italy, Norway, and Portugal.

This repository hosts up to date firmware for the instruments currently  at the IDMIL. Driver and Instrument patches in Max/MSP. Spec Sheets and Schematics for all instruments.

## Overview

There are multiple variants of the T-Stick: The Sopranino, the Soprano, and the Tenor. The most obvious difference of these variants is their size.

All T-Sticks come with sensors for capturing capacitive touch, acceleration, and shock. Some variations have additional sensors available for mapping, as shown in below list.

Building instructions and specifications can be found in the respective subfolders. Numbered folders within those folders contain files related to the T-Stick with that specific serial number.

- Sopranino
  - 2G
    - S/N 172
  - 2GW: Additional Wi-Fi connectivity and inertual measurement unit (accelerometer + gyroscope)
    - S/N 181, 191
- Soprano
  - 2G
    - S/N 010, 012, 024, 171
  - 2G-IMU: Additional inertial mesurement unit (accelerometer + gyroscope)
    - S/N 173
  - 2GX: Additional sensors for light, breath / air pressure, infrared range, no IMU
    - S/N 015
- Tenor
  - 2G
    - S/N 014 

### Getting started

The steps you need to do to get your own T-Stick up and running:

1. Gather building materials from the bill of materials (a price estimate can be found on each list)
2. Construct physical parts (skills needed: 3D printing, sawing a PVC tube lengthwise)
3. Manufacture printed circuit board (DIY by etching or milling, or order from a supplier)
4. Add sensors and electronics
5. Install and test firmware
6. Set up mapping and audio synthesis on a separate computer

If you get stuck because the documentation on this repository is missing or unclear, please [file an issue](https://docs.github.com/en/enterprise/2.15/user/articles/creating-an-issue).

## Quick access guides

[T-Stick connection guide – v1.1 for wireless T-Sticks](./Sopranino/2GW/FW19101/Docs/T-Stick_2GW_Connecting_Guide(v1.1).md) (model [2GW-19X](./Sopranino/2GW/FW19101/README.md))

[How to build a T-Stick Sopranino](./Sopranino/2GW/FW19101/Docs/T-Stick_2GW_building_instructions.md)

## Instrument Inventory

As of October 2019 there are 13 instruments at [IDMIL](http://www.idmil.org). The following list contains the quantities and serial numbers of the avilable T-Sticks.

- Sopranino
  - 01 2G: S/N ??
  - 05 2GW: S/N 181, 191, ??
- Soprano
  - 04 2G: S/N 010, 012, 024, 171
  - 01 2GX: S/N 173
  - 01 2G-IMU: S/N 015
- Tenor
  - 01 2G: S/N 014
  
## Firmware releases

For now, the firmware versions are found inside the respective subfolders for each T-Stick variant. In the future, we will add them as [releases](https://github.com/IDMIL/TStick/releases).

## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome.

## Links

- Project homepage: http://www-new.idmil.org/project/the-t-stick/
- Repository: https://github.com/IDMIL/TStick/
- Issue tracker: https://github.com/your/awesome-project/issues
  - In case of sensitive bugs like security vulnerabilities, please contact
    my@email.com directly instead of using issue tracker. We value your effort
    to improve the security and privacy of this project!
- Related projects:
  - IDMIL - Input Devices and Music Interaction Laboratory - http://www-new.idmil.org/
  - CIRMMT - Centre for Interdisciplinary Research in Music Media and Technology - http://www.cirmmt.org/
  - Schulich School of Music - McGill University


## Licensing

The code in this project is licensed under MIT license.
