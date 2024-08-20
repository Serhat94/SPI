# SPI
SPI communication for 320F32069

![image](https://github.com/user-attachments/assets/d7454ecd-1f1b-418b-8117-7435c467b713)

**What is SPI**

SPI is generally used to communicate between a master device and one or more slave devices. The master device sends a clock signal using the SCLK line and data is transmitted according to the edges of this signal. The master device sends data on the MOSI line, while the slave device sends data on the MISO line. The slave devices are selected and communicated with the SS/CS line.

**Connection**

--> SCLK (Serial Clock): Bu hattın üzerinden saat sinyali gönderilir ve diğer cihazların veri alışverişini senkronize eder.
--> MOSI (Master Out Slave In): Ana cihazdan veri göndermek için kullanılır. Ana cihazın gönderdiği veriler bu hattan slave cihazlara iletilir.
--> MISO (Master In Slave Out): Slave cihazların ana cihaza veri göndermek için kullandığı hattır. Ana cihaz, bu hattı kullanarak veriyi alır.
--> SS/CS (Slave Select/Chip Select): Her bir slave cihazın seçilmesini veya devre dışı bırakılmasını sağlamak için kullanılır. Ana cihaz, hangi slave cihazla iletişim kurmak istediğini bu hattı kullanarak belirtir.
