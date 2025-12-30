# Imagine Engine 用户调研问卷系统

一个精美的、基于 Supabase 的用户反馈问卷系统，专为 Imagine Engine 项目设计。

## ✨ 特性

- 🎨 **精美设计**：采用深蓝主色调，符合 Imagine Engine 品牌风格
- 📱 **响应式布局**：完美支持桌面、平板和手机
- ⚡ **实时提交**：直接连接 Supabase 数据库，无需后端服务器
- 🔒 **安全可靠**：RLS 行级安全策略保护数据
- 🌟 **用户体验**：流畅的动画效果和友好的提示消息

## 🚀 快速开始

### 方式一：直接使用

1. 将 `index.html` 文件上传到您的 Web 服务器
2. 通过浏览器访问即可使用

### 方式二：GitHub Pages 部署

1. 在仓库设置中启用 GitHub Pages
2. 选择主分支作为源
3. 访问 `https://sxxxxxxxxxxxxxxxxxxxxx.github.io/imagine-engine-survey` 即可

### 方式三：Vercel/Netlify 部署

1. 将仓库连接到 Vercel 或 Netlify
2. 自动部署，无需配置

## 📋 功能说明

### 问卷内容

1. **基本信息**：用户身份选择
2. **核心体验反馈**：问题多选（配额显示、文字识别、错误提示等）
3. **功能满意度评分**：5个维度的1-5分评分
4. **建议与展望**：开放性问题反馈

### 数据存储

所有提交的数据自动保存到 Supabase 数据库的 `user_feedback_surveys` 表中。

## 🔧 技术栈

- **前端**：纯 HTML + CSS + JavaScript
- **数据库**：Supabase (PostgreSQL)
- **样式**：原生 CSS（无框架依赖）
- **字体**：Inter + Noto Sans SC

## 📊 数据查看

### 通过 Supabase Dashboard

1. 访问 https://supabase.com/dashboard
2. 选择 `useer` 项目
3. 进入 **Table Editor** → `user_feedback_surveys`
4. 查看所有提交的问卷数据

## 🔒 安全说明

- 使用 Supabase Anon Key（已通过 RLS 保护）
- 行级安全策略（RLS）已启用
- 任何人都可以提交问卷（INSERT）
- 只有管理员和用户本人可以查看（SELECT）

## 📝 文件说明

- `index.html` - 主问卷页面（可直接部署）

## 🎯 部署建议

### GitHub Pages

1. Settings → Pages → Source: main branch
2. 访问 `https://sxxxxxxxxxxxxxxxxxxxxx.github.io/imagine-engine-survey`

---

**注意**：此问卷系统已完全配置好，可以直接使用。所有提交的数据都会自动保存到 Supabase 数据库中。
