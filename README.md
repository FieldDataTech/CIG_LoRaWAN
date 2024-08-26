These source files are needed to create custom firmware for the LoRaWAN module on the CIG open source device.
To use these, you must first download and install Segger Embedded Studio. And then download the ISP4520B example project from Semtech. 
After adding these zipped source files to the project you'll need to customize parameters in the Commissioning.h file to create unique LoRaWAN
identifiers for your device. Load the compiled firmware into your device using a Segger J-Link programming cable with a needle connector, or equivalent.
