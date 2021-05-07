int led1 = D0;
int led2 = D7;

void dot()
{
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    delay(200);
    
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    delay(500);
}

void dash()
{
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    delay(700);
    
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    delay(500);
}

void setup()
{
    pinMode(led1, OUTPUT);
    pinMode(led2, OUTPUT);
    
}

//My First Name is A-Y-E
void loop() 
{
    dot();
    dash();
    
    delay(700);
    
    dash();
    dot();
    dash();
    dash();
    
    delay(700);
    
    dot();
    delay(2000);
    
    digitalWrite(led2, HIGH);
    delay(100);
    digitalWrite(led2, LOW);
    delay(100);
    digitalWrite(led2, HIGH);
    delay(100);
    digitalWrite(led2, LOW);
    delay(100);
    digitalWrite(led2, HIGH);
    delay(100);
    digitalWrite(led2, LOW);
    delay(100);
    digitalWrite(led2, HIGH);
    delay(100);
    digitalWrite(led2, LOW);
    delay(3000);

}
