<p align="center"><img src="buildroot/share/pixmaps/logo/marlin-outrun-nf-500.png" height="250" alt="MarlinFirmware's logo" /></p>

<h1 align="center">Custom Marlin Firmware for 45° Belt 3D Printer</h1>

<p align="center">
    <a href="/LICENSE"><img alt="GPL-V3.0 License" src="https://img.shields.io/github/license/marlinfirmware/marlin.svg"></a>
    <a href="https://github.com/MNwake/3D-printer-firmware/graphs/contributors"><img alt="Contributors" src="https://img.shields.io/github/contributors/marlinfirmware/marlin.svg"></a>
    <a href="https://github.com/MNwake/3D-printer-firmware/releases"><img alt="Last Release Date" src="https://img.shields.io/github/release-date/MarlinFirmware/Marlin"></a>
</p>

This is a custom fork of Marlin firmware, specifically tailored for my custom-built 45° belt-driven 3D printer. This printer is **3 feet wide** and designed to handle large-format 3D printing tasks. The printer build is still in progress, and this firmware is subject to changes as the hardware and configuration evolve.

---

## Printer Overview

- **Type**: 45° Belt 3D Printer  
- **Build Width**: 3 feet (custom large format)  
- **Custom Features**:
  - Conveyor belt Z-axis for continuous printing.
  - Optimized motion system for wide-format precision.
  - Supports Marlin’s advanced features, adapted to a unique build.

---

## Building and Using the Firmware

To build and upload the firmware, use one of the following tools:

- **[Visual Studio Code](https://code.visualstudio.com/download)** with the **[Auto Build Marlin](https://marlinfw.org/docs/basics/auto_build_marlin.html)** extension (recommended).
- **[PlatformIO IDE](https://platformio.org/)** integrated with Visual Studio Code.

Refer to the Marlin documentation for more details on [building Marlin](https://marlinfw.org/docs/basics/install_platformio.html).

---

## Configurations

The configuration files for this custom printer are based on Marlin 2.1 and tailored for the unique hardware of the printer. These include:
- Custom stepper motor configurations for the belt-driven Z-axis.
- Adjusted bed dimensions and motion parameters for the 3-ft width.
- Modifications to accommodate the 45° belt printing angle.

As the printer build is ongoing, configuration updates will be applied and documented in this repository.

---

## Contributing

This firmware is under active development, and contributions or feedback are welcome! If you want to help improve or suggest features for this project:
- Submit an issue or pull request via GitHub.
- Ensure that any contributions follow the [Marlin coding standards](https://marlinfw.org/docs/development/coding_standards.html).

---

## License

This firmware is distributed under the [GPL license](LICENSE). Any modifications or distributions of this firmware must comply with the GPL, ensuring the source code remains open and accessible.
