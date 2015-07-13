> Time table:

>* Research: monday 22 June 2015
* First run: Thuesday 23 June 2015 (nes, part of leap)
* Second run: Wednesday 23 June 2015 (leap, tweaking, final testing)
* Creating a nice browser UI (with speaking ??): Thursday 24 June 2015

###### Side project: What happens when you combine a vintage NES controller, a leap motion and a drone?

## Let's control a drone vintage style!

This projects builds on my project: **Arduino-nes**

## The start
A few months ago I connected my vintage NES controller to an arduino. It was just for fun and I didn't know what to use it for but when I saw a drone I knew what my next project had to be. Wouldn't it be awesome to control a drone with a good old fashion controller? So that what I worked on this last week.

#### The drone
I borrowed the AR-Drone for school for a week.
The AR-drone is a the drone node-copter uses for their awesome projects. If you don't know how they are you should check them out! The drone can be controlled by node with the ar-drone package. I just installed the package in an empty project an I just start playing around. 

##### Connect to the drone
The drone will create its own wifi network so you could fly it everywhere. After I connected to the network I just ran the REFL example that comes with ar-drone. Within 10 minutes from unboxing the drone I could control it from my laptop! However I found it is pretty hard to control a drone inside a building with the command line.

##### Ar-drone
Testing a lot of commands, created a very simple ui for controlling the alititude and some of the steering. I recorded some of the max values so I could see how the drone reacted.

##### The nes controller.
Now I got the drone working I started working on the nes controller. I downloaded my own arduino-nes package and attached the nes to my arduino. I sat and just played around a little to figure out how I could control the drone with this 8 button controller.

##### The controlls
I figured I would use the arrow buttons for steering as that is an abvious thing to do. And I would use the A and B button to control the alititude of the drone. Now to let the drone rotate clockwise and counter clockwise I figured why not using the select and start buttons. 

I had the buttons to control the drone figured out now I justed needed some combinations to let the drone takeoff and land. I used the combination of the select and start buttons because you wouldn't let the drone rotate clockwise and counter clockwise at the same time right? To flip the drone I used a combination of the select and the A button. 

##### Let's make the controls feel natural
Commands, message, status, battery, buttons pressed, drone values (up,down, etc) Used socket.io to make it real time.

##### Multiple controllers?
Leap motion, modular programming for multiple controllers.

##### Drone object.
A drone object before the ar-drone client object.
Values, messages/logs, etc. Max, min values, phisics/vectors.

##### Testing


##### Adjusting


##### Let's have some fun!


##### The final setup.
Code -> github
Pictures
Movie ???


Thank you for reading,  
Danny van der Jagt


Let me know what you think in the comments!
Do you have a fun project, I would love to see it!

