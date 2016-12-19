# Components
* Arduino Mini Prov 3V
* RFM69 (866Mhz) : 
Total:

# Wiring
![RFM69_nano](https://github.com/pigetArduino/rfm69hw_test_rx/raw/master/doc/rfm69_minipro3v_wiring.png)

```
RFM69 -----
X
NSS (Purple) --> D10
MOSI (Brown) --> (3.3V) --> TX1
MISO (Green) --> (Nano) --> D12
SCK (Orange) --> (3.3V) --> RX0
GND (Black)  --> (3.3V) --> GND
ANA          --> Antenna (8cm cable)
X

RESET (Yellow) --> RX0
DI0 (Blue) --> D2
X
X
X
X
X
3.3V

5V / 3.3V ------------
TX1 --> NSS (Purple)
RX0 --> RESET (Yellow)
GND
LV  --> 3.3V
RX0 --> SCK (Orange)
TX1 --> MOSI (Brown)

TX0 --> D10 (Purple)
RX0 --> D9 (Yellow)
GND
HV --> 5V
RX1 --> D13 (Orange)
TX0 --> D11 (Brown)
```
