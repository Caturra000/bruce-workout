# Bruce的硬核训练

单文件 HTML、多平台同步的健身打卡 app。

## 亮点

- 自定义训练计划
- 每日训练记录
- 热力图统计
- 历史回放
- JSON 导入导出
- 无后端，无需账号
- GitHub 跨设备/云同步
- iOS/Android 应用支持

## 快速开始

任选以下方式：
- 直接使用静态网站：<https://workout.bluepuni.com>
- 或 保存 index.html，本地用浏览器打开
- 或 自行部署静态网站，比如 GitHub Pages

手机上可以进一步作为 Android/iOS app 去使用（基于 [PWA](https://developer.mozilla.org/zh-CN/docs/Web/Progressive_web_apps)）：
- iOS: Safari - 分享⬆ - 添加到主屏幕
- Android: Chrome - 三个点┇ - 添加到主屏幕

## 数据隐私

数据持久保存在本地。如果使用云同步，数据也会保存在你指定的 GitHub 仓库。

本项目不收集任何隐私信息。

## 许可证

MPL 2.0

## Changelog

v0.1:
- 试行 single-html-workout：统计、跟踪、JSON 备份、PWA。

v1.0:
- 改名 bruce-workout。
- 实现 GitHub Contents API 多平台同步。
- 修复 Safari 的 PWA 兼容性问题。（Only Apple can do!）

v1.1:
- 修复 Safari 的 16px 兼容性问题。（Only Apple can do!）

v10.0:
- 实现 GitHub 指定历史版本的拉取。
- 修复 GitHub token 显示溢出。

v11.0:
- 实现 sw.js 同时保持 single HTML，做法是比较反模式的。

v11.1:
- 修复动作修改显示，兼容屏宽偏窄的折叠机。
- 修复 sw 缓存策略，避免 GitHub Contents API 冲突。

v100.0:

v101.0:

v110.0:
