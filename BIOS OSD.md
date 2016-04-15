h1. *BIOS & OSD Handler*


______________________________________________________________________________________________________________
_[Up-to-date with WIP 06, OBT 13 (2015/12/07)]_

h2. _BIOS handler :_ 


You can use a PlayStation BIOS dump with POPS. Put a "BIOS.BIN" file in the VMC directory (example : __common/POPS/PBPX-95000.MY_GAME/BIOS.BIN) so POPStarter can handle it.
If you didn't, POPS will use the built-in BIOS.



______________________________________________________________________________________________________________


h2. _OSD handler :_ 


If you put an OSD replacement image in the VMC directory, named as "OSD.BIN" (example : __common/POPS/PBPX-95000.MY_GAME/OSD.BIN), it will be injected in the built-in BIOS for POPS to run it.
When using a OSD replacement file, "BIOS.BIN" is ignored. 



______________________________________________________________________________________________________________

h1. "*Back*":https://bitbucket.org/SaulGoodman/popstarter-documentation-stuff/wiki/Home