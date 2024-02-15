# [Miyoo Mini + OnionOS] CRT layout and Filter
CRT layout and Filter for Miyoo Mini + under OnionOS

## Description
The frame and `.so` filter ware taken from [OnionUI/Onion/discussions #708](https://github.com/OnionUI/Onion/discussions/708)
What I did was:
- Added smoothing bloor to frame png.
- Create `.filt` edit to `.so` filter, to prevent resolution change.
- New CRT `.png` pattern done by hand, using this as a reference:
- - ![](.misc/CRT_screen_closeup-refrence.png)

## Comparison
### Darkwing Duck (U) [NES]
 |-Nothing-|NTSC Filter
:--|---|---
-Nothing-|![1](.misc/Darkwing%20Duck%20(U)%20[!].png)|![2](.misc/Darkwing%20Duck%20(U)%20[!]_NTSC.png)
CRT Layout|![3](.misc/Darkwing%20Duck%20(U)%20[!]_CRT.png)|![4](.misc/Darkwing%20Duck%20(U)%20[!]_CRT+NTSC.png)

### Fox Junction (J) [PSX]
 |-Nothing-|NTSC Filter
:--|---|---
-Nothing-|![1](.misc/Fox%20Junction%20(Japan).png)|![2](.misc/Fox%20Junction%20(Japan)_NTSC.png)
CRT Layout|![3](.misc/Fox%20Junction%20(Japan)_CRT.png)|![4](.misc/Fox%20Junction%20(Japan)_CRT+NTSC.png)

### Shinsetsu Samurai Spirits - Bushidou Retsuden (J) [NEOGEO CD]
 |-Nothing-|NTSC Filter
:--|---|---
-Nothing-|![1](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J).png)|![2](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_NTSC.png)
CRT Layout|![3](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_CRT.png)|![4](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_CRT+NTSC.png)

## Changes:
- Replaced wrong filter's .filt file.
- The .png layout file is still v,2.
- Compared to original v.1 the frame is smoother and the .psd and .xcf files ware extended to have more customization.

## Useful resources:
- https://github.com/CyberLabSystems/CyberLab-Custom-Blargg-NTSC-Video-Filter-Presets/releases
- https://github.com/drkhrse/drkhrse_miyoo_bezels/releases
- https://aegis.disinfo.zone/user/1playerinsertcoin
- https://www.reddit.com/r/MiyooMini/comments/17tf2hu/miyoo_mini_plus_bezel_pack_download
- https://www.reddit.com/r/MiyooMini/comments/1616xs3/i_adjusted_all_825_sgb_borders_as_gbgbc_overlays/
