# advancedwallclock
 A heavily modified version of DIY Machines' code for his awesome wall shelf clock project.

Please read through!

This program can be loaded directly onto a standard ESP32 microcontroller*. The intermediate step shown in the video of DIY-Machines (to synchronize the time) is omitted. The time is displayed in 24h format (as it should be ^^). 

Recommendation: 
If you don't put the board, time module and keyboard in the shelf itself but hidden under the shelf (for example by the power socket), it is much easier to assemble and much more accessible. 

Changes to the original code:
- Added: Membrane keyboard to control the clock**
- Added: Timer
- Added: direct adjustment of color(s) and brightness
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



No reflinks, just Suggestions:

*https://www.amazon.de/gp/product/B08BZGC22Q/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1

**https://www.amazon.de/DollaTek-Universial-Schl%C3%BCsselschalter-Tastatur-Arduino/dp/B07DK57KVM/ref=d_pd_sbs_sccl_2_3/257-5768396-1370358?pd_rd_w=9Usa8&content-id=amzn1.sym.e240add7-999b-4e0b-8c0e-340ec2846a97&pf_rd_p=e240add7-999b-4e0b-8c0e-340ec2846a97&pf_rd_r=Y1QMGZS81AZJSCG0BH0Y&pd_rd_wg=p5836&pd_rd_r=8c833c43-3762-4f8a-85ce-b7b84640d665&pd_rd_i=B07DK57KVM&psc=1)
