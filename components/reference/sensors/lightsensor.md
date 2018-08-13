# LightSensor

LightSensor is a non-visible component that measures the ambient light level \(illumination\) in lx.

**Event-handler block.** Event is triggered when a sensor change occurred

![](../../../.gitbook/assets/image%20%2815%29.png)

**Properties block.**

LightSensor includes following properties-blocks. They allow you to determine if user's device has this type of sensor or enable / disable this sensor.

![](../../../.gitbook/assets/image%20%2811%29.png) ![](../../../.gitbook/assets/image%20%2818%29.png)

Example

In Screen initialize , you can check if LightSensor is available or not. You can use block LightSensor.LightChanged to determine the sensitivity of light changed in lx unit:

![](../../../.gitbook/assets/6a6d31b9-5a91-4f26-8562-2924ec75ffde.jpg)

![](../../../.gitbook/assets/image%20%2820%29.png)

