# DeviationTX-Board-7e-u256

Designed with EAGLE https://www.autodesk.fr/products/eagle/free-download

This board use https://stm32-base.org/boards/STM32F103RCT6-STM32-Mini-V2.0.html and asume the flash on the board is used. (you have to unsold the pin of the cs flash and wire to the good point (TODO: provide a photo from the post for this point)

## BOM
### Screen
there is 2 possibility for the screen. Original from a DEVO 7e or SSD1306 (but you need a prticular firmware for this  !)

### Radio module
radio pins is designed to provide easyly what you need for a 4 in 1 module or mod to use 4 radio module.

### Lazy power management mod
If you dont want try to sold SMD parts, use :
* 2 5V booster like the DD0505MC (10a45 5v booster) 
* external charger/protector for a lipo battery (like a TP4056 shield for 18650 or lipo)

### Power management
If you are courageous you need :
* 2 10A45
* 1 TP4056
* 1 8205A
* TODO

### Plugs
JST-PH 2.5

### Other parts (buzzer and vibrator part):
* SS8050 ("Y1")
* SS8550 ("Y2")
