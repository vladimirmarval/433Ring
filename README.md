# 433Ring
Melodic ring scann


tl_433 version unknown inputs file rtl_tcp RTL-SDR SoapySDR
Use -h for usage help and see https://triq.org/ for documentation.
Trying conf file at "rtl_433.conf"...
Trying conf file at "/home/vlada/.config/rtl_433/rtl_433.conf"...
Trying conf file at "/usr/local/etc/rtl_433/rtl_433.conf"...
Trying conf file at "/etc/rtl_433/rtl_433.conf"...
Registered 122 out of 149 device decoding protocols [ 1-4 8 11-12 15-17 19-21 23 25-26 29-36 38-60 63 67-71 73-100 102-105 108-116 119 121 124-128 130-149 ]
Detached kernel driver
Found Rafael Micro R820T tuner
Exact sample rate is: 250000.000414 Hz
[R82XX] PLL not locked!
Sample rate set to 250000 S/s.
Tuner gain set to Auto.
Tuned to 433.920MHz.
Allocating 15 zero-copy buffers
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2021-06-26 17:26:30
model     : Waveman-Switch                         id        : D
channel   : 4            button    : 3             state     : off
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2021-06-26 17:26:30
model     : Smoke-GS558  id        : 21824
unit      : 10           learn     : 0             Raw Code  : aaa80a
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2021-06-26 17:26:33
model     : Waveman-Switch                         id        : D
channel   : 4            button    : 3             state     : off
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2021-06-26 17:26:33
model     : Smoke-GS558  id        : 21824
unit      : 10           learn     : 0             Raw Code  : aaa80a
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _






vlada@vlada-ThinkCentre-E73:~$ rtl_433 -A
rtl_433 version unknown inputs file rtl_tcp RTL-SDR SoapySDR
Use -h for usage help and see https://triq.org/ for documentation.
Trying conf file at "rtl_433.conf"...
Trying conf file at "/home/vlada/.config/rtl_433/rtl_433.conf"...
Trying conf file at "/usr/local/etc/rtl_433/rtl_433.conf"...
Trying conf file at "/etc/rtl_433/rtl_433.conf"...
Registered 122 out of 149 device decoding protocols [ 1-4 8 11-12 15-17 19-21 23 25-26 29-36 38-60 63 67-71 73-100 102-105 108-116 119 121 124-128 130-149 ]
Detached kernel driver
Found Rafael Micro R820T tuner
Exact sample rate is: 250000.000414 Hz
[R82XX] PLL not locked!
Sample rate set to 250000 S/s.
Tuner gain set to Auto.
Tuned to 433.920MHz.
Allocating 15 zero-copy buffers
Detected OOK package	2021-06-26 17:43:33
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2021-06-26 17:43:33
model     : Waveman-Switch                         id        : D
channel   : 4            button    : 3             state     : off
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2021-06-26 17:43:33
model     : Smoke-GS558  id        : 21824
unit      : 10           learn     : 0             Raw Code  : aaa80a
Analyzing pulses...
Total count:  461,  width: 746.36 ms		(186590 S)
Pulse width distribution:
 [ 0] count:  297,  width:  312 us [308;328]	(  78 S)
 [ 1] count:  164,  width:  952 us [944;960]	( 238 S)
Gap width distribution:
 [ 0] count:  278,  width:  956 us [952;964]	( 239 S)
 [ 1] count:  164,  width:  320 us [312;332]	(  80 S)
 [ 2] count:   18,  width: 9864 us [9860;9872]	(2466 S)
Pulse period distribution:
 [ 0] count:  442,  width: 1272 us [1268;1284]	( 318 S)
 [ 1] count:   18,  width: 10180 us [10180;10184]	(2545 S)
Level estimates [high, low]:  15979,      3
RSSI: -0.1 dB SNR: 37.3 dB Noise: -37.4 dB
Frequency offsets [F1, F2]:   17189,      0	(+65.6 kHz, +0.0 kHz)
Guessing modulation: Pulse Width Modulation with multiple packets
Attempting demodulation... short_width: 312, long_width: 952, reset_limit: 9876, sync_width: 0
Use a flex decoder with -X 'n=name,m=OOK_PWM,s=312,l=952,r=9876,g=968,t=256,y=0'
pulse_demod_pwm(): Analyzer Device
bitbuffer:: Number of rows: 19 
[00] {25} af ea aa 80 : 10101111 11101010 10101010 1
[01] {25} af ea aa 80 : 10101111 11101010 10101010 1
[02] {25} af ea aa 80 : 10101111 11101010 10101010 1
[03] {25} af ea aa 80 : 10101111 11101010 10101010 1
[04] {25} af ea aa 80 : 10101111 11101010 10101010 1
[05] {25} af ea aa 80 : 10101111 11101010 10101010 1
[06] {25} af ea aa 80 : 10101111 11101010 10101010 1
[07] {25} af ea aa 80 : 10101111 11101010 10101010 1
[08] {25} af ea aa 80 : 10101111 11101010 10101010 1
[09] {25} af ea aa 80 : 10101111 11101010 10101010 1
[10] {25} af ea aa 80 : 10101111 11101010 10101010 1
[11] {25} af ea aa 80 : 10101111 11101010 10101010 1
[12] {25} af ea aa 80 : 10101111 11101010 10101010 1
[13] {25} af ea aa 80 : 10101111 11101010 10101010 1
[14] {25} af ea aa 80 : 10101111 11101010 10101010 1
[15] {25} af ea aa 80 : 10101111 11101010 10101010 1
[16] {25} af ea aa 80 : 10101111 11101010 10101010 1
[17] {25} af ea aa 80 : 10101111 11101010 10101010 1
[18] {11} af e0       : 10101111 111



CO POSILAT ZAZVONENI JE

10101111 11101010 10101010 1

