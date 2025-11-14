# KiCad Symbol Library

This repository contains a collection of custom KiCad symbols for use in schematic designs. These symbols are designed to simplify the process of creating schematics for various electronic components and modules.

## Installation

To use these symbols in your KiCad project:

1. Clone this repository or download the `components.kicad_sym` file.
2. In KiCad, go to Preferences > Manage Symbol Libraries > Global Libraries.
3. Add a new library entry pointing to the `components.kicad_sym` file.

## Usage

Once installed, the symbols will be available in the symbol chooser under the library name you assigned.

## Currently Added Symbols
- ESP32-C3_Super_Mini
- GY-MAX4466_mic_module
- HW-373 Charge Controller
- MT3608_Boost_Converter
- WS2812B_LED_Strip
## Updating the Symbol List

To generate an updated list of symbols, run the following task:

```bash
task list-symbols
```

This will output the current list of symbols in the library.

## Contributing

Feel free to contribute new symbols by submitting a pull request. Please ensure that new symbols follow KiCad's symbol creation guidelines and are properly tested.
