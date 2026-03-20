# 智能客服机器人原型

基于 HTML + Tailwind CSS 的多页面客服系统原型，支持用户端、管理后台和人工坐席三个视角的实时交互。

## 页面说明

| 页面 | 文件 | 说明 |
|------|------|------|
| 用户端 | `index.html` | 移动端客服咨询界面 |
| 管理后台 | `admin.html` | 数据分析和业务监控面板 |
| 人工坐席 | `agent.html` | 客服人员工作台 |

## 交互功能

- **用户 ↔ AI**：智能问答、FAQ 快捷入口
- **用户 → 人工**：一键转接，排队等待
- **人工 → 用户**：实时回复，会话接管
- **数据同步**：所有页面通过 localStorage 共享状态

## 部署

项目为纯静态页面，可直接部署到 Vercel、Netlify 等平台。

```bash
# Vercel 部署
npx vercel

# 或通过 GitHub 连接 Vercel 自动部署
```

## 技术栈

- Tailwind CSS (CDN)
- Iconify (图标库)
- ECharts (图表，仅 admin 页面)
