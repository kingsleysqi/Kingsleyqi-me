Markdown
# Kingsleyqi.me

个人表达站 / Personal Identity Site

> Exit the logic, Enter the life.  
> —— Kingsleyqi

---

## 📌 项目简介

Kingsleyqi.me 是一个以 **个人表达、身份展示与内容沉淀** 为核心的独立网站项目。

不同于传统博客或作品集站点，本项目更强调：

- **表达（Expression）**：记录思想、状态与认知  
- **存在（Presence）**：构建长期可持续的个人空间  
- **系统化（System）**：与 Kingsleyqi 生态站点形成联动  

这是一个介于：

- 个人主页（Profile）  
- 内容站（Content Site）  
- 思考记录（Thinking Log）  

之间的“中间形态”。

---

## 🧭 项目定位

该项目在整体站点体系中的角色：

| 站点 | 定位 |
|------|------|
| Kingsleyqi.com | 主站 / 品牌表达 |
| Kingsleyqi.cn | 中文内容 / 本土表达 |
| Media.* | 媒体内容 / 资源 |
| Kingsleyqi.me | 个人状态 / 自我表达 / 内在空间 |

👉 `.me` 更偏向 **“我是谁，而不是我做了什么”**

---

## 🧱 个人站点体系（System Architecture）

```text
                ┌────────────────────────────┐
                │     Kingsleyqi.com         │
                │   主站 / Brand Core        │
                └────────────┬───────────────┘
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
┌───────────────┐   ┌────────────────┐   ┌────────────────────┐
│ Kingsleyqi.cn │   │ Kingsleyqi.me  │   │ Media.*            │
│ 中文表达      │   │ 自我表达 / 内在 │   │ 媒体 / 资源分发     │
└───────────────┘   └────────────────┘   └────────────────────┘
说明：
.com → 对外表达（认知 / 能力 / 品牌）
.cn → 本土内容沉淀
.me → 内在表达（状态 / 思考 / 自我）
media → 媒体资源系统
⚙️ 技术栈
本项目采用现代静态站点方案构建：
Framework: Astro / 静态站点架构
Styling: CSS / 自定义主题
Deployment: Cloudflare Pages / Vercel
Content: Markdown
特点：
⚡ 极致轻量
🌐 全球 CDN 分发
🔒 无后端依赖
📦 易于迁移与扩展
📁 项目结构
Bash
.
├── public/              # 静态资源
├── src/
│   ├── components/     # 组件
│   ├── layouts/        # 页面布局
│   ├── pages/          # 页面入口
│   ├── styles/         # 样式
│   └── content/        # 内容（文章/数据）
├── astro.config.mjs    # Astro 配置
├── package.json
└── README.md
🚀 本地运行
Bash
# 安装依赖
npm install

# 本地开发
npm run dev

# 构建
npm run build

# 预览
npm run preview
🌍 部署方式
推荐平台：
Cloudflare Pages（优先）
Vercel
Netlify
Cloudflare Pages 配置
Bash
# 构建命令
npm run build

# 输出目录
dist
🧠 设计理念
这个项目不是“做给别人看的”，而是：
用来承载长期自我认知与表达的空间。
核心原则：
不迎合
不堆信息
不做内容农场
保持克制与留白
🧩 功能规划
[x] 基础页面结构
[x] 主题风格统一
[ ] 内容模块细分
[ ] 状态流（Status Stream）
[ ] 与主站联动
[ ] 私域表达扩展
🔗 相关项目
https://kingsleyqi.com⁠�
https://kingsleyqi.cn⁠�
https://media.kingsleyqi.com⁠�
📄 License
MIT License
👤 Author
Kingsleyqi
Building systems, not just websites.