# Vectrex Pad miniNeoGeo

Allows you to convert a mini NeoGeo controller into a Vectrex controller.

This PCB reuses the analog pad of the mini NeoGeo controller. You will have to unsolder it from the original PCB.
There are two models of the NeoGeo mini controller. One contains classic directional switches (you can hear the clicks when using the directional controller). The other one uses an analogue pad. Make sure you have the right model of controller (the one with the analogue pad) before you start making this Vectrex mod.

!!! Please note that the PCB must be 1.2mm thick !!!

!!! Another warning: It is essential to cut the pins of the two auto-fire switches SW5 and SW6 (OS203011MS1QP1) at the level of the PCB BEFORE soldering. This is because the plastic of the lower part of the joystick has two rings that press on this area. Over soldering in this area could block the auto-fire buttons and deform the plastic at the back.

![PCB Top](https://github.com/Guimli/Vectrex-Pad-miniNeoGeo/raw/main/Images/Vectrex%20Pad%20miniNeoGeo%20Top.jpg)

![PCB Bottom](https://github.com/Guimli/Vectrex-Pad-miniNeoGeo/raw/main/Images/Vectrex%20Pad%20miniNeoGeo%20Bottom.jpg)

The Star and Select buttons have been replaced by an auto-fire on the A and D buttons (equivalent to the 1 and 4 button of the Vectrex controller).

## Three possible modes:

> Auto-fire disabled

> Auto-fire when the button is active.

> Auto-fire when the button is inactive (press the button to disables the auto-fire).

The SMD electronics are positioned on one side only to facilitate factory production.

![Image01](https://github.com/Guimli/Vectrex-Pad-miniNeoGeo/raw/main/Images/Image01.jpg)

![Image02](https://github.com/Guimli/Vectrex-Pad-miniNeoGeo/raw/main/Images/Image02.jpg)

![Image03](https://github.com/Guimli/Vectrex-Pad-miniNeoGeo/raw/main/Images/Image03.jpg)

## In the known problems of this controller:
- The auto-fire does not start when the button is pressed. The unstable circuit works continuously. It is therefore possible to have a lag time between the moment the button is pressed and the actual action when the auto-fire is set to low frequency.
- The lack of a user manual (I promise I will try to find the time to do so).

## The strong points of this controller :
- Its low price for a Vectrex controller.
- The very good linearity and amplitude of the analog pad.
- The integrated auto-fire.

## Weaknesses :
- Lack of a knob to adjust the auto-fire speed (adjustment has to be done with a flat screwdriver).


The colour information for the DB9 cable connection on the PCB corresponds to the colours of the cables I bought. This information helps to speed up my own production of controllers. But there is no guarantee that these colours will match the cable you bought. So I'm putting below the correspondence between pin number, function, and the silkscreen inscriptions on my PCB:
- Pin 1 - Button 1 (A) - Red
- Pin 2 - Button 2 (B) - Black
- Pin 3 - Button 3 (C) - Grey
- Pin 4 - Button 4 (D) - Orange
- Pin 5 - Horizontal   - Brun
- Pin 6 - Vertical     - Green
- Pin 7 - +5V          - White
- Pin 8 - GND          - Blue
- Pin 9 - -5V          - Yellow