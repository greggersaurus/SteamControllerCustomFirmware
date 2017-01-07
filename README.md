# Introduction

The purpose of this project is to create a firmware.bin file to load onto the
 Steam Controller. Ideas for what this firmware might do would be to allow
 access to the LPC11U37 Boot ROM or EEPROM. 

All we have to work with are the raw binary firmware files. Details on obtaining
 these can be found at [How to manually load firmware on NXP chip](https://steamcommunity.com/sharedfiles/filedetails/?id=572740074).

# Initialization

In order to make sure the LPC11U37 is setup properly firmware for the Steam
 Controller was simulated using [pinkySim](https://github.com/greggersaurus/pinkySim).
 The information obtained from this simulation is then reconstructed into 
 initialization code.

