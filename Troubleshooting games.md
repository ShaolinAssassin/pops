h1. [COMPATIBILITY] *Troubleshooting games*


______________________________________________________________________________________________________________


You can use the Cheat Engine feature to troubleshoot problematic games.

Here is a ready-to-use CHEATS.TXT file which can help you and save you time :

pre. 
Single compatibility mode test
// mode 1 = help restoring the music/voices in several games 
COMPATIBILITY_0×01
------------------------------------------------------------------
// mode 2 = help restoring the music/voices + not breaking the MDECoding of FMVs
COMPATIBILITY_0×02
------------------------------------------------------------------
// mode 3 = (aletrnate to mode 1) help restoring the music/voices in several games 
COMPATIBILITY_0×03
------------------------------------------------------------------
// mode 4 = fixes slowdowns, flickering, and many other glitches 
COMPATIBILITY_0×04
------------------------------------------------------------------
// mode 5 = made for fixing the cutscenes of the PAL Resident Evil: Director’s Cut 
COMPATIBILITY_0×05
------------------------------------------------------------------
// mode 6 = un-freeze somes games at startup
COMPATIBILITY_0×06
==================================================================
Combinaison of 2 compatibility modes 
// modes 1+4
COMPATIBILITY_0×01
COMPATIBILITY_0×04
------------------------------------------------------------------
// modes 1+6
COMPATIBILITY_0×01
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 2+4
COMPATIBILITY_0×02
COMPATIBILITY_0×04
------------------------------------------------------------------
// modes 2+6
COMPATIBILITY_0×02
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 3+4
COMPATIBILITY_0×03
COMPATIBILITY_0×04
------------------------------------------------------------------
// modes 3+6
COMPATIBILITY_0×03
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 4+5
COMPATIBILITY_0×04
COMPATIBILITY_0×05
------------------------------------------------------------------
// modes 4+6
COMPATIBILITY_0×04
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 6+5
COMPATIBILITY_0×06
COMPATIBILITY_0×05
==================================================================
Combinaison of 3 compatibility modes 
// modes 1+4+6
COMPATIBILITY_0×01
COMPATIBILITY_0×04
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 2+4+6
COMPATIBILITY_0×02
COMPATIBILITY_0×04
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 3+4+6
COMPATIBILITY_0×03
COMPATIBILITY_0×04
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 4+5+6
COMPATIBILITY_0×04
COMPATIBILITY_0×05
COMPATIBILITY_0×06

* *How to use it :* 

1. Copy past all lines into a CHEATS.TXT file.
2. Put that file into the game VMC folder. 
3. Use uLE Text editor to active the wanted combinaison ($) + and let the other lines unedited.


Ex : modes 3+4 enabled 


pre. 
Single compatibility mode test
// mode 1 = help restoring the music/voices in several games 
COMPATIBILITY_0×01
------------------------------------------------------------------
// mode 2 = help restoring the music/voices + not breaking the MDECoding of FMVs
COMPATIBILITY_0×02
------------------------------------------------------------------
// mode 3 = (aletrnate to mode 1) help restoring the music/voices in several games 
COMPATIBILITY_0×03
------------------------------------------------------------------
// mode 4 = fixes slowdowns, flickering, and many other glitches 
COMPATIBILITY_0×04
------------------------------------------------------------------
// mode 5 = made for fixing the cutscenes of the PAL Resident Evil: Director’s Cut 
COMPATIBILITY_0×05
------------------------------------------------------------------
// mode 6 = un-freeze somes games at startup
COMPATIBILITY_0×06
==================================================================
Combinaison of 2 compatibility modes 
// modes 1+4
COMPATIBILITY_0×01
COMPATIBILITY_0×04
------------------------------------------------------------------
// modes 1+6
COMPATIBILITY_0×01
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 2+4
COMPATIBILITY_0×02
COMPATIBILITY_0×04
------------------------------------------------------------------
// modes 2+6
COMPATIBILITY_0×02
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 3+4
$COMPATIBILITY_0×03
$COMPATIBILITY_0×04
------------------------------------------------------------------
// modes 3+6
COMPATIBILITY_0×03
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 4+5
COMPATIBILITY_0×04
COMPATIBILITY_0×05
------------------------------------------------------------------
// modes 4+6
COMPATIBILITY_0×04
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 6+5
COMPATIBILITY_0×06
COMPATIBILITY_0×05
==================================================================
Combinaison of 3 compatibility modes 
// modes 1+4+6
COMPATIBILITY_0×01
COMPATIBILITY_0×04
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 2+4+6
COMPATIBILITY_0×02
COMPATIBILITY_0×04
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 3+4+6
COMPATIBILITY_0×03
COMPATIBILITY_0×04
COMPATIBILITY_0×06
------------------------------------------------------------------
// modes 4+5+6
COMPATIBILITY_0×04
COMPATIBILITY_0×05
COMPATIBILITY_0×06

* *Tip :* start by mode 0x04. 



______________________________________________________________________________________________________________

h1. "*Back*":https://bitbucket.org/ShaolinAssassin/popstarter-documentation-stuff/wiki/Home