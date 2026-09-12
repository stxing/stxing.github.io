# stxing.github.io

> 我的个人主页 · 由 [GitHub Pages](https://pages.github.com/) 免费托管，自动启用 HTTPS。

- 🌐 **在线访问**：https://stxing.github.io
- 📄 **入口文件**：`index.html`
- 🚀 **部署分支**：`main`（根目录 `/`）
- 🔒 **HTTPS**：由 GitHub 自动签发，无需配置

## 目录结构

```
stxing.github.io/
├── index.html   # 主页页面（唯一需要维护的文件）
└── README.md    # 本说明
```

## 本地预览

```bash
git clone https://github.com/stxing/stxing.github.io.git
cd stxing.github.io
python -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 如何更新内容

1. 编辑 `index.html`（页面结构、文案、样式都在这一份文件里）。
2. 提交并推送到 `main` 分支：
   ```bash
   git add index.html
   git commit -m "update homepage"
   git push
   ```
3. GitHub Pages 会自动重新构建并发布，通常 1–2 分钟生效。

## 关于这个仓库

这是一个 **GitHub Pages 用户站点**（仓库名必须为 `<用户名>.github.io`）。
访问地址固定为 `https://<用户名>.github.io`，无需额外配置域名即可使用。

---

由 WorkBuddy 协助搭建与整理。
