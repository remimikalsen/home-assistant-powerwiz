# Home Assistant PowerWiz
A powersaver and power limiting scheme for Home Assistant - with minimal dependencies

Considering the ongoing energy crisis, you may feel the need to limit your energy consumption. With PowerWiz for Home Assistant, I have implemented a basic approach to limiting your peak hourly energy consumption and cutting power during peak price hours. 

PowerWiz doesn’t have dependencies like Node Red or other addons. The hard requirements are access to your power meter readings and the power readings and on/off switch of the devices you include in your power saving scheme. If you also have access to the hourly accumulated and estimated energy consumption from your power meter, that is a plus, but you can create these two sensors yourself with access to the power meter reading alone.

PowerWiz will not try to speculate on how much money you have saved or how much you have spent; it will simply cut power to devices of your choosing when 1) you consume too much energy 2) the prices are too high.

You can control thresholds for cutting power, for how long the power should be cut, and how long devices must remain on before cutting power again.

Read more about [how to use PowerWiz at TheAwesomeGarage.com](https://theawesomegarage.com/blog/powerwiz-for-home-assistant-control-your-power)
