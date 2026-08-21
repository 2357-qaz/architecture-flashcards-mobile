# 架构闪卡 · Architecture Flashcards

一个手机端优先的静态 PWA 闪卡应用，用来复习入门到中级的软件架构知识。

题库覆盖：架构基础、分层与边界、DDD、微服务、分布式、数据与缓存、消息与集成、可靠性、可观测性、安全、工程演进。

## 功能

- 手机端优先暗色 UI
- 分类筛选、搜索、今日待复习、薄弱题卡模式
- 点击显示答案，左右滑动评分
- 简化 Leitner 复习箱：答对进入更高 Box，答错回到 Box 1
- 本地进度保存到浏览器 localStorage
- 支持导出和导入学习进度
- PWA manifest 与 Service Worker 离线缓存

## GitHub Pages 发布

这个仓库是静态站点，根目录已经包含 `index.html`、`manifest.json`、`sw.js`、`icon.svg` 和 `.nojekyll`。

在 GitHub 仓库页面进入：

`Settings` → `Pages` → `Build and deployment` → `Source` 选择 `Deploy from a branch` → `Branch` 选择 `main` / `/(root)` → `Save`。

发布成功后，默认地址通常是：

`https://2357-qaz.github.io/architecture-flashcards-mobile/`

## iPhone 使用

用 Safari 打开部署地址，点击分享按钮，选择“添加到主屏幕”。之后就可以像小 App 一样打开。

## 隐私

学习进度只保存在当前设备浏览器的 localStorage。应用没有后端，也不会上传你的学习记录。
