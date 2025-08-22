### Procedure

1.	Connect the IR Sensor to Arduino:
Connect the VCC pin of the IR sensor (U2) to the 5V pin of Arduino (U1).Connect the GND pin of the IR sensor to the GND pin of Arduino.Connect the OUT pin of the IR sensor to the D2 (Digital Pin 2) of Arduino.
2.	Connect the LED:
Connect the anode (positive leg) of the LED (D1) to Digital Pin 13 (D13) of the Arduino.Connect the cathode (negative leg) of the LED to one end of a 1kΩ resistor (R1).Connect the other end of the resistor to GND.
3.	Power the Circuit:
Make sure the Arduino is connected to your computer via USB or powered via a 5V supply.Verify that the IR sensor receives 5V and is grounded properly.
4.	Upload the Code:
Open the Arduino IDE and enter the code that reads the IR sensor and controls the LED.Verify the code and upload it to the Arduino Uno board.
5.	Test the Circuit:
Place an object in front of the IR sensor.If the object is detected (sensor output LOW), the LED turns ON.If no object is detected (sensor output HIGH), the LED stays OFF.
6.	Adjust and Observe:
Test the response by moving your hand or various objects near the IR sensor.Observe the LED behaviour and ensure it matches the sensor’s output.
