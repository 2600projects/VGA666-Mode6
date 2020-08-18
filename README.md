# VGA666-Mode6
VGA666 Mode6 Device Tree Overlay for Raspberry Pi

Requirements:<br />
Device wired for DPI Mode 6

Usage:<br />
Copy vga666-mode6.dtbo to /boot/overlays/

Add the following lines to config.txt<br />
enable_dpi_lcd=1<br />
display_default_lcd=1<br />
dpi_group=2<br />
dpi_mode=87<br />
dtoverlay=vga666-mode6<br />
dpi_output_format=6<br />
hdmi_timings=320 1 16 30 34 240 1 2 3 22 0 0 0 60 0 6400000 1 #320x240p@60hz Change this line to your choice of resolution
