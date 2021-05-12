

<b>Design inspired by the TSDZ2 Wireless Project by Casainho.</b>
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
(https://devzone.nordicsemi.com/f/nordic-q-a/58983/nrf52840-dongle-matching-network-for-ext-antenna)<br><br>
<br>
I am not only sure if the PCB dimensions will be perfect, unfortunately I am waiting <br>
for a spare controller and I do not want to disassemble the engine :)<br><br>
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

<a href="https://www.fotosik.pl/zdjecie/7f113ee466bc0085" target="_blank"><img src="https://images91.fotosik.pl/501/7f113ee466bc0085med.png" border="0" alt="" /></a>

<a href="https://www.fotosik.pl/zdjecie/d578191964af04d6" target="_blank"><img src="https://images92.fotosik.pl/501/d578191964af04d6med.png" border="0" alt="" /></a>

<a href="https://www.fotosik.pl/zdjecie/061baf7992c5fff2" target="_blank"><img src="https://images92.fotosik.pl/501/061baf7992c5fff2med.png" border="0" alt="" /></a>

<a href="https://www.fotosik.pl/zdjecie/61608f84c9f4ba9b" target="_blank"><img src="https://images90.fotosik.pl/501/61608f84c9f4ba9bmed.png" border="0" alt="" /></a>
