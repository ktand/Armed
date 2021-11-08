# Armed 3D Printer Controller

![Armed 1.1](Armed.png?raw=true)

## Features

* 32bit STM32F407VET6 
  * 168MHz 
  * 512kB Flash 
  * 192kB RAM 
* Power supply from 12-24V 
* Dual power inputs with separate fuses 
  * One for one of the high current outputs and the other one for the rest 
* Up to 5 steppers 
  * Dual outputs for one stepper for use with dual stepper Z-axis 
* 3 high current outputs 
* 3 fan outputs 
* 3 temperature sensors inputs 
* 3 endstops inputs 
* Filament runout detection 
* LCD display header 
* USB support 
* 10 extension pins 
* Support for TMC2130 SPI 
* 12-24V supply 
* I2C, SPI and UART extension ports 
* SWD header 
* Stepper configuration using solder jumpers 
* Einsy Rambo Form Factor (100x71mm) 

## Schematic and PCB Design

Designed using [Kicad 5.0](http://kicad.org/).

## Compatibilty

Arduino compatbile using the [Arduino Core STM32](https://github.com/stm32duino/Arduino_Core_STM32) and working with the [Marlin 2.0 3D printer firmware](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x).

## Board configuration and pinout

![Armed 1.1](Armed-back.png?raw=true)
