# OpenElDispv2


=======
A tool for displaying on an OLED display the telemetry flight data:

-speed
-altitude
-heading
-distance to home
-heading to home
-parameters of sat. navigation (valid fix, number of satellites, HDOP, etc)

Data is received over the serial port. The received data is stored in a EEPROM memory, so that it can be recovered in case of crash, or analysed.

Two data formats are supported:

-Mavlink
-Eleres


-Arduino Pro Mini

-OLED 2.42'' I2C diplay:

http://www.ebay.com/itm/I2C-2-42-OLED-128x64-Graphic-OLED-White-Display-Arduino-PIC-Multi-wii-/191835417966?hash=item2caa482d6e:g:3a0AAOSwQTVWBkTu

-memory I2C

http://www.microchip.com/wwwproducts/en/24LC256

<<<<<<< HEAD
-two buttons
=======
-two buttons for switching between screens and configuration
>>>>>>> 339b594ab8df32d40cacfd2aa78d0c5feec3f062

compile with arduino 1.6.8
