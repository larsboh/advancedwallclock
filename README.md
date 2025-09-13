# advancedwallclock

A modified version of DIY Machines' code for his wall shelf clock project.

Changes to the original code:
- Added: Membrane keyboard to control the clock**
- Added: Countdown
- Added: Direct adjustment of color(s) and brightness
- The independent brightness adjustment has been removed
- The digit 9 is displayed as you are used to from seven-segment displays.



Setup:

Enter your network name in the field "ssid = YOUR SSID" and your password in "password = YOUR PASSWORD". Further settings should be self-explanatory. 




Notice:

Whenever the module is powered, it tries to connect to the internet. If successful, the online time is overwritten once with the data of the RTC module. If not (because the internet is down), the "old" time of the RTC module is used after a certain time. 



Operation:

In stand-by mode (clock) the keys "A", "B", and "C" of the membrane keypad are active. With "D" you always come back. Once you have tried out the functions, everything is self-explanatory.


"A" - Mode selection

Mode "1" - Time

Mode "2" - Timer

Mode "3" - System test




"B" - Brightness setting

"*" - brighter 

*#* - darker

"0" - change between display and downlighter




"C" - color setting
   
"1" < +   red (minute digits)   - > "4"

"2" < +   green (minute digits) - > "5"

"3" < +   blue (minute digits)  - > "6"


"7" < +   red (hour digits)     - > "*"

"8" < +   green (hour digits)   - > "0"
 
"9" < +   blue (hour digits)    - > "#"



"A" - synchronize colors (hour color takes over minute color) 

"B" - Switch everything white (blanc)
