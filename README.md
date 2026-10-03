# AI Agent 开发者 · 个人主页

> 大模型应用开发 · 个人简历与项目展示

在线访问：[打开个人主页](https://heibaixiong1118.github.io/my-resume/)

## 这个仓库是什么

个人简历主页，使用 HTML、CSS 和 JavaScript，单文件、无需安装依赖或构建。
页面包含简历资料编辑、Markdown 简历下载、网页导出，以及手机布局。

## 文件结构

```text
index.html   网页源码，包含页面结构、样式和交互
README.md    仓库介绍和更新说明
```

## 本地查看

下载仓库后，直接用浏览器打开 `index.html`。

## 修改资料

打开网页，点击“编辑资料”，填写后保存。
“保存资料”仅保存在当前浏览器，不会自动更新 GitHub 或线上网站。

要把填写后的资料保存到仓库：

1. 在网页中点击“导出网页”。
2. 将下载的 HTML 文件重命名为 `index.html`，替换仓库中的同名文件。
3. 提交并推送到 GitHub。

导出的网页会隐藏编辑按钮，适合分享或部署。
也可以直接编辑 `index.html` 中 `id="profile-data"` 的 JSON 来填写默认资料。

## 自动发布

网页由 GitHub Pages 托管。`main` 分支根目录是发布来源。
更新并提交 `index.html` 后，GitHub 会自动发布，访问网址保持不变。
发布状态可以在仓库的 Actions 或 Deployments 中查看。
