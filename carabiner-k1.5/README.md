# Carabiner-K1.5

This is a carabiner for either K1 or K2, Rev X.
It has two different versions which only differ by which hotend you're using

## Features

- Input via 16pin horizontal/vertical microfit
- Two outputs for partcooling fans
- Soldered seperate voltage selection for hotend fan and partcooling fan
   - Uses either the hotend voltage or one alternative voltage
- Thermistor for the chamber
  - Supports any size from 0603 to 1206

## Connectors & Amperage

_Note: All amperage-values have been designed to work in an enclosed printer with up to 65° chamber temperature & have safety margins. While you could use higher ampere in an open-frame printer, this is not encouraged.<br/>
When multiple connectors are supported **bold** marks the recommended connector._

|   | Supported Connectors | Maximum Ampere |
| ------------- | ------------- | ------------- | 
| Hotend  | 2-pin JST XH <br/> Microfit 430450227 <br/> **Microfit 436500227** (compatible with e3d heater) | 2 Ampere (40W heater on 24V) <br/> 4.2 Ampere (100W heater on 24V) <br/>4.2 Ampere (100W heater on 24V)
| Hotend Thermistor  | 2-pin JST XH <br/> **Microfit 436500227** (compatible with e3d thermistor) | / <br/> /
| Hotend Fan | 2-pin JST XH | 1 Ampere
| 2x Partcooling Fan | 2-pin JST XH | 1 Ampere (total for both)
| Stepper | 4-pin JST XH | 1.2 Ampere <br/> 0.84 Ampere on TMC drivers as you specify the RMS ampere which is ~70% of peak
| Aux / Probe | 4-pin JST XH | 0.8 Ampere

## BOM / Parts

Links to purchase fully assembled boards can be found here: [ANNEX Sourcing Guide](https://docs.google.com/spreadsheets/d/1aSM1jGxg-s0tyynyR3f8M0IQMXuXw57RJvoJbt98Clw/edit?usp=sharing)

Be aware that the Carabiner K1.5 has 2 options for different hotends.

## Hotends & Versions

<tbd>


