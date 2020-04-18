# TK4_Jason
Scripts/Programs to have the TK4- Tur(n)Key system run inside the Jason GUI (Windows only)

Installation:

Step 1:
. Download "tk4-_v1.00_current.zip" from http://wotho.ethz.ch/tk4-/
. Extract it onto a folder called, for example, "tk4-J".

Step 2:
. Download "tk4-Jason.zip"
. Extract it onto the same folder as above.

Step 3:
. Download latest SDL Hercules from http://www.softdevlabs.com/hyperion.html
. Extract it onto a separate folder.
. Add this separate folder to the windows PATH variable.
. Copy hercules.exe from this folder onto the tk4-J folder.

Step 4 (Optional):
Remove some terminals:
. Remove (comment out) terminals 00C2-00C7 from tk4-.cnf
. Remove (comment out) terminals 03C0-03C7 from tk4-.cnf

Step 5:
. Double click MVSJ.BAT to start Jason, wc3270 terminal emulation and Hercules.

Step 6 (Optional):
Remove some terminals:
. Edit SYS1.VTAMLST(L3274)
. Comment out terminals C2 and up
. Save
. Delete SYS1.VTAMOBJ(L3274)
. Shutdown
. Shutdown/restart MVS

Usage:
. On the terminal emulator press ALT-K to bring up the PFKEY keypad.

USING JASON'S NATIVE TERMINALS
. Double click MVSJ2.BAT to start Jason and Hercules.
. On the terminal, type HERC01 to logon.
. An error message will appear, press PA1 (ctrl-F1).
. Type now LOGON HERC01.
. Proceed with the regular logon process.


