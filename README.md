# Lilly Portfolio — 文件结构说明

## 目录结构

```
portfolio/
├── index.html                  ← 主页面（直接双击打开即可预览）
└── media/
    ├── videos/                 ← 将你的项目视频放在这里
    │   ├── project-01.mp4      ← 对应：Brand Identity — Noir
    │   ├── project-02.mp4      ← 对应：Editorial Campaign
    │   ├── project-03.mp4      ← 对应：Exhibition Design
    │   ├── project-04.mp4      ← 对应：Digital Experience
    │   ├── project-05.mp4      ← 对应：Auction Catalogue
    │   └── project-06.mp4      ← 对应：Painting Series
    ├── thumbnails/             ← 可选：项目封面图
    └── assets/                 ← 其他静态资源（字体、图标等）
```

## 如何使用

1. 将你的视频文件按命名规则放入 `media/videos/` 文件夹
2. 在浏览器中打开 `index.html` 即可
3. 如需在线上传，点击视频区域悬浮出现的「Upload Video」按钮

## 自定义项目信息

打开 `index.html`，找到 `PROJECTS` 数组（约第 200 行），修改：
- `name` — 项目名称
- `year` — 年份
- `tags` — 标签（如 Art Direction, Brand, Motion 等）
- `video` — 视频路径

## GitHub Pages 部署

这个发布版本保留 HTML、图片和 `videos/3d-cover.mp4`。原始 01-06 视频文件超过 GitHub 单文件 100MB 限制，未纳入 Pages 发布包；首页视频区使用静态作品图作为线上封面。

上线方式：在 GitHub 仓库 Settings → Pages 中选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/ (root)`。
