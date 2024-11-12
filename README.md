# video-quality-calculator
a script that calculates parameters for video processing.  size, resolution, bitrate, bits-per-pixel, etc...


has mouse/arrow key support and you can also type numbers directly into the fields

usage:
./video-quality-calculator.bsh [vidfile.mp4]

use arrow keys or scroll wheel to move and make adjustments
hold shift key to increase multiplyer
left click to select line
z removes fraction part of current selected field
q or right click or esc to exit


i mostly use this for calculating quality values for x264 and x265, and for meeting file size requirements.

requires ffmpeg and ffprobe to work.

some useful links:
https://www.exit1.org/dvdrip/doc/gui-gui_zoom_calc.cipp#gui_zc_bpp
http://www.silverjuke.net/public/misc/bitrate-calculator

https://trac.ffmpeg.org/wiki
https://trac.ffmpeg.org/wiki/Encode/H.264
https://trac.ffmpeg.org/wiki/Encode/H.265
