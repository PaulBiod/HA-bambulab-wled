# HA-bambulab-wled
Based on Dreed47 original blueprint.
I decided to update his blueprint cause after a bambulab update, the blueprint wasn't working at all. Indeed, the blueprint was based on light chamber state, but now when you turn off your printer, the Home assistant switch "light chamber" stays on. So the wled wasn't switching off. 

I've managed to update the blueprint to use the binary sensor "Printer state" which works flawlessly.
I also integrated some wled basic presets to make it more "fun" (no need to create wled custom presets), included more errors management, seperated effects/colors for idle/finish, added light during filament (un)loading. I guess that's all.

But more important, is that it's not based anymore on light chamber state but on printer state (On/Off).
You have to import it as a new blueprint.
I tested it on my P1S and it"s working flawlessly. Didin't try with Bambu X1 so not sure for lidar management cause I can't test it.
Hope it will help

PS : this is my first blueprint edit, so please don't hesitate to report/ameliorate the code.
