# Warning:
any information presented here is for educational purposes only.
Opening the device and its modifications will void the warranty. 
You perform all activities at your own risk, I am not responsible for any damages.

If you have never had a soldering iron in your hand, start with something simpler. You will save yourself nerves and money.

To add a serial inteface you need to solder 3 gold pins.
First clean the fields marked 1, 2, 3 from tin remnants.
Insert the three GOLD PINs from the top side and solder them.

But that's not all ...

You still need to solder two copper wire bridges, marked in red in the picture or
solder the elements as described below.

R9 = R0402 - 0R

R10 = R0402 - 10K

Q1 = SOT-23 - BSN20

Element designations and values correspond to those in the diagram Orange_Pi_Zero2_H616 in the DEBUG section page 9.
The diagram is available at: https://linux-sunxi.org/File:Orange_Pi_Zero2_H616_Schematic_v1.3.pdf

Remember that this is a 3.3V interface, never connect to 5V.
