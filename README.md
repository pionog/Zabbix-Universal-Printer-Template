## Overview

My attempt to make a universal printer template in Zabbix 6.4.

It works fine on Konica Minolta and HP color printers (at least they seem to work for me on KM bizhub c250i and some hp officejet pro / laserjet pro printers).
I don't know if this template works on other companies' color printers.

### Important - To use this template you have to enable communication with your printers through SNMP version 1 or version 2C.

### Following components:

- Color toners
- Total number of printed pages
- Printer model
- Color mode (CMYK, KCMY, YMCK)
- Error status (written in decimal number instead of binary array)

## Todo

Make black and white printers work fine as the color ones.

## Ending

I take no responsibility for losses incurred by using this template. You use it at your own risk.
Anyway, if you find an error, don't hesitate to report it. You will help me improving this template.
