# RK技术地图

## 认识平台

- RK芯片系列与定位
- 开发板、核心板与底板
- Linux / Android BSP
- 启动链、镜像与烧录

## 系统开发

- 交叉编译
- U-Boot、Kernel、RootFS
- 设备树
- 内核驱动与用户态接口
- 系统服务和应用部署

## 图形界面位置

- Qt、LVGL或Android UI：应用与GUI框架
- Skia、OpenGL ES、Vulkan：绘制或图形API
- Wayland、Weston、SurfaceFlinger：窗口和合成
- DRM/KMS：Linux显示管理
- GPU、显示控制器、面板和触摸驱动：内核及厂商栈

参见[[06-图形界面开发/图形界面开发入口]]和[[06-图形界面开发/Linux图形栈技术地图]]。当前以理解图形栈和完成框架适配为目标，不深入GPU驱动内部。

## 其他平台能力

- 显示、摄像头、NPU和多媒体
- 网络和存储
- 与MCU通过UART、USB、SPI或网络协同
