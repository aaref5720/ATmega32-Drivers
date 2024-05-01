# ATmega32 Drivers

This repository contains essential drivers for the ATmega32 microcontroller, organized into two main folders: MCAL and HAL.

## MCAL (Microcontroller Abstraction Layer)

The MCAL folder comprises low-level drivers that directly interact with the hardware peripherals of the ATmega32 microcontroller. These drivers offer an abstraction layer to efficiently manage the microcontroller's hardware components.

### Included Drivers:
- **USART:** Driver for USART (Universal Synchronous/Asynchronous Receiver/Transmitter) communication.
- **SPI:** Driver for SPI (Serial Peripheral Interface) communication.
- **ADC:** Driver for Analog-to-Digital Converter (ADC) module.
- **TIMER0:** Driver for Timer/Counter 0 module.
- **GPIO:** Driver for General Purpose Input/Output pins.

## HAL (Hardware Abstraction Layer)

The HAL folder contains higher-level drivers that build upon the MCAL layer, providing simplified APIs for interfacing with complex peripherals and external devices.

### Included Drivers:
- **LCD:** Driver for Liquid Crystal Display (LCD) interfacing.
- **Keypad:** Driver for interfacing with a keypad.

## Usage

To utilize these drivers in your ATmega32 projects, include the necessary files from the respective folders in your project. Refer to the documentation within each driver for detailed usage instructions.

## Contributing

Contributions to enhance or expand the functionality of these drivers are encouraged! Feel free to submit pull requests or open issues for any bugs or feature requests.


