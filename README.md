CopyPics
========

A script to copy pictures and movies from various cameras to DNG with a 
date-time filename, while preserving sidecar files on OS X 

Presently works for Canon A3000IS, Fuji, Canon 5DmII, 100S, G12 and EOS-M. 
Uses the Adobe RAW utility to convert to DNG, and preserves sidecar files
such as JPG. Basically works as a LightRoom import replacement but this 
can actually handle movie files correctly. It uses exiftool for pictures
to determine the time, and uses a timestamp for movies. The pictures
are imported to a particular directory, in my case a remote share. 

Filenames created are of the form YYYYMMDD-HHMMSS.XYZ, multiple pictures
taken in one second are of the form YYYYMMDD-HHMMSS_N.XYZ, where _N goes
_1, _2, etc. 