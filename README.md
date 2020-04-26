# mongoose_ds18b20
外部的温湿度传感器，DS18b20驱动代码

# 配置

DS18B20 是一款温度传感器，ESP32可以通过 1-Wire 协议与 DS18B20 进行通信，最终将温度读出。1-Wire 总线的硬件接口很简单，只需要把 DS18B20 的数据引脚和ESP32的一个 IO 口接上就可以了

![](https://wiki.jikexueyuan.com/project/mcu-tutorial-three/images/35.png)

# main.c

- 编写1-Wire总线读时序接口

- 实时监控环境温度


