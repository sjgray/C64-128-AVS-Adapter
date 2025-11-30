C64/C128 and Multi-System AVS Boards  by Steve J. Gray,  WWW.CBMSTEVE.CA
====================================

These are Commodore C64/C128 and Multi-System adapter boards based on
designs by Sven Petersen (https://github.com/svenpetersen1965?tab=repositories)
Sven has several designs for C64, C128 and VIC-20. These are separate boards
due to different DIN connectors, placement, and pinout differences. Also the
boards were designed with Eagle CAD.

My idea was first to combine the C64 and C128 boards into one by re-arranging
the RCA and S-VIDEO connectors to place them all at the top and hence allowing
the board to work on either machine. This is my "C64/C128" version.

The second idea was to make a board that could be configurable for different
systems. I added various solder-pad jumpers and added VIC-20, VIC-20 S-Video,
and Atari 8-bit configurations. This is the "Multi-System AVS" version.

Since I use Kicad I initially imported Sven's designs to get the proper part
footprints, and then working from there pretty much re-designed everything
for the new form factor(s) and options. I also added options for TRS connector
jacks for the Audio In, a connector for power output, and PH2.0 connector for
an additional video link cable to my C128 VGA15kHz+S-VIDEO 40/80 adapter
board (coming soon).

Designs
=======

V1:	- "C64/C128 AVS", for late model C64, 64C, C128, C16, SX-64 etc with DIN-8 video port.
	- Relocated connectors.
	- Power connector for +5V.
	- Made all jumpers 3-pin for headers or small switches (2.54mm spacing).
	- Not suitable for 3D printed case due to clearance issue.
	- Verified working.

V2:	- Now "Multi-System AVS".
	- Add support for VIC-20 (DIN-5)
	- Add support VIC-20 with Retro-Channel S-video adapter board (DIN-5).
	- Add support for Atari 8-bit (DIN-5) and chroma output.
	- Add support for U64 (DIN-8).
	- Move switches to top for easier access.
	- Add more clearance above DIN connector. Good for 3D case (Future).
	- Add TRS jacks for audio in.
	- Add header for cable to my C128 video adapter board.
	- Verified working.

GitHub
======

Designs are available here: https://github.com/sjgray/C64-128-AVS-Adapter


History
=======

2025-09-13 - Created C64/C128-AVS adapter
2025-09-22 - Created Github
2025-10-08 - Created Multi-System AVS completed
2025-11-29 - Tested ok, released V2 to Github
