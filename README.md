

<b>Design inspired by the 
<span class="colour" style="color: rgb(34, 34, 34);"> </span>**[TSDZ2 Wireless Project](https://opensourceebike.github.io/)**
 <span class="colour" style="color: rgb(34, 34, 34);">by </span>**[Casainho](https://endless-sphere.com/forums/memberlist.php?mode=viewprofile&u=18879).**</b>
<br>
<br>

Hello.<br>
In my spare time, I finally managed to design an internal PCB <br>
based on the TSDZ2 EBike Wireless Controller with some small additions  :) <br>
I added Relay for lights with a voltage higher than 5V <br>
(you can choose whether it should be controlled from nRF or from the motor controller), solder pads <br>
for the temperature sensor and Ufl connector for an external antenna.<br>
<br>
<br>
Unfortunately, in order to connect it, I plan to slightly modify the nRF.<br>
(**[link](https://devzone.nordicsemi.com/f/nordic-q-a/58983/nrf52840-dongle-matching-network-for-ext-antenna)**)<br><br>

<br>
I am not only sure if the PCB dimensions will be perfect, unfortunately I am waiting <br>
for a spare controller and I do not want to disassemble the engine :)<br><br>
<br>
<br>
version 1.2:<br>
Change from internal 5V inverter to external <a href="https://export.rsdelivers.com/product/xp-power/sth0548s05/xp-power-surface-mount-dc-dc-switching-regulator/1883365" target="_blank">XP Power STH0548S05</a>.
<br>
<br>

<br>

I hope people will like the project!<br>
I am also waiting for constructive criticism, maybe someone will manage to notice some error for which I will be able to fix!<br><br>
<br>
Link created in EasyEDA<br>
link:<br>
https://easyeda.com/woojak666/tsdz2-wireles-board_copy<br><br>
<br>
<br>
<br>
jumpers "SJ1" "SJ2", you can select the signal
source for the light switch (by default not selected)

Soldered "SJ1" - 5v signal from the controller
Soldered "SJ2" - signal from nRF52840 (P0.17)

temperature sensor: LM35CZNOPB (P0.15)

external antenna:
2.4GHZ (50ohm internal resistance)
<br>
Version 1.1
<img src="Front.png" border="0" alt="" />

<img src="Back.png" border="0" alt="" />

<img src="3D%20Front.png" border="0" alt="" />

<img src="3D%20Back.png" border="0" alt="" />

<br>
<br>
Version 1.2
<img src="Front.png" border="0" alt="" />

<img src="Back.png" border="0" alt="" />

<img src="3D%20Front.png" border="0" alt="" />

<img src="3D%20Back.png" border="0" alt="" />
<br>
<br>

nRF Adaptive Board:<br>
Minimalist PCB board to assemble **[DIY EBike wireless controller](https://opensourceebike.github.io/ebike_wireless_controller.html).**<br>
<br>
<br>
<img src="Front%20nRF.png" border="0" alt="" />
<br>
<br>
<br>
<br>
<img src="nRF%20Back.png" border="0" alt="" />
<br>
<br>
<br>
<br>
<img src="nRF%203D%20front.png" border="0" alt="" />
<br>
<br>
<br>
<br>
<img src="nRF%203D%20back.png" border="0" alt="" />
<br>
<br>
The PCB board has not been assembled by me yet.
I am currently waiting for delivery.




