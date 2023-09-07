# ESP32-ETH-CLK-OUT17-SPIRAM

A variant of the ESP32 envelope that supports ethernet. The ESP32
outputs the PHY's clock on pin 17. This variant furthermore enables
SPIRAM.

Since Bluetooth and SPIRAM support use some memory, the Toit interpreter
doesn't fit into the SPIRAM anymore. As such, Toit programs may run
slower on this variant.