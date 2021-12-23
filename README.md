# FT-AV-Fami-Buddy
This board is currently untested. Feel free make one and leave feedback!

A breakout board for NESRGB installs on AV Famicoms. Attaches to the underside of the AV multiout and extends pads to the side of the board. This allows installers to run ribbon or wire straight to pads rather than trying to solder directly to the pins.

# PCB Manufacturing
Thickness: 0.8<br>
Project Link: https://oshwlab.com/fragolroc/av-famicom-buddy<br>
OshPark: https://oshpark.com/shared_projects/0wSuEfyF

# Installation
This board is deisgned to be installed alongside an NESRGB mod. 

If you are concerned about the potential "jailbars" which may be present after the NESRGB installtion, please reference this guide to fix the noisy ground of the AV multiout. If "jailbars" do not conern you, then continue. https://www.laserbear.net/blogs/news/removing-jailbars-from-av-famicom-nesrgb

After the NESRGB is install and you're running wire to multiout, solder this board to the underside of the AV multiout so that the screw hole is aligned properly with the mainboard. Solder into place and then run wires accordingly to the pads. CS# runs to the SYNC pin of AV multiout for this board.

The pad labeled "pin 45" is an optional connection to allow expansion audio to be mixed through a Famicom cart. From the NESRGB, connect O to the Fami-Buddy and then connecto the "pin 45" pad to pin 45 of the cart connector. Audio from the NESRGB will be routed to the Famicom cart, mixed with the on-board expansion audio chip, and then routed back through pin 46 to the AV multiout. Again, this is optional and requires that you also run wires from CPU pin 1 & 2 to the NESRGB (as you would for installation on an NES).

TianFeng orignally came up with this idea and I adapted it to work on this board. For installation pictures regarding pin 45 follow the below link.<br>
https://twitter.com/Tian_Feng44/status/1253359763259342855?s=20

