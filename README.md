# Marlin 2.0.8.1 Config for my Ender 3 V2

## Some info
I uploaded my configuration to git for tracking my changes and easy rollback to a working state. But feel free to use it for your Ender 3 V2 too at your own risk!

## My setup
Currently I am running an Ender 3 V2 with following modifications:
- Mainboard version 4.2.2
- BLTouch 3.1 Kit

## Important info
In my setup I use a BLTouch in Version 3.1 and so I have activated BLTOUCH_SET_5V_MODE. If you are not sure please disable it else you printer can break!

```
/**
 * Danger: Don't activate 5V mode unless attached to a 5V-tolerant controller!
 * V3.0 or 3.1: Set default mode to 5V mode at Marlin startup.
 * If disabled, OD mode is the hard-coded default on 3.0
 * On startup, Marlin will compare its eeprom to this value. If the selected mode
 * differs, a mode set eeprom write will be completed at initialization.
 * Use the option below to force an eeprom write to a V3.1 probe regardless.
 */
```

## Important
Use at your own risk and compare to Marlin Configuration for easy checking against my changes!