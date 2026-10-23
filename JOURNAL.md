---
title: "Ir Sensor Module Devlog"
author: "Ryan :D"
description: "Building a simple test Ir Sensor Module, as a step towards my bigger 6 module version as a step towards my Robocup Comp Robot”
created_at: "2026-03-20"
---

# Oct 25 : Building First Test
The first module has been completed, time summary below is an accumulation of multiple days.
Finished soldering the two legs on the side of the Trct 5000, it is now able to be properly wired up.
All wires that are to connect to Arduino are soldered
Wires have been connected to Arduino properly
Uploading code
Code upload failure
CLOSES IT AND OPENS IT AGAIN
Code upload success

Ir sensor test module resulting values:
Pointing away: 3-8
Pointing towards: 740-860

Next steps:
Identification of certain colors, eg. Green
Figuring out how to ATTACH DAMN IMAGES


Time also contains previous 3 Iterations, Which are undocumented, who’s times have been quartered, and the planning stages, which have also been quartered.


Planning - 2h/4 - ~30Mins
V1 - 8 Hours/4 = 2h
V2 - 11 Hours/4 = ~2h
V3 - 6 Hours/4 = ~1h

Current Progress - 1h
**Total time spent: 6 hours 30 minutes**



# Oct 26 : Soldering Prep
30 mins - So the first test has been completed and is working properly, now, I’m just trying to prep to start soldering the bigger module, I already finished my schematic which took roughly half an hour, I understand if my time gets cut down, but I am yet to learn how to do everything - 

MY PHOTOS ARE IN THIS DRIVE: https://drive.google.com/drive/folders/14RNFrdZYEur0siDXHzPnogz5Q2L4HWWF

18 mins - I’ve placed most of the components, but am getting rather confused on which leg of the transmitter and reciever is the power and ground etc.

12 mins - Turns out the transmitter’s shorter leg is it’s power, which is interesting, and I’m going to have to spend another couple mins redoing this.

Components are placed, but I’m just gonna spend a while doing homework, then come back to this.

Damn I was worried about if I don’t get full hours to either write in decimal or to just write minutes but I got a perfect hour of work in.

**Total time spent: 1h**


# Oct 26 : Soldering Prep P2
20 mins - I was just testing on how to block the IR sensors from interacting with each other when they are right next to one another, but due to some sort of glitch, I’m currently trying to patch up the errors.

I think I know the error, but I’m not sure how to fix it, the receiver seems to be working perfectly, while the transmitter seems to work, but doesn’t really do much

After changing some of the variable resistor values to no avail, I’ve decided to assume I’ve somehow burnt out the transmitter, and am going to solder on a new one.

17 mins - In the drive is a cropped times-lapse of me soldering on the replaced Ir Sensor under “26 oct part 2 …”

Changing it didn’t seem to do anything, with the unreplaced transmitter, I went from values 3-5 to 8-9, now, with the new transmitter its going from 0-1 to 25-32, which, while it is an improvemnt, is far from my original results, therefore, I’m going to try replacing the reciever.

7 mins - Receiver is replaced, testing for results will begin now. Nope, that didn’t work, results are still roughly the same, I’m not quite sure what’s wrong. Maybe it’s one of the Variable Resistors malfunctioning? Or something isn’t properly connected, I’m going to do some testing.


**Total time spent: 1h**





