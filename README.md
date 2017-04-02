# STM32F107 Makefile FreeRTOS Network

[![Build Status](https://travis-ci.org/runmec/stm32f107_makefile_freertos_network.svg?branch=master)](https://travis-ci.org/runmec/stm32f107_makefile_freertos)

## Requirement

Working GNU ARM GCC (https://launchpad.net/gcc-arm-embedded)

Texane stlink to flash the STM32F10x (https://github.com/texane/stlink)

FreeRTOS Source (http://www.freertos.org)

## Usage

### build project

```$ make```

### clean project

```$ make clean```

### download to mcu by stlink 
```$ make flash```

### erase flash
```$ make erase```

## Example

mcu: STM32F103C8T6

GPIOB11--Led

