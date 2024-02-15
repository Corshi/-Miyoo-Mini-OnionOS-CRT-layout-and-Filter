# [Miyoo Mini + OnionOS] CRT layout and Filter
CRT layout and Filter for Miyoo Mini + under OnionOS

## Description
The frame and `.so` filter ware taken from [OnionUI/Onion/discussions #708](https://github.com/OnionUI/Onion/discussions/708)
What I did was:
- Added smoothing bloor to frame png.
- Create `.filt` edit to `.so` filter, to prevent resolution change.
- New CRT `.png` pattern done by hand, using this as a reference:
  - ![](.misc/CRT_screen_closeup-refrence.png)

## Comparison
*All images done while using `Bilinear Filtering`
*All CRT layouts are at 100% intensity

### A Very Super Mario World (Hack) [SNES]
-Nothing-|v2|v4
---|---|---
![none](.misc/A%20Very%20Super%20Mario%20World.png)|![v2](.misc/A%20Very%20Super%20Mario%20World_001.png)|![v4](.misc/A%20Very%20Super%20Mario%20World_002.png)
![none_zoom](.misc/A%20Very%20Super%20Mario%20World_zoom.png)|![v2_zoom](.misc/A%20Very%20Super%20Mario%20World_001_zoom.png)|![v4-zoom](.misc/A%20Very%20Super%20Mario%20World_002_zoom.png)

### Darkwing Duck (U) [NES]
 |-Nothing-|Blargg NTSC SNES
:--|---|---
-Nothing-|![1](.misc/Darkwing%20Duck%20(U)%20[!].png)|![2](.misc/Darkwing%20Duck%20(U)%20[!]_NTSC.png)
CRT Layout v2|![3](.misc/Darkwing%20Duck%20(U)%20[!]_CRT.png)|![4](.misc/Darkwing%20Duck%20(U)%20[!]_CRT+NTSC.png)

 |-Nothing-|Blargg NTSC SNES
:--|---|---
-Nothing-|![1](.misc/Darkwing%20Duck%20(U)%20[!]_zoom.png)|![2](.misc/Darkwing%20Duck%20(U)%20[!]_NTSC_zoom.png)
CRT Layout v2|![3](.misc/Darkwing%20Duck%20(U)%20[!]_CRT_zoom.png)|![4](.misc/Darkwing%20Duck%20(U)%20[!]_CRT+NTSC_zoom.png)

### Fox Junction (J) [PSX]
 |-Nothing-|Blargg NTSC SNES
:--|---|---
-Nothing-|![1](.misc/Fox%20Junction%20(Japan).png)|![2](.misc/Fox%20Junction%20(Japan)_NTSC.png)
CRT Layout v2|![3](.misc/Fox%20Junction%20(Japan)_CRT.png)|![4](.misc/Fox%20Junction%20(Japan)_CRT+NTSC.png)

 |-Nothing-|Blargg NTSC SNES
:--|---|---
-Nothing-|![1](.misc/Fox%20Junction%20(Japan)_zoom.png)|![2](.misc/Fox%20Junction%20(Japan)_NTSC_zoom.png)
CRT Layout v2|![3](.misc/Fox%20Junction%20(Japan)_CRT_zoom.png)|![4](.misc/Fox%20Junction%20(Japan)_CRT+NTSC_zoom.png)

### Shinsetsu Samurai Spirits - Bushidou Retsuden (J) [NEOGEO CD]
 |-Nothing-|Blargg NTSC SNES
:--|---|---
-Nothing-|![1](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J).png)|![2](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_NTSC.png)
CRT Layout v2|![3](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_CRT.png)|![4](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_CRT+NTSC.png)

 |-Nothing-|Blargg NTSC SNES
:--|---|---
-Nothing-|![1](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_zoom.png)|![2](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_NTSC_zoom.png)
CRT Layout v2|![3](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_CRT_zoom.png)|![4](.misc/Shinsetsu%20Samurai%20Spirits%20-%20Bushidou%20Retsuden%20(J)_CRT+NTSC_zoom.png)

## Changes:
- Replaced wrong filter's `.filt` file.
- v2 is smoother and the `.psd` and `.xcf` files ware extended to have more customization.
- v3 is crt patter customization improvement.
- v4 is crt patter x2 the size of v3 (bigger pixel density on MM+ screen).

### Note:
- `.filt` is not compatible with all system, like:
  - GBA
  - GG
  - PSX
  - *etc.*

(It is a thing with how original `.so` works. If someone has a way to fix it please inform as an Issue)

## Useful resources:
- https://github.com/CyberLabSystems/CyberLab-Custom-Blargg-NTSC-Video-Filter-Presets/releases
- https://github.com/drkhrse/drkhrse_miyoo_bezels/releases
- https://aegis.disinfo.zone/user/1playerinsertcoin
- https://www.reddit.com/r/MiyooMini/comments/17tf2hu/miyoo_mini_plus_bezel_pack_download
- https://www.reddit.com/r/MiyooMini/comments/1616xs3/i_adjusted_all_825_sgb_borders_as_gbgbc_overlays/
