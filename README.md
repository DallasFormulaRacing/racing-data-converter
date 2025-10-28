# Testing Data Converter

A tool for converting CAN Bus channel data into MoTec I2 pro files. It handles unit conversion, channel pruning, and interpolation to prepare data for analysis in MoTec I2 Pro.

## Features

- Exports every channel from CAN Bus files to MoTec I2 pro format.
- Handles unit support and configurable sampling frequency.
- Prunes channels by filtering out null data points and removing samples recorded within 10 milliseconds to reduce density.
- Interpolates channels to maintain a consistent sampling frequency.

## Usage

See example_use.py for an example of how to use the tool.

## Documentation

- Official documentation: https://software.dallasformularacing.com/projects/racing-data-converter/
