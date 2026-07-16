Hi. This is the IIC-OSIC-TOOLS ihp-sg13cmos5l PDK but with some bugs fixed because there is a tapeout deadline tomorrow and our LVS is NOT done.

What was added:

1) option to disable tap extraction (shamelessly stolen from https://github.com/iic-jku/IHP-Open-PDK/pull/48)
2) metal4 now connects to topmetal1 properly
3) probably quite a few bugs. don't use this with xschem, just klayout.

How do I use:

1) clone repo into /foss/designs
2) cd /foss/designs/osic-tools-sg13-fixed
3) (inside of the folder) source source_cursedness.rc
4) now cd out and be free to open whatever you want. note that the pdk symbols are all different from the standard pdk ones, since this is technically a different folder. so **don't use this with anything but klayout**
