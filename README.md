# Why use-the AAT?

Tempature isn't helpful for knowing how comfortable the air will be. Humidity is also essential to determine how comfortable the air will be.
A metric that combines these is the AAT (Australian Apparent Temperature). It also conveniently allows me to use both my new tempature and humidity module.
This program utilizes a MicroOLED, a DHT22, a switch and a LED

By default the display shows Humidity and Temp
The brightness of the LED reflects humidity. Off at 0%, full intensity at 100%
While the switch is held down, the display reflects AAT

The AAT quantifies how the air will feel based on both variables. 
AAT = Ta + 0.33•ρ−0.70•ws−4.00
AAT = the Apparent Temperature in °C;
Ta = the Dry bulb Temperature in °C;
ρ= rh•6.105•e(17.27*Ta/(237.7+Ta))is the water vapor pressure (hPa);
ws = the wind speed (m/s) at 10 meter above the ground;
rh = the Relative Humidity (%)
