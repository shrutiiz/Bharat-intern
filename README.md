# Bharat-intern

# CAR PARKING:

The components are as follows:

Arduino board (e.g., Arduino Uno, Arduino Nano, etc.): The main microcontroller that runs the code and controls the other components.

Ultrasonic sensor: It consists of two components - a transmitter (triggerPin) and a receiver (echoPin). The sensor measures the time taken for an ultrasonic pulse to travel from the transmitter to an object and back to the receiver, which is then used to calculate the distance of the object from the sensor.

LCD display: It is used to show the status of the parking spot (whether it is occupied or vacant). The LCD is connected using the LiquidCrystal library and is initialized with the pin configuration (12, 11, 5, 4, 3, 2).

Servo motor: The servo motor is used to simulate the barrier/gate of the parking spot. It is connected to the servoPin (6) and controlled using the Servo library.

These components work together to create a basic smart parking system. The ultrasonic sensor detects the presence of a vehicle in the parking spot, and the LCD display shows the status of the spot. If the spot is occupied, the barrier/gate is closed using the servo motor. If the spot is vacant, the barrier/gate is opened.


# AIR MONITORING SYSTEM:

Components needed:
Arduino Uno board
MQ-135 air quality sensor
LCD display (16x2 or 20x4)
Potentiometer (to adjust the contrast of the LCD display)
Jumper wires
Wiring Connections:

Connect the VCC pin of the MQ-135 sensor to the 5V pin of Arduino.
Connect the GND pin of the MQ-135 sensor to the GND pin of Arduino.
Connect the AOUT pin of the MQ-135 sensor to the A0 pin of Arduino.
Connect the VSS pin of the LCD display to GND.
Connect the VDD pin of the LCD display to 5V.
Connect the V0 pin of the LCD display to the middle terminal of the potentiometer.
Connect one end of the potentiometer to GND and the other end to 5V.
Connect the RS pin of the LCD display to digital pin 12 of Arduino.
Connect the Enable (E) pin of the LCD display to digital pin 11 of Arduino.
Connect the D4-D7 pins of the LCD display to digital pins 5-8 of Arduin
