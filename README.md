# microSD-breakout-board
This is a compact microSD breakout board for both directions.  
It can also be used as a sniffer in between a host and a microSD card for analyzing signals or performing tests.  
The PCB is optimized for signal integrity with coplanar single ended impedance matching (50 Ω ±10 %).  

| Top | Bottom |
| :---: | :---: |
| ![microSD breakout board](/images/microSD%20breakout%20board%20-%20assembly%20top.PNG) | ![microSD breakout board](/images/microSD%20breakout%20board%20-%20assembly%20bottom.PNG) |

## Components  
Two optional components can be placed on the PCB:
- microSD card header `Molex 475710001`
- 2x8 2.54 mm pin header (e.g. `Molex 10897080`)

## Manufacturing
The PCB has the following properties:
- Size: 26.5 x 12.5 mm
- PCB thickness: 0.8 mm
- Layers: 2
- Copper weight: 1 oz
- Min. via hole size: ⌀ 0.3 mm
- Min. via diameter: ⌀ 0.4 mm
- Min. trace width: 0.4326 mm
- Min. distance between traces or pads: 0.127 mm
- Min. distance to board outline: 0.3 mm

Gerber files (RS-274X) are available [here](/electronics/production/).

The impedance was calculated for the standard 2 layer, 0.8 mm stack-up from JLCPCB: "JLC0208".

## Licence
This repository is in public domain.  
[Read more](/LICENSE)
