# Home Assistant PowerWiz
A powersaver and power limiting scheme for Home Assistant - with minimal dependencies

Considering the ongoing energy crisis in 2022, you may feel the need to limit your power consumption. With PowerWiz for Home Assistant, I have implemented a basic approach to limiting your peak hourly power consumption and reducing energy consumption during peak price hours.

PowerWiz doesn’t have dependencies like Node Red or other addons. The only requirements are that you have access to your power meter energy readings, and the energy readings of the devices you include in your power saving scheme.

PowerWiz will not try to speculate how much money you have saved, or how much you have spent; it will simply cut power to devices of your choosing when 1) you use too much energy 2) the prices are high. You can control for how long the power should be cut, and how long devices must remain on before cutting power again.

Check out my article on theawsomegarage.com to read more about it; and feel free to check out the source code here on github.
