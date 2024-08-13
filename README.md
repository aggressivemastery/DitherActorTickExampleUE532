UNREAL ENGINE 5.3.2 BLUEPRINT ACTOR DITHERING TICK MANAGER EXAMPLE BY GAMEDEV MICAH BERNINGHAUSEN / GAMEDEVMICAH / GAMEDEVMICAH@GMAIL.com / AGGRESSIVEMASTERY.com
8/13/2024 
Within is a free to use and re-use (please provide credit to me, Micah Berninghausen, when able.) Notes within Blueprints.
Any questions please reach out to me via Linkedin, Twitter or Youtube. @GAMEDEVMICAH and GameDevMicah@Gmail.com 
In-EDITOR / Non-Shipping Builds : Enable STAT FPS / STAT UNIT to see impacts via CONSOLE ~ 

Actions/EVENTS are the work that the Unreal Engine or any Game Engine has to do with the CPU. In this example, we take 11,000 actors and instead of ticking each actor every frame, we use a manager to tick a subset each frame until they are all touched. 
Doing so allows us to limit the work done each frame, at the cost actors being ticked/called/action less often. 

This example could be improved, by adding ranged-based tick prefference or actor based perfference to give actor types or ranges additional ticks per loop. 

The Niagara Example shows the use of Effect Types for distance activation of niagara systems. 
We are also passing data to niaraga for particle color, but our hue math is off. 
If you can help correct it, please let me know!

Thank you,
Micah Berninghausen on Linkedin
@GAMEDEVMICAH & GAMEDADMICAH on Twitter
Aggressive Mastery on Youtube
Aggressive Performance LLC

If you want to support me, or are in need of optimization consulting, please reach out or donate at micah.berninghausen@gmail.com (PAYPAL) THANK YOU VERY MUCH!!!

TICK DITHER PACKAGED SHIPPING 5.3.2 . ZIP : CONTAINS A PACKAGED SHIPPING 5.3.2 BUILD OF THE PROJECT
CONTROLS:

ESC : EXIT

Page Up : Increase Actors Ticked per frame by 250

Page Down: Decrease by 250

ENTER: Load OTHER level

In-EDITOR / Non-Shipping Builds : Enable STAT FPS / STAT UNIT to see impacts via CONSOLE ~ 
