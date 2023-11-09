# Roomba-Fixes
Roomba vacuuming robots often crash into walls (and sometimes animals) when cleaning surfaces. Included in this repository are 2 potential fixes to this problem I have created to optimize the cleaning power and pet-compatibility of the Roomba device. 

# Collision-Warning
One fault of Roomba vaccuming devices is that they do not have a warning system in place when they are approaching some delicate surfaces. For example, you wouldnt want your Roomba to rely on the default "bump and turn" (hit the object, turn, and continue forward) feature on your dog or cat. To fix this, Collision Warning senses objects and calculates the distance when are they 100, 30, and 5 CM away respectively. It then, based on the proximity, makes certain noises and lights up in various colors to warn your animal that is approaching. Do not worry though, if your sleepy dog does not move, the robot will still stop and play a loud, high pitched noise. No more vaccum-pet fiascos!

# Robot-Deflection
Okay, the animal example is obviously a little ridiculous. But, neverless, the Roomba still relies on the "bump and turn" method for navigating which can cause damage to wallboards, personal items on the floor, smaller items, etc. To fix this, Robot Deflection takes information from the sensors and calculates its distance to the object. It then, based on the angle it is approaching the item, stops when it is 10 CM away and turns at that exact angle. It will continue going forward without hitting the surface and display a blue light signaling it has detected the object and successfully avoided it,

# Notes
These functions work with and were produced using the Roomba Combo® i5 Robot Vacuum.
Thank you to Dr. Rodrigo Borela for your help!
