On some PIR sensors, the pins are clearly labelled on the circuit board. Others have the labels hidden beneath their cap. If this is the case for your sensor, gently pop its cap off so that you can distinguish the pins.

Using three female-to-female jumper cables, connect each of the PIR sensor's pins to the appropriate pins on the Raspberry Pi:

- Connect the PIR sensor's pin labelled **VCC** to the **5V** pin on the Raspberry Pi. This provides power to the PIR sensor.
- Connect the one labelled **GND** to a ground pin on the Pi (also labelled **GND**). This completes the circuit.
- Connect the one labelled **OUT** to any numbered GPIO pin on the Pi. In this example, we have chosen **GPIO 4**. The **OUT** pin will output a voltage when the sensor detects motion. The voltage will then be received by the Raspberry Pi.

![PIR connection](images/pir-diagram.png)
