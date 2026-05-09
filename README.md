# Holmeslym.github.io（鹿鸣的 Agent 技术博客）

基于 **GitHub Pages + Jekyll（Minima）** 的个人 Agent 技术博客源码。

线上地址：<https://holmeslym.github.io>

## 首次发布 checklist

1. 将本仓库推送到 GitHub：`Holmeslym/Holmeslym.github.io`（用户名与仓库名需与你的账号一致）。
2. 打开仓库 **Settings → Pages**：Source 选择 **Deploy from a branch**，Branch 选 **main**（或 **master**），文件夹 **/(root)**，保存。
3. 等待 Actions（若有）或 Pages 构建完成（通常 1～3 分钟），再访问上述 URL。

## 本地预览（可选）

需安装 Ruby + Bundler。在项目根目录：

```bash
bundle install
bundle exec jekyll serve
```

浏览器打开提示的本地地址（一般为 `http://127.0.0.1:4000`）。

Windows 若环境棘手，可用 WSL2，或仅依赖 GitHub 在线构建、不做本地预览。

## 文章位置与命名

- 文章放在 `_posts/`，文件名：`YYYY-MM-DD-英文短横线标题.md`。
- 文件头部须含 YAML front matter（参考已有文章）。

日常更新流程见同目录下的 **《GitHub-Pages-Agent博客日常运营指南》**（不参与站点构建，仅供本地查阅）。
