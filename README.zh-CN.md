# MarkTeX

[**简体中文**](README.zh-CN.md) | [**English**](README.md)

> 一款适用于 Windows 的实时 **Markdown + LaTeX** 渲染器。  
> 左侧编辑，右侧即时预览排版精美的数学公式与富文本。

---

## ✨ 特性

- **实时预览** — 300 毫秒防抖，边写边同步渲染
- **完整的 LaTeX 支持** — 通过 [KaTeX](https://katex.org/) 完美渲染行内 `$...$` 与独立块 `$$...$$` 公式
- **语法高亮** — 通过 [highlight.js](https://highlightjs.org/) 实现代码块自动高亮
- **三大主题** — 深色 (Dark) / 浅色 (Light) / 护眼 (Sepia) 模式，支持无缝实时切换
- **字体自定义** — 可直接在工具栏调整字体样式与大小
- **PDF 导出** — 导出 PDF 时支持选择纸张尺寸 (A4 / A3 / Letter / Legal)，且强制使用纯白背景以保证最佳阅读效果
- **打印支持** — 调用浏览器原生打印弹窗，无论当前处于何种主题，均强制使用白底打印
- **文件操作** — 支持快速打开 / 保存 `.md` 文件，内置 `Ctrl+S` / `Ctrl+O` 快捷键
- **分屏模式** — 提供双栏并排、纯编辑模式和纯预览模式自由切换

---

## 💡 适用场景

- **打印 AI 生成内容** — 完美承接从大语言模型（如 ChatGPT, Claude）复制的 Markdown 和数学公式，彻底告别复制到 Word 时格式错乱、公式变代码的烦恼，一键导出为排版精美的 PDF 文件。
- **学术与科研写作** — 极其适合数学、物理、计算机等理工科专业的学生和研究人员，用于快速起草包含大量公式的论文片段、作业或实验报告。
- **技术笔记沉淀** — 纯本地运行，作为轻量级的沉浸式 Markdown + LaTeX 桌面编辑器，随时记录灵感与推导过程。

---

## 🛠 技术栈

| 层面 | 技术 |
|---|---|
| UI 框架 | WPF (.NET 8) |
| Web 渲染引擎 | Microsoft WebView2 |
| Markdown 解析 | [marked.js](https://marked.js.org/) v12 |
| 数学公式渲染 | [KaTeX](https://katex.org/) v0.16 |
| 代码语法高亮 | [highlight.js](https://highlightjs.org/) v11 |

---

### 环境要求

- Windows 10 / 11
- [.NET 8 运行时](https://dotnet.microsoft.com/download/dotnet/8.0)
- [WebView2 运行时](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) (Windows 11 已默认预装；Windows 10 用户需自行下载)


### 运行发行版

请前往 Releases 页面下载最新版本，解压后直接运行 MarkTeX.exe 即可

---

## 📖 使用指南

| 操作 | 快捷键 |
|---|---|
| 打开文件 | `Ctrl+O` |
| 保存文件 | `Ctrl+S` |
| 打印 | `Ctrl+P` |
| 导出 PDF | `Ctrl+Shift+E` |

### 数学公式语法

**行内公式** — 使用单美元符号包裹:

```
著名的欧拉公式 $e^{i\pi} + 1 = 0$ 非常优雅。
```

**独立公式块** — 使用双美元符号包裹:

```
$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$
```

---

## 📄 开源协议

MIT © 2025 YuTian
