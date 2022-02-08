# Tuya IoTOS 综合 SDK

[English](./README.md) | [中文](./README_zh.md)

## 概述

Tuya IoTOS 综合 SDK 采用分层、插拔式组件的方式设计，各个业务被划分成独立的组件库，开发者按需链接对应的组件库，以实现快速构建具有差异性的网关产品。

SDK 提供基本的连接涂鸦云的能力，支持工程施工、故障替换、本地自动化以及跨网关局域网联动等功能。

SDK 还提供设备管理的能力，搭配涂鸦网关 Zigbee 模组和蓝牙模组，可以低代码实现涂鸦生态子设备接入，也可以使用自定义模组，如 Zigbee、433、485、Z-Wave、Lora 等，把子设备接入到涂鸦生态，与涂鸦生态其他智能设备互联互通。

SDK 还提供安防、红外、中控、路由器和中继器等能力，支持开发复合型网关。

基于 SDK 能够开发的产品有：  

- 搭配涂鸦网关 Zigbee 模组，低代码实现接入涂鸦生态 Zigbee 子设备的网关产品。同时，支持接入第三方 Zigbee 子设备，与涂鸦生态的智能设备互联互通。
- 搭配涂鸦网关蓝牙模组，低代码实现接入涂鸦生态蓝牙子设备的网关产品，支持蓝牙配网。
- 特定协议模组，实现特定协议的网关产品，把子设备接入到涂鸦生态，与涂鸦生态的智能设备互联互通。
- 低代码实现路由器和中继器产品。
- 低代码实现安抚网关产品。
- 低代码实现中控产品。
- 更多产品......

## 下载

访问 [下载](./DOWNLOAD.md) 页面，下载您所使用的工具链对应的产物包。本仓库提供最新稳定版本 SDK 下载，如果您所使用的工具链，请联系涂鸦技术支持。

## 技术架构  

![](https://images.tuyacn.com/fe-static/docs/img/ff480bfc-5c51-4933-bdb6-8b726aa15dc5.jpg)

## 目录结构  

```  
.
├── apps                # 应用示例代码目录，开发者可以根据需求修改
├── build_app.sh        # 编译脚本
├── CHANGELOG.md        # 版本信息
├── doc                 # API 文档
├── gen_demo.py         # （可选）demo 示例代码生成脚本
├── platforms           # 工具链，编译时会自动把工具链下载到该目录下
├── README.md           
├── sdk
│   ├── include         # SDK 头文件
│   └── lib             # SDK 库文件，开发者可以按需链接
└── template            # （可选）demo 模板文件，gen_demo.py 使用
```

## 快速开始

- [快速入门](https://developer.tuya.com/cn/docs/iot-device-dev/integrated_sdk_quick_start?id=Kb6bj1rn0wrnl)
- [开发文档](https://developer.tuya.com/cn/docs/iot-device-dev/integrated_sdk_development_guide?id=Kb8xgrcicra72)
- [接口说明](https://developer.tuya.com/cn/docs/iot-device-dev/integrated_sdk_api?id=Kb8xfvo1dp6wc)

## 获取支持

如果您在开发过程中遇到任何问题，请通过以下渠道获取支持。

- [涂鸦 IoT 开发者平台](https://developer.tuya.com/cn)  
- [涂鸦帮助中心](https://support.tuya.com/zh/help)  
- [涂鸦技术工单平台](https://service.console.tuya.com)  

## License

[MIT License](./LICENSE)