# Anycubic-i3-Mega-IDEX-mod
This mod converts the Anycubic i3 Mega into an IDEX 3D printer.
![all1](https://user-images.githubusercontent.com/84620081/231165230-d3afbbfe-5f22-417b-bd14-b3eb3cc21254.JPG)

The project is currently still in its design phase and has not been brought to life yet.
It uses a 1515 aluminum extrusion and MGN12 linear rail for the X gantry.
(The printer itself will get a linear rail mod for the bed as well and upgrades to 24V.)
![x_gantry1](https://user-images.githubusercontent.com/84620081/231167820-eca77ade-9970-43e1-a085-4397b2fd5f43.JPG)
![x_gantry_rear1](https://user-images.githubusercontent.com/84620081/231167839-94bfd6d9-bd2c-4763-83f4-73f2a0bf0cd2.JPG)

The two independent print heads are driven by 1.8° Nema17 pancake stepper motors to save weight.
It uses E3D compatible V6 hotends with M12 threaded heatsinks and ceramic heating cores to get a small size:
![print_heads_close1](https://user-images.githubusercontent.com/84620081/231166961-236a1625-e9de-4f42-af86-ebdb551d7c6d.JPG)
The coldend will be cooled by a 30 mm axial fan and the printed model is being cooled by a powerful GDSTIME 4010 radial fan with 12k RPM.

Intention is to print the parts with ASA-CF for more rigidity. But ABS or ASA should be fine as well.

## Features:
- slim print heads
- MGN12 linear rails with MGN12C blocks
- V6 hotends with CHC blocks and threaded heatsinks
- 30 mm coldend fan
- 4010 mm radial fan for part cooling
- endstops on both ends of the X rail and on right print head to have multiple homing options
- bowden setups for light weight print heads

## Electronics:
- You will need a board with at least 7 driver sockets.
- Upgrade to 24 V PSU and board and all fans (mind the heating bed as well!).

## BOM:
- 2 * 30 mm axial fan (5 pack) [GDSTIME](https://aliexpress.com/item/1910412689.html)
- 2 * 4010 radial fan (2 pack) [GDSTIME](https://aliexpress.com/item/1005005094281105.html)
- 2 * threaded heatsink [TriangleLab](https://aliexpress.com/item/32888313090.html)
- 2 * Ceramic Heating Core [TriangleLab](https://aliexpress.com/item/32697889176.html)
- 2 * Nema17 pancake stepper motors [17HE08-1004S](https://www.omc-stepperonline.com/de/e-serie-nema-17-bipolar-1-8deg-17ncm-24-07oz-in-1a-42x42x23mm-4-draehte-17he08-1004s)
- 300 mm MGN12 linear rail with 2 MGN12C blocks
- 300 mm 1515 aluminum extrusion
- M3 heat inserts 
- to be updated...

## Changelog:
- 2023-04-11: Creation of this project
- 2023-04-21: Upload of print heads STLs
- 2023-05-22: Upload of left and right X axis mounts and respective motor mounts
- 2023-05-28: Replaced X axis mounts with v2 versions and corrected linear bearing diameter (reference Anycubic i3 Mega model was wrong here)
