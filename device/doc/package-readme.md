# Azure IoT Hub Device Client SDK

## How to Install
```
pip install azure-iothub-device-client
```

Additionally, if running on Linux or OSX:

```
apt-get install libboost-python-dev
```

For best results, ensure that your version of boost is >= 1.58

## Feature List
Use this SDK to:

* Send event data to Azure IoT Hub
* Recieve messages from Azure IoT Hub
* Communicate with Azure IoT Hub via AMQP, MQTT or HTTP protocols
* Synchronize an Azure IoT Hub Device Twin or Module Twin with Azure IoT Hub from a device or module
* Implement Azure IoT Hub Direct Device/Module Methods on devices/modules
* Implement Azure IoT Device/Module Management features on devices/modules
* Implement Azure IoT Edge and custom modules connecting to Edge Hub

## User Guides
* Read the [Azure IoT Fundamentals][iot-fundamentals] guide to get an overview of what Azure IoT can do.
* Read the [Azure IoT Hub][iothub-doc] guide to understand how to connect devices to the Azure IoT Hub using this SDK.
* Read the [Azure IoT Edge][edge-doc] guide to understand how to bring the power of the IoT Hub "to the edge" instead of the cloud.

## Examples
Please refer to our [sample repository][device-samples] for examples of how to use the Azure IoT Hub Device Client SDK.


[iot-fundamentals]: https://docs.microsoft.com/en-us/azure/iot-fundamentals/
[iothub-doc]: https://docs.microsoft.com/en-us/azure/iot-hub/
[edge-doc]:
https://docs.microsoft.com/en-us/azure/iot-edge/
[device-samples]: https://github.com/Azure/azure-iot-sdk-python/tree/master/device/samples