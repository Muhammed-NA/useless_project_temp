🎯
Basic Details
Team Name: Why are we here
Team Lead: Irfan Mohammed - Ace college of engineering 
Member 2: Muhammed NA - ACE College of engineering 

Project Description
A robotic trash can that actively follows you around the room, patiently waiting to be useful — and then dodges, and slams its lid shut when you actually try to throw something in it. It also mocks you on a screen and keeps score of your failures.
The Problem (that doesn't exist)
Trash cans are far too easy to use. everyone moves on with their day. Where's the challenge? Where's the humiliation? Society has normalized successful waste disposal, and someone needed to put a stop to it.
The Solution (that nobody asked for)
A trash bin on wheels that uses ultrasonic sensors to hunt you down and stay close by like a loyal, well-meaning pet — building false trust — right up until you try to actually use it for its one job. At that exact moment it panics, reverses, spins away, snaps its lid shut, blares a mocking tune, and flashes "U SUCK / U NUB" on its built-in LCD, complete with a running tally of how many times you've failed.
Technical Details
Technologies/Components Used
For Hardware:
Arduino Uno
2x HC-SR04 ultrasonic distance sensors (one for tracking you, one for detecting a throw attempt near the opening)
L298N dual H-bridge motor driver
2x DC gear motors + wheels (differential drive chassis)
SG90 micro servo (snaps the lid shut)
Passive piezo buzzer (alarm + mocking melody, generated with tone() — no audio files needed)
JHD162A 16x2 character LCD (HD44780-compatible) — live status + taunts + miss counter
7.4–9V battery pack for motor power
Breadboard, jumper wires, chassis/trash can body
Tools required:
Arduino IDE
Screwdriver set, wire strippers, hot glue gun
Multimeter (for power/wiring debugging)

![Build](Add photos of build process here) — Chassis assembly, sensor mounting (front for tracking, top for opening detection), motor driver wiring, LCD + buzzer integration.
![Final](Add photo of final product here) — Completed bin: mobile chassis, sensors mounted, lid mechanism, LCD display visible on the front.
Project Demo
Video
[Add your demo video link here] — Shows the bin following a person, then dodging and slamming its lid shut the moment someone tries to throw trash in, with the LCD flashing "U SUCK / U NUB" and the buzzer playing its mocking tune.
Additional Demos
[Add any extra demo materials/links]
Team Contributions
Muhammed NA: [Hardware assembly,]
Irfan Mohammed: [e.g. Arduino firmware — state machine, sensor filtering, motor control, wiring]
