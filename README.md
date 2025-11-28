# [Welcome to Jackthin's Blog!]

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/JackthinShin/JekyllThemeBlog)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.x-red.svg)](https://jekyllrb.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

欢迎来到我的个人博客！这里是我记录学习笔记、技术分享和生活感悟的地方。

👉 **访问博客**: [https://jackthinshin.github.io/JekyllThemeBlog/](https://jackthinshin.github.io/JekyllThemeBlog/)

## 📖 简介

这个博客基于 [Jekyll](https://jekyllrb.com/) 构建。主要用于分享：

- 💻 技术教程与编程心得
- 📚 阅读笔记与书评
- 🚀 个人项目展示
- 💭 生活随笔

## ✨ 特性

- **响应式设计**：适配移动端和桌面端。
- **标签系统**：方便按分类查找文章。
- **代码高亮**：支持多种语言的语法高亮。
- **评论系统**：集成了 [Disqus/Gitalk/Utterances] 评论功能。
- **SEO 优化**：包含 Sitemap 和 SEO 元数据。
- **分析统计**：集成了 [Google Analytics/百度统计]。

## 🚀 快速开始

如果您想在本地运行此博客进行预览或修改，请按照以下步骤操作：

### 环境要求

- Ruby 2.7+
- Bundler
- Jekyll 4.x

### 安装步骤

1. **克隆仓库**

   ```bash
   git clone https://github.com/[您的用户名]/[仓库名称].git
   cd [仓库名称]
   ```

2. **安装依赖**

   ```bash
   bundle install
   ```

3. **启动本地服务器**

   ```bash
   bundle exec jekyll serve
   ```

4. **预览**

   打开浏览器访问 `http://127.0.0.1:4000` 即可看到博客效果。

## 📝 写作指南

在 `_posts` 目录下创建一个新的 Markdown 文件，文件名格式为 `YYYY-MM-DD-文章标题.md`。

文件头（Front Matter）示例：

```yaml
---
layout: post
title:  "文章标题"
date:   2023-10-01 12:00:00 +0800
categories: [技术]
tags: [Jekyll, 教程]
---
```

## 📂 目录结构

```text
.
├── _config.yml       # 网站配置文件
├── _posts/           # 博客文章存放目录
├── _layouts/         # 页面布局模板
├── _includes/        # 可复用的 HTML 片段
├── _sass/            # 样式文件
├── assets/           # 图片、CSS、JS 等静态资源
└── index.html        # 首页
```

## 👤 关于作者

**Jackthin Shin**

- 📍 坐标：China
- 💼 职业：Student
- 📫 邮箱：Jackthin@foxmail.com
- 🔗 个人主页：https://jackthinshin.github.io/JekyllThemeBlog/

### 关注我

- [GitHub](https://github.com/jackthinshin)

## 📄 许可证

本项目采用 [MIT License](LICENSE) 许可证。文章内容采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 协议。
