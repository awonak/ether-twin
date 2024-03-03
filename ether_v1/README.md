# Ether Twin v1

## Bill of Materials

| Reference(s) | Qty | Value | Supplier Link |
|-|-|-|-|
| J1 - J16  | 16 | Thonkiconn 3.5mm Mono Jack | https://www.thonk.co.uk/shop/thonkiconn/ |
| J17, J18 | 2 | Ethernet Connectors | https://www.mouser.com/ProductDetail/571-1-406541-5 |
| S1, S2, S3, S4 | 4 | DPDT Switch ON-ON | https://www.thonk.co.uk/shop/sub-mini-toggle-switches/ |
| S5 | 1 | 1PDT Slide Swith ON-ON | https://www.mouser.com/ProductDetail/611-JS102011SAQN |

## Build Guide v1.2

### Solder the components to the main PCB

Follow the ibom component placement guide [here](https://htmlpreview.github.io/?https://github.com/awonak/ether-twin/blob/main/ether_v1/bom/ibom.html).

1. Start by soldering the Ground Select switch S5

1. Place the two Ethernet Jacks. Begin by tacking one mounting hole lug on each Ethernet Jack. Press firmly on the jack while heating the tacked solder to ensure a snug fit.

1. Once the Ethernet Jack lugs are soldered and the jacks are flush against the PCB, then proceed to solder the 8 jack pins. (Pro tip; smear a bit of rosin flux against the pins, then drag a large bead of solder across the pins.)

1. Next, place all 16 cv jacks on the PCB. Attach the top panel, and screw nuts on the 4 corner jacks to hold them in place. Now you can flip the module over and lay it down flat while soldering the cv jacks.

1. (v1.2+ only) Remove the top panel and place the 4 toggle switches. Place the top panel back on and screw on the same 4 corner nut jacks and the 4 switch nuts. Flip the module over and solder the 4 toggle switches. (Either carefully rest the module against one side of the toggle switches, or use a third-hand to hold the module.)

### Assemble the enclosure

1. Remove the top panel attached during the previous step. This will make it easier to attach the standoffs later.

1. Start by threading the loger M3 screws through the 4 mounting holes of the bottom panel.

1. Tighten the M3 nut against those screws.

1. Place the components PCB against the nuts, components facing up.

1. Tighten the 10mm nylon standoffs to the bottom panel screws sticking up from the components PCB.

1. Attach the top panel to the component pcb and screw on all 16 cv jack nuts and 4 toggle switch nuts.

1. Screw the shorter M3 screws into the top panel mounting holes and into the standoffs.
