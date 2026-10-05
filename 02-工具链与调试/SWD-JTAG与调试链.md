# SWD、JTAG与调试链

## 完整链路

```text
IDE调试界面
→ GDB
→ GDB Server或OpenOCD
→ USB调试探针
→ SWD/JTAG
→ 目标芯片
```

## 需要掌握

- SWDIO、SWCLK、GND、VTref、RESET的作用
- 调试探针固件与PC端驱动的区别
- 目标供电和参考电压
- 连接失败、芯片锁定和复位模式
- 断点、单步、调用栈、寄存器和内存查看
- ST-LINK、J-Link和CMSIS-DAP的工具生态

## 参与边界

需要使用、配置和排障调试链；不以设计调试器硬件或开发调试器固件为目标。
