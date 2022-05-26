## [Get this title for $10 on Packt's Spring Sale](https://www.packt.com/B08216?utm_source=github&utm_medium=packt-github-repo&utm_campaign=spring_10_dollar_2022)
-----
For a limited period, all eBooks and Videos are only $10. All the practical content you need \- by developers, for developers

# IoT Projects with Bluetooth Low Energy
This is the code repository for [IoT Projects with Bluetooth Low Energy](https://www.packtpub.com/hardware-and-creative/iot-projects-bluetooth-low-energy?utm_source=github&utm_medium=repository&utm_campaign=9781788399449), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Bluetooth Low Energy, or Bluetooth Smart, is Wireless Personal Area networking aimed at smart devices and IoT applications. BLE has been increasingly adopted by application developers and IoT enthusiasts to establish connections between smart devices.

This book initially covers all the required aspects of BLE, before you start working on IoT projects. In the initial stages of the book, you will learn about the basic aspects of Bluetooth Low Energy—such as discovering devices, services, and characteristics—that will be helpful for advanced-level projects. This book will guide you through building hands-on projects using BLE and IoT. These projects include tracking health data, using a mobile App, and making this data available for health practitioners; Indoor navigation; creating beacons using the Raspberry Pi; and warehouse weather Monitoring. This book also covers aspects of Bluetooth 5 (the latest release) and its effect on each of these projects.

By the end of this book, you will have hands-on experience of using Bluetooth Low Energy to integrate with smart devices and IoT projects.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
private void initialiseBluetooth() {
bluetoothManager =
(BluetoothManager)getSystemService
(Context.BLUETOOTH_SERVICE);
bluetoothAdapter = bluetoothManager.getAdapter();
bluetoothLeScanner = bluetoothAdapter.getBluetoothLeScanner();
}
```

This book will guide you through the installation of all the tools that you need to follow the
code samples. Code samples introduced in various chapters are for both Android and iOS
platforms hence you will need to install the Android Studio and XCode IDEs. Since
simulators lack Bluetooth functionality, hence you will need physical Android and iOS
devices to run the code samples. In terms of hardware, you will be needing a Raspberry Pi
for the Code Lab specific for Chapter 5, Beacons with Raspberry Pi. For Chapter 4, Designing
a Personal Tracking System, and Chapter 6, Weather Monitoring Using BLE in Warehouses, you
will be needing a very low cost iTag and the Texas Instruments Sensor Tag. All of the
hardware can be easily procured online.

## Related Products
* [IoT: Building Arduino-Based Projects](https://www.packtpub.com/hardware-and-creative/iot-building-arduino-based-projects?utm_source=github&utm_medium=repository&utm_campaign=9781787120631)

* [Building Bluetooth Low Energy Systems](https://www.packtpub.com/hardware-and-creative/building-bluetooth-low-energy-systems?utm_source=github&utm_medium=repository&utm_campaign=9781786461087)

* [Intelligent IoT Projects in 7 Days](https://www.packtpub.com/hardware-and-creative/intelligent-iot-projects-7-days?utm_source=github&utm_medium=repository&utm_campaign=9781787286429)

