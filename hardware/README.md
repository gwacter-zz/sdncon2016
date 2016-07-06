# Hardware on the day

We have providing *SEVEN* pre-built development testbeds built around Raspberry PIs and Zodiac FX switches. 

That should be enough for each team although it might mean some individuals need to find someone to work with on the day itself.

## What you should bring along

At least one laptop, we expect that you will use this to connect to the testbed and other equipment.

You will need [PuTTY for Windows](https://the.earth.li/~sgtatham/putty/latest/x86/putty.exe).

## What is given to you.

<img src="https://github.com/gwacter/sdncon2016/blob/master/hardware/SDNcon2016_network_diagram.png" width=25%></img>)

A Raspberry Pi 2 Model B functions as the OpenFlow controller. The on­board Ethernet port (of the Raspberry Pi ­ labelled Ctrl) connects the controller to the controller switch port on a Zodiac FX OpenFlow switch (labelled ZFX). A USB to Ethernet adapter (labelled UEt) connects the controller to the data plane (more specifically switch port 3) on the Zodiac FX mentioned above.

This wireless connection allows the other hosts (labelled hA and hB) that were connected to the Zodiac FX to access the Internet through the controller. A WiFi USB dongle was used to provide an Internet connection to the controller.

The user name and password for the raspberry Pis are :

user: pi

password: raspberry

# Getting started

When you arrive the testbed should be prebuilt and configured. However, it is still a good idea to test it out in order to get started.

See : https://github.com/gwacter/sdncon2016/blob/master/hardware/testbed-setup.md

# Other hardware

We will also have some other equipment available but we strongly suggest that you use our pre-built environment. Depending upon numbers of people on the day, we may suggest individual participants combine together into a team to share a testbed.



