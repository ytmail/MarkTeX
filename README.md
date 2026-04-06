# MarkTeX

[**简体中文**](README.zh-CN.md) | [**English**](README.md)

> A real-time **Markdown + LaTeX** renderer for Windows.  
> Edit on the left, see beautifully typeset math and markup on the right.

---

## ✨ Features

- **Real-time preview** — 300 ms debounce, renders as you type
- **Full LaTeX support** — inline `$...$` and display `$$...$$` math via [KaTeX](https://katex.org/)
- **Syntax highlighting** — code blocks highlighted by [highlight.js](https://highlightjs.org/)
- **Three themes** — Dark / Light / Sepia, switchable on the fly
- **Font customization** — family and size adjustable in the toolbar
- **PDF export** — print to PDF with selectable paper size (A4 / A3 / Letter / Legal), always exported on a clean white background
- **Print support** — browser-native print dialog, white background enforced regardless of current theme
- **File operations** — open / save `.md` files, Ctrl+S / Ctrl+O shortcuts
- **Split-view modes** — side-by-side, editor-only, or preview-only

---

## 📸 Screenshot

> *(Add a screenshot here)*

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| UI Framework | WPF (.NET 8) |
| Web Renderer | Microsoft WebView2 |
| Markdown Parser | [marked.js](https://marked.js.org/) v12 |
| Math Rendering | [KaTeX](https://katex.org/) v0.16 |
| Code Highlighting | [highlight.js](https://highlightjs.org/) v11 |

---

## 🚀 Getting Started

### Prerequisites

- Windows 10 / 11
- [.NET 8 Runtime](https://dotnet.microsoft.com/download/dotnet/8.0)
- [WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) (pre-installed on Windows 11; download for Windows 10)


### Run Release

Download the latest release from the [Releases](../../releases) page and run `MarkTeX.exe`.

---

## 📖 Usage

| Action | Shortcut |
|---|---|
| Open file | `Ctrl+O` |
| Save file | `Ctrl+S` |
| Print | `Ctrl+P` |
| Export PDF | `Ctrl+Shift+E` |

### Math Syntax

**Inline math** — wrap with single dollar signs:

```
The formula $e^{i\pi} + 1 = 0$ is elegant.
```

**Display math** — wrap with double dollar signs:

```
$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$
```

---

## 📄 License

MIT © 2025 YuTian
