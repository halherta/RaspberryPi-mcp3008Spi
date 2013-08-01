halherta-RaspberryPi-mcp3008Spi
===========================================================================================================
Author: Hussam Al-Hertani

Description: The mcp3008Spi class enables the Raspberry Pi to communicate with the MCP3008 SPI ADC using spidev. The class can be easily modified to enable the Raspberry Pi to communicate with other SPI devices.

============================================================================================================
For more information please visit : 
http://hertaville.com/2013/07/24/interfacing-an-spi-adc-mcp3008-chip-to-the-raspberry-pi-using-c/

========================================================================================
To build example binary natively on the Raspberry Pi:

g++ -fpermissive -Wall mcp3008Spi.cpp mcp3008SpiTest.cpp -o outBin


Make sure that the mcp3008Spi.h header file is in the work directory.
