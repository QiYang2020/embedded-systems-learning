---
type: concept
maturity: outline
scope: architecture
---

# ARM Cortex-M、R、A技术地图

## 定位

| 系列 | 主要目标 | 常见运行环境 | 当前深度 |
|---|---|---|---:|
| Cortex-M | 低功耗、确定性控制 | 裸机、FreeRTOS、RT-Thread | 深入 |
| Cortex-R | 高可靠硬实时 | 汽车、存储、工业安全系统 | 了解定位 |
| Cortex-A | 高性能应用处理 | Linux、Android | 熟悉 |

## 关系

Cortex是处理器内核系列，不是完整芯片。STM32、AT32、GD32多采用Cortex-M；RK通常采用Cortex-A。芯片厂商还会集成存储器、总线、外设控制器和专用加速单元。

## 学习重点

- Cortex-M：向量表、NVIC、异常、中断、SysTick、内存映射和调试。
- Cortex-R：知道实时性、可靠性和功能安全定位。
- Cortex-A：异常级、MMU、Cache、多核、用户态与内核态。

## 权威来源

- [Arm Cortex-M processors](https://www.arm.com/products/silicon-ip-cpu/cortex-m)
- [Arm Cortex-R processors](https://www.arm.com/products/silicon-ip-cpu/cortex-r)
- [Arm Cortex-A processors](https://www.arm.com/products/silicon-ip-cpu/cortex-a)

## 关联主题

- [[01-系统基础/Cortex-M与Cortex-A]]
- [[01-系统基础/MCU-MPU-SoC与开发板]]
- [[01-系统基础/MCU与Linux系统分层对比]]
