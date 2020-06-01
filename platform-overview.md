# Platform Overview

The Relay platform has two sides - on one side are your devices and sensors, and on the other is a cloud portal giving you secure access to your devices and sensors from anywhere you have an internet connection.

![Relay Platform Overview](https://edgecastle.github.io/docs/images/platform-overview.jpg)

## Relay "Edge"

In "Internet of Things" (IoT) terms, the "edge" is where web-connected devices and sensors are.

Relay provides several ways for edge devices to securely communicate with the Relay cloud platform.

More capable devices like the [Raspberry Pi](https://www.raspberrypi.org), which can run full operating systems, can use rich, interactive methods of authenticating like [OpenID Connect](https://openid.net/connect/). 

Meanwhile, simpler web-connected devices such as the ESP8266 Arduino Wifi Module (also known as the NodeMCU) can use (API Key authentication)[./security].