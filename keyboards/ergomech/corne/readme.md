# Corne Keyboard (CRKBD)

Also known (incorrectly) as the `HeliDox`. 

![Crkbd](https://user-images.githubusercontent.com/736191/40575636-6fba63a4-6123-11e8-9ca0-3f990f1f9f4c.jpg)

![Crkbd](https://user-images.githubusercontent.com/736191/40887871-0eead5dc-678a-11e8-9518-e3ad9e5d2bac.png)

A split keyboard with 3x6 vertically staggered keys and 3 thumb keys.

Original Keyboard Designer: [foostan](https://github.com/foostan/) [@foostan](https://twitter.com/foostan)  

THis particular keyboard version is maintained by Ergomech Store
Keyboard Maintainer: [Ergomech Store](https://github.com/ergomechstore/) [@ErgomechStore](https://ergomech.store)  
Hardware Supported: Crkbd PCB, Pro Micro  
Hardware Availability: [PCB, Kit and Case](https://ergomech.store)

Make example for this keyboard (after setting up your build environment):

```sh
qmk compile -kb ergomech/corne -km vial -e CONVERT_TO=promicro_rp2040
```

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

The Corne PCBs have a reset button next to the TRRS jack to enter in to the bootloader.
To go into bootloader, double tap the reset button, an mass storage device should appear in your pc, copy the   `uf2` firmware file to that drive

## RGB Matrix 
The Corne Keyboard also supports using the RGB Matrix feature, in place of RGB Light.  This provides a better experience when using the keyboard, as it supports a number of per key effects properly.  If you're not using the in switch LEDs, then you may want to pass on doing this. 

This is configured to you by default in this repo so you won't have to do anything to activate it
