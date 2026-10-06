---
type: concept
maturity: outline
scope: mcu
---

# RTOS技术地图

## 解决的问题

RTOS为多个并发职责提供可预测的任务调度、通信和同步机制。它不是普通桌面操作系统，也不会自动解决错误的软件结构。

## 核心知识

```text
任务与调度
├─ 优先级、阻塞、延时和时间片
├─ 队列、任务通知和事件组
├─ 信号量、互斥锁和优先级反转
├─ 中断与任务通信
├─ 任务栈和动态/静态内存
└─ 死锁、饥饿和实时性分析
```

## 学习路线

1. 先理解裸机非阻塞状态机。
2. 以FreeRTOS作为第一套深入RTOS。
3. 完成任务、队列、中断通信、互斥和栈监控实验。
4. 再比较RT-Thread的设备框架、组件和软件包生态。

## FreeRTOS与RT-Thread

| 项目 | FreeRTOS | RT-Thread |
|---|---|---|
| 强项 | 内核小、生态广、厂商集成多 | 设备框架和组件生态完整 |
| 当前定位 | 第一主线 | 后续对比与扩展 |

## 权威来源

- [FreeRTOS Documentation](https://www.freertos.org/Documentation/RTOS_book.html)
- [RT-Thread Documentation](https://www.rt-thread.io/document/site/)

## 关联主题

- [[01-系统基础/裸机-状态机-RTOS]]
- [[01-系统基础/轮询-中断-DMA]]
- [[03-MCU固件开发/MCU固件入口]]
