---
type: concept
maturity: outline
scope: interface
---

# USB技术地图

## 分层

```text
应用功能
→ USB Class
→ Endpoint与传输类型
→ USB Device/Host协议栈
→ USB控制器与PHY
→ 线缆和设备
```

## 角色

- Device：作为外设连接电脑或主机。
- Host：枚举并管理外部USB设备。
- OTG：根据连接场景切换角色。

## 传输类型

- Control：枚举和配置
- Bulk：可靠大块数据
- Interrupt：低延迟小数据
- Isochronous：实时音视频，允许一定丢失

## 常见Class

- CDC：虚拟串口
- HID：键盘、鼠标和自定义HID
- MSC：U盘类存储
- UAC：音频
- UVC：视频

## 学习顺序

USB Device CDC/HID → 描述符与枚举 → Endpoint与抓包 → MSC → 按项目进入Host、UAC或UVC。

## 权威来源

- [USB-IF Specifications](https://www.usb.org/documents)

## 关联主题

- [[05-接口与通信/接口与通信入口]]
- [[02-工具链与调试/分层故障诊断]]
