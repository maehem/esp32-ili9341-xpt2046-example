# esp32-ili9341-xpt2046-example
## A simple example of the ESP32, (ILI9341 + XPT2046) touchscreen working together.

This is the documentation of my project to connect a common and inexpensive 320x240 LCD-Touchscreen module to a ESP32 (AdaFruit Huzzah). While I found demo code at both AdaFruit and PJRC, both original sources for the libraries used here, neither were focused or completelty compatible with ESP32.

AdaFruit supplied the LCD library and it did work all by itself on ESP32, but AdaFruit uses a different touch screen (analog only).  PJRC released a touch screen library for the XPT2046 touch screen but they married it with and enhanced version of the AdaFruit LCD library, which happens to be only compatible with PJRC microcontrollers.  So my delema was to reassemble these libraries into something that worked on my Huzzah module.

## Parts used:
### AdaFruit Huzzah ESP32 module
 - [Product Link ](https://www.adafruit.com/product/3405 "AdaFruit Product Link")
### DIANN 3.2" ILI9341 SPI TFT LCD Display Touch Panel 
  - ILI9341 Chip (can be found in different size LCDs)
  - 320x240 TFT LCD Touch Screen on a PCB with headers 
  - 5V/3.3V (3.3v used here)
  - STM32 Display Module 
  - SPI Serial with included Touch Pen
  - SDCard Socket ob board (not demoed here).
  - [Amazon Product Link]( https://www.amazon.com/dp/B0BNQD38T2 "Amazon Link") 
  - There are many other sellers to choose from.
  
## Libraries Referenced:
  - [ AdaFruit TFT LCD Library]( https://github.com/adafruit/TFTLCD-Library )
  - [ PJRC XPT2046 Touch Library ]( https://github.com/PaulStoffregen/XPT2046_Touchscreen )
