# esphome-buffer-tank-monitor

This monitor uses existing sensors and the status of switches in a buffer tank installation. The buffer tank is equipped with various heat sources: a heat pump, an electric element, solar collectors, and a wood-fired central heating stove. The central heating pump circulates warm water to the radiators. The heat sources enter the buffer tank at different heights, and temperatures are measured at four different levels.

With the buffer tank monitor, the temperatures at these four levels are measured and displayed in colors corresponding to the temperature. The LEDs are also used to flash the status of the heat sources. The bottom LED shows the status of the central heating pump.

Temperature color codes:

Blue: Temperature below 38°C
Green: Temperature between 38°C and 43°C
Orange: Temperature between 43°C and 50°C
Red: Temperature above 50°C
The colors are used to visually represent the status of the buffer tank, depending on the temperature at different heights.
![Buffer Tank](https://github.com/ltvanderkrogt/esphome-buffer-tank-monitor/blob/b95d7cf0896e7c8e9885a070d57d6b16f92aebb1/buffervat%20temp.jpg)
The LED strip is connected to D2 of a Wemos Mini D1.
The Wemos Mini D1 is added as an ESPHome device in Home Assistant. 
![Wemos mini d1 + LED strip](https://github.com/ltvanderkrogt/esphome-buffer-tank-monitor/blob/004b270ed4e56d30e2fed7afcd0e297cf155829f/wemos%20led%20strip.jpg)

![8 LED WS2812 stripe](https://github.com/ltvanderkrogt/esphome-buffer-tank-monitor/blob/5d7355d51f4499c3ad0afcec4144e243f8d440a7/WS2812-5050-RGB-1-400x400.jpg)

