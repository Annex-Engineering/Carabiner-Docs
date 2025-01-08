# Carabiner

The Carabiner-PCBs are a series of toolboards for a quick & easy connection between the backpack and toolhead.

## Different Variants

| Name | Location | Recommended for Printer | 
| ------ | ------ | ------ |
| Carabiner Classic | Toolhead | Any printer |
| K3rabiner | Toolhead | K3 |
| Carabiner K1.5 | Toolhead | K1 / K2 |
| Carabiner Distributor | Backpack | Any printer
| Carabiner Distributor XOL | Backpack | Any printer with a matching XOL Toolhead Board

As an alternative for any Carabiner in the backpack, you can use a Constellation Sirius (coming soon!) to make wiring your Carabiner even easier!

## Features
All variants of Carabiner share the following main features:
- 16-pin input/output via MicroFit connector
- Chamber thermistor
- USB support
- 48V on your heater, hotend-fan and part-cooling fan (if your mainboard allows for it!)

Most variants of the Carabiner also have the following feature:
- Selectable Voltage for partcooling-fan / hotend-fan between the hotend voltage & 1 alternative voltage

## Warnings

Here be dragons - as with everything that involves electronics, make sure to double-check your wiring before powering it on to avoid producing magic smoke & frying components.  
It's recommended to check the following points:
- Both Carabiners have their MicroFit connector plugged in on the same side of the PCB (usually marked as 'Side A').
- Check for shorts between the following pins with your multimeter:
   - Main+ and HE-
   - Main+ and PCF-
   - Main+ and HEF-
   - Alt+ and PCF-
   - Alt+ and HEF-
   - Alt+ and Main+

## Source, PCBs, Gerbers

While I (iKirin), do enjoy releasing most things that I work/worked on as open-source, I've decided to remove the source as well as the gerbers for all current and future revisions of all carabiners.
This is due to a very limited amount of vendors believing, that just because a source is uploaded to Github, they can take the files and make them, even if commercial use is generally not permitted. 
There is no licensing fee charged for any shop that decides to carry the board, however I do kindly ask that they donate a small amount of money per order to reforestation or local communities dedicated to keep the local flora & fauna intact.

If you want to help to get the carabiner from any shop that is officially affiliated, please check out the [sourcing guide](https://docs.google.com/spreadsheets/d/1O3eyVuQ6M4F03MJSDs4Z71_XyNjXL5HFTZr1jsaAtRc/edit?usp=sharing)

## License

Please see the License.md file in this repo
