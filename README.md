# Klipper-Backup 💾 

Backup of klipper config currently used. Working to breakout parts into their own config files (think modular, and a shout out to [ascii-ts](https://github.com/ascii-ts/my-klipper-configs/tree/master/config) for the idea) to make head swapping easier.
Any hardware that can live in its own config file resides in [printer_data/config/configs](https://github.com/stephenfeather/klipper-backup/tree/main/printer_data/config/configs). Sometimes a hardware component requires new or additional settings when used with a different head. Currently, only klipper is being backed up. 

## Ender 3v2 with multiple heads

### Support System
- Pi4 w/ Bookworm
- [Logitech C920x HD Pro Webcam](https://amzn.to/4jV1uYG) (enclosure)
- PiCam (build plate)

### Base Hardware

- BTT SKS Mini E3 v2
- dual z screws
- magnetic bed with PEI sheet over glass plate
- PTFE from Sunlu Dryer v2 to the hotend (for now)
- Wham Bam Mutant V2 System

### Mutant Heads

#### Ender OEM w/ mods

- OEM Hot End
- CR-Touch Probe
- Hero Me 5 Cooling System

#### Biqu

- [Biqu H2 V2S extruder](https://amzn.to/3EA0B9a)
- [BTT SFS V2.0 Smart Filament Sensor](https://amzn.to/430Og64)
- [CR-Touch](https://amzn.to/3EBZN3D)

## Upcoming additions

- adxl
- rp2040 for sensor management
- nozzle cam
- photos of the heads for context

## Software
- [Kiauth](https://github.com/dw-0/kiauh) for installation ease
- [Mainsail](https://docs.mainsail.xyz/) for web gui
- [Obico](https://www.obico.io/)

## Hardware
- [WHam Bam Mutant](https://www.whambamsystems.com/pages/mutant)
- [BIQU H2 V2S Direct Drive Extruder](https://amzn.to/42yuSOC)
- [BIGTREETECH Smart Filament Detector V2.0](https://amzn.to/4iXn8LP)
- [BIGTREETECH SKR Mini E3 V3.0 Motherboard](https://amzn.to/4j5VZqk) (link to the V3 vs my V2)

## Decisions
- Decisions and choices were made with the best information available at the time.
- The Hero Me part cooling system was and may still be one of the most efficient printable coolers available.  However, it was abandoned by its creator and the community had to take it over.  I began to lose faith in the patreon access around the time the magnetic connection unit was being developed. It is also rather large and bulky (forward of the hotend), so additional torque on the x axis connections and wheels.
- Ender 3v2 was on sale for dirt cheap at Microcenter when I was starting out (50% off!) and it wasn't outdated at the time.
- Bought Ender, so was stuck with Creality. My first resin printer was a Creality simply out of comfort. I see all the Chinese manufacturers about the same. You get what you pay for.
- Modifying vs purchase: A lot has changed in the FDM space, and for production use I'd just buy a new Prussa or Bambu (get your crap together on 3rd party access!). But rebuilding a printer will force you to think more about what you need, what you want, and what could be possibe.
- Adding Dual Z screws was probably one of the better choices made in everything.  It helped to prevent right side sagging of the X-axis due to the weight of the heads.
- The Pi4b still runs. Haven't found a need to upgrade it yet, although I do have a number of the new Pi5s (when in doubt, throw Pi!) running data collection for other projects and they are smoking!
- Ran Jyers version of Marlin almost from day one on the Creality mainboards and it took away a lot of the Marlin pain points.  However, needing to rebuild a firmware make what were often very small changes was time consuming.  Klipper offers not only faster config changes, but also addtional hardware options. Klipper on the printer, klipper on the rp2040s - and it just works.

 -----
 This backup is graciously provided by [Klipper-Backup](https://github.com/Staubgeborener/klipper-backup).
 Many thanks to that team for helping to automate all this.
