# GPS Tracking Device — Hardware

An electronic device built for GPS tracking. The project was made with KiCad.

---

## Features

- STM32F401RE microcontroller.
- 32.768 kHz crystal oscillator for the internal RTC of the microcontroller.
- USB micro B connector to power the board and to provide USB based host - target runtime communication.
- USBLC6-2SC6 ESD protection diode network to protect the USB connector from ESD events.
- CH340C USB-UART converter IC to provide communication capabilities between host and target with a USB cable.
- LD30950PU33R LDO for 5 V to 3.3 V conversion.
- u-blox NEO-6M GPS module connected to the microcontroller via UART.
- U.FL antenna connector for the ceramic patch antenna.
- 3 V CR2032 coin cell for the internal RTC of the microcontroller.
- microSD card slot connected to the microcontroller via SPI.
- Three user button connectors.
- A 4 pin connector for the display (I2C).
- A 5 pin debug connector (SWD).
- A connector for an external GPS module in case the on-board module is not operational (UART).

---

![GPS board](images/device.jpg)