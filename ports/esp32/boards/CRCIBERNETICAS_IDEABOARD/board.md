# MicroPython Firmware for CRCibernetica IdeaBoard (ESP32)

This Micropython build s designed for CRCibernetica's IdeaBoard, an ESP32-based development board designed for IoT and robotics applications. This board features an ESP32-WROOM-32E module with **8MiB of flash**, this build is designed to better suit this as the regular ESP32 builds are designed for **4MiB of Flash Memory**, Other QoL improvements are also made such as Pin aliases.

CRCibernetica's IdeaBoard is an educational Internet of Things (IoT) and robotics development board based on the ESP32-WROOM-32E microcontroller. It features dual H-bridges for motor control, a multi-color programmable RGB LED (WS2812B), and is programmable using CircuitPython/MicroPython or the Arduino IDE (C/C++). The board includes a USB-C interface for programming and debugging, standard 0.1" headers for convenient interfacing, a STEMMA/QWIIC 4-pin interface for easy connections to I2C modules, and direct DC power input for battery or power supply (5VDC - 9VDC). It offers 14 general-purpose I/O pins, with 7 pins suitable for servos or other applications requiring direct power. 

## Getting Started with MicroPython on the IdeaBoard

1. **Download the Firmware**
   - Visit this fork's [Releases page](https://github.com/emanuel-mena/crcibernetica-ideaboard-micropython/) and select the appropriate firmware for your board.

2. **Flash the Firmware**
   - Use [`esptool.py`](https://docs.micropython.org/en/latest/esp32/tutorial/intro.html#flashing-the-firmware) to flash the firmware onto the IdeaBoard.
   - Ensure you have installed the necessary drivers for the CH340G USB-to-serial converter if required.

3. **Connect to the Board**
   - After flashing, connect to the board using a serial terminal program (e.g., `picocom`, `screen`, `minicom`, or the MicroPython IDE `mpremote`).
   - You can then access the MicroPython REPL to start developing your applications.
   - You can also use a more conventional IDE such as [Thonny](https://thonny.org/)



## Additional Resources

- [CRCibernetica IdeaBoard Buying Page](https://www.crcibernetica.com/crcibernetica-ideaboard/)
- [CRCibernetica's GitHub Repository](https://github.com/CRCibernetica)
- [MicroPython Official Documentation](https://docs.micropython.org/)

For any issues or further support, visit the CRCibernetica community forums or MicroPython discussions.
