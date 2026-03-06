# 🔍 腾讯云 ES 知识工坊

> 150 个核心知识点，系统学习腾讯云 Elasticsearch Service 全栈技能

[![Live Demo](https://img.shields.io/badge/Demo-在线体验-FBBF24?style=for-the-badge)](https://learn-es-liart.vercel.app)

## 简介

腾讯云 ES 知识工坊是一个交互式学习平台，基于腾讯云 Elasticsearch Service 官方文档，系统梳理 **150 个核心知识点**，覆盖 **17 个主题分类**。从产品概述到向量搜索，从集群架构到性能优化，帮助云计算从业者全面掌握 ES 服务的核心能力。

## 在线体验

🔗 **https://learn-es-liart.vercel.app**

## 学习模式

| 模式 | 说明 |
|------|------|
| 📖 渐进学习 | 逐步学习每个知识点，内含随堂测验 |
| 🃏 闪卡复习 | 翻转卡片快速复习，支持键盘操作 |
| 📚 知识索引 | 按分类浏览全部知识点，支持搜索筛选 |
| 📊 进度追踪 | 查看学习统计、已掌握列表和薄弱环节推荐 |

## 知识分类（17 类）

产品概述 · 产品版本 · 集群架构 · 核心概念 · 数据写入与采集 · 搜索与查询 · 数据分析与可视化 · 应用场景 · 安全与访问控制 · 集群管理与运维 · 性能优化 · 计费与资源 · 高可用与容灾 · 向量搜索与AI · X-Pack功能 · 日志增强版特性 · 最佳实践与常见问题

## 技术特性

- **PWA 支持** — 可添加到主屏幕，支持离线访问
- **响应式设计** — 适配桌面、平板和手机
- **本地存储** — 学习进度自动保存在浏览器中
- **零依赖** — 纯 HTML/CSS/JS，无需构建工具

## 项目结构

```
learn-es/
├── index.html          # 首页
├── learn.html          # 渐进学习
├── flashcard.html      # 闪卡复习
├── roots.html          # 知识索引
├── progress.html       # 进度追踪
├── root-detail.html    # 知识点详情
├── css/
│   └── minimal.css     # 样式表
├── js/
│   ├── wordData.js     # 150 个知识点数据
│   ├── siteConfig.js   # 站点配置
│   └── storage.js      # 本地存储管理
├── sw.js               # Service Worker
├── manifest.json       # PWA 配置
├── icon-192.png        # PWA 图标
├── icon-512.png        # PWA 图标
├── robots.txt          # 爬虫配置
├── sitemap.xml         # 站点地图
└── knowledge.md        # 知识点源文件
```

## 本地运行

```bash
# 任选一种方式启动静态服务器
npx http-server -p 8080
# 或
python3 -m http.server 8080
```

然后访问 `http://localhost:8080`

## License

MIT
