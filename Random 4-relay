#include <Pushbutton.h>


#define RELAY1  6
#define RELAY2  7
#define RELAY3  8
#define RELAY4  9

Pushbutton button(13);

int kanal = 0;
int tid = 1000;
int tid2 = 500;


void setup() 
{

  digitalWrite(RELAY1, HIGH);
  digitalWrite(RELAY2, HIGH);
  digitalWrite(RELAY3, HIGH);
  digitalWrite(RELAY4, HIGH);

  pinMode(RELAY1, OUTPUT);
  pinMode(RELAY2, OUTPUT);
  pinMode(RELAY3, OUTPUT);
  pinMode(RELAY4, OUTPUT);

}

void loop() {

while (1)
{
  
int kanal = random (12);

   if (button.getSingleDebouncedRelease())
{
    switch (kanal) {
    case 0:
    delay(tid);
    digitalWrite(RELAY1, LOW);
    delay(tid2);  
    digitalWrite(RELAY1, HIGH);
    break;                
    case 1:
    delay(tid);
    digitalWrite(RELAY2, LOW);  
    delay(tid2);
    digitalWrite(RELAY2, HIGH);
    break;
    case 2:
    delay(tid);               
    digitalWrite(RELAY3, LOW);  
    delay(tid2);
    digitalWrite(RELAY3, HIGH);
    break;
    case 3:
    delay(tid);               
    digitalWrite(RELAY4, LOW);  
    delay(tid2);
    digitalWrite(RELAY4, HIGH);
    break;
    case 4:
    delay(tid);
    digitalWrite(RELAY3, LOW);
    delay(tid2);  
    digitalWrite(RELAY3, HIGH);
    break;                
    case 5:
    delay(tid);
    digitalWrite(RELAY4, LOW);  
    delay(tid2);
    digitalWrite(RELAY4, HIGH);
    break;
    case 6:
    delay(tid);               
    digitalWrite(RELAY2, LOW);  
    delay(tid2);
    digitalWrite(RELAY2, HIGH);
    break;
    case 7:
    delay(tid);               
    digitalWrite(RELAY1, LOW);  
    delay(tid2);
    digitalWrite(RELAY1, HIGH);
    break;
    case 8:
    delay(tid);               
    digitalWrite(RELAY2, LOW);  
    delay(tid2);
    digitalWrite(RELAY2, HIGH);
    break;
    case 9:
    delay(tid);               
    digitalWrite(RELAY4, LOW);  
    delay(tid2);
    digitalWrite(RELAY4, HIGH);
    break;
    case 10:
    delay(tid);               
    digitalWrite(RELAY1, LOW);  
    delay(tid2);
    digitalWrite(RELAY1, HIGH);
    break;
    case 11:
    delay(tid);               
    digitalWrite(RELAY3, LOW);  
    delay(tid2);
    digitalWrite(RELAY3, HIGH);
    break;                                                                
  }
}
}
}
