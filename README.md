# Endeaxim-3 - Ender 3 Upgrade Project (ALPHA)

## Overview
Endeaxim-3 is a comprehensive upgrade package for the Creality Ender 3 3D printer, transforming it into a high-performance machine. This ALPHA version includes essential upgrades and lays the foundation for future expansions.

## Current Features (ALPHA)
- **Dual Z-axis Upgrade**: Improved stability and print quality
- **Linear Rail System**: 
  - 12 high-quality [linear bearings](https://www.prusa3d.com/category/mk3-s-spare-parts/?page=2) (Prusa MK3/MK2 compatible)
  - Precision [linear rods](https://www.prusa3d.com/category/mk3-s-spare-parts/?page=3) (Prusa MK3/MK2 compatible)
- **Control Board**: Bigtreetech SKR 2 mainboard
- **Extruder**: Creality Sprite Extruder
- **Power Supply**: Meanwell power supply
- **Firmware**: Klipper firmware running on Raspberry Pi

## Installation Requirements
- Creality Ender 3 (base model)
    - Has dual Z upgrade
    - Linear rods and 12 bearings (same that Prusa MK3 has)
    - Has BL-Touch or CR-Touch
- Basic 3D printing knowledge
- Mechanical assembly skills
- Electronic skills
- Raspberry Pi (for Klipper)
- Printed parts

## Supported Components (ALPHA)
- **Mainboards**: SKR 2
- **Extruders**: Creality Sprite Extruder

## Future Plans
- Multi-board support (additional mainboards)
- Multi-extruder support
- Additional mounting solutions
- Enhanced cooling systems
- Marlin firmware configuration
- Comprehensive assembly guide

## Installation Notes
1. Ensure all components are properly aligned during assembly
2. Follow Klipper installation guidelines for Raspberry Pi setup
3. Calibrate the dual Z-axis motors for optimal performance
4. Verify linear rail smoothness before final assembly

## Safety Considerations
- Disconnect power during installation
- Handle linear bearings with care to avoid contamination
- Ensure proper cable management to prevent interference
- Verify all connections before powering up

## Known Issues (ALPHA)
- Limited component compatibility
- Requires manual calibration
- Documentation still in progress

## Contributing
As this is an ALPHA release, feedback and contributions are welcome. Please report any issues or suggestions through the project's repository.

## License
This project is licensed under the GNU Affero General Public License v3.0. See the [LICENSE](./LICENSE) file for more information.

## Disclaimer
This is an ALPHA version. Use at your own risk. The developers are not responsible for any damage to equipment or personal injury resulting from the use of this upgrade package.

## Printing Instructions
- Print all parts with minimum:
  - 3 perimeters
  - 40% infill
    - recommended due to limiting vibrations
  - Recommended materials: PETG or ABS for better heat resistance
- Printable parts available at: [Printables Link](./Printable%20Parts/)

## Configuration
- **Klipper Configuration**: [Klipper Config Link](./Klipper/Configuration/)
- **Marlin Configuration**: Planned for future release

## Versioning
Current Version: ALPHA  
[View all versions and releases](https://github.com/MartinNovan/Endeaxim-3/releases)  
[Download previous versions](./Versions/)
