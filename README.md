# Arduino Robotics, Summer 2014

This class repository contains homework assignments, useful guides, and code for "Arduino Robotics" at CCA, summer 2014.

### Monday, June 2, 2014

Lecture:
- Introduction
- Discussion of goals, projects, robots, Arduino
- Lots of digressions into very technical topics, including binary, coordinate systems, and trigonometry. (We went very quickly over these topics -- don't worry if they didn't make super much sense. We'll talk more about these topics in the future, and lots of stuff will start to make sense once we get hands-on.)

Hands-on:
- Arduino IDE
- Breadboard

Videos:
- Basic robots
    - [Coffee-can robot](http://www.youtube.com/watch?v=b0mIshBIbvI#t=24)
    - [Tree-climbing robot](http://www.youtube.com/watch?v=zkpH1BjD6Wc)
    - [Self-balancing robot](http://www.youtube.com/watch?v=Tw9Jr-SPL0Y)
    - [Insect robot](http://www.youtube.com/watch?v=tOsNXg2vAd4#t=120)
    - [Treadbot](http://www.youtube.com/watch?v=YblSltHDbIU)
    - [Velociraptor robot](http://www.youtube.com/watch?v=lPEg83vF_Tw)

- Drink-makers
    - [Textspresso](http://www.youtube.com/watch?v=kx9D74t7GD8#t=89)
    - [The Inebriator](http://www.youtube.com/watch?v=WqY7fchs7H0)

- Art bots
    - [Arc-o-matic](http://vimeo.com/57082262#at=130)
    - [Robo Faber](http://vimeo.com/78771257)
    - [Eggbot](https://www.youtube.com/watch?v=w4cdbV2oaEc)

- Computer Numerical Control (CNC)
    - [Shapoko / tinyg](http://www.youtube.com/watch?v=pCC1GXnYfFI#t=11)
    - [Makerbot Replicator](http://www.youtube.com/watch?v=NAbiAzYhTOQ)

- Music
    - [Laser harp](http://www.youtube.com/watch?v=sLVXmsbVwUs#t=20)

- Vacuuming
    - [Roomba](https://www.youtube.com/watch?v=0DNkbZvVYvc)


#### Homework 1 (due Wednesday, June 4, 2014)

- [Download](http://arduino.cc/en/Main/Software) and [install](http://arduino.cc/en/Guide/HomePage) the Arduino IDE (get version 1.0.5, not 1.5!) on your laptop.
- Watch the first episode of [AdaFruit's Circuit Playground](https://www.youtube.com/watch?v=exlRjDKHGRg)
- Read through the [Blink tutorial](http://arduino.cc/en/Tutorial/Blink) that we talked about in class.
- A bit more complicated: read through the [Digital Read Serial code](http://arduino.cc/en/Tutorial/DigitalReadSerial) -- it'll probably feel very complicated, don't worry about that.
- Prof. Shiloh has a [sheet of basic math exercises](http://teachmetomake.com/wordpress/wp-content/uploads/2012/09/basicMathExercises.pdf). Try to do one out of every five exercises. Bring questions to Wednesday's class.
- Bring your laptop on Wednesday!


### Wednesday, June 4, 2014

Lecture:
- Introduction to Arduino software & hardware
- Basic circuit theory, discussion of common electronic components and circuits

Hands-on:
- Using the multimeter
- Blink with Input
- `Serial.println`
- [Electronic Etch-a-Sketch](http://workshopweekend.net/arduino/projects/etch_a_sketch)

Resources:
- [Datasheet for your LED](http://www.jameco.com/Jameco/Products/ProdDS/2006730.pdf)
- [Lecture slides](arduino-intro.pdf)


### Thursday, June 5, 2014

Lecture:
- Motors
- Programming

Hands-on:
- Brushed DC motors
- Servos
- Arc-o-matic


#### Homework 2 (due Monday, June 9, 2014)

- Research intersting kinetic or electromechanical systems, like the ones in the videos we saw the first day (see Monday's entry above for links to the videos). Find some new ones, and post 5 [here](https://github.com/zamfi/cca-arduino-summer-2014/issues/1).
- We'll spend some time next week building a mechanism like the ones in the [mechanisms handout](machinations-mechanisms.pdf). Design a mechanism to build next week, and be prepared to talk about on Monday. Start prototyping it, using wood, cardboard, paper, whatever you have. Doesn't have to be completely functional.


### Monday, June 9, 2014

Lecture:
- Presentations on Mechanisms

Hands-on with motors:
- Work through the [Adafruit DC motor reversing tutorial](https://learn.adafruit.com/adafruit-arduino-lesson-15-dc-motor-reversing/overview).
- This [Arduino Cheat Sheet](arduino-cheat-sheet.pdf) might be useful.
- Here's a [cheat sheet for the L293D DC motor driver](arduino-dc-motors-l293d.pdf).
- For a refresher on servo motors, see the [sweep tutorial](http://arduino.cc/en/Tutorial/sweep) on the Arduino site.

#### Homework 3 (due Wednesday, June 11, 2014)

- Bring any materials you need to complete your mechanism. Be prepared to make substantial progress on Wednesday. Remember, one goal is to motorize your mechanism, either with a servo motor or with a brushed DC motor.
- See the resources list below for good places to get materials we didn't have in lab.


### Wednesday, June 11, 2014

Lecture & hands-on:
- Sensors
    - Light-dependent resistor
	  - Ultrasonic rangefinder [library](http://freecode.com/projects/hc-sr04-ultrasonic-arduino-library)
    - [Capacitive Sensing](http://playground.arduino.cc/Main/CapacitiveSensor)

### Thursday, June 12, 2014

Hands-on:
- Mechanism building!
Lecture:
- Review of material so far -- Ohm's law, voltage, current, resistance, calculating LED resistor.


Review materials:
- [Current-limiting Resistor for LED](https://www.sparkfun.com/tutorials/219)
- [Voltage divier](https://learn.sparkfun.com/tutorials/voltage-dividers/ideal-voltage-divider)
- [Servo motor vs. DC motor](http://handyboard.com/hb/faq/hardware-faqs/dc-vs-servo/)
- Know how and when to use `digitalRead`, `digitalWrite`, `analogRead`, and `analogWrite`. The [Arduino reference] may be helpful.

## Resources

Nearby places to get materials, courtesy of Prof. Shiloh:
- [Arch](http://www.archsupplies.com/): Art supply store. Easy walking distance.
- [Center Hardware](http://www.centerhardware.com/): Hardware store. Easy walking distance.
- [Tap Plastics](http://www.tapplastics.com/): All sorts of plastics, resins, and mold making supplies and tools. Laser cutting service.
- [SF Laser](http://sflaser.io): Low-cost laser cutting service, next to Tech Shop.