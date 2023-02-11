# Awesome Continuous Testing Actions

GitHub Actions with examples mostly around Continuous testing for Microcontroller things.

<!-- markdown-link-check-disable-next-line -->
[![CI badge](https://github.com/designer2k2/awesome-Continuous-testing-actions/actions/workflows/spell-check.yml/badge.svg)](https://github.com/designer2k2/awesome-Continuous-testing-actions/actions) [![CI badge](https://github.com/designer2k2/awesome-Continuous-testing-actions/actions/workflows/link-check.yml/badge.svg)](https://github.com/designer2k2/awesome-Continuous-testing-actions/)

## General info

- [Wikipedia CI](https://en.wikipedia.org/wiki/Continuous_testing) - Continuous testing on Wikipedia.
- [GitHub.com](https://github.com/features/actions) - GitHub Actions.

## Code checks

### Compiling examples of Arduino library

For Arduino librarys, this compiles all provided examples. If all compiles its considered a pass.

- [DS3231](https://github.com/NorthernWidget/DS3231/blob/master/.github/workflows/compile-examples.yml) - Compile all examples, bare minimum.
- [STM32_CAN](https://github.com/pazi88/STM32_CAN/blob/main/.github/workflows/compile-examples.yml) - Compile all examples for STM32.
- [ESP32-A2DP](https://github.com/pschatzmann/ESP32-A2DP/blob/main/.github/workflows/compile-examples.yml) - Compile all examples for ESP32.
- [EMUcan](https://github.com/designer2k2/EMUcan/blob/main/.github/workflows/compile-examples.yml) - Compile specific examples for Arduino, ESP32, Teensy4 and STM32.
- [Stepper](https://github.com/arduino-libraries/Stepper/blob/master/.github/workflows/compile-examples.yml) - Compile for many targets (13!).

### Compiling specific sketch

For any Arduino Project, a provided sketch is compiled. It it compiles its considered a pass.

- [BerlinUhr](https://github.com/designer2k2/BerlinUhr/blob/main/.github/workflows/main.yml) - Compile sketch for ATtiny167.
- [can-multidisplay](https://github.com/designer2k2/can-multidisplay/blob/main/.github/workflows/compile-sketch.yml) - Compile sketch with many libs for Teensy4.
- [xmas-tree](https://github.com/designer2k2/xmas-tree/blob/master/.github/workflows/compile_sketch.yml) - Compile sketch for Digistump, ESP32C3 and ESP32S2.
- [BSB-LAN](https://github.com/fredlcore/BSB-LAN/blob/master/.github/workflows/platformio.yaml) - Compile Platformio project.

## Surrounding

- [EMUcan Library](https://github.com/designer2k2/EMUcan/blob/main/.github/workflows/clang-format-check.yml) - Arduino formatting check like CRTL+T in Arduino IDE.
- [Ethernet](https://github.com/arduino-libraries/Ethernet/blob/master/.github/workflows/check-arduino.yml) - Check for Arduino compliant library format
- [Spell check](https://github.com/designer2k2/EMUcan/blob/main/.github/workflows/spell-check.yml) - English spell check.
- GitHub Markdown check.
- [pyroscope](https://github.com/pyroscope-io/pyroscope/blob/main/.github/workflows/lint-markdown.yml) - Markdown check for not working links.
