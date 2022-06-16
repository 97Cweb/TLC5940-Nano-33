# TLC5940-Nano-33
Arduino library for Arduino Nano 33. Based originally off of Paul Stoffregen's library found at https://github.com/PaulStoffregen/Tlc5940

Incomplete: to be used as reference only. It does work, but only in the specific case

           ARDUINO                                         TLC5940       
           
              13|-> SCLK (pin 25)           OUT1 String "B" |1     28| OUT0 String "A"
              
              12|                           OUT2 String "C" |2     27|-> GND (VPRG)
              
              11|-> SIN (pin 26)            OUT3 String "D" |3     26|-> SIN (pin 11)
              
              10|-> BLANK (pin 23)          OUT4 String "E" |4     25|-> SCLK (pin 13)
              
               9|-> XLAT (pin 24)           OUT5 String "F" |5     24|-> XLAT (pin 9)
               
               8|                           OUT6 String "G" |6     23|-> BLANK (pin 10)
               
               7|                           OUT7 String "H" |7     22|-> GND
               
               6|                           OUT8 String "I" |8     21|-> VCC (+5V)
               
               5|                           OUT9 String "J" |9     20|-> 2K Resistor -> GND  
               
               4|                          OUT10 String "K" |10    19|-> +5V (DCPRG)
               
               3|-> GSCLK (pin 3)         OUT11 String "L" |11    18|-> GSCLK (pin 3)
               
               2|                          OUT12 String "M" |12    17|-> SOUT (only used when you want to use more than one tlc5940)
               
               1|                          OUT13 String "N" |13    16|-> XERR (can be used as error report, but not necessary)
               
               0|                          OUT14 String "O" |14    15| OUT15 String "P"       

