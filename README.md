# CLK_IN
CLK_IN increasingly convoluted clock generators from five items you already have under your sink~

We've all been there, at the lab bench, about to get started on <next_unfinished_project>. All you need is 0-5v and a CLK.

We've got you covered.



## Named Clocks

Here are some of the highlights: 


### Vampire_Clock
Suck a high-speed CLK out of SEE (or similar) using H-Probe
CLK_ID: 1004
6502CS-test: Not yet
Absurd: 🤷
Sub-HZ: N

### Tide clock
Mount a water lever sensor (https://wiki.dfrobot.com/Liquid_Level_Sensor-FS-IR02_SKU__SEN0205) to a GPIO
CLK_ID: 1006
Absurd: N
Sub-HZ: Y


### PicoScope AWG
Use your PicoScope to generate a square waave
CLK_ID: 1007
Absurd: N
Sub-HZ: N
Max-rate: 100Khz
Min-rate: 10khz 

### Calibrator Clock
Use your scopes built in probe-compensator (you know, for calibrating your probes).
CLK_ID 1010
Absurd: N
Sub-HZ: N
Score:  1.0
rate_max: 1

1 / (1/10) HZ (i.e., once every ten seconds) 

| Range         |  explanation  |   Rate(min)    |
| 000 - 100     |   Reserved    |   N/A     | 
| 100
| 101 - 200     | 


| CLK_ID        |  score        |   Rate    |
| ------------- | ------------- | ----------|
| Content Cell  | Content Cell  |  001      |
| Content Cell  | Content Cell  |  002      |
| Content Cell  | Content Cell  |  003      |
| Content Cell  | Content Cell  |  004      |
