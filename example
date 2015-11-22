#include "MPXV6115V.h"

MPXV6115V mpxv6115v(A0);

void setup()
{
  Serial.begin(9600);
}
void loop()
{
  float vacuum=mpxv6115v.hesap();
  Serial.println(vacuum);
  delay(500);
}
