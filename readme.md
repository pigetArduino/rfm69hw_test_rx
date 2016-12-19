Test for an radio module using an arduino mini pro 3v     
Suitable to make batteries powered sensors    

Based on Adafruit tutorial : https://learn.adafruit.com/adafruit-rfm69hcw-and-rfm96-rfm95-rfm98-lora-packet-padio-breakouts

# Usage
* Make a rfm69 gateway (https://github.com/pigetArduino/rfm69hw_test_tx)    
* Upload code
* If the buzzer sounds, no communication is established

# Components
* Arduino Mini Prov 3V
* RFM69 (866Mhz) :     
Total:

# Wiring
![RFM69_nano](https://github.com/pigetArduino/rfm69hw_test_rx/raw/master/doc/arduino_minipro3v_rfm69_wiring.png)

```
RFM69 -----
X
NSS (Purple) --> D10
MOSI (Brown) --> D11
MISO (Green) --> D12
SCK (Orange) --> D13
GND (Black)
ANA          --> Antenna (8cm cable)
X

RESET (Yellow) --> D9
DI0 (Blue) --> D2
X
X
X
X
X
3.3V

Buzzer --> D3

```