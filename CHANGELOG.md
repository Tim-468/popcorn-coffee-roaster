# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and the versions are numbered incrementally, e.g. v1, v2, v3...

## [Unreleased]

### Changed

- Higher series resistor for triac
- Larger capacitor package (smallest ones 0402 -> 0603) for easier soldering

### Removed

- Unnecessary mounting holes

## [v2]

### Added

- Alternative 24 V supply directly from the heater, like on the original board
- WROOM32-D board footprint on same PCB, to fit inside same Hammond case
- LED to indicate when heater is on
- Mounting holes for Hammond case

### Changed

- Bigger AC/DC converter because the fan needs around 1.3 A
- Triac orientation on PCB (tab up to tab down)
- Larger resistor package (0603) for easier soldering
- Use same diodes from the alternative supply as freewheeling diodes for the motor

## [v1]

### Added

- First prototype
