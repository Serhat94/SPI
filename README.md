# SPI
SPI communication for 320F32069

![image](https://github.com/user-attachments/assets/d7454ecd-1f1b-418b-8117-7435c467b713)

**What is SPI**

SPI is generally used to communicate between a master device and one or more slave devices. The master device sends a clock signal using the SCLK line and data is transmitted according to the edges of this signal. The master device sends data on the MOSI line, while the slave device sends data on the MISO line. The slave devices are selected and communicated with the SS/CS line.

**Connection**

--> SCLK (Serial Clock): The clock signal is sent over this line and synchronizes the data exchange of other devices.

--> MOSI (Master Out Slave In): It is used to send data from the master device. The data sent by the master device is transmitted to the slave devices via this line.

--> MISO (Master In Slave Out): This is the line that slave devices use to send data to the master device. The master device receives data using this line.

--> SS/CS (Slave Select/Chip Select): It is used to enable or disable each slave device. The master device specifies which slave device it wants to communicate with using this line.
