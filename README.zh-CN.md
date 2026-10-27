# Nord · Prism

**蓝灰底色、雪色文字，让内容有清晰的位置。**

[English](README.md) · [下载 theme.json](https://github.com/EllisMorrow/tine-theme-nord-prism/releases/latest/download/theme.json)

Prism 系列的第一款主题：以 Nord 配色为基础，为 Tine 适配青色链接、紫色标签与琥珀色高亮。只提供颜色，保留 Tine 与用户自己的字体、排版设置。

![Nord · Prism 深色模式实拍](docs/nord-dark.png)

## 安装

1. 下载上方的 `theme.json`。
2. 在 Tine 中打开 **设置 → 外观 → 主题包 → 选择 theme.json**。
3. 选择文件，点击 **使用颜色**，切换至 **深色模式**。

需要支持 Tine 主题 API 0.2 的版本。图谱的 `logseq/custom.css` 仍有更高优先级；设备上的自定义强调色也可能影响强调色或链接的实际显示。

## 配色与边界

| 角色 | 颜色 |
| --- | --- |
| 主背景 / 侧栏 | `#2e3440` / `#272c36` |
| 正文与标题 | `#d8dee9` |
| 强调色 / 链接 | `#88c0d0` / `#b6d9e2` |
| 标签 / 高亮文字 | `#b48ead` / `#ebcb8b` |

主题提供全部 21 个受支持的深色颜色变量，不包含脚本、额外 CSS、字体或布局预设。语法高亮、任务标记及其它超出主题包 API 的样式由 Tine 控制。

**本包不提供浅色配色。** 切换至浅色模式后使用 Tine 的回退外观。下面的截图用于兼容性展示，不是 Nord 浅色版。

<details>
<summary>查看浅色模式兼容性截图</summary>

![Tine 浅色模式回退外观，并非 Nord 浅色配色](docs/nord-light-fallback.png)

</details>

## 验证情况

已通过 Tine 官方主题格式检查，并收到 Windows 下的明暗实机截图，展示标题、正文、层级、链接、标签、行内代码、导航与引用区域。截图未覆盖高亮、文字选中和设置等所有状态，不据此宣称全部交互或平台均已验证。主题包也不包含早期本地 CSS 原型中超出官方 API 的组件规则。

## 来源与许可

Nord 配色来自 [Sven Greb / Nord](https://github.com/nordtheme/nord)，遵循 [MIT 许可](LICENSE)。Tine 适配与 Prism 打包由 EllisMorrow 完成，使用 AI 辅助开发。最初的本地原型参考了 Codex 中 Nord 预设的视觉角色；仓库不包含 Codex 程序代码、标志或附带资源。本主题为独立社区适配，不代表 Nord 或 OpenAI 官方产品。

问题反馈请在本仓库创建 Issue，附上 Tine 版本、系统、当前模式，以及不包含私人笔记的截图。
