# 白龙 · 柔光 — Codex 毛玻璃主题

白色与淡紫色的白龙背景，搭配半透明侧栏、圆角输入框，以及用户消息和助手回复的毛玻璃效果。

![白龙背景原图](background.png)

> 上图是背景素材，不是客户端运行截图。本项目是社区主题，依赖 **Codex Dream Skin**，不是 OpenAI 官方主题或独立客户端。

## 下载与安装

1. 安装官方 Codex / ChatGPT 桌面客户端。
2. 按照 [Codex Dream Skin 中文说明](https://github.com/Fei-Away/Codex-Dream-Skin/blob/main/README.zh-CN.md) 安装对应系统的皮肤引擎。安装程序来自 [上游 Releases](https://github.com/Fei-Away/Codex-Dream-Skin/releases)。
3. 下载本仓库的 [WhiteDragon-Glass-v1.0.0.zip](https://github.com/DaiNaAuToMan/codex-white-dragon-glass/releases/latest/download/WhiteDragon-Glass-v1.0.0.zip)，打开文件页面后点击下载按钮。
4. 在 Codex Dream Skin 托盘菜单（macOS 为菜单栏）选择 **Import Theme ZIP / 导入主题 ZIP**，选中下载的 ZIP。
5. 导入后，再从 **Saved Themes / 已保存主题** 中选择 **白龙 · 柔光**。导入只添加到主题库，不会自动切换。
6. 打开主题管理器，将透明度设为 **75%**，作为起始效果；想让背景更明显，可以继续调高。

**导入的是 `WhiteDragon-Glass-v1.0.0.zip`，不是 GitHub 的整个仓库 Source code ZIP。** 不需要先解压主题 ZIP，也不需要安装 Node.js 或运行脚本。

## 毛玻璃效果

| 区域 | 样式 |
| --- | --- |
| 用户消息、助手回复 | 16px 背景模糊、轻微饱和度增强、16px 圆角、淡紫描边、轻阴影 |
| 输入框 | 14px 背景模糊、24px 圆角、淡紫描边 |
| 侧栏 | 12px 背景模糊、柔和白色底层 |
| 对话框 | 14px 背景模糊、18px 圆角 |

透明度调整的是背景层，文字和图标不会一起变淡。主题 ZIP 不会携带或覆盖你的本地透明度偏好，所以首次导入后请手动调整。即使设为 100%，消息区域仍声明背景模糊效果；实际观感取决于引擎和客户端版本。

## 版本与兼容性

- v1.0.0 提取自 2026-10-29 正在使用的活动主题，包含后续新增的对话毛玻璃样式，以及输入框内部重复底色的修复。
- 使用 Dream Skin schemaVersion 1 的简化主题 ZIP 格式，包含且仅包含 `theme.json`、`theme.css`、`background.png`。
- 已通过本机 Codex Dream Skin v1.5.21 的主题包与 Safe CSS 校验。
- 运行效果的既有验证环境为 Windows 11 + 本机定制的 Dream Skin v1.5.21。尚未在全新安装的上游引擎及 macOS 上做完整视觉验收。
- 本机另有引擎层的界面细节修复；本主题包提供背景、颜色和毛玻璃样式，不包含那些引擎补丁。不同客户端版本下的首页布局、项目图标等细节可能不同。

## 常见问题

**导入后没有变化？** 导入和切换是两个步骤，请在已保存主题中选择“白龙 · 柔光”。

**背景太白，或者太透？** 在主题管理器调整透明度。建议从 75% 开始；数值越大，背景层越透明。

**如何恢复？** 使用 Codex Dream Skin 自带的恢复原版外观入口，或切换到其他主题。不要手动删除客户端文件。

**是否包含启动动画？** 本包分享的是背景与毛玻璃主题。启动动画是独立项目，不是使用本主题的前提，参见 [Dragon Codex Boot](https://github.com/yushua0808-cpu/dragon-codex-boot)。

## 文件与来源

仓库根目录保存可编辑的 `theme.json`、`theme.css`、`background.png`，以及可直接导入的主题 ZIP 和 SHA-256 校验值。发布版本也提供主题 ZIP 下载。

感谢 [Fei-Away / Codex-Dream-Skin](https://github.com/Fei-Away/Codex-Dream-Skin) 提供皮肤引擎。本项目仅分享定制主题，不打包官方客户端、上游安装器或个人运行数据。下载包不包含聊天记录、账号凭据、浏览器 profile、日志或本机路径。

欢迎下载体验、分享本仓库链接。OpenAI、ChatGPT、Codex 等名称及相关标识属于各自权利人，本主题不代表官方认可。

