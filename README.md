# RF Switch CG2179M2 or HMC544A
This PCB can hold either the CEL CG2179M2 [1] or the Analog Devices (former Hitite) HMC544A [2] which are both medium power reflective RF switches (31 and 39 dBm, respectively). The frequency range is DC to 3 GHz or DC to 4 GHz, respectively.

The PCB has a height of 0.6 mm, which is crucial (at least at higher frequencies) and it was ordered in China [3]. The populated PCB was soldered into a tinplate filter housing FG1 of size 37x20x20 mm [4]. To get the control voltages into the housing two 1000 pF feed through capacitor DF 38 [5] were used.

If you wish to use the switch for fast switching you should not populate the two capacitors C4 and C5. Additionally C1, C2 and C3 may be increased for frequencies lower than 100 MHz and decreased for frequencies above 500 MHz. Use proper high frequency capacitors. If DC signal is required, the capacitors C1, C2 and C3 must be replaced by a short or 0 Ohm resistor.

## Images
![Finished switch in the tinplated housing](https://raw.githubusercontent.com/akaFunk/RF-Switch-CG2179M2-HMC544A/master/images/img_0001.jpg)

## References
[1] http://www.cel.com/parts.do?command=load&idRootPart=2604  
[2] http://www.analog.com/en/products/rf-microwave/rf-switches/spdt-t-r/hmc544a.html  
[3] http://www.elecrow.com  
[4] http://www.schubert-gehaeuse.de/prod01.htm  
[5] http://www.oppermann-electronic.de/html/durchf__c_s.html  
