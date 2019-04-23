# Draw boat

## Bill of material

### Horizontal tracks and traveler


- Arduino Uno
- CNC Shield
- [12V 2A Wall Transformer](https://www.amazon.com/Adapter-100-240V-Transformers-Switching-Adaptor/dp/B019Q3U72M)


- engine x2
[Hanpose 17HS4401 x1](http://www.datasheet4u.com/pdf/17HS4401-pdf/928661)
HANPOSE 17HS4401-S 40mm Nema 17 Stepper Motor 42 Motor 42BYGH 1.7A 40N.cm 4-lead Motor for 3D printer CNC Laser


- track: x2
 [Machifit 100-1000mm Black 2040 V-Slot Aluminum Profile Extrusion Frame for CNC](https://www.banggood.com/Machifit-100-1000mm-Black-2040-V-Slot-Aluminum-Profile-Extrusion-Frame-for-CNC-Tool-DIY-p-1342020.html?rmmds=detail-left-hotproducts__9&ID=515970&cur_warehouse=CN)

- endstop:

- Traveler:

- plastic wheels:    x4
[10Pcs/Pack TEVO® POM Material Big Pulley Wheel with Bearings for V-slot 3D Printer Part](https://www.banggood.com/10PcsPack-TEVO-POM-Material-Big-Pulley-Wheel-with-Bearings-for-V-slot-3D-Printer-Part-p-1411601.html?rmmds=search&cur_warehouse=CN)



### Vertical Track
- track x1
[Machifit 100-1000mm Black 2040 V-Slot Aluminum Profile Extrusion Frame for CNC](https://www.banggood.com/Machifit-Black-2020-V-Slot-Aluminum-Profile-Extrusion-Frame-for-CNC-Laser-Engraving-Machine-p-1341703.html?rmmds=detail-left-hotproducts__10&ID=534076&cur_warehouse=CN)

### Head
- Traveler:
- pen holder:
- engine: x2
[Hanpose 17HS4401 x1]  (http://www.datasheet4u.com/pdf/17HS4401-pdf/928661)
HANPOSE 17HS4401-S 40mm Nema 17 Stepper Motor 42 Motor 42BYGH 1.7A 40N.cm 4-lead Motor for 3D printer CNC Laser

- plastic wheels:    x4
[10Pcs/Pack TEVO® POM Material Big Pulley Wheel with Bearings for V-slot 3D Printer Part](https://www.banggood.com/10PcsPack-TEVO-POM-Material-Big-Pulley-Wheel-with-Bearings-for-V-slot-3D-Printer-Part-p-1411601.html?rmmds=search&cur_warehouse=CN)


- endstop:
[endstop](https://www.banggood.com/Mechanical-End-Stop-Endstop-Limit-Switch-With-Cable-For-CNC-3D-Printer-RAMPS-1_4-p-1067211.html?rmmds=search&cur_warehouse=CN)
or
[endstop](https://www.banggood.com/3Pcs-Horizontal-Type-Mechanical-Endstop-Switch-with-1m-Cable-for-3D-Printer-Reprap-Ramps1_4-p-1348195.html?rmmds=search&cur_warehouse=CN)


engrenage: [16/20/36T GT2 Aluminum Timing Pulley For DIY 3D Printer - 20](https://www.banggood.com/20T-GT2-Aluminium-Timing-Pulley-2GT-5M-Belt-For-RepRap-Prusa-Mendel-3D-Printer-p-1081330.html?rmmds=detail-left-hotproducts__4&cur_warehouse=CN
)

[wires hider](https://www.banggood.com/Tevo-1m-Length-1010mm-Opening-Plastic-Towline-for-3D-Printer-p-1260336.html?rmmds=search&cur_warehouse=CN)

[belt](https://www.banggood.com/TEVO-10m-Length-6mm-Width-GT2-Open-Timing-Belt-for-3D-Printer-p-1266888.html?rmmds=search&cur_warehouse=CN)


## Softwares
Python

g-code parser : [grbl] (https://github.com/gnea/grbl)
[grbl-servo](https://github.com/robottini/grbl-servo)

[inkscape](https://inkscape.org/en/)

[g-code sender](https://winder.github.io/ugs_website/download/)

[Inkscape plugin to generate g-code](http://www.mediafire.com/file/ae0wquqornzc3o2/MI+Inkscape+Extension.zip)

Arduino code: (compiled and uploaded using the Arduino IDE; make sure to update config.h in your /Arduino/libraries/grbl folder to enable CoreXY !!!)
[More info on CoreXY here: http://corexy.com/theory.html]
