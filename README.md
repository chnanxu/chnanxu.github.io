# chnanxu 的个人博客

基于 Astro 构建的个人博客，部署在 GitHub Pages。

## 快速开始

```bash
# 安装依赖
bun install

# 启动开发服务器
bun run dev

# 构建生产版本
bun run build

# 预览构建结果
bun run preview
```

## 项目结构

```
├── src/
│   ├── content/posts/    # Markdown 文章
│   ├── layouts/          # 页面布局
│   ├── components/       # UI 组件
│   ├── pages/            # 页面路由
│   └── styles/           # 全局样式
├── public/               # 静态资源
└── astro.config.mjs      # Astro 配置
```

## 写作

在 `src/content/posts/` 目录下创建 `.md` 或 `.mdx` 文件：

```markdown
---
title: "文章标题"
description: "文章描述"
pubDate: 2024-01-15
tags: ["标签1", "标签2"]
---

文章内容...
```

## 技术栈

- [Astro](https://astro.build) - 静态站点生成器
- [SCSS](https://sass-lang.com) - CSS 预处理器
- [TypeScript](https://www.typescriptlang.org) - 类型安全
- [GitHub Pages](https://pages.github.com) - 托管平台

## License

MIT
