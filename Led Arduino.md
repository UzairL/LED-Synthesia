#include <LedControl.h>

//by uzairL. contact me if u want to ask anything uzairbinlatip@gmail.com

LedControl lc = LedControl(10, 12, 8, 1);

byte incomingByte;
byte note;
byte velocity; 
int action;

void onLED ()
{
  if (note==36){lc.setLed(0,7,4,true);}
  if (note==37){lc.setLed(0,7,3,true);}
  if (note==38){lc.setLed(0,7,2,true);}
  if (note==39){lc.setLed(0,7,1,true);}
  if (note==40){lc.setLed(0,7,0,true);}
  if (note==41){lc.setLed(0,6,7,true);}
  if (note==42){lc.setLed(0,6,6,true);}
  if (note==43){lc.setLed(0,6,5,true);}
  if (note==44){lc.setLed(0,6,4,true);}
  if (note==45){lc.setLed(0,6,3,true);}
  if (note==46){lc.setLed(0,6,2,true);}
  if (note==47){lc.setLed(0,6,1,true);}
  if (note==48){lc.setLed(0,6,0,true);}
  if (note==49){lc.setLed(0,5,7,true);}
  if (note==50){lc.setLed(0,5,6,true);}
  if (note==51){lc.setLed(0,5,5,true);}
  if (note==52){lc.setLed(0,5,4,true);}
  if (note==53){lc.setLed(0,5,3,true);}
  if (note==54){lc.setLed(0,5,2,true);}
  if (note==55){lc.setLed(0,5,1,true);}
  if (note==56){lc.setLed(0,5,0,true);}
  if (note==57){lc.setLed(0,4,7,true);}
  if (note==58){lc.setLed(0,4,6,true);}
  if (note==59){lc.setLed(0,4,5,true);}
  if (note==60){lc.setLed(0,4,4,true);}
  if (note==61){lc.setLed(0,4,3,true);}
  if (note==62){lc.setLed(0,4,2,true);}
  if (note==63){lc.setLed(0,4,1,true);}
  if (note==64){lc.setLed(0,4,0,true);}
  if (note==65){lc.setLed(0,3,7,true);}
  if (note==66){lc.setLed(0,3,6,true);}
  if (note==67){lc.setLed(0,3,5,true);}
  if (note==68){lc.setLed(0,3,4,true);}
  if (note==69){lc.setLed(0,3,3,true);}
  if (note==70){lc.setLed(0,3,2,true);}
  if (note==71){lc.setLed(0,3,1,true);}
  if (note==72){lc.setLed(0,3,0,true);}
  if (note==73){lc.setLed(0,2,7,true);}
  if (note==74){lc.setLed(0,2,6,true);}
  if (note==75){lc.setLed(0,2,5,true);}
  if (note==76){lc.setLed(0,2,4,true);}
  if (note==77){lc.setLed(0,2,3,true);}
  if (note==78){lc.setLed(0,2,2,true);}
  if (note==79){lc.setLed(0,2,1,true);}
  if (note==80){lc.setLed(0,2,0,true);}
  if (note==81){lc.setLed(0,1,7,true);}
  if (note==82){lc.setLed(0,1,6,true);}
  if (note==83){lc.setLed(0,1,5,true);}
  if (note==84){lc.setLed(0,1,4,true);}
  if (note==85){lc.setLed(0,1,3,true);}
  if (note==86){lc.setLed(0,1,2,true);}
  if (note==87){lc.setLed(0,1,1,true);}
  if (note==88){lc.setLed(0,1,0,true);}
  if (note==89){lc.setLed(0,0,7,true);}
  if (note==90){lc.setLed(0,0,6,true);}
  if (note==91){lc.setLed(0,0,5,true);}
  if (note==92){lc.setLed(0,0,4,true);}
  if (note==93){lc.setLed(0,0,3,true);}
  if (note==94){lc.setLed(0,0,2,true);}
  if (note==95){lc.setLed(0,0,1,true);}
  if (note==96){lc.setLed(0,0,0,true);}

}

