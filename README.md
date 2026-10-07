# NL Works · 杨南龙个人作品集

静态个人作品集，包含中英文内容、序与尾声、作品分类、图片浏览及滚动动效。

## Vercel 部署

在 Vercel 中导入 `ymike0758-boop/portfolio`。根目录使用仓库根目录，Framework Preset 选择 Other，无需安装依赖和构建命令；输出目录为 `.`，配置已写入 vercel.json。

## 本地预览

在仓库目录运行 `python3 -m http.server 8000`，打开 http://localhost:8000 。

## 内容

- index.html：页面与中英文介绍
- content.json：原作品数据及媒体链接
- app.js：分类、语言与详情
- interactions.js：动效、图片查看器与章节导航
- style.css：响应式样式
- assets/：作品图片

视频仍从原 Canva 网站加载；迁移仓库不会将视频文件一并保存。
