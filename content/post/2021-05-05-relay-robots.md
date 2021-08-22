---
title: Now this is Pod Racing, Autonomous Relay Robots
date: 2021-05-05
hero: "/images/relayrobots.jpg"
excerpt: Robots that autonomously run a relay with an IR based navigation system. Coded in C using hierarchical state machines running on PIC32 MCUs.
timeToRead: 10
authors: 
- Tim Samuelsen

---
Robots that autonomously run a relay with an IR based navigation system. Coded in C using hierarchical state machines running on PIC32 MCUs. This is a project I worked on with Adam Wiktor and Chris Barresi in the ME218 course series at Stanford. You can find more detailed documentation on the hardware and software in our [project report website](https://hotgluehope.weebly.com/). Including circuit schematics, state diagrams, code lisiting, and pseudocode.

Our team was tasked with building 3 robots to autonomously run a relay race for 2 minutes and 18 seconds. The track was a 2.5 meter diameter circle with two handoff boxes on either side of the circle 2 meters apart. We designed each robot with three subsystems run on PIC32 MCUs. 
* Navigation: Two IR sensing phototransistors soldered to signal conditioning boards which implemented op-amps, comparators and AC coupling to ensure a clean and reliable signal. An IR beacon board emits a homing signal for the robots to locate each other. 
* Locomotion: two-wheel differential drive layout, with power coming from two DC gearmotors running in locked anti-phase drive
* Master which implements the hierarchical state machine and acts as the brain of the operations. 

|  Handoff and Exit |  Traversing the Track |
:-------------------------:|:-------------------------:
![](https://media.giphy.com/media/2Vco2b407VFqqLjDFJ/giphy.gif)  | ![](https://media.giphy.com/media/f315xgjq2cxD0e0tiv/giphy.gif)

Etiam id quam venenatis, laoreet lacus id, tempor ipsum. Morbi in consectetur velit, nec finibus ex. Donec tempus et velit vel interdum. Integer eget nisl scelerisque, sagittis justo et, porttitor turpis. Maecenas eu diam tincidunt, sodales urna convallis, rhoncus elit. Maecenas pulvinar euismod dignissim. Nullam vestibulum libero a nisl imperdiet varius. Fusce lectus orci, finibus nec ipsum commodo, tempor sagittis tellus.

|  Pod Racers in Action |
:-------------------------:|
{{< youtube id="PLo9WaXOa68" title="Full Relay" >}}