# Tuya IoTOS Integrated SDK

[English](./README.md) | [中文](./README_zh.md)

## Overview

With a component-based plug-and-play architecture, the Tuya IoTOS integrated SDK helps you build an IoT-enabled gateway in a quick and easy way. Each service is offered in an independent component library, allowing you to flexibly implement and adjust your service offerings as the market needs change over time.

The integrated SDK provides cloud connectivity as well as a bunch of features such as engineer mode, failover, local automation, and cross-gateway LAN-based linkage.

This SDK comes with device management capability. With Tuya's Zigbee modules and Bluetooth modules, you can integrate with the `Powered by Tuya` (PBT) ecosystem through low-code development. If your product is built with third-party modules, such as Zigbee, RS-433, RS-485, Z-Wave, and LoRa, you can also connect them to the PBT ecosystem to interact with other PBT devices.

This SDK provides capabilities in terms of security, infrared, control hub, router, relay, and repeater to help develop a multifunctional gateway.

What you can build with the integrated SDK:

- With Tuya's Zigbee module, build gateways that can connect to PBT Zigbee devices. Third-party Zigbee devices can also be connected to the gateway so that they can interact with the `Powered by Tuya` ecosystem.
- With Tuya's Bluetooth module, build gateways that can connect to PBT Bluetooth devices and pair devices over Bluetooth.
- With your proprietary or third-party modules, such as Zigbee, RS-433, RS-485, Z-Wave, and LoRa, build gateways that enable interconnection to the PBT ecosystem.
- Routers and repeaters.
- Gateway with security features.
- Control hub.
- And many more.

## Download

[Download](./DOWNLOAD.md) the toolchain and production package. You can download the latest SDK from this repository. If you do not find the desired toolchain, please contact Tuya's technical support.

## Architecture

![](https://images.tuyacn.com/fe-static/docs/img/ff480bfc-5c51-4933-bdb6-8b726aa15dc5.jpg)

## Directory structure

```
├── apps                # The sample applications, which can be modified as needed.
├── build_app.sh        # The compilation script
├── CHANGELOG.md        # The changelog
├── doc                 # API documentation
├── gen_demo.py         # (Optional) demo script
├── platforms           # The toolchain. The toolchain will be automatically saved to this folder when you compile code.
├── README.md           
├── sdk
│   ├── include         #  Header file.
│   └── lib             # The SDK library.
└── template            # (Optional) The demo template, used in tandem with gen_demo.py.
```

## Quick start

- [Quick Start](https://developer.tuya.com/en/docs/iot-device-dev/integrated_sdk_quick_start?id=Kb6bj1rn0wrnl)
- [Documentation](https://developer.tuya.com/en/docs/iot-device-dev/integrated_sdk_development_guide?id=Kb8xgrcicra72)
- [API Reference](https://developer.tuya.com/en/docs/iot-device-dev/integrated_sdk_api?id=Kb8xfvo1dp6wc)


## Technical support

You can get support from Tuya with the following methods:

+ [Tuya Developer Platform](https://developer.tuya.com/en/)
+ [Help Center](https://support.tuya.com/en/help)
+ [Service & Support](https://service.console.tuya.com)

## License

[MIT License](./LICENSE)
