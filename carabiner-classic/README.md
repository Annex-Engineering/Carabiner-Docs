# Carabiner-Classic
(Previously known as Carabiner or Carabiner-Toolboard)

![picture](images/Overview.JPG)

The carabiner-classic is a toolboard for easy & quick connection between the backpack and toolhead.
It's a generic design, intended to be used a reference and for printers without space constraints.
It was inspired by the first iterations of the dumbboard by LukesLab and designed to bring the idea of a 'simple toolboard' to the next level!

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

Find the latest BOM in the [Annex Sourcing Guide](https://docs.google.com/spreadsheets/d/1O3eyVuQ6M4F03MJSDs4Z71_XyNjXL5HFTZr1jsaAtRc) under PCBs

## Revisions

The following revisions have been made to the Carabiner-Classic (Previously known as Carabiner).
This overview is non-exhaustive and does not cover all revisions that were previously released.

|Version|Changes|Known Bugs|
|:------|:-----|:---------|
|1.3|Remove 5th pin for AUX.<br>Add USB-support on the AUX-port|-|
|1.2.1|-|The second A3 port, after JP_A3 is not connected.|
|1.2|-|The second A3 port, after JP_A3 is not connected.|

## Build Guide

[Please check out this simple written build guide](buildguide/README.md).

## Wiring Guide

[Please refer to the pinout-section of the docs](../pinout/README.md)

## Gallery
![picture](images/PCB.JPG)
