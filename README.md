# LED-lighting-
This is a set of programs to turn a light on and start a blinking light sequence on a simple LED circuit
int seconds
 int redLEDPin = // enter LED Pin number here ;
 int blueLEDPin = // enter LED Pin numher here ;
 int greenLEDPin = // enter LED Pin numer here ;
 void setup () {
  // put your setup code here to run once;
 seconds = 0 ;
 Serial.begin(9600);
 pinMode(redLEDPin, OUTPUT);
 pinMode(blueLEDPin, OUTPUT);
 pinMode(greenLEDPin, OUTPUT);
 }
 void loop () {
  //vput your main code here, to run repeatedly:
 digitalWrite(redLedPin, HIGH);
 digitalWrite(greenLedPin, HIGH);
 delay(500);
 digitalWrite(redLedPin, LOW);
 digitalWrite(greenLedPin, LOW);
 digitalWrite(blueLedPin, HIGH);
 delay(500);
 digitalWrite(blueLedPin, LOW);
 digitalWrite(greenLedPin, HIGH);
 delay(500);
 digitalWrite(greenLedPin, LOW);
 }
