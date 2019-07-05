## Hovalin Variables

| Variable Name          | 1/4     | 1/2     |    3/4  | 4/4     | Unit |
|------------------------|---------|---------|---------|---------|------|
| chamber_length         | 285     | 320     | 337     | 354     | mm   |
| chamber_thickness      | 37      | 37      | 37      | 37      | mm   |
| chamber_wall_thickness | 1.6     | 1.6     | 1.6     | 1.6     | mm   |
| thumb_to_thumb         | 93      | 104     | 110     | 115     | mm   |
| rod_diameter           | 9       | 9       | 9       | 9       | mm   |
| rod_length             | 400     | 500     | 500     | 500     | mm   |
| neck_top_width         | 20      | 21      | 22.5    | 24      | mm   |
| neck_top_over_rad      | 2       | 2       | 2       | 2       | mm   |
| neck_top_under_rad     | 10      | 10.5    | 11.25   | 12      | mm   |
| neck_thick             | 4       | 4       | 4       | 4       | mm   |
| neck_bot_width         | 25      | 27      | 28.5    | 30      | mm   |
| neck_bot_over_rad      | 4       | 4       | 4       | 4       | mm   |
| neck_bot_under_rad     | 12.5    | 13.5    | 15      | 15      | mm   |
| string_diameter_g      | 0.85    | 0.85    | 0.85    | 0.85    | mm   |
| string_diameter_d      | 0.68    | 0.68    | 0.68    | 0.68    | mm   |
| string_diameter_a      | 0.55    | 0.55    | 0.55    | 0.55    | mm   |
| string_diameter_e      | 0.45    | 0.45    | 0.45    | 0.45    | mm   |
| thumb_top_inset        | See *1  | See *1  | See *1  | See *1  | mm   |
| thumb_bot_inset        | See *2  | See *2  | See *2  | See *2  | mm   |
| nut_lift               | 4       | 4       | 4       | 4       | mm   |
| nut_action             | 1       | 1       | 1       | 1       | mm   |
| tuner_mount_length     | 60      | 60      | 60      | 60      | mm   |
| fretboard_extension    | 100     | 100     | 100     | 100     | mm   |
| nut_to_bridge          | 267     | 287     | 306     | 325     | mm   |
| neck_bot_lift          | 14      | 8       | 9       | 10      | mm   |
| neck_top_sink          | 14      | 3       | 4       | 5       | mm   |
| neck_bot_beef          | 0       | 0       | 0       | 2       | mm   |
| bridge_width           | 46      | 46      | 46      | 46      | mm   |
| sound_post_diameter    | 5       | 5       | 5       | 5       | mm   |

*1:  
```
( 2 * neck_top_width * thumb_to_thumb + neck_top_width * neck_bot_width ) / ( 4 * thumb_to_thumb + 4 * neck_bot_width - 2 * neck_top_width )
```  

*2:  
```
neck_bot_width / 2
```  
