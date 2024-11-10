# esphome-buffer-tank-monitor

This monitor uses existing sensors and the status of switches in a buffer tank installation. The buffer tank is equipped with various heat sources: a heat pump, an electric element, solar collectors, and a wood-fired central heating stove. The central heating pump circulates warm water to the radiators. The heat sources enter the buffer tank at different heights, and temperatures are measured at four different levels.

With the buffer tank monitor, the temperatures at these four levels are measured and displayed in colors corresponding to the temperature. The LEDs are also used to flash the status of the heat sources. The bottom LED shows the status of the central heating pump.

Temperature color codes:

Blue: Temperature below 38°C
Green: Temperature between 38°C and 43°C
Orange: Temperature between 43°C and 50°C
Red: Temperature above 50°C
The colors are used to visually represent the status of the buffer tank, depending on the temperature at different heights.

The LED strip is connected to D2 of a Wemos Mini D1.
The Wemos Mini D1 is added as an ESPHome device in Home Assistant. 
