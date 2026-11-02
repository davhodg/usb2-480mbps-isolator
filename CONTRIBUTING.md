# Contributing to usb2-480mbps-isolator

This project is at an early stage: the power stage is still being chosen on the bench, and there is no schematic yet. It is looked after by one person in their own time, so there is no promised response time, but every issue and discussion is read.

Everyone taking part is asked to follow the [code of conduct](CODE_OF_CONDUCT.md).

## How to take part

**Issues and discussions are welcome. Pull requests are limited to the maintainer for now.**

- **[Discussions](https://github.com/davhodg/usb2-480mbps-isolator/discussions)**: questions, ideas, part suggestions, your own measurements, and anything not yet clearly a problem.
- **[Issues](https://github.com/davhodg/usb2-480mbps-isolator/issues)**: something in the repository that is wrong — an error in the README, a measurement, a calculation, or later the schematic, layout or BOM.
- **Safety**: if you think something here could be unsafe — an isolation claim, a creepage distance, a missing warning — open an issue and say so in the title. See [Safety](README.md#safety): the design is functional isolation only.

### Why no pull requests yet

The design changes too quickly for outside changes to land cleanly, and keeping one author for now keeps the licensing simple while the layout settles. If you have a fix, describe it in an issue; it will be made and credited. Pull requests are likely to open up once the first sample boards are built or the firmware exists.

## Useful reports

- **For a mistake:** say where it is (file and section, or line), what is wrong, and what it should be, with a source if you have one: a datasheet page, an app note, or a measurement.
- **For a measurement:** say what was measured, with what instrument and probe, at what input voltage and load, and on which board or EVM.
- **For a part suggestion:** give the manufacturer's part number and why it fits, and say whether it is stocked at the usual distributors. Parts must be hand-solderable (SOIC, SSOP, TSSOP, SOT-23 and similar; 0805 passives or larger).

## Licensing

Hardware is CERN-OHL-S-2.0 and firmware is Apache-2.0; see [Licence](README.md#licence). Anything you post in an issue or discussion that ends up in the repository is used under those licences.
