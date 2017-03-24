int relay=4;

char data=0;

void setup() {
  // put your setup code here, to run once:
pinMode(relay,OUTPUT);
Serial.begin(9600);
  
}

void loop() {
  // put your main code here, to run repeatedly:
if(Serial.available() > 0)      // Send data only when you receive data:
   {
      data = Serial.read();        //Read the incoming data & store into data
      Serial.print(data);          //Print Value inside data in Serial monitor
      Serial.print("\n");        
      if(data == '1')
{
  // Checks whether value of data is equal to 1

         digitalWrite(relay, HIGH);
   }
}
}
