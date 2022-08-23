# Communicate between two STM32F4 Cards


## Features

Using spi2 :
- Send Data from master card
- Check the data in slave card
- If data transmitted correctly to slave , it will send a data with true signal(40 in code) else false signal(80 in code)

## Connections

- Connect PB13 of the two cards together it is the MOSI(Master output slave input) line
- Connect PB15 of the two cards together they are the SCK (spi2 clock) pins
- Connect PC2 of the two cards together it is the MISO(Master input slave output) line
- Connect GND of the two cards together


## Challenge

I have a mini challenge to you!

Fork the repo then :
> - Check if user button pressed in slave card
> - If button pressed 1 time send a data to slave and light the led 1 in slave card if 2 light the second if 3 light the third
> - When the button is prssed for the fourth time turn off all the leds

Hint : Check comment lines (unused code it will maybe helpful :) )
