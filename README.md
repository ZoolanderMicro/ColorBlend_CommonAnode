# ColorBlend_CommonAnode
   Scetch ColorBlend_CommonAnode is a color fade/blend routine for a tri-color
   common anode led connected to Arduino Uno digital pins 9, 10, and 11 as PWM
   outputs. Colors transition from blue through teal, green, yellow, orange, red,
   violet, purple, and back to blue. With common anode tri-colored LEDs,
   analogWrite() value of 0 results in a full 'on' state, and analogWrite()   
   value of 255 results in a full 'off' state. This scetch works with common
   cathode tri-colored leds, only the color blend runs in the opposite order.
   Written in Arduino C language.
   @author Mike Tonge
   @date 11/28/2019
