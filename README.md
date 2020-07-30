<!-- Please do not change this html logo with link -->
<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# Basic Peripherals

This application uses the ADC to measure an analog input voltage, typically from a potmeter. It uses the sampled value to control the PWM duty cycle of an I/O pin, typically connected to a LED. The printf() will be redirected to USART to print status information, while the Timeout Driver schedules the timing of these operations. This results in a LED dimmer and printf() application.

## Related Documentation

- [ATmega328PB Device Page](https://www.microchip.com/wwwproducts/en/ATmega328pb)

## Software Used

- [MPLAB® X IDE](http://www.microchip.com/mplab/mplab-x-ide) 5.40 or later
- [ATmega DFP](http://packs.download.atmel.com/) 2.2.108 or later
- [MPLAB® XC8](http://www.microchip.com/mplab/compilers) 2.20 or a later
- [AVR/GNU C Compiler](https://www.microchip.com/mplab/avr-support/avr-and-arm-toolchains-c-compilers) 5.4.0 or later


## Hardware Used

- [ATmega328PB Xplained Mini](https://www.microchip.com/DevelopmentTools/ProductDetails/atmega328pb-xmini)
- Micro-USB cable (Type-A/Micro-B)

## Setup

1. Connect ADC Channel 0 (PC0) to analog input voltage source, such as potmeter.

2. Connect PWM Channel 0 (PD6) to observable output, such as a LED.


## Operation

1. Connect the board to the PC.

2. Download the zip file or clone the example to get the source code.

3. Open the project in MPLAB X IDE.

4. Build the solution and program the device.

5. Open the EDBG COM-port in a terminal window to observe the printf() output.

6. Operate the analog input voltage source (e.g. potmeter) and observe the change in LED and printf() output.

## Conclusion

This code example has illustrated how to use basic peripherals of the ATmega328PB to create a LED dimmer and printf() application.
