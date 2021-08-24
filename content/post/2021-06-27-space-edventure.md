---
title: Space EdVenture, Game and Handheld Console
date: 2021-06-27
hero: "/images/space-edventure.jpg"
excerpt: A handheld game console soldered together and mounted in a 3D printed case, comes with a custom game written in C for the OLED screen. 
timeToRead: 8
authors:
- Tim Samuelsen

---
A handheld game console soldered together and mounted in a 3D printed case, comes with a custom game written in C for the OLED screen.
This is a project I worked on with Adam Wiktor and Ethan Kurteff in the ME218 course series at Stanford. You can find more detailed documentation on the hardware and software on our [project report website](https://space-edventure.weebly.com/). Including circuit schematics, state diagrams, code lisiting, and pseudocode.

|  Standard Laser |  Proton Bomb |   Super Laser |
:-------------------------:|:-------------------------:|:-------------------------:
![](https://media.giphy.com/media/wkOnQNY0NJps0oVl0I/giphy.gif) | ![](https://media.giphy.com/media/XgVBoQ4dubMzya32O8/giphy.gif) | ![](https://media.giphy.com/media/AXPEvCLGbYEeo2AI9d/giphy.gif)  |

Space EdVenture is an arcade style survival game in which the player must navigate through an endless asteroid field to rack up the high score. As the score rises the asteroids field grows thicker, resulting in a progressively increasing difficulty. The ship is equipped with an advanced weapons system to destroy asteroids in it's path. Picking up ammo along the way will greatly benfit the player. See above for a look at the Standard Laser, Proton Bomb, and Super Laser in action.

|  Space EdVenture Demo |
:-------------------------:|
{{< youtube id="3R-3P-1K4Go" title="Space EdVenture" >}}

The electronics are soldered onto a perfboard and mounted into a custom designed 3D printed case. The power supply can be connected to an outlet through the barrel jack or powered by a 9V battery for a completely wireless experience. The PIC32 microcontroller serves as the brains of the operation, interpreting user inputs and coordinating communication between subsystems. User input comes from an analog joystick, a capacitive touch sensor, and a mechanical button. The game is displayed on an OLED screen and uses RGB LEDs as indicators, both display subsystems are connected to the PIC32 using SPI. A 74AC244N buffer is used to shift clock and data signals to the 5v logic level required to drive the DotStar.

{{< figure src="/images/space-edventure-schematic.png#center" class="aligncenter" width="800em" title="Master Electrical Schematic" >}} 