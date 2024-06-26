# Arduino-Self-Driving-Car
This is part of a giant project on fully autonomous car. This project is self study of creating a arduino uno based self driving car.
This lessons are from YOUTUBE channel SCIENCE BUDDIES.
Link to playlist:

https://youtube.com/playlist?list=PLlBVuTSjOrckzVWHWOYAkyKoQZhmoqH1S&si=hYOSTgE0W4nVKrid

Lesson_1:
Controlling the DC motors in forward and backward motion and stopping it.
========================================================================================

Components Required are:

![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/4f753a37-cf73-474b-a313-128aadf4bdd3)

The circuit diagram for this part is attached as below.
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/bc00ccd9-e149-461e-9f06-8583826f17a7)

The schematic diagram for the circuit is as below:
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/0c3c3341-9713-4e65-a28f-9c33b75bd73d)

The TINKERCAD link to this part is as below:
https://www.tinkercad.com/things/eHN8Ka1tjP4-grand-crift-borwo

The Output Video is as below:
https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/09d4132a-fedf-4679-8c74-2049de6cc789




Lesson_2:
Controlling the DC motors in forward and backward motion and turning left and right and stopping.
========================================================================================

Components Required are:

![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/b53dc295-d6a9-4d11-939c-d16850d042f1)

The circuit diagram for this part is attached as below:
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/be316e8c-d1b9-4745-8c34-613548e8316b)



The schematic diagram for the circuit is as below:
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/b79416ae-0114-44c0-a935-b3a4a336e8ce)



The TINKERCAD link to this part is as below:
https://www.tinkercad.com/things/1dqA0yPc91p-copy-of-controlling-motor-forward-and-backward

The Output Video is as below:
https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/307574b6-367b-466a-8ea4-c5f073460132

Lesson_3:
Controlling the speed of the DC Motors in all forward,backward,right,left direction using analog write command
========================================================================================

The previous code is for the forward motion of the motors, but due to the internal resistance of the motors or unsymmetrical design of the real life car, there might be some 
errors that cause the car to disbalance and not move completely forward. We use the analog command to use PWM method to control the speed of the mototrs individually. It is a trial and error method to get the correct right and left speed of the car. Once we get the correct speed we inser then in the code as left_speed and right_speed.

Components Required are:

![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/9737bbf3-4d04-4ea6-968a-ba3297631774)

The circuit diagram for this part is attached as below:
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/c0fb1416-7ca5-42de-821e-a05e0649d655)

The schematic diagram for the circuit is as below:
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/45faf2a0-0aff-4695-8316-08c0bbf7bc03)

The TINKERCAD link to this part is as below:
https://www.tinkercad.com/things/lLZ1DY4hY3C-arduino-car-l3?sharecode=2iRYl9ByAPtlIzCGDlzI6xkF5IhevtN8CeGrkDWia84

The Output Video is as below:
https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/af4a147b-ace4-406b-8705-55ed020aacec


Lesson_4:
Using the ultrasonic sensor to detect objects and blink LED 
========================================================================================

Components Required are:

![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/b65129a6-4b76-4942-9749-138db78ddfa8)

The circuit diagram for this part is attached as below:
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/74bd95e8-59f9-4cc8-91ad-101c27f56a40)

The schematic diagram for the circuit is as below:

![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/0f5b0787-1cbf-4cb1-815c-a373844df402)

The TINKERCAD link to this part is as below:
https://www.tinkercad.com/things/esmkDhaWWXH-using-ultrasonic-sensor?sharecode=SNakASYRnn4Gz-oD-djRLVdOa5yZ-nAsvLd9B5JCYvE

The Output Video is as below:
https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/1a8317fd-652d-4e28-a62c-ff46b5038b0e

Lesson_5:
Object detection using Ultrasonic sensor and making an algorithm to move around the obstacle
============================================================================================
This code will help to detect obstacles in the way. Here only a simple case is used when the car detects an object it follows the following predefined path:
stop->turn right->move forward->turn left->move forward->turn left->move forward->turn right->move untill next object is detected

Components Required are:

![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/60bfc4e6-2e65-460f-af7c-64a8e0975e5a)

The circuit diagram for this part is attached as below.
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/5e8046ba-41e4-4a88-a90e-241e2cd98ae5)

The schematic diagram for the circuit is as below:
![image](https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/921e7a45-5456-4fa9-8ca0-3451b19e19a0)

The TINKERCAD link to this part is as below:
https://www.tinkercad.com/things/gyAEKhraVgw-arduino-car-l4?sharecode=O0ewfp8wHcU5zTxAFwvV4PYrQKPWl-8aL0FBwoPj9ko

The Output Video is as below:
https://github.com/PratyushShubh/Arduino-Self-Driving-Car/assets/148980412/9deefe5e-122e-4a01-934c-ffabe913a004








