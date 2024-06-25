#include “ArduinoLearningBoard.h”

Servo myservo; // create servo object to control a servo

int pos = 0; // variable to store the servo position

void setup()
{
myservo.attach(2); // attaches the servo on pin 2 to the servo object
myservo.write(90); // Center Servo
delay(3000); // Delay 3 seconds
}

void loop()
{
for(pos = 0; pos <= 180; pos++) // goes from 0 degrees to 180 degrees
{
myservo.write(pos); // tell servo to go to position in variable ‘pos’
delay(10); // waits 10ms for the servo to reach the position
}
for(pos = 180; pos >= 0; pos — ) // goes from 180 degrees to 0 degrees
{
myservo.write(pos); // tell servo to go to position in variable ‘pos’
delay(10); // waits 10ms for the servo to reach the position
}
}
