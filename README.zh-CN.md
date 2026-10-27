# Catppuccin · Prism

**晨光里，一抹薰衣草；暮色中，几颗未眠的星。让思绪轻轻落在纸页上。**

[![发行附件下载量](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-catppuccin-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-catppuccin-prism/releases)

[English](README.md) · [下载 theme.json](https://github.com/EllisMorrow/tine-theme-catppuccin-prism/releases/latest/download/theme.json)

Latte 与 Mocha 相逢于同一款 Prism 主题：一页清浅晨色，一片深蓝夜幕，以薰衣草紫、蓝色链接和些许金色暖意相连。

### 深色模式

![Catppuccin · Prism 深色模式实拍](docs/catppuccin-dark.png)

### 浅色模式

![Catppuccin · Prism 浅色模式实拍](docs/catppuccin-light.png)

*用户测试后提供的 Windows 实机截图，两套配色均实际包含在同一个主题包中。*

## 安装

1. 下载 [theme.json](https://github.com/EllisMorrow/tine-theme-catppuccin-prism/releases/latest/download/theme.json)。
2. 在 Tine 打开 **设置 → 外观 → 主题包 → 选择 theme.json**，选择下载的文件。
3. 点击 **使用颜色**，选择 **浅色、深色或跟随系统**。

需要主题 API **0.2** 支持。原有 `logseq/custom.css` 和设备强调色可能影响效果；主题只负责 API 支持的颜色，不包含额外字体、布局或任务标记样式。

## 配色

| 角色 | 浅色 | 深色 |
| --- | --- | --- |
| 主背景 | `#eff1f5` | `#1e1e2e` |
| 侧栏 | `#e6e9ef` | `#181825` |
| 正文 | `#4c4f69` | `#cdd6f4` |
| 标题 | `#4c4f69` | `#cdd6f4` |
| 强调色 | `#8839ef` | `#cba6f7` |
| 链接 | `#1852c8` | `#8eb7fa` |
| 标签 | `#7632d0` | `#cba6f7` |
| 高亮底色 | `#ecddca` | `#4a4548` |

## 验证情况

通过官方主题格式检查；浏览器样例检查了两套完整变量、模式切换及指定颜色组合。用户提供了上方 Windows 明暗实机截图，展示公开欢迎页面上的标题、正文、层级、链接、标签、行内代码和引用区域。高亮、选中操作、设置状态和其它平台未由这些截图覆盖，不据此宣称全部路径均已验证。

## 来源与边界

基于 [Catppuccin Latte / Mocha](https://github.com/catppuccin/palette)，固定版本 `07d02aa110ef9eb7e7427afca5c73ba9cf7f8ebd`，采用 MIT 许可并保留 [原始声明](LICENSE)。两种模式均基于 Catppuccin 官方开源 Latte 与 Mocha 色板，对应 Codex 所采用的明暗系列；它们独立映射至 Tine 语义角色，选中背景和文字可读性调整逐项记录。

独立社区适配由 EllisMorrow 完成，使用 AI 辅助开发。不分发 Codex 程序代码、标志或附带资源，不代表相关项目或 OpenAI 的官方产品，也不承诺与 Codex 像素级一致。具体映射和验证边界见 [适配说明](docs/adaptation.md)。

顶部徽标统计 GitHub Release 附件累计下载量，不代表安装人数。可在本仓库反馈问题，附版本、系统、模式及不包含私人内容的截图。
