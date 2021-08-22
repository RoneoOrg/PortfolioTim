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

Our team was tasked with building 3 robots to autonomously run a relay race for 2 minutes and 18 seconds. The track was a 2.5 meter diameter circle with two handoff boxes on either side of the circle 2 meters apart. We designed each robot with three subsystems run on PIC32 MCUs; navigation, locomotion, and master. The navigation subsystem included two IR sensing phototransistors and an IR beacon board. By scanning for 

We equipped each robot with a navigation system comprised of a PIC32 MCU connected to two IR sensing phototransistors and an IR beacon board. The navi
With precise signal conditioning circuits and tuned software we 

|  Handoff and Exit |  Traversing the Track |
:-------------------------:|:-------------------------:
![](https://media.giphy.com/media/2Vco2b407VFqqLjDFJ/giphy.gif)  | ![](https://media.giphy.com/media/f315xgjq2cxD0e0tiv/giphy.gif)

Etiam id quam venenatis, laoreet lacus id, tempor ipsum. Morbi in consectetur velit, nec finibus ex. Donec tempus et velit vel interdum. Integer eget nisl scelerisque, sagittis justo et, porttitor turpis. Maecenas eu diam tincidunt, sodales urna convallis, rhoncus elit. Maecenas pulvinar euismod dignissim. Nullam vestibulum libero a nisl imperdiet varius. Fusce lectus orci, finibus nec ipsum commodo, tempor sagittis tellus.

Integer semper vulputate magna, at mollis sapien vulputate a. Sed vestibulum nunc vel dictum venenatis. Maecenas nec commodo nisi. Vestibulum volutpat mauris ac consectetur aliquet. Nulla finibus arcu ante, eu vehicula elit facilisis vel. Aenean tempus, elit sit amet tincidunt pellentesque, nibh eros dignissim libero, vel porta leo lacus a mauris. Interdum et malesuada fames ac ante ipsum primis in faucibus. Vestibulum malesuada, nibh vitae eleifend varius, eros mi ultricies velit, in porttitor felis metus nec felis.

Donec laoreet luctus pharetra. Pellentesque consequat nibh neque, a dapibus ipsum sagittis non. Duis leo orci, dictum non fringilla vitae, accumsan molestie est. Maecenas vehicula dui lacus. Curabitur et gravida tortor, sed bibendum nisi. Cras eleifend venenatis fermentum. Donec quis nibh a turpis egestas euismod. Nullam interdum arcu quis tellus sagittis imperdiet. Nam vel sem mi. Aliquam dapibus mollis enim nec scelerisque. Nunc sed finibus nisi.


|  Pod Racers in Action |
:-------------------------:|
{{< youtube id="PLo9WaXOa68" title="Full Relay" >}}