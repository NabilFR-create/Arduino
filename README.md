# Arduino
Arduino Alphabet Series "D"

This is the code for a text to brail converter. This system mimics a brailie push system with solenoids an mimics it using LEDs. 
Visual for how this looks like:
![image](https://github.com/user-attachments/assets/5578a17d-d6f6-4616-85f0-4454beeb7d8c)

Code: 

// C++ code
void setup()
{
  pinMode (13, OUTPUT);
  pinMode (12, OUTPUT);
  pinMode (11, OUTPUT);
  pinMode (10, OUTPUT);
  pinMode (9, OUTPUT);
  pinMode (8, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s) digitalWrite(LED_BUILTIN, LOW);
  
  digitalWrite(12, HIGH);
  delay(1000);
  
  digitalWrite(11, HIGH);
  delay(1000); // Wait for 1000 millisecond(s) digitalWrite(LED_BUILTIN, LOW);
  
  digitalWrite(10, LOW);
  delay(1000);
  
  digitalWrite(9, LOW);
  delay(1000);
  
  digitalWrite(8, LOW);
  delay(1000);
  

}
