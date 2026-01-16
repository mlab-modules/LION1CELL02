# LION1CELL02 - Single-cell Li-Ion BMS power supply with I2C interface 

![LION1CELL02](/doc/img/LION1CELL02_top_big.jpg)

Integrated battery management solution for 18650 Li-ion batteries. It can measure remaining energy in the battery, perform a charging cycle from a USB-C power source, and protect batteries against overvoltage or overdraining conditions.

## Features 

  * Charging, balancing, termination (temperature protected)
  * Gas-gauging (temperature compensated)
  * Over-voltage protection
  * Over-current protection
  * Under-voltage is not protected - the module is constructed to power the device until battery death 

## Connection

The module could communicate on the I2C or HDQ bus.

| Mark | signal| Description |
|------|-----|---|
|1 | PG |	|
|2 | STAT2 | |
|3 | GND |	|
|4 | CE | |
|5 | STAT1 | |
|6 | CMODE | |
