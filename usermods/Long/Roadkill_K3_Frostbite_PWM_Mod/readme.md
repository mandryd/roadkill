Roadkill - K3 Frostbite PWM Mod
============
**THIS BOARD IS FOR *K3 only*.**  
***IMPORTANT*** - *Hotend fan and part cooling fan share the same (+) voltage.*
<table width=100%>
<TR><TD width=50%><img src="Images/rke3-pwm.jpg"></TD>
       <TD width=50%><img src="Images/combined.png"></TD></TR>
<TR><TD width=50%><img src="Images/front.png"></TD>
       <TD width=50%><img src="Images/back.png"></TD></TR>     
<TR><TD width=50%><img src="Images/board_mounted.jpg"></TD>
       <TD width=50%><img src="Images/board_with_frostbite.jpg"></TD></TR>     
</TABLE>

**Acknolwedgement:**
 - This board is 100% just a mod of roadkill.  My work pure hackery of the great work by Safflower.  Please give him all the credit he deserves.
 
 **Notes:**
 - The K3 doesn't use some of the features of the RKE2 board such as the omron probe and filament switch, so I streamlined the features somewhat.
 - This board is no longer compatible with the base roadkill.  It is only compatible with itself.
 - Changes
   - 3 pairs of wires for the heater.  RKE2 uses 2 pairs.  This adds an additional two to allow more for headroom.  
   - Part cooling fan and hotend fan share two wires for (+)
     - Partcooling fan also has two wires for (-) for the frostbite 4028 fan.
     - My 4028 fan uses 1.3 amps at full power and some 4028s use even more.
     - Adds a line for PWM on the part cooling fan (for frostbite toolhead).
     - ***IMPORTANT*** - *Hotend fan and part cooling fan share the same (+) voltage.*
   - Moved the heater screw terminal into the board a little bit.  You can use the stock side exiting wires or top exiting wires now without the terminal hanging off the side of the board.  
   - the 3 of rke3 was just a mental note for myself as to how many pairs of wires were for the heater.  I was previously using a mod with 4 pairs which i put as rke4.  This wasn't meant to confuse anyone with it being a new version of RK or something.  
