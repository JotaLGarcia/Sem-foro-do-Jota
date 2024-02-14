# Semaforo-do-Jota
https://www.tinkercad.com
// C++ code
//
void setup()
{
  pinMode(13,OUTPUT);//Amarelo (1)
  pinMode(12,OUTPUT);//Verde (1) 
  pinMode(11,OUTPUT);//Vermelho (1)
  pinMode(10,OUTPUT);//Amarelo (2)
  pinMode(9,OUTPUT);//Verde (2) 
  pinMode(8,OUTPUT);//Vermelho (2)
}

void loop()
{
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,HIGH);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,LOW);
  delay(5000); 
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,HIGH);
  digitalWrite(10,HIGH);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  delay(5000);
  digitalWrite(13,LOW);
  digitalWrite(12,HIGH);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,HIGH);
  delay(5000);
  digitalWrite(13,HIGH);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,HIGH);
  delay(5000);
}
