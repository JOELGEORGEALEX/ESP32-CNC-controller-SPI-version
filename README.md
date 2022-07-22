# ESP32 CNC board_ SPI version
The version 1 created was to use non SPI/UART based stepper motor controllers. This version of ESP32 Controller uses SPI to communicate with stepper drivers like TMC 2130/2660. Here we use TMC 2130 as the stepper driver. The board acts as an Access point and this wireless interface will allow any wifi enabled system to connect to the CNC machine



# Fabricated board (from fabhouse)

![Alt text](/images/espsp1.jpg "Optional title")



![Alt text](/images/espspi2.jpg "Optional title")

# SD Card

The board has an SD card slot which is used to upload gcodes, nc for machining jobs. With the interface the files could be uploaded wirelessly
![Alt text](/images/espspi5.jpg "Optional title")

# Controller interface

![Alt text](/images/espspi4.jpg "Optional title")

# Command display

![Alt text](/images/espspi6.jpg "Optional title")

# Firmware
The board runs on esp32 grbl firmware developed by bdring https://github.com/bdring/Grbl_Esp32.
The SPI data is sent to stepper controllers using daisy chaining technique. Whole the 4 drivers need to work for the communication


# Working video

![Alt text](/images/espspi3.mp4 "Optional title")

