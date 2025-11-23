## Bill Of Materials

| Manufacture Part Number | Manufacturer               | Package      | Description                      | Quantity |
| ----------------------- | -------------------------- | ------------ | -------------------------------- | -------- |
| ATMEGA328P-AU           | MICROCHIP                  | TQFP-32(7x7) | AVR Microcontroller - ATmega328p | 1        |
| X322516MLB4SI           | YXC Crystal Oscillators    | SMD3225-4P   | Crystal Oscillator - 16MHz 9pF   | 1        |
| B3U-1000P               | OMRON                      | SMD,3x2.5mm  | Round Button - 2.5mm 12V         | 1        |
| TZ-P2-0603YGTCS1-0.6T   | TUOZHAN                    | 0603         | Indication LED - Green 1.9V~2.4V | 1        |
| XL-1608SURC-06          | XINGLIGHT                  | 0603         | Indication LED - Red 2.3V        | 1        |
| CL10A105KB8NNNC         | Samsung Electro-Mechanics  | 0603         | Ceramic Capacitor - 1uF 50V      | 1        |
| CC0603KRX7R9BB104       | YAGEO                      | 0603         | Ceramic Capacitor - 100nF 50V    | 3        |
| CL10C120JB8NNNC         | Samsung Electro-Mechanics  | 0603         | Ceramic Capacitor - 12pF 50V     | 2        |
| RC0603FR-0710KL         | YAGEO                      | 0603         | Chip Resistor - 10kΩ 75V         | 2        |
| 0603WAF3300T5E          | UNI-ROYAL                  | 0603         | Chip Resistor - 330Ω 75V         | 1        |

<br>

## Pinout Description

<pre>
      _⎽⎽⎽⎽⎽⎽⎽⎽⎽_
     |○             ◻|
     |○             ○|
     |○             ○|
     |○             ○|
     |○             ○|
     |○             ○| ← J1
J2 → |○             ○|
     |○             ○|
     |○             ○|
     |○ ◻ ○ ○ ○ ○ ○ ○|
     |○|‾⎺⎺↑⎺⎺⎺⎺|○|
     |◻|    J3     |○|
      ⎺            ⎺
</pre>

|    |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  |  10  |  11  |  12 |
| -- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :--: | :--: | :-: |
| J1 | D9  | D8  | D7  | D6  | D5  | D4  | D3  | D2  | GND | RST  | RXI  | TXO |
| J2 | RAW | GND | RST | VCC | A3  | A2  | A1  | A0  | SCK | MISO | MOSI | D10 |
| J3 | DTR | TXO | RXI | VCC | GND | GND |     |     |     |      |      |     |
