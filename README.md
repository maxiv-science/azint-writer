# Azint Writer

**Azint Writer** is a Python package for writing HDF5 files in the **NXazint** format, a new extension to the [NeXus](https://www.nexusformat.org/) standard. The NXazint format is specifically designed for storing data related to azimuthal integration in diffraction experiments.

---

## Features

- **HDF5 File Writing**: Easily generate NeXus-compliant HDF5 files.
- **NXazint Format**: Supports the new NXazint format for azimuthal integration.
- **Customizable Configuration**: Flexible options for writing metadata and experimental data.
- **Seamless Integration**: Compatible with existing NeXus tools and libraries.

---

## Installation

Install Azint Writer via `pip`:

```bash
pip install azint-writer
```
or `conda (mamba)`
```bash
conda install -c maxiv azint-writer
```
---

## NXazint Format

- **Experiment Metadata**: Beamline details, sample information, and experimental setup.
- **Azimuthal Integration Data**: One-dimensional and two-dimensional (cake) integration results.
- **Calibration Information**: Detector geometry and calibration parameters.

For more details on the NeXus standard, see the NeXus documentation.

---

## Contributing
We welcome contributions to Azint Writer! Here's how you can help:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Submit a pull request with a clear description of your changes.

Please follow the NeXus standard guidelines when adding features related to NXazint.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Support
If you encounter any issues or have questions, feel free to open an issue on GitHub.

