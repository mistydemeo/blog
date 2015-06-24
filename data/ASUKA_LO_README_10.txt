=====================================================
  ___            _           __   _____  _____ _   __
 / _ \          | |         /  | / __  \|  _  (_) / /
/ /_\ \___ _   _| | ____ _  `| | `' / /'| |/' |  / / 
|  _  / __| | | | |/ / _` |  | |   / /  |  /| | / /  
| | | \__ \ |_| |   < (_| | _| |_./ /___\ |_/ // / _ 
\_| |_/___/\__,_|_|\_\__,_| \___/\_____/ \___//_/ (_)
                                                     
                                                     
    _     _           _ _     _____                     
   | |   (_)         (_) |   |  _  |                    
   | |    _ _ __ ___  _| |_  | | | |_   _____ _ __      
   | |   | | '_ ` _ \| | __| | | | \ \ / / _ \ '__|     
   | |___| | | | | | | | |_  \ \_/ /\ V /  __/ |        
   \_____/_|_| |_| |_|_|\__|  \___/  \_/ \___|_|        
                                                     
=====================================================

Asuka 120% Limit Over, English translation 1.0

Intro
=====

This is the 1.0 release of a menu translation patch for the 1999 Saturn
fighting game Asuka 120% Limit Over. Limit Over is an unofficial hack of
the 1997 release Asuka 120% Limited, with substantially updated and
refined gameplay.

For more information on Limit Over and this patch, see my announcement
blog post:
http://mistys-internet.website/blog/blog/2015/06/21/release-asuka-120-percent-limit-over-english-translation/

How to use
==========

This ZIP file contains two versions of the patch: a PPF file you can apply
to the disc image, and IPS files for the four files on the disc that were
changed. You only need to use one of the two.

PPF
---

Applying a PPF patch is easier, if it works for you. To apply the PPF patch,
you need a copy of Asuka 120% Limit Over in BIN/CUE format; the PPF patch
may or may not work with other formats.

If you use Windows, you can use the PPF-O-Matic program to apply it:
http://www.romhacking.net/utilities/356/

Just follow the onscreen instructions.

If you use Mac OS X, Linux, or another Unix-like OS, you can use uCON64, a
commandline tool: http://ucon64.sourceforge.net/

To apply the patch, do this at the commandline:
ucon64 path_to_your_disc_image.bin --ppf Asuka120P_LO.ppf

IPS
---

It's possible your disc image might not be compatible with the PPF patch;
if so, you can patch each of the four files that were changed individually.
There are four files to patch: 0.bin, TTLDAT.SSP, V_GAGE.SSP, and VS_SPR.SSP.

* Extract the files from disc using a tool like CDmage:
  http://www.oocities.org/cdmage/frames.html
* Use an IPS patching tool, like uCON64 or IPS XP, to apply the IPS patches
  to the files.
* Import the files back into the disc image using CDmage.
  (You can do this by right-clicking on a file in CDmage's file browser and
  picking "Import File".)

TODOs
=====

* Tweak and improve lettering
* Add additional shading to character names

Credits
=======

Hacking / graphics / etc. by Ms. Tea (mistydemeo@gmail.com)

Special thanks
==============

SF and QETZL, my faithful playtesters.
