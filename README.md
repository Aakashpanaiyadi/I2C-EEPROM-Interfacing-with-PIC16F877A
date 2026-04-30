# I2C-EEPROM-Interfacing-with-PIC16F877A

This project implements I2C communication using the PIC16F877A microcontroller in master mode. The MSSP module is configured to communicate with an external EEPROM. The code performs both write and read operations by sending the memory address, writing data, and then using a repeated start condition to read the stored data back.

---

### Components Used (Simulation)

* PIC16F877A microcontroller
* 24C02 EEPROM
* Pull-up resistors (4.7kΩ for SDA and SCL)
* Proteus simulation environment

---

### Output

* Data (0x55) is successfully written to a specific EEPROM memory location
* The same data is read back correctly using I2C read operation
* Communication verified using I2C debugger sequence (Start → Address → Data → Stop)
