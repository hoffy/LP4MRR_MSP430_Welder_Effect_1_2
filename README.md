LP4MRR_MSP430_Welder_Effect_1_2
===============================

Launchpad for Model Railroading LED Welder Lighting Effect Ver 1.2


Instructions and Notes.txt
/*
* Welding Visual Effect Version 1.2
* COPYRIGHT © 2013 S.D. "Hoffy" Hofmeister
* http://www.hoffysworld.com
* Provided under a Creative Commons Attribution, Non-Commercial Share Alike,3.0
Unported License
* TARGETED TO MSP430 LANUCHPAD W/MSP430G2553 PROCESSOR
************************************************************************************
**************
* Design Notes:
*
* This code uses a random number between 0 and and the defined count
* to select between 10 defined effects for two high brightness LEDs.
*
* This has been designed to use two high brightness white light LEDs in order to
make the effect
* more intense but you can operate with one of you choose.
*
* I have purposely left room for a lot of growth and improvement on this project,
have fun!
************************************************************************************
***************
* Circuit Pinout:
* PIN 1.0 = Anode of LED #1 > Cathode to Ground
* PIN 1.1 = UNASSIGNED - UART
* PIN 1.2 = UNASSIGNED - UART
* PIN 1.3 = Anode of LED #2 > Cathode to Ground
* PIN 1.4 = UNASSIGNED
* PIN 1.5 = UNASSIGNED
* PIN 1.6 = UNASSIGNED
* PIN 1.7 = UNASSIGNED
* PIN 2.0 = UNASSIGNED
* PIN 2.1 = UNASSIGNED
* PIN 2.2 = UNASSIGNED
* PIN 2.3 = UNASSIGNED
* PIN 2.4 = UNASSIGNED
* PIN 2.5 = UNASSIGNED
************************************************************************************
***************
************************************************************************************
**************/
FILES IN THIS PACKAGE:
----------------------
Welder_Effect V1_2_COMPILER_CODE.TXT -- The code of copy and paste into the Code
Coposer Studio Software
Welder_Effect V1_2_CODE.PDF -- Color separated PDF version of code for easier
reading
Welder_Effect V1_2_schem.PDF -- The Electrical Schematic for this project
Welder_Effect V1_2_Visual.PDF -- A visual representation of how to wire this
project to the MSP430 Launchpad
Insructions and Notes.PDF -- This File
__________________________________________________________________________________
COMPONENTS NEEDED FOR THIS PROJECT:
-----------------------------------
Page 1
Instructions and Notes.txt
2 - Radio Shack Model: NTE30044 Catalog# 55050632 - hite Super-bright LED or
comparable
Wire
appropriate insulating material for connections to LEDS ie. Electrical Tape
__________________________________________________________________________________
UNDERSTANDING YOUR COMPONENTS:
------------------------------
What is an Anode and a Cathode?
Imagine the image below is an LED
/\
||
--
|| An LED as two leads that come off of it, one long and one short.
|| The long Lead is the ANODE and the short one is the CATHODE, on many LEDS
you will notice the LED has a flat edge on one side and a
| rounded edge on the other. The flat side is the CATHODE
What is VCC and GND Mean?
VCC is your (POSITIVE Voltage +) connection
GND is your (NEGATIVE - or GROUND) connection
___________________________________________________________________________________
PREPARING YOUR MSP430 LAUNCHPAD FOR THIS PROJECT:
-------------------------------------------------
No Special Preparation Required
____________________________________________________________________________________
CONNECTING YOUR MSP430 LAUNCHPAD TO THE LEDS:
---------------------------------------------
Connect the Anode of one of LEDs to PIN 1.0 and the Cathode to GND
Connect the Anode of the other LED to PIN 1.3 and the Cathode to GND
If you wish for the welder effect to not be as intense, only use the one LED
Page 2
