# Chengyu Du's Personal Homepage

个人学术主页模板，基于 [Siyu Yuan](https://siyuyuan.github.io/) 的风格设计。

## 📁 文件结构

```
chengyudu.github.io/
├── index.html      # 主页面
├── stylesheet.css  # 样式文件
├── README.md       # 说明文档
└── images/         # 图片目录
    ├── dcy.jpg         # 个人照片
    ├── favicon.png     # 网站图标
    ├── her.png         # HER论文图
    ├── minimax.png     # MiniMax论文图
    ├── terminal.png    # Terminal Gym论文图
    ├── thinkthrice.png # Think Thrice论文图
    ├── persona.png     # Persona论文图
    ├── webexplorer.png # WebExplorer论文图
    └── cem.png         # CEM论文图
```

## 🚀 部署到 GitHub Pages

1. **创建 GitHub 仓库**：
   - 在 GitHub 上创建名为 `chengyudu.github.io` 的仓库

2. **上传文件**：
   ```bash
   cd chengyudu.github.io
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/chengyudu/chengyudu.github.io.git
   git push -u origin main
   ```

3. **启用 GitHub Pages**：
   - 进入仓库 Settings → Pages
   - Source 选择 `main` 分支
   - 保存后等待几分钟即可访问

## 🖼️ 需要添加的图片

请将以下图片添加到 `images/` 目录：

1. **dcy.jpg** - 你的个人照片（建议正方形，300x300px 以上）
2. **favicon.png** - 网站图标（建议 32x32px 或 64x64px）
3. 各论文的缩略图（建议 400x300px）

## ✏️ 自定义修改

### 修改个人信息
编辑 `index.html` 中的以下部分：
- 个人简介
- 邮箱地址
- 社交媒体链接
- Google Scholar ID

### 修改配色
编辑 `stylesheet.css` 中的 CSS 变量：
```css
:root {
  --primary-color: #1a5f7a;    /* 主色调 */
  --accent-color: #c97c5d;     /* 强调色 */
  --text-color: #2d3436;       /* 文字颜色 */
}
```

### 添加新论文
复制现有的论文表格块，修改：
- 论文标题和链接
- 作者列表
- 会议/期刊信息
- 缩略图

## 📱 响应式设计

主页已适配移动端，会自动调整布局。

## 📄 License

MIT License - 欢迎自由使用和修改。

---

**Last Updated**: December 2025

