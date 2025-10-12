# Marlin Firmware for Endeaxim‑3

**Repository:** [MartinNovan/Marlin-Endeaxim-3](https://github.com/MartinNovan/Marlin-Endeaxim-3)

This project provides the Marlin-based firmware and configurations for the Endeaxim‑3 3D printer.

## Contents
- Marlin source code with custom modifications for Endeaxim‑3
- Configuration files (`Configuration.h`, `Configuration_adv.h`, pin definitions, extras)
- Build and flashing instructions

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/MartinNovan/Marlin-Endeaxim-3.git
   ```
2. Edit the configuration files according to your hardware.
3. Build using PlatformIO or Arduino IDE (instructions are in the repo).
4. Flash the firmware to your printer.

## Important Notes
* Ensure your configuration matches your printer’s hardware (stepper settings, endstops, sensors, etc.).
* Always back up your existing firmware before flashing a new one.
* For additional features (e.g., BLTouch, filament runout sensor), refer to the Marlin documentation.