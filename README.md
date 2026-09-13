# smart-milk-adulteration-detector
Smart Portable Milk Adulteration Detection Device using ESP32 and multi-sensor analysis
### Team: Innovexa
A portable and low-cost milk adulteration screening device designed to estimate water dilution in milk using multiple sensor parameters and provide a rapid indication of adulteration.

## Problem Statement

Milk adulteration, particularly dilution with water, can reduce the quality and nutritional value of milk.

Conventional testing methods may require laboratory equipment, trained personnel, or more time.

There is a need for a simple, portable, and rapid screening solution that can provide an initial indication of milk dilution.

## Proposed Solution

We propose a **Smart Portable Milk Adulteration Detection Device** that measures multiple properties of a milk sample and processes the sensor readings to estimate the level of dilution.

The system uses:

- Electrical conductivity
- pH
- Temperature
- Density

The sensor readings are processed using an **ESP32-based system and a calibrated model** to provide an estimated dilution percentage.

---

## Objectives

- Detect and estimate water dilution in milk.
- Provide a rapid screening indication.
- Develop a portable and user-friendly device.
- Combine multiple sensor parameters for improved estimation.
- Reduce dependence on complex laboratory equipment for initial screening.

---

## System Working

1. Collect a milk sample.
2. Place the sample in the sensing chamber.
3. Measure conductivity, pH, temperature, and density.
4. Send the sensor readings to the ESP32.
5. Process the measured parameters using the calibrated model.
6. Estimate the dilution/adulteration percentage.
7. Display the result on the LCD.
8. The result can be used as a rapid screening indication.
