# ContinuousCulture
**ESP8266 control sketches, sensor datasheets and hardware drawings for automated microalgae continuous culture system.**
**基于ESP8266的自动化微藻连续培养系统：控制代码、传感器说明书与硬件图纸**

This repository contains ESP8266 source code, sensor datasheets and CAD hardware drawings for photobioreactor platforms. It implements sensor data acquisition, WiFi wireless transmission, data logging and automatic actuator control for column reactors and raceway pond microalgae continuous culture experiments.
本仓库存放光生物反应器平台ESP8266源码、传感器资料与CAD硬件图纸，实现传感器数据采集、WiFi无线传输、数据记录与执行器自动控制，适配柱状反应器、跑道池微藻连续培养实验。

## Repository Structure | 仓库目录
- `/datasheets` — Sensor specification manuals
  `/datasheets` — 传感器说明书
- `/hardware_drawings` — CAD hardware drawings & wiring diagrams
  `/hardware_drawings` — CAD硬件图纸、接线原理图
- `/esp8266_code` — ESP8266 sketches: sensor reading, actuator control, WiFi data upload
  `/esp8266_code` — ESP8266程序：传感器读取、执行器控制、WiFi数据上传
- `/docs` — Hardware assembly guide, wiring notes and experiment documentation
  `/docs` — 硬件组装指南、接线说明与实验文档

## Application Scenarios | 应用场景
Automated continuous culture of microalgae, real-time monitoring of biomass and water quality parameters, wireless data transmission of photobioreactor.
微藻自动化连续培养，生物质、水质参数实时监测，光生物反应器数据无线上传。

## Requirements | 运行依赖
- Arduino IDE with ESP8266 board support package
- Related sensor driver libraries
Arduino IDE，安装ESP8266板支持包，配套传感器驱动库

## License | 许可证
MIT License
MIT开源协议
