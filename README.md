# Fjango

> 🔗 **在线访问：** [https://fjango.github.io/fjango/](https://fjango.github.io/fjango/)

**Fjango** — 开放、免费、极简的经验分享平台。每个人走过的路，都是后来者的一盏灯。

---

## 🚀 快速开始

### 本地预览

```bash
# 1. 安装依赖
pip install mkdocs-material

# 2. 启动本地服务器
mkdocs serve

# 3. 浏览器打开 http://127.0.0.1:8000
```

### 构建

```bash
mkdocs build
```

生成的文件在 `site/` 目录中。

---

## 📁 项目结构

```
fjango/
├── .github/workflows/    # GitHub Actions 自动部署
├── docs/                 # 网站内容（Markdown文件）
│   ├── index.md          # 首页
│   ├── about.md          # 关于页面
│   ├── contribute-guide.md  # 投稿指南
│   └── share/            # 经验分享文章
├── mkdocs.yml            # 网站配置
└── requirements.txt      # Python 依赖
```

---

## ✍️ 投稿

查看 [投稿指南](https://fjango.github.io/fjango/contribute-guide/) 了解如何分享你的经验。

---

## 🛠️ 技术栈

- [MkDocs](https://www.mkdocs.org/) + [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- [GitHub Pages](https://pages.github.com/) 免费托管
- [GitHub Actions](https://github.com/features/actions) 自动部署

---

## 📄 许可证

- 源码：[MIT License](LICENSE)
- 内容：[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
