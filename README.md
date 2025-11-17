# Personal Academic Website

个人学术主页 - Personal Academic Homepage for Pengyu Zha (查鹏宇)

## 简介

这是一个使用 Jekyll 构建的个人学术主页，托管在 GitHub Pages 上。网站展示了个人信息、研究方向、教育背景等内容。

## 本地开发

### 前置要求

- Ruby 2.7 或更高版本
- Bundler gem

### 安装步骤

1. 克隆仓库：
```bash
git clone https://github.com/zpyc1oud/zpyc1oud.github.io.git
cd zpyc1oud.github.io
```

2. 安装依赖：
```bash
bundle install
```

3. 启动本地服务器：
```bash
bundle exec jekyll serve
```

4. 在浏览器中访问 `http://localhost:4000`

## 配置

编辑 `_config.yml` 文件来自定义网站配置：

- **个人信息**：姓名、学校、研究方向等
- **社交媒体**：GitHub、邮箱等链接
- **网站URL**：GitHub Pages 地址

## 添加内容

### 添加个人照片

将您的照片保存为 `assets/images/profile.jpg`，网站会自动显示。

### 更新个人信息

编辑以下文件来更新内容：
- `index.html` - 首页内容
- `about.md` - 关于页面
- `research.md` - 研究页面
- `contact.md` - 联系页面

## 部署到 GitHub Pages

1. 将代码推送到 GitHub 仓库 `zpyc1oud.github.io`
2. 在仓库设置中启用 GitHub Pages
3. 选择主分支作为源
4. 网站将自动构建和部署

## 文件结构

```
.
├── _config.yml          # Jekyll 配置文件
├── _layouts/            # 布局文件
│   └── default.html
├── _includes/           # 包含文件
│   ├── header.html
│   └── footer.html
├── assets/              # 静态资源
│   ├── css/
│   │   └── main.css
│   └── images/
├── index.html           # 首页
├── about.md            # 关于页面
├── research.md         # 研究页面
├── contact.md          # 联系页面
├── Gemfile             # Ruby 依赖
└── README.md           # 说明文档
```

## 参考资源

- [Jekyll 文档](https://jekyllrb.com/docs/)
- [GitHub Pages 文档](https://docs.github.com/en/pages)
- [Jekyll on GitHub Pages](https://jekyllrb.com/docs/github-pages/)

## 许可证

本项目使用 MIT 许可证。

