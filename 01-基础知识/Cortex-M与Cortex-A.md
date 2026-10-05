# Cortex-M与Cortex-A

## 定位

Cortex-M面向微控制器和实时控制；Cortex-A面向运行复杂操作系统的应用处理器。

| 维度 | Cortex-M | Cortex-A |
|---|---|---|
| 常见平台 | STM32 | Rockchip RK |
| 操作环境 | 裸机或RTOS | Linux或Android |
| 内存 | 片上Flash/SRAM为主 | 外部DDR和存储 |
| 启动 | 毫秒级、流程直接 | 多级启动链 |
| 实时性 | 强、容易预测 | 受调度和系统负载影响 |
| 应用 | 控制、采集、低功耗 | UI、网络、媒体、AI |

## 关键理解

Cortex-M上，程序往往与硬件紧密结合，中断和寄存器是核心。Cortex-A通常启用MMU，应用运行在用户态，通过内核驱动访问硬件。

Unity应用在RK上更接近普通Android/Linux应用；在STM32上不存在Unity运行时，需要把需求转化为C代码、状态机或RTOS任务。

## 常见误解

- Cortex是ARM定义的处理器架构或内核系列，不是完整芯片。
- Cortex-A并不天然具备实时性。
- Cortex-M也可以运行操作系统，但通常是RTOS而不是完整Linux。

## 下一步

结合[[01-基础知识/MCU与Linux系统分层对比]]理解两类平台的软件边界。
