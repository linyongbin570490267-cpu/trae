# Personal Kanban - 个人看板待办应用

一个轻量级、功能完整的个人任务管理 Web 应用，无需后端，直接在浏览器中运行。

## 功能特性

- **任务添加**：支持输入任务文本 + 截止时间
- **状态切换**：一键切换任务完成/未完成状态
- **智能过期提示**：自动检测过期任务，高亮显示 + 浏览器通知提醒
- **本地持久化**：使用 localStorage 保存所有任务数据，刷新页面不丢失
- **实时统计**：底部显示任务总数与已完成数
- **响应式设计**：适配移动端与桌面端，渐变配色清爽美观
- **纯前端实现**：无需任何构建工具，直接打开 index.html 即可使用

## 快速开始

1. 克隆或下载本仓库
2. 在浏览器中打开 `index.html` 文件
3. 开始添加你的任务吧！

```bash
# 或者本地启动一个简单静态服务器
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 项目结构

```
trae/
├── index.html   # 主页面（含 HTML/CSS/JS，全部内联）
└── README.md    # 项目说明文档
```

## 技术栈

- 原生 HTML5 + CSS3 (Flexbox / CSS Grid 布局)
- 原生 JavaScript (ES6+)
- Web Storage API (localStorage)
- Notification API (浏览器桌面通知)

## License

MIT
