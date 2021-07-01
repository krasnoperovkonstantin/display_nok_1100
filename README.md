# display_nok_1100

Библиотека для дисплея Nokia 1100 или любого другого с контроллером PCF8814 для Arduino pro mini подобных.

// Arduino Dueminalove Atmega328
// Interfacing with the Nokia 1100 LCD, PCF8814
//    0----------- X max 16
//    |
//    |
//    |
//    Y max 8
// Arduino pinout // Nokia 1100 LCD pinout (VDD & VDDI ==> 3.3V, VLED+ connected via 10 ohm resistor to 3.3V)
// Connected via resistor-voltage-divider 1.8K & 3.2K
// Use:
// LcdInitialise();
// LcdClear();
// LcdGotoXY(char,char);
// LcdLongInt(long int);  //2018
// LcdLongInt(long int,char);  //00002018
// LcdString("Hello world");
// LcdChar(unsigned char);   //LcdChar('T');
