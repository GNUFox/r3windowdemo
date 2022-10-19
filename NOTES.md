# Random notes / brainstorm

## basic idea
* use pico-W + hacked wifi outlets (smart outlets) for switching -> maybe check for existing solution in R3 (ask people)  
-> WiFi Sockets

* As the screen startup is slow a LED gimmick could bve used to get peoples attention until the screens are active.  
  * power LED gimmickc directly from Radar or from same socket as Screens  
    * Directly from Radar: very quick response
    * Screen Socket: Radar can be low power / self-sufficient

* Show a simple demo from the Pico-VGA-board
* show infor from normal raspberry pi (Zero / 3 / ...) running kiosk (display webpage)

## User activated sound feature:  
  * Touch sensor behind glass where people can actvate a (low volume) sound demo  
  * Should automatically turn off after a few seconds.
  * Should only be activated when presence was detected by radar

## advanced idea
* Multiple picos connected to multiple VGA monitors displaying a bigger demo (synchronized)
  * cat / dog / ? running across screens?
  * Use multiple I2C interfaces between picos (cascaded) `(Pico0:I2C_1) ==== (I2C_0:Pico1:I2C_1) ==== (I2C_0:Pico2:I2C_1) ==== ...`
