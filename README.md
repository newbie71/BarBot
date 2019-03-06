# BarBot fork from sexycyborg
An Automated Bartender powered by Arduino  

Based on the work of Lukas Šidlauskas:  
https://create.arduino.cc/projecthub/sidlauskas/barbot-cocktail-mixing-robot-0318aa  
https://github.com/sidlauskaslukas/barbot

Based on the work of Naomi Wu

https://github.com/sexycyborg/BarBot/

## About

For my BarBot I wanted to make sure it was rock-solid reliable.
16 popular drinks (15 alcoholic and 1 non-alcoholic for non-drinkers and so that children can participate with supervision) are available from 16 arcade style buttons. A printed menu lists what button number corresponds to which drink.

Since the BarBot is designed for a working bars, party or company environments, it had to do without pumps or difficult to clean feed lines. All of the components that require nightly cleaning are the same that bar staff are already accustomed to cleaning- spirit measures and bar mats. All drive components and bearings have been moved from under the pour spouts to well above or behind so there is no risk of an accumulation of sugar-rich liquids gumming up hard to clean moving parts of the machine or attracting vermin.

This BarBot is a functional novelty- it's something fun for visitors to play with. Perfect for my home and company where a large number of patrons are tech professionals. It is not secured for true commercial use- and with a bar full of half-drunk hardware engineers it would be pointless to try. In this case, it's better to rely on good faith then pretend you could stop them if challenged. Patrons could still manually press their cups to the spirit measures to manually dispense alcohol if they wanted to- but they could also reach over the bar and steal liquor while the bartender's back was turned. So far none have because why ruin the fun when there's no "hack" in doing so? If you really wanted to, a clear acrylic panel could be added to the front to prevent any manual dispensing, but it's really a lot less fun that way.

Portion control and payment is handled via an inexpensive arcade token acceptor. A customer can pay the bartender for a cup of ice and a token. When the correct token is inserted into the BarBot a contact is momentarily closed. The customer then has 60 seconds to press a drink selection button. That same contact can be closed with the key switch, in which case no tokens are needed for any orders while the switch is in that position.

Barbots of this configuration typically use either a servo or a stepper motor with a lead screw to depress the spirit measure spout depending on the type of dispenser it is. My code changes allow for either as RAMPS boards can control both steppers and a servo.

In the build and demonstration videos, you'll see that the full 25ml "shot" the spirit measure contains is usually only partially dispensed. This is because the actual shot size is defined in the code as a function of how long the spout is depressed. This allows for finer tuning of the drink flavor and portion size which would not be possible if only 25ml increments were used.

This BarBot was designed to be easy to build with off-the-shelf OpenBuilds components, V-Slot aluminum extrusion, and low-cost 3D printer parts. The heart of the BarBot is a standard Arduino Mega, RAMPS 1.6 and TMC2xxx or DRV8825 stepper driver combination as used in many 3D printers. But my prefered combination is a BIQU re-arm clone,RAMPS 1.6+ and TMC2130 V1.1 spi.

<img src="https://i.imgur.com/Lqtft5d.jpg" width="800" height="565" alt="BarBot"><BR>
See [Build Guide](https://github.com/sexycyborg/BarBot/blob/master/BarBotDrwMk01.PDF). 
  *Guide and SolidWorks CAD drawings courtesy of [Vexelius](https://www.thingiverse.com/Vexelius/).*
 
 
 

## Attention this BOM variats from the Sexyborg due to high cost's and shipment from openbuilds-store  
### All sources including prices can be found in the BOM Excel-sheet


## BOM

The BOM can be found here https://github.com/newbie71/BarBot/blob/master/BOM_Barbot_1.0.xlsx 
with links where to order and the cost.
