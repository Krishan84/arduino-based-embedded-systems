
char data=0;
int D1=4;
int D2=5;
int D3=6;
int D4=7;



void setup() {
  
 Serial.begin(9600);

 pinMode(D1,OUTPUT);
 pinMode(D2,OUTPUT);
 pinMode(D3,OUTPUT);
 pinMode(D4,OUTPUT);
}

void loop() 
  {
    if(Serial.available()>0)
    {
      data=Serial.read();
 Serial.print(data);          //Print Value inside data in Serial monitor
      Serial.print("\n");     
      if (data=='2')
      {
        digitalWrite(4,HIGH);
        digitalWrite(5,LOW);
        digitalWrite(6,HIGH);
        digitalWrite(7,LOW);
        delay(100);
        
      }
      else if(data=='4')
      {
      digitalWrite(4,LOW);
        digitalWrite(5,HIGH);
        digitalWrite(6,HIGH);
        digitalWrite(7,LOW);
       delay(100);
}
else if(data=='6')
{
digitalWrite(4,HIGH);
        digitalWrite(5,LOW);
        digitalWrite(6,LOW);
        digitalWrite(7,HIGH);
       delay(100);
       }
       
else if(data=='8')
       {
        digitalWrite(4,LOW);
        digitalWrite(5,HIGH);
        digitalWrite(6,LOW);
        digitalWrite(7,HIGH);
       delay(100);
      }
      
    }
  }
  void delay(int a)
  {
    int i,j;
    for(i=0;i<=a;i++)
    {
      for(j=0;j<=1000;j++);
      {
      
      
      }
    }
      
  }
    
