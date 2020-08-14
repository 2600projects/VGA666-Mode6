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
