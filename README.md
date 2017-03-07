#Duckuino
##Live version here: 
DuckyScript -> Arduino converter/compiler + HID mouse emulation.

```diff
- DEPENDENCY: https://github.com/NicoHood/HID (*IMPORTANT!*)
```
Download HID-Project from: https://github.com/NicoHood/HID/archive/master.zip and add it to Arduino Library.

###If you got any problems with the keyboard layout (if you don't have a QWERTY keyboard) then use the library that Thecakeisgit has created: https://github.com/Thecakeisgit/LocaleKeyboard.js

### If you don't want to use the mouse emulation then use Thecakeisgit's compiler: https://github.com/Thecakeisgit/Dckuino.js

###NOTE: You should update the Arduino IDE to the latest version for better cross-platform compatibility! (Or use the Arduino Create Web IDE)

###Commands: https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript
The commands are basically the same except that you can simulate a mouse with Duckuino like so:
"MOUSEMOVE xPos,yPos,wheelPos" for positioning and "MOUSECLICK left/right/middle" for clicks.
