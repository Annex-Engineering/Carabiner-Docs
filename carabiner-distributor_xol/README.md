# Carabiner Distributor XOL

The distributor for the XOL toolboard. 
Be warned that this does not use the official carabiner pinout, and as such can cause damage to your electronics, unless used with the XOL toolboard.

## Features

- Input via 16pin horizontal or vertical microfit
- Testpads for easy thermistor troubleshooting
- Easy to read labeling of the connectors

## Connectors & Amperage

_Note: All amperage-values have been designed to work in an enclosed printer with up to 65° chamber temperature & have  some safety margins. While you could use higher ampere in an open-frame printer, it's highly discouraged. <br/>
When multiple connectors are supported **bold** marks the recommended connector._

|   | Supported Connectors | Maximum Ampere |
| ------------- | ------------- | ------------- | 
| Hotend  | 2-pin JST XH <br/> Microfit 430450227 <br/> **Microfit 436500227** (compatible with e3d heater) | ~2 Ampere (50W heater on 24V) <br/> 4.2 Ampere (100W heater on 24V) <br/>4.2 Ampere (100W heater on 24V)
| Hotend Thermistor  | 2-pin JST XH <br/> **Microfit 436500227** (compatible with e3d thermistor) | / <br/> /
| Hotend Fan | 2-pin JST XH | 1 Ampere
| Partcooling Fan | 2-pin JST XH | 2 Ampere
| Stepper | 4-pin JST XH | 1.2 Ampere <br/> 0.84 Ampere on TMC drivers as you specify the RMS ampere which is ~70% of peak
| Aux / Probe | 4 or 5-pin JST XH | 0.8 Ampere

## Sourcing

Links to purchase fully assembled boards can be found here: [ANNEX Sourcing Guide](https://docs.google.com/spreadsheets/d/1aSM1jGxg-s0tyynyR3f8M0IQMXuXw57RJvoJbt98Clw/edit?usp=sharing)

Be aware that the distributor pcb has 2 options for connectors regarding the thermistor and heater.

## Using the Testpads

When using both the hotend and chamber thermistor, it is important to ensure that you don't accidentially have the Ground swapped with the Thermistor-Pin.
To validate your thermistors are wired up correctly, it's recommended to use a multimeter and the Testpads on the Distributor.
Connect the Distributor to the mainboard of the printer.
When everything is wired up correctly, the resistance between the two Testpads should be close to 0 Ohms. 
If it does not measure 0 Ohms, please check your wiring and ensure that both ThTest as well as ThGnd are wired to the ThermistorGnd on the mainboard of your printer.

## Revisions

The following revisions have been made to the Carabiner Distributor.
This overview is non-exhaustive and does not cover all revisions that were previously released.

|Version|Changes|Known Bugs|
|:------|:-----|:---------|
|1.0|-|-|

## Wiring Guide

_Be warned that this does not use the official carabiner pinout, and as such can cause damage to your electronics, unless used with the XOL toolboard._






