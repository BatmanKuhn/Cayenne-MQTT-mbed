# Cayenne MQTT mbed Library
The Cayenne MQTT mbed Library provides functions to easily connect to the Cayenne IoT project builder.

This library bundles the [Eclipse Paho MQTT C/C++ client](https://github.com/eclipse/paho.mqtt.embedded-c).

## Repository Structure
- **src** - The library source code.
  - **CayenneUtils** - Common code for creating and parsing Cayenne topics and payloads. This code can be used with any MQTT client.
  - **CayenneMQTTClient** - Platform independent Cayenne C++ library using the Paho MQTT C++ library. To create platform specific versions of this library networking and timer code for the platform are required.
  - **MQTTCommon** - Common Paho MQTT C code used by both the C and C++ libraries.
  - **Platform** - Platform specific networking and timer code, as well as test and example applications.

## Other Cayenne Libraries
- **[Cayenne-MQTT-C](https://github.com/myDevicesIoT/Cayenne-MQTT-C)** - C version of the Cayenne MQTT Library.
- **[Cayenne-MQTT-CPP](https://github.com/myDevicesIoT/Cayenne-MQTT-CPP)** - C++ version of the Cayenne MQTT Library.

