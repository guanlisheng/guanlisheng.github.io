---
layout: default
title: "Poker Terminal — 技术支持"
description: "Poker Terminal 使用帮助：配置终端地址、遥控排查、外接屏显示与网络问题。"
permalink: /support/pokerterminal-zh/
---

# Poker Terminal 技术支持

[English]({{ '/support/pokerterminal/' | relative_url }}) · [营销页]({{ '/marketing/pokerterminal-zh/' | relative_url }}) · [隐私政策]({{ '/privacy/pokerterminal/' | relative_url }})

## 快速开始

1. 打开 App，默认会加载应用内配置的演示终端地址。
2. 在主界面的 **设置** 入口中，将终端地址替换为你自己的 HTTPS 赛事终端页面。
3. 连接成功后，即可查看级别、盲注、前注、倒计时、参赛人数与计分数据。
4. 若系统提供独立外接屏，赛事页面会在外接屏全屏显示，iPhone 保留控制界面。

## 修改终端地址

- 进入主界面 → **设置** → **终端地址**。
- 仅支持 `https://` 开头的地址；输入后保存并返回主界面重新加载。
- 终端地址保存在本机，不会上传到任何服务器。

## 遥控功能不工作

遥控依赖目标网页提供兼容的 **TerminalRemote** 接口：

- 如果网页未提供该接口，遥控按钮会不可用，但页面仍可正常显示。
- 如果网页已提供接口但遥控无响应，请确认页面已完全加载，并尝试手动刷新。
- 遥控接口属于终端网页的实现，应用无法为不兼容的网页启用遥控。

## 电视没有独立显示赛事页面

- 独立外接屏需要 iOS 与接收设备同时支持独立显示场景。
- 若系统仅提供 **屏幕镜像**，电视会显示整个 iPhone 画面，这是系统行为。
- 可尝试在 iOS 控制中心检查外接屏设置，或更换支持独立显示的接收设备。

## 网络与加载问题

- **一直加载**：确认终端地址可访问，且设备网络正常。
- **连接错误**：检查地址是否为 HTTPS、证书是否有效、终端服务是否在线。
- **页面空白**：尝试手动刷新；若仍空白，确认终端页面本身可正常打开。
- 若终端位于局域网，iOS 可能请求 **本地网络** 权限，请允许后重试。

## 联系支持

如以上内容无法解决问题，请邮件联系：

**your-email@example.com**

邮件中请附上：iOS 版本、设备型号、终端地址类型（公网/局域网）、错误提示截图。请勿发送终端登录凭据或赛事敏感数据。

## 相关链接

- [隐私政策]({{ '/privacy/pokerterminal/' | relative_url }})
- [营销页]({{ '/marketing/pokerterminal-zh/' | relative_url }})
- [所有 App]({{ '/marketing/' | relative_url }})
