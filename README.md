int count=0;

void setup() {

pinMode(8,OUTPUT);

pinMode(2,OUTPUT);

put your setup code here, to run once:

}

void loop() {

int A=digitalRead(8);

if (A==HIGH)

count=count+1;

if (count%2==1)

{digitalWrite(2,HIGH);

}

else

{digitalWrite(2,LOW);

}

}
