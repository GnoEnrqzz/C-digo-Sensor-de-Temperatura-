#include <LiquidCrystal.h>

LiquidCrystal 1cd (2,3,9,10,11,12): 
int sensor;
float temperatura;
void setup {
1cd. begin (16, 2);
 16x2
void 100p()
lcd.clear();
1cd. print ("Temperatura" ");
sensor = analogRead (A0);
temperatura = ((sensor * 5000.0 )/1023)/10:
lcd. setCursor (0, 1);
lcd. print (temperatura);
delay (1000);
