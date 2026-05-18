# DIY-Datron-1281-Resistance-Option
Add resistance measurement capabilities to your Datron 1281

I also replicated the resistance measurement board as closely as I could. This was a lot harder than the current board. Most of the parts are still avaiable. The CLA3106 ASIC can be replaced with my CPLD replacement. For other unavaiable components I tried to find alternatives. The precision resistors are the most expensive part of this project, but there is no real other choice than Vishay foil resistors and there are quite a few. There are also two resistance standards on this PCB. These are importeant for the selftest and the selfcal capability of this meter. For this purpose I ordered VHP resistors. The resistors for the current ranges are mostly custom ordered from Texas Components. The PCB features full mechanical compatibility to the original board and all guard traces.

![DIY Resistance Option in Datron 1281](PCB.png)

A full characterization of the resistance option was not possible due to not having access the known standard resistors. I did a comparative measurement in the 10kOhm range with a short against my Solartron 7081. The noise is definitly comparable to the Solartron meter. At the moment I will see this as a win until I am able to perform better measurements.

![Noise and stability of the 10kOhm range](Measurements/0Ohm.png)
