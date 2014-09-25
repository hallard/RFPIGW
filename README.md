RFM12B RFM69CW Raspberry Pi Gateway With OLED and OOK
=====================================================

This is a simple board to be able to 
- Receive RFM12B data
- Receive RFM69CW data
- Blink 1st led when receiving from 1st module
- Blink 2nd led when receiving from 2nd module
- Display whatever on I2C OLED LCD
- Ready for OOK send/receive (see [jeelabs][5] for how to)

This is the 2nd proto board, I've ordered one on OSHPark, assembled 
then and it works fine so far. In this new version I've flipped the 
OLED since on some enclosure it was impossible to close them due to 
the total thickness of the board + OLED over it.

This version replace the 1.1 version which had some wiring reversed 
(MOSI/MISO) on the bottom module. I've also put the crystal on top 
side of the PCB instead of the bottom

No firmware or documentation is released because I'm currently working on 
project that will use this board as a gateway and I will release all source
code and documentation in the same time.
But you can take a look to this new project [Ultra Low Power Wireless Arduino Node][3]

This board gateway should work with the official firmware of [RFM2PI][6]
board dedicated for emoncms with small tweaking.

Check out news and other projects on my [blog][4]

Detailed Description
====================

Everything will be documented on my [blog][4]

**Schematic**  
![schematic](https://raw.github.com/hallard/RFPIGW/master/RFPIGW-sch.png)

**Board**  
<img src="https://raw.github.com/hallard/RFPIGW/master/RFPIGW-brd.png" align="center" alt="board" width="33%" height="33%">  

<img src="https://raw.github.com/hallard/RFPIGW/master/RFPIGW-top.png" alt="top" width="223" height="250">&nbsp;&nbsp;<img src="https://raw.github.com/hallard/RFPIGW/master/RFPIGW-bottom.png" alt="bottom" width="223" height="250">


[3]: http://hallard.me/bp-ulpnode/
[4]: http://hallard.me
[5]: http://jeelabs.net/projects/cafe/wiki/Receiving_OOKASK_with_a_modified_RFM12B
[6]: http://wiki.openenergymonitor.org/index.php?title=RFM12Pi_V2


