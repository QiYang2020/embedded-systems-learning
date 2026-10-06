---
type: concept
maturity: outline
scope: mcu
---

# MCU平台家族技术地图

## 学习策略

不平均学习所有平台。以STM32建立深度，用AT32/GD32验证迁移能力，用ESP32扩展RTOS、无线和联网。

| 平台 | 主要定位 | 建议深度 |
|---|---|---:|
| STM32 | MCU主学习平台 | L4 |
| AT32 | Cortex-M国产MCU迁移 | L2～L3 |
| GD32 | Cortex-M国产MCU迁移 | L2～L3 |
| ESP32 | RTOS、Wi-Fi、蓝牙、OTA | L3 |
| RK | Linux/Android SoC，非MCU同类路线 | L3 |

## 跨平台比较维度

- 启动文件、链接脚本和内存布局
- 时钟树、引脚复用和中断
- HAL、SDK或设备框架
- DMA、Flash和低功耗
- 编译、烧录和调试工具
- RTOS、网络和升级机制

## 权威来源

- [STM32 MCU Developer Zone](https://www.st.com/content/st_com/en/stm32-mcu-developer-zone.html)
- [ESP-IDF Programming Guide](https://docs.espressif.com/projects/esp-idf/en/latest/)
- [Artery AT32](https://www.arterychip.com/)
- [GigaDevice GD32 MCU](https://www.gigadevice.com/product/mcu)

## 关联主题

- [[03-MCU固件开发/STM32/STM32技术地图]]
- [[04-嵌入式Linux与RK/RK技术地图]]
