# AVR-ISP_Isolator
Isolator Board for AVR ISP/SPI Programmers

Works well with the AVR Dragon and eBay USB AVRISP clones. With the buttons (relays) it's possible to disconnect the data and power lines from the external circuit. This is very useful if the SPI pins have multiple purposes. The external voltage can vary from 3 to 5V. (The large THT resistor is already designed into the kicad project. This resistor was necessary because the P-Ch. FET has a higher leakage than expected)
