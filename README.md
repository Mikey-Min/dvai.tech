# PAIA / DVAI 官网（V1.0）

这是 **PAIA（Personal AI Terminal）** 的官方网站项目，采用 **纯前端静态站点**，通过 **GitHub + Vercel** 实现自动化部署。

## 项目目标
- 展示 PAIA 产品理念
- 提供 Android APK 下载入口（当前占位）
- 作为产品与开发对外入口网站

## 技术栈
- HTML / CSS（极少量原生 JS）
- 无后端 / 无数据库 / 无登录系统

> 当前阶段不使用 React / Next.js，目标是最快上线、最低维护成本。

## 目录结构
```
.
├── index.html        # 官网首页
├── download.html     # Android 下载页
├── assets/
│   ├── logo.png      # PAIA App Logo
│   ├── mascot.png   # PAIA 形象
│   └── styles.css   # 全局样式
└── README.md
```

## 部署
- GitHub：push 到 `main` 分支
- Vercel：自动触发部署（Framework Preset: Other）
- 域名：https://www.dvai.tech

## 当前不做
- 用户登录
- 数据收集 / 分析 SDK
- SEO 优化

---
PAIA / DVAI
