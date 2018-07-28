# TOR
teste
comandos:
int pinIn = 2;
int led13 = 13;
 
volatile int buttonState = LOW;

void setup()
{
  pinMode (pinIn , INPUT);
  pinMode (led13, OUTPUT);
}
void loop()
{buttonState = digitalRead(pinIn); //pino2
 
 if (buttonState == HIGH) {
   //
   digitalWrite(led13,HIGH);
   //
 } else{
   //
   digitalWrite(led13,LOW);
 }
 delay(10);
}
