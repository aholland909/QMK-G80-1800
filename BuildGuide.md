# aHolland's QMK G80-1800 Build Guide

## Parts list
* 1x 	  G80-1800 Case
* 1x 	  G80-1800 PCB
* 1x 	  Teensy 2.0++
* 1x    Breakboard/Stripboard 50*70 (Optional)
* 1x    SIL turner pin socket (2x20 pins)
* 1x    Spool of wire

## Step 1 - Desoldering

First you will need to desolder the old controller board from the PCB. Once done desolder the LEDs and the black spacer. 
![img](https://i.imgur.com/ySP3WIQ.jpg)

## Step 2 - Case prep

Next you will need to remove the tabs in the case to create some extra room for the Teensy, wires and cable. 
![img](https://i.imgur.com/H1tK3fc.jpg)

## Step 3 - Breakboard and Teensy

If you are using breakboard this will need to be cut down to size to fit the case. Then the Teensy will need to be soldered onto the breadboard by your preferred method. Here I am using two lots of SIL turner pin sockets and sinlge core wire and solder to make the connection. 
![img](https://i.imgur.com/Oh1sr4Z.jpg)

## Step 4 - Soldering wires

After that you can now connect wires from the PCB to the Teensy. I made the error of connecting a wire to AREF, so I had to move it to another pin. I did the columns first then did the rows. 
![img](https://i.imgur.com/XjfwfGh.jpg)
![img](https://i.imgur.com/JxB6cti.jpg)

## Step 5 - LEDs
Next I made a breakout for the LEDs. I made link wires, as one side of the LED goes to 5V and the other side goes to the pin that you assign it to. Then I made connections from the stipboard to the Teensy. 
![img](https://i.imgur.com/64fWzQx.jpg)

## Step 6 - Putting it all together
I squeezed all of the parts into the case and added in a USB wire to the Teensy. 
![img](https://i.imgur.com/s9Uk1On.jpg)

## Final Board
![img](https://i.imgur.com/GLZ2BeS.jpg)
