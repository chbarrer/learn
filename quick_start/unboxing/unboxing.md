---
layout: default
title:  "Unboxing and Assembling a Magni Robot"
permalink: unboxing
author: Alan Federman
---

#### &uarr;[top](https://ubiquityrobotics.github.io/learn/) - - - &uarr;[up](ix_quick_start)

## Unboxing and Assembling a Magni Robot

The Magni comes almost ready to run with minimal assembly. There are three different version of Magni: Bronze, Silver and Gold. Silver and Gold comes with a Raspiberry Pi 3 computer and software image. The Bronze version does not come with a computer. Two 12v SLA (Sealed Lead Acid) batteries should be purchased separately. An allen wrench (for M6 bolts) will be included in the shipping box. In addition a small Phillips (cross point) screw driver may be needed for mounting the Raspberry Pi camera.


#### Step 1 - open the box


 ![Shipping Box](unb1.JPG)

 Inside the box you will find the battery cables, brackets for the cover plate, fasteners, and a cover plate.


 ![Components](unb2.JPG)

 After removing the robot, the cover plate is stored at the bottom of the shipping box.

 ![Cover plate](unb4.JPG)

 The Raspberry Pi 3 + SD image card can be installed if you have your own image with your own software (Silver and Gold). However a default image may already have been installed in the factory.
 ![Parts](unbparts.JPG)

  In the small parts bags, you will find fastners and  M4 and M2 Allen wrench that fits the included fasteners. The additional sensors (Silver and Gold versions) are wrapped separately.


 ![RPi 3 installed](unb7.JPG)

 The front and back brackets can be installed using the brackets require a M4 hex Allen wrench. We suggest an extra long (6 cm). The other included fasteners are M3 (M2 hex wrench) and a small Phillips screwdriver for Raspi Cam attachment. [See the detailed section on camera and sensor installation.](camera_sensors)


#### Brackets

![Front](camfront.jpg)

Front Bracket with Camera.  The power switches are system above the "U" in Ubiquity, and wheels above the "y'. The charging port is between the two switches. Switches light up when on. The on position is with the switch extended out, the left (closest to the wheel, turns on the system power, and the right most switch enables power to the wheels. Both buttons should be lit. It is a major error to attempt to operate the robot with the power to the wheels off. Commands will be stored by the robot and then when power is enabled, the robot may move unexpectedly. Installing the camera is discussed separately.

The Motors are connected next. This should be done at the factory, If they are detached, there are arrows on the connectors that (-> <-) show the alignment. These connectors are sometimes hard to insert and separate, because hard to grip them.


![Motors to MC](unb5.JPG)  

Finally the batteries are connected. The red lead from battery 1 to positive, the black from ground to ground on battery 2, and the yellow to connect the negative of battery 1 to the positive of battery 2. There are cables for both spade type and screw type battery terminals. A 24 volt battery charger is included in the package (Photo not available). The recommended batteries are of the type specified by UB12xxx  where xxx specifies Amp Hours.  Commonly UB1250, UB1290, or UB12150 are used.
Since it is unknown what size and shape the batteries will be it is the user's reponsiblity to see thay are secured in the chassis by the use of straps or packing material.

<!-- *{TODO: Somewhere there needs to be a discussion of what size batteries to use.  The spade connector sizes need
to be specified.  The user should be prepared for a current inrush spark? (not sure that this still occurs on initial battery insertion)  Is there a strap to hold the batteries down?  How is it installed? }*-->

![Final](unb-bat.JPG)

#### The Real-Time Clock battery
There is also a coin cell battery on the back of the circuit board, it is a CR2032.  This provides power to the real-time clock, which is essential.  If this battery is not installed, obtain one and install it. Insert the battery with the lettering side up.

![Battery Holder](battery_holder.png)

A video of the unboxing process is available:  [Video](https://youtu.be/pF38kFOl0Ic)

<<[back](ix_quick_start)- - - - - - - - - - [next](logitech)>>
