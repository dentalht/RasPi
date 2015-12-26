The White wire from the sensor is a spare ground, and is not needed.  Cut it off inside the sensor case, being careful not to cut any of the other wires.

Braid the other three wires to keep them together, and cut them off about 3.5 inches long.

Prepare a 5-pin single inline female connector (cut from https://www.sparkfun.com/products/115 or equivalent), and solder the wires to it:

1) Red (+3.3V)
2) No Connection
3) No Connection
4) Yellow (Data)
5) Black (Ground)

Plug the connector into the GPIO on the Raspberry Pi so that pin 1 on the connector (red wire) is on pin 1 of the GPIO connector (label P1 on the board, upper right in the picture).  Note that the Red wire is on GPIO Pin 1 (+3.3V), the Yellow wire is on GPIO pin 7 (GPIO 4), and the Black wire is on GPIO Pin 9 (Ground).

Tuck the excess wire into the case.

Use a short CAT5 cable (something like http://www.monoprice.com/Product?c_id=102&cp_id=10232&cs_id=1023201&p_id=7505 ) to connect the LAN OUT on the PoE splitter and the Raspberry Pi Ethernet jack.  Twist it up to make it stay close to the case.

Take the PoE output cable and a Micro-USB connector or cable and solder them together.  If using an AdaFruit http://www.adafruit.com/products/1390 Micro-USB connector, wire it up as shown at http://learn.adafruit.com/assets/12402 , if using a cut-off cable, determine +5 and Gnd wires with a multimeter.  Note that the TP-Link wire with the white stripe is POSITIVE.
