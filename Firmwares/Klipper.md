# Klipper Firmware for Endeaxim‑3

**Repository:** [MartinNovan/Klipper-Endeaxim-3](https://github.com/MartinNovan/Klipper-Endeaxim-3)

This project contains the Klipper firmware and configuration files for the Endeaxim‑3 3D printer.

## Contents
- Klipper source and custom adjustments for Endeaxim‑3
- Example configuration files (`printer.cfg`, macros, pinouts)
- Build and flashing instructions

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/MartinNovan/Klipper-Endeaxim-3.git
    ```
2. Adjust the configuration (e.g., `printer.cfg`) to match your hardware.
3. Run `make menuconfig` and configure your target board.
4. Compile the firmware.
5. Flash the board (via SD card or USB, depending on your setup).
6. Once installed, you can update configurations directly in Klipper without recompiling.

## Important Notes
* Flashing this firmware will overwrite any existing firmware on your board.
* Make sure pinouts, stepper drivers, and sensors match your setup.
* Always back up your working configuration before making changes.