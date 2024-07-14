Arduino Traffic Light Control Mini Project 

Arduino Traffic Light Control Mini Project is a fun and educational project that teaches kids and beginners how to use Arduino boards to control traffic lights.
By using sensors and programming, you can make the traffic lights change colors just like real ones you see on the road. 
This project is a great way to learn about electronics, programming, and how traffic lights work in a hands-on and engaging way.
So grab your Arduino board and start building your own traffic light control system today!

 Write the code for Arduino Traffic Light Control Mini Project 

 int red = 9;
 
int yellow = 8;

int green = 7;

void setup(){

  
  pinMode(red, OUTPUT);
  
  pinMode(yellow, OUTPUT);
  
  pinMode(green,  OUTPUT);
  
}

void loop(){

digitalWrite(red, HIGH);

 delay(15000);
 
digitalWrite(red,  LOW);
  
  digitalWrite(yellow, HIGH);
  
delay(1000);

  digitalWrite(yellow,  LOW);
  
delay(500);

  digitalWrite(yellow, HIGH);
  
delay(1000);

  digitalWrite(yellow,  LOW);
  
delay(500);

  digitalWrite(yellow, HIGH);
  
delay(1000);

  digitalWrite(yellow,  LOW);
  
delay(500);
  
  digitalWrite(yellow, HIGH);
  
delay(1000);

  digitalWrite(yellow, LOW);
  
delay(500);
  
  digitalWrite(yellow, HIGH);
  
delay(1000);

  digitalWrite(yellow, LOW);
  
delay(500);
  
digitalWrite(green, HIGH);

delay(20000);

digitalWrite(green,  LOW);


digitalWrite(yellow, HIGH);

delay(1000);

  digitalWrite(yellow,  LOW);
  
delay(500);

  digitalWrite(yellow, HIGH);
  
delay(1000);

  digitalWrite(yellow,  LOW);
  
delay(500);

  digitalWrite(yellow, HIGH);
  
delay(1000);  

  digitalWrite(yellow, LOW);
  
delay(500);
  
  digitalWrite(yellow, HIGH);
  
delay(1000);

  digitalWrite(yellow, LOW);
  
delay(500);
  
  digitalWrite(yellow, HIGH);
  
delay(1000);

  digitalWrite(yellow, LOW);
  
delay(500);
  
}
