# The Hovalin
## A 3D printable Acoustic Violin.

This document goes over the details for design of a 3D printable 4/4 violin.

## [Design overview](##design-overview-1)  
## [3rd Party Hardware](#3rd-party-hardware-1)  
## [CAD structure](#cad-structure-1)  
## [Variables](#44-violin-variables)  
  
## Design Overview  
The Hovalin is designed to be printed on a standard desktop FDM / FFF 3D printer.
The following assumptions are being made about the 3D printer :
  - The 3D printer has a 0.4 mm nozzle  
    - Most FFF 3D printers have a 0.4mm nozzle.
    - The violin chamber's walls will be 1.5mm thick (almost 4 extrusions)  
  - The 3D printer has a height of at least 360mm (Designing specifically for the CR-10) 
    - The Hovalin's body will print upright and will have a height of 357mm  

## 3rd Party Hardware
Although the Hovalin is 3D printed, it isn't entirely made of printed parts. We'll need the following items:
- [Carbon Fiber Rod](https://www.amazon.com/carbon-8mmx6mmx500mm-wrapped-glossy-finish/dp/B07DTB937Z/ref=sr_1_9?ie=UTF8&qid=1532236459&sr=8-9&keywords=500mm+8mm+carbon+fiber+rod)  
  - 500mm length  
  - 8mm outer diameter  
- [4x guitar tuning pegs](http://www.amazon.com/gp/product/B009AQIZYS/ref=as_li_tl?ie=UTF8&amp;camp=1789&amp;creative=9325&amp;creativeASIN=B009AQIZYS&amp;linkCode=as2&amp;tag=hovalin-20&amp;linkId=RR43FGQCYG63T4VS)  
- [Strings](http://www.amazon.com/gp/product/B0002Y6BJI/ref=as_li_tl?ie=UTF8&amp;camp=1789&amp;creative=9325&amp;creativeASIN=B0002Y6BJI&amp;linkCode=as2&amp;tag=hovalin-20&amp;linkId=RMBKSKN5ZX76LXDL)  

## CAD structure  
  - Printed Parts
    - Chamber (Body)
    - Neck
  - Hardware
    - Carbon Fiber Rod
    - Tuners
    - Strings
    - (possibly) Bridge


## 4/4 Violin Variables. 

| Variable Name         | Value   | Unit |
|-----------------------|---------|------|
| violin_body_length    | 354     | mm   |
| violin_body_thickness | 37      | mm   |
| chamber_thickness     | 1.5     | mm   |
| chamber_rail_diameter | 2.5     | mm   |
| thumb_to_thumb        | 115     | mm   |
| rod_diameter          | 9       | mm   |
| rod_length            | 500     | mm   |
| neck_top_width        | 24      | mm   |
| neck_top_over_rad     | 2       | mm   |
| neck_top_under_rad    | 12      | mm   |
| neck_thick            | 4       | mm   |
| neck_bot_width        | 30      | mm   |
| neck_bot_over_rad     | 4       | mm   |
| neck_bot_under_rad    | 15      | mm   |
| string_diameter_g     | 0.85    | mm   |
| string_diameter_d     | 0.68    | mm   |
| string_diameter_a     | 0.55    | mm   |
| string_diameter_e     | 0.45    | mm   |
| thumb_top_inset       | See *1  | mm   |
| thumb_bot_inset       | See *2  | mm   |
| nut_lift              | 4       | mm   |
| nut_action            | 1       | mm   |
| tuner_mount_length    | 39      | mm   |
| fretboard_extension   | 100     | mm   |
| nut_to_bridge         | 325     | mm   |
| bridge_lift           | 14      | mm   |

*1:  
```
( 2 * neck_top_width * thumb_to_thumb + neck_top_width * neck_bot_width ) / ( 4 * thumb_to_thumb + 4 * neck_bot_width - 2 * neck_top_width )
```  

*2:  
```
neck_bot_width / 2
```  
