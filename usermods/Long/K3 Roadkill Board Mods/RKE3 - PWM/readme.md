K3 - Roadkill PWM Mod
============
**THIS BOARD IS FOR *K3 only*.**  
***IMPORTANT*** - *Hotend fan and part cooling fan share the same voltage.*
<table width=100%>
<TR><TD width=50%><img src="images/rke3-pwm.jpg"></TD>
       <TD width=50%><img src="images/combined.png"></TD></TR>
<TR><TD width=50%><img src="images/front.png"></TD>
       <TD width=50%><img src="images/back.png"></TD></TR>       
</TABLE>

**Acknolwedgement:**
 - This toolhead is 100% just a mod of roadkill.  My work merely hackery compared to the initial development by Safflower.  Please give him all the credit he deserves.
 
 **Notes:**
 - The K3 doesn't use some of the features of the RKE2 board such as the x-endstop and filament switch, so I streamlined the features somewhat.
 - Changes
   - 6 lines for the heater.  RKE2 uses 4 lines.  This adds an additional two to allow more for headroom.  
   - PCF uses 4 lines (this is to allow for more current for the frostbite toolhead.
     - My 4028 fan uses 1.3 amps at full power.
   - Adds a line for PWM on the part cooling fan (for frostbite toolhead).
   - ***IMPORTANT*** - *Hotend fan and part cooling fan share the same voltage.*