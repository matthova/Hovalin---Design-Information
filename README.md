# The Hovalin
A 3D printable Acoustic Violin.

This document goes over the details for design of a 4/4 

## Hovalin Variables

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
