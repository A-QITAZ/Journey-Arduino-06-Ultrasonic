# Arduino Ultrasonic Distance Measurement

A simple Arduino Uno project to measure distance using an HC-SR04 ultrasonic sensor.

About : In this project, an HC-SR04 ultrasonic sensor is used to detect the distance of objects. The Echo pin is connected to digital pin 3, and the Trigger pin is connected to digital pin 4. The Arduino emits an ultrasonic pulse and uses the `pulseIn()` function to measure the duration of the returning echo, which is then converted into centimeters. The code is designed professionally using the `millis()` function to create a non-blocking 100ms delay, allowing the microcontroller to execute other tasks simultaneously without freezing.

Components :
* Arduino Uno
* 1 HC-SR04 Ultrasonic Sensor
* Breadboard
* Jumper wires

Tools :
* Arduino IDE
* C/C++
* Tinkercad Circuits

A-QITAZ Mechatronics Engineering Student :)
