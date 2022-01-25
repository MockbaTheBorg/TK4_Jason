# TK4_Jason

## Scripts/Programs run the TK4- Tur(n)Key system inside the Jason GUI (Windows only)

### Installation:

**Step 1:**<br>
. Download "tk4-_v1.00_current.zip" from http://wotho.ethz.ch/tk4-/<br>
. Extract it onto a folder called, for example, "tk4-J".<br>
<br>
**Step 2:**<br>
. Download "tk4-Jason.zip"<br>
. Extract it onto the same folder as above.<br>
<br>
**Step 3:**<br>
. Download latest SDL Hercules from http://www.softdevlabs.com/hyperion.html<br>
. Extract it onto a separate folder.<br>
. Add this separate folder to the windows PATH variable.<br>
. Copy hercules.exe from this folder onto the tk4-J folder.<br>
. Copy also dasdls.exe and tapemap.exe onto the tk4-J folder.<br>
<br>
**Step 4 (Optional):**<br>
Remove some terminals to cleanup the setup:<br>
. Remove (comment out) terminals 00C2-00C7 from tk4-.cnf<br>
. Remove (comment out) terminals 03C0-03C7 from tk4-.cnf<br>
<br>
**Step 5:**<br>
. Double click MVSJ.BAT to start Jason, wc3270 terminal emulation and Hercules.<br>
<br>
**Step 6 (Optional):**<br>
Remove some terminals, if step 4 was executed:<br>
. Edit SYS1.VTAMLST(L3274)<br>
. Comment out terminals C2 and up<br>
. Save<br>
. Delete SYS1.VTAMOBJ(L3274)<br>
. Shutdown<br>
. Shutdown/restart MVS<br>
<br>
**Usage tips:**<br>
. On the terminal emulator press ALT-K to bring up the PFKEY keypad.<br>
<br>
## USING JASON'S NATIVE TERMINALS
. Double click MVSJ2.BAT to start Jason and Hercules.<br>
. On the terminal, type HERC01 to logon.<br>
. An error message will appear, press PA1 (ctrl-F1).<br>
. Type now LOGON HERC01.<br>
. Proceed with the regular logon process.<br>
<br>
A JCL job called nocheck.jcl is provided to eliminate this error.<br>
After running the JCL job a CLPA IPL is required to apply the changes.
