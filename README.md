# Voron-FCC-Toolhead-Board

This is a hartk style toolhead board that is meant to be paired with the FFC cable kit (https://www.schmidtproto.com/product-page/voron-2-4-ffc-mod-kit). The board uses the same mounting holes as the original hartk board and should be a drop in replacement. This board is based off the Enraged Rabbit project board which means it has support for a filament sensor. I also added the option to run a secondary voltage source so that fans, bed leveling sensors, and filament sensors could be run at a different voltage from the 24v. I currently have 2 versions of the boards. One uses the traditional microfit connector and the other uses a 90 degree XT30 connector for the hotend heater. All of the connectors have been replaced with 90 degree versions so that wires don't stick out as much. Depending on the board, some of the connectors will be mounted to the back side of the PCB (the green ones on the images below), this was done because the 90 degree connectors take up more space. This shouldn't however interfear with anything and should be fully accessible. The only difference being that a larger spacer is needed when mounting it to the toolhead.


Here is the traditional microfit version:

![Screenshot 2021-09-30 172041](https://user-images.githubusercontent.com/88988273/135537802-c198590a-74cb-4a0a-b07a-19de98ca468c.png)


Here is the XT30 version. (this one is denoted with "X" in the version number in the file):
![Screenshot 2021-09-30 172016](https://user-images.githubusercontent.com/88988273/135537817-4cdc0cac-7621-4da6-8ad7-c88fc26d738b.png)


Here is the pinout for the board.

![image](https://user-images.githubusercontent.com/88988273/141663864-c868aeac-5b89-4ef9-9683-bba137d24fdd.png)



By default everything is wired to 24V. If you would like to run a different voltage to a component, simply cut the corresponding trace (where the dash line is shown) and bridge the middle pin to the "Alt V" pin. If you ever want to convert it back to 24V, the pins on top are there to bridge back over the cut trace.

![image](https://user-images.githubusercontent.com/88988273/135538372-7765fff0-e6c2-4675-bba5-b7b5dacc4b92.png)


**The following materials are needed for building the board:**

1x - SLW20R-1C7LF (Use the one that comes in FFC kit)

1x - MOLEX 436500200 (for microfit version)

1x - xt30pw-m (for xt30 version)

1x - BAT85 diode (don't need with spirder board)

4x - S2B-XH-A

3x - S3B-XH-A

1x - S4B-XH-A

1x - NCD0805R1

1x - CR0805-FX-1501ELF

1x - CMFB103F3950FANT
