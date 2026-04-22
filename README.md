# iFolder

一个在浏览器里自定义 macOS 文件夹图标的小工具。单文件 HTML，打开即用。

## 功能

- 自定义文件夹颜色与「含文件」时的内页颜色
- 内置数百个 Tabler 图标，可按分类搜索，一键叠加到文件夹上
- 支持取色滴管、色卡、预设调色板
- 导出 PNG / SVG，直接用于 macOS 「显示简介 → 拖到左上角图标」

## 使用

下载本仓库，双击 `index.html` 即可在浏览器中打开。无需构建、无需安装依赖。

如果需要本地预览服务，也可以任选一种：

```bash
# Python
python3 -m http.server 8099

# Node
npx serve .
```

然后访问 `http://localhost:8099`。

## 浏览器兼容

推荐 Chrome / Safari / Edge 最新版。移动端已适配。

## 技术栈

- 纯 HTML / CSS / 原生 JavaScript，单文件
- [iro.js](https://iro.js.org/) — 颜色选择器
- [Tabler Icons](https://tabler.io/icons) — 图标库

## 许可

MIT