void offLED (){
  if (note==36){lc.setLed(0,7,4,false);}
  if (note==37){lc.setLed(0,7,3,false);}
  if (note==38){lc.setLed(0,7,2,false);}
  if (note==39){lc.setLed(0,7,1,false);}
  if (note==40){lc.setLed(0,7,0,false);}
  if (note==41){lc.setLed(0,6,7,false);}
  if (note==42){lc.setLed(0,6,6,false);}
  if (note==43){lc.setLed(0,6,5,false);}
  if (note==44){lc.setLed(0,6,4,false);}
  if (note==45){lc.setLed(0,6,3,false);}
  if (note==46){lc.setLed(0,6,2,false);}
  if (note==47){lc.setLed(0,6,1,false);}
  if (note==48){lc.setLed(0,6,0,false);}
  if (note==49){lc.setLed(0,5,7,false);}
  if (note==50){lc.setLed(0,5,6,false);}
  if (note==51){lc.setLed(0,5,5,false);}
  if (note==52){lc.setLed(0,5,4,false);}
  if (note==53){lc.setLed(0,5,3,false);}
  if (note==54){lc.setLed(0,5,2,false);}
  if (note==55){lc.setLed(0,5,1,false);}
  if (note==56){lc.setLed(0,5,0,false);}
  if (note==57){lc.setLed(0,4,7,false);}
  if (note==58){lc.setLed(0,4,6,false);}
  if (note==59){lc.setLed(0,4,5,false);}
  if (note==60){lc.setLed(0,4,4,false);}
  if (note==61){lc.setLed(0,4,3,false);}
  if (note==62){lc.setLed(0,4,2,false);}
  if (note==63){lc.setLed(0,4,1,false);}
  if (note==64){lc.setLed(0,4,0,false);}
  if (note==65){lc.setLed(0,3,7,false);}
  if (note==66){lc.setLed(0,3,6,false);}
  if (note==67){lc.setLed(0,3,5,false);}
  if (note==68){lc.setLed(0,3,4,false);}
  if (note==69){lc.setLed(0,3,3,false);}
  if (note==70){lc.setLed(0,3,2,false);}
  if (note==71){lc.setLed(0,3,1,false);}
  if (note==72){lc.setLed(0,3,0,false);}
  if (note==73){lc.setLed(0,2,7,false);}
  if (note==74){lc.setLed(0,2,6,false);}
  if (note==75){lc.setLed(0,2,5,false);}
  if (note==76){lc.setLed(0,2,4,false);}
  if (note==77){lc.setLed(0,2,3,false);}
  if (note==78){lc.setLed(0,2,2,false);}
  if (note==79){lc.setLed(0,2,1,false);}
  if (note==80){lc.setLed(0,2,0,false);}
  if (note==81){lc.setLed(0,1,7,false);}
  if (note==82){lc.setLed(0,1,6,false);}
  if (note==83){lc.setLed(0,1,5,false);}
  if (note==84){lc.setLed(0,1,4,false);}
  if (note==85){lc.setLed(0,1,3,false);}
  if (note==86){lc.setLed(0,1,2,false);}
  if (note==87){lc.setLed(0,1,1,false);}
  if (note==88){lc.setLed(0,1,0,false);}
  if (note==89){lc.setLed(0,0,7,false);}
  if (note==90){lc.setLed(0,0,6,false);}
  if (note==91){lc.setLed(0,0,5,false);}
  if (note==92){lc.setLed(0,0,4,false);}
  if (note==93){lc.setLed(0,0,3,false);}
  if (note==94){lc.setLed(0,0,2,false);}
  if (note==95){lc.setLed(0,0,1,false);}
  if (note==96){lc.setLed(0,0,0,false);}

}

void setup()
{
  Serial.begin(115200);
  pinMode(13, OUTPUT);
  lc.shutdown(0, false);
  lc.setIntensity(0, 8);
  lc.clearDisplay(0);
  digitalWrite(13, LOW);
}

void loop()
{
  if (Serial.available() > 0){
  incomingByte = Serial.read();
  
  if (incomingByte==144){
    action=1;
  }
  else if (incomingByte==128){
    action=0;
  }
  
else if ( (action==1)&&(note==0) ){ 
  note=incomingByte;
  onLED();
  velocity=incomingByte;
}
  
else if ( (action==0)&&(note==0) ){ 
  note=incomingByte;
  offLED();
  velocity=incomingByte;
}

if (velocity==0){
    offLED();}

   note=0;
  
  }
  }
