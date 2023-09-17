# Anycubic-Chiron-Klipper

I won't be making any more updates to this repository. Unfortunately, the Chiron's Trigorilla mainboard let out the magic black smoke, and no replacement available.
This printer will be converted to something custom down the road and I will create a new repository for everything not just files.

I have spent a fair amount of time converting my mostly stock Anycubic Chiron with the Trigorilla 
Mainboard to Klipper. After many revisions and chasing out Pinout issues, I finally have a working config 
for Klipper.

I followed Ellis’ Print Tuning Guide once I had the printer running to tune my printer. I’d suggest if 
you have never done a Klipper Conversion before follow that tuning guide to the letter. It hasn’t failed 
me yet across multiple printers to get it dialed in 90% and then do small changes to get it perfect. 

Some things to note:

•	My stock bed probe does work and appears to work just as well as it did under Marlin. Your probe 
  may or may not work as I have seen across the internet that some people had real issues 
  making the stock button probe work well.

•	I am using a bondtech extruder and Bowden tube setup still so make sure to adjust your e-stops.

•	I replaced my bed springs with solid bed mounts, so my config doesn’t have any kind of bed 
  leveling commands or macros, only heightmap (bed mesh). 

•	Make sure you go through your printer and tighten everything down before running any 
  input shaping. This printer will shake everything loose if you don’t.

•	I did leave all of my PID tuning, heightmap, input shaping, and z-offset in the config as this is also 
  my backup for my own printer so be sure to remove and adjust it for your own use. I AM NOT 
  RESPONSIBLE FOR YOU MESSING UP YOUR OWN PRINTER.

I don’t provide support anywhere actively. That being said I do help with others on the Anycubic Chiron support group on Facebook as well as r/anycubic on reddit when I have time. 
