void setup() {
  // LED_BUILTIN = 2 doesn't work for ESP-01S. Needs to be "1"
  pinMode(1, OUTPUT);// Initialize the BUILTIN_LED pin as an output  
  pinMode(0, OUTPUT);// Initialize the RELAY pin as an output
  digitalWrite(0, HIGH);
}

// the loop function runs over and over again forever
void loop() {
  
  for (int i = 0; i <= 5400; i++)  //6hours  -  60 360 * 60  21600 / 4 =5400 6
      
      {
  digitalWrite(1, HIGH);   // Turn the LED on - LOW
  delay(1000);             // Wait for a second
  digitalWrite(1, LOW);    // Turn the LED off - HIGH
  delay(1000);             // 4 seconds
  digitalWrite(1, HIGH);
  delay(1000);                      
  digitalWrite(1, LOW);  
  delay(1000);
  digitalWrite(1, HIGH);
      }
 
  digitalWrite(0, LOW);
  delay(100);  
  digitalWrite(0, HIGH);  
}
