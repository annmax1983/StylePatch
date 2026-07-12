# StylePatch

[English](README.md) | [中文](README_zh.md) | [Español](README_es.md) | [Deutsch](README_de.md) | [日本語](README_ja.md) | [Français](README_fr.md)

轻量浏览器插件，一键自定义任意网页背景色、文字颜色与字体大小

> 基于Chromium内核 · Manifest V3规范 · 无数据追踪 · 分网站独立配置

## 功能一览

| 功能 | 说明 |
|------|------|
| 🎨 自定义背景&文字颜色 | 内置取色器选色，也可直接输入十六进制色值 |
| 🔠 字体缩放调节 | 缩放范围80%–150%，使用CSS zoom适配 |
| 👁️ 预设主题 | 明亮、暖色调、绿豆沙、暗色四套预设一键切换 |
| 🔄 全局开关 | 启用/禁用插件，不影响已保存设置 |
| 🚫 网站黑名单 | 排除不需要美化的网站 |
| 💾 分网站保存配置 | 不同网站可保存专属样式，再次访问自动生效 |
| ⚡ 实时预览效果 | 拖动调节即时生效，无需刷新页面 |
| 🌍 多语言支持 | 支持中文、英语、西班牙语、德语、日语、法语 |
| 🔒 最小权限请求 | 仅申请storage和host_permissions权限 |
| 🏗️ Manifest V3 | 使用chrome.scripting.insertCSS注入，零content script开销 |

## 效果预览

<p align="center">
  <img src="screenshot/zh.png" alt="StylePatch预览图" width="640">
</p>

## 支持浏览器

| 浏览器 | 兼容状态 |
|--------|----------|
| Google Chrome | ✅ 完全支持 |
| Microsoft Edge | ✅ 完全支持 |
| 其他Chromium内核浏览器 | ✅ 均可正常使用 |

## 安装步骤

1. 打开浏览器扩展管理页面
   - Chrome：`chrome://extensions/`
   - Edge：`edge://extensions/`
2. 开启右上角「开发者模式」开关
3. 点击「加载已解压的扩展程序」，选中项目文件夹
4. 点击工具栏StylePatch图标即可开始使用

## 使用教程

1. 点击浏览器工具栏上StylePatch图标
2. 设置颜色：使用取色器挑选，或直接输入十六进制色号
3. 选择预设：明亮、暖色调、绿豆沙、暗色四套一键切换
4. 调节字体：拖动滑块，缩放区间80%–150%
5. 保存配置：点击「应用并保存」，当前网站样式永久留存
6. 重置页面：点击↺按钮，恢复网页原始默认样式
7. 排除网站：点击「排除此网站」，该域名不再生效
8. 全局开关：使用启用/禁用开关，临时关闭不丢失设置

## 隐私说明

- 仅使用storage和host_permissions权限，无额外权限
- 不会读取浏览记录、不追踪用户行为、不上传任何数据至外网
- 所有配置数据仅保存在本地浏览器，不会外泄

## 版权许可

Copyright © 2026 StylePatch 保留所有权利

---

## ❤️ 支持作者

如果 StylePatch 对你有帮助，请作者喝杯咖啡吧！

**[👉 点击这里支持](https://ko-fi.com/annmax?buyACoffee=true&ref=stylepatch)**
