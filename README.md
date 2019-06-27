*led&Digital I/O
void setup()
{
   pinMode(6,OUTPUT); 
   pinMode(9,OUTPUT);
   pinMode(13,OUTPUT);
}

void loop()
{
    digitalWrite(6, HIGH);
    delay(1000);
    digitalWrite(6, LOW);
    delay(1000);
    digitalWrite(9, HIGH);
    delay(10);
    digitalWrite(9, LOW);
    delay(10);
    digitalWrite(13, HIGH);
    delay(100);
    digitalWrite(13, LOW);
    delay(100);
}
