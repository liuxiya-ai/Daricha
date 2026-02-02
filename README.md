# 🪟 Daricha (The Window)

> **"Lighting a candle where the electricity is cut."**  
> 在电力切断的地方点燃蜡烛。

**Daricha (达里语: 窗户)** 是一个为网络与政治环境极端受限地区（重点为阿富汗）的女性设计的 **“离线数字求生工具包” (Digital Survival Kit)**。

它表面上是一个极简的导航站，内核是一个**反封锁、反追踪、离线优先**的知识避难所。

---

## 🏗️ Project Structure (项目结构)

```text
D:\Daricha
├── 📂 doc/                # 项目核心文档
│   ├── PRD.md            # 产品需求文档 (必读)
│   └── project_strategy.md # 产品与运营战略
├── 📂 design/             # 设计资源
│   └── ui_mockup.png     # 移动端视觉原型
├── index.html            # 网站入口 (Single Page Application)
├── style.css             # 极简样式表 (High Contrast)
└── README.md             # 本文件
```

---

## 🎨 Design Philosophy (设计哲学)

基于 `design/ui_mockup.png` 与产品战略，本项目严格遵循以下原则：

1.  **Offline First (离线优先)**
    *   这不是一个需要时刻联网的 Blog。
    *   它是一个**“打开即下载”**的工具包。所有核心信息（安全指南、急救知识）必须直接包含在 HTML 文本中，断网后依然可读。

2.  **Digital Aesthetics of Survival (生存美学)**
    *   **极简 (Minimalist)**: 没有任何装饰性图片。为了在 2G 网络下秒开。
    *   **高对比度 (High Contrast)**: 黑白为主，为了在低亮度、廉价屏幕上清晰可读。
    *   **大触控区 (Thumb-Friendly)**: 为了在老旧的小屏幕手机上容易操作。

3.  **Safety & Anonymity (安全与匿名)**
    *   无 Cookie，无追踪脚本 (No GA)，无复杂的 JS 交互。
    *   保护使用者，也保护管理者。

---

## 🚀 How to Contribute (如何参与)

这是一个纯静态项目 (Static Site)，不需要复杂的构建工具。

1.  **添加内容**: 直接编辑 `index.html`，模仿现有的 `<li>` 标签格式添加链接。
2.  **调整样式**: 修改 `style.css`。
3.  **发布**: 代码推送到 GitHub `main` 分支后，GitHub Pages 会自动部署。

---

## ⚠️ Safety Warning (安全警告)

*   **For Admins**: 请严格阅读 `doc/project_strategy.md` 中的运营红线。绝对使用**身份隔离**的账号进行维护。
*   **For Users**: 本站内容旨在提供教育与生存信息，不涉及政治敏感话题。

---
*Created with ❤️ for the women who keep learning in the dark.*
