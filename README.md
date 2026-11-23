# The-ArnoPad

It is a hackpad that can change the volume(rotary dial), has 6 buttons that can do whatever you want it to, a screen for your favourite gifs and leds for nessacery lighting

For this project I used the hackpad guides tutorial and then made my own with all the allowed parts. <p>
I used kicad for the PCB and Fusion 360 for the case. <p>

The reason I wanted to make this is that my friend from school came with the one he made once and I thought it was really cool, so I thought that maybe I can make one. So I found the guide on stardance and decided to make my own. 

The features of the Arno pad are:
<p>A cool case that has a window to show spiderman and orpheus</p>
<p>A screen, the screen will most likely just have an animation or some other software I make later like a weather widget</p>
<p>A rotary encoder to increase and decraese volume</p>
<p>6 leds for PEAK RGB switch backlighting(because as we all know it improves fps)</p>
<p>6 keys(and diodes) for clickity clacking. In order to make the switches work I made it use a matrix system because that is what the guide said to do if you are using more than 4 switches, and also because if I didnt I wouldnt have any way to connect the switches to the XIAO board</p>

The most difficult part of this was KICAD, it was very confusing at the start cuz it was new and I had no idea how to use it and then the wires were impossible to route without overlap(via's helped a lot)

CAD medel case:
The case has 4 holes to put everything together
It is made in 2 pieces, the case and the lid
It also has a little hole to show spiderman and orpheus on the PCB
An embossing of the word ArnoPad on the side to show what it is<img 
                                                                 width="962" height="612" alt="da case" src="https://github.com/user-attachments/assets/f8716d35-0595-4d4c-9a17-d9c2a85e8576" />
I made it in Fusion360

For the part on the left im going to make a transperant cover so that you can see the images under. 

                                                                 
The PCB:
Here is the PCB I made, I made it in KiCad.

PCB<img width="870" height="721" alt="arnopad jpeg" src="https://github.com/user-attachments/assets/1a18ea40-f253-4e3a-92c5-a59516a0f1b3" />

Schematic<img width="657" height="487" alt="image" src="https://github.com/user-attachments/assets/05f6b4f8-c626-409c-bc7d-a310958eaf70" />

BOM:
<p>6x Cherry mx switches</p>
<p>6x keycaps</p>
<p>4x screws</p>
<p>4x bolts</p>
<p>6x diodes</p>
<p>6x LED's</p>
<p>1x OLED display</p>
<p>1x rotary dial</p>
<p>1x XIAO controller</p>
<p>1x 3d printed case</p>
<p>1x custom ArnoPad PCB</p>
<p>(Basicly the hackpad kit)</p>

Firmware:
I have not made the firmware yet because I would rather do it when I have the Arnopad assembled cuz thats easier for me
