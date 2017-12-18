# p-and-e-final-project-fall-2017

Blood Oxygen Level Monitor Ring

I propose to build a SpO2 (Blood Oxygen Level) monitoring ring, allowing user to know their current health condition.


Summary

Blood oxygen level is a crucial value for health, its closely related to brain activities and physical performance. Users with asthma, myself as an example, often have compressed chest and tired of breathing, therefore holds breath unconciously and drops Spo2 dramatically. Healthy people usually rated 95-100%, dropping below 95% is abnormal, and below 90% could be potentially harmful over time. It is common for many of the athletes / fitness enthusiast to experience short of breath, because recruiting muslce fibers requires large amount of oxygen, insufficent oxygen due to breathing problem will cause dizziness and lower physical performance, and eventually lead to injury. Many amateurs, even coaches would have their athletes rest a fixed amount time between sets, from 30s to 2 minutes, this rest time between sets is often determined the goals of the athletes (muscle building/ power training), which often will not be enough for users with breathing problems. The SpO2 ring can help the users determine when their body is ready to work, both physically and mentally. Ultimately the ring will vibrate and signal the user when their Spo2 level has reached an ideal level. 


Component Parts

1. SparkFun Particle Sensor Breakout - MAX30105
2. Arduino
3. Breadboard
4. Jumperwires
5. soldering iron

![alt text](https://cdn.sparkfun.com/r/600-600/assets/learn_tutorials/5/7/7/Wires_into_MAX30105.jpg)

The sensor contains 5 pin labels, INT/GND/5V/SDA/SCL. (Ignore INT pin)
Connect each labeled pin to the coordinated Arduino slots 
5V pin of the sensor with 5v on arduino (minimun of 3v if no 5v) etc, see diagram below.

![alt text](https://cdn.sparkfun.com/r/600-600/assets/learn_tutorials/5/7/7/Fritzing_Hookup.jpg)

Source from www.cdn.sparkfun.com

Challengers

The sensor itself was totally inaccurate, the readings of bloodpresure and Spo2 level was unstable. Not enough resource about this sensor, only found one code avalible. 
The most challenging part of the project was understanding how does the code works, and how to make it work better.
After all, if the sensor worked as expected, fitting itself onto a finger with the right amount of constant pressure will be also be a challenge. If this monitor/sensor is used during excercise, hyperaemia which is caused by increase of blood flow, will enlarge muscle tissues and changed the pressure of the sensor against the skin once again.


Timeline

Week 1 : Ordered parts (took 2 weeks to arrive due to thanksgiving)
week 2 : Project research (more details on the hardware)
week 3 : sensor hook up+coding
week 4 : refine code
week 5 : present 

Final Work


![alt text](https://github.com/EricSihongL/p-and-e-final-project-fall-2017/blob/master/IMG_1041.jpg?raw=true)
![alt text](https://github.com/EricSihongL/p-and-e-final-project-fall-2017/blob/master/IMG_1042.jpg?raw=true)

References 
https://www.maximintegrated.com/en/products/analog/sensors-and-sensor-interface/MAX30105.html
https://learn.sparkfun.com/tutorials/max30105-particle-and-pulse-ox-sensor-hookup-guide





