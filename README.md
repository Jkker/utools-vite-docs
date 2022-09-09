<div align="center">
  <a href="https://github.com/Jkker/utools-vite-docs">
    <img src="https://github.com/Jkker/utools-vite-docs/raw/main/src/vite.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">uTools Vite Documentation</h3>
  <p align="center">
    一键查询 Vite 文档
    <br />
    <br />
    <a href="https://github.com/Jkker/utools-vite-docs/issues">Report Bug</a>
    ·
    <a href="https://github.com/Jkker/utools-vite-docs/issues">Request Feature</a>
  </p>
</div>

## 功能预览
![Preview](https://raw.githubusercontent.com/Jkker/utools-vite-docs/main/docs/utools-vite-docs.webp)


## 选项设置

通过 `Vite Setting` 指令打开设置页面，可以设置以下选项：

![Setting](https://raw.githubusercontent.com/Jkker/utools-vite-docs/main/docs/utools-vite-docs-settings.webp)

- 文档语言: 中文 / 英文
- 打开方式: 使用系统默认浏览器打开 / 使用 uTools 内置浏览器打开


## 实现原理

通过调用 Vite 的官方 algolia API 查询文档

```json
{
  "x-algolia-application-id": "7H67QR5P0A",
  "x-algolia-api-key": "deaab78bcdfe96b599497d25acc6460e",
  "url": "https://7h67qr5p0a-dsn.algolia.net/1/indexes/*/queries"
}
```

