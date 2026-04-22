# GeoGuide in China

<div align="center">

![GeoGuide](./docs/imgs/geocaching.svg)

**为中国 Geocaching 爱好者提供的全面指南**

[访问网站](https://www.geoguide.top/) • [GitHub](https://github.com/Konano/geoguide-in-china)

</div>

## 简介

GeoGuide in China 是一份为中文用户量身定制的 Geocaching（地理藏宝）完整指南。Geocaching 是一项结合了户外探险与现代科技的全球性游戏，利用 GPS 设备或手机定位功能，在现实世界中寻找隐藏的「藏宝点」。

## 📚 内容概览

- **如何开始 Geocaching** - 适合新手的入门教程

- **创建你的第一个藏宝点** - 从零开始隐藏藏宝点

- **术语表** - 了解 Geocaching 的专业术语

## 🚀 快速开始

### 本地开发

#### 环境要求
- Python 3.7 或更高版本

#### 安装依赖

```bash
pip install -r requirements.txt
```

#### 启动本地服务器

```bash
mkdocs serve
```

然后在浏览器中访问 `http://localhost:8000`

#### 构建静态网站

```bash
mkdocs build
```

## 📖 项目结构

```
geoguide/
├── README.md              # 本文件
├── mkdocs.yml             # MkDocs 配置文件
├── requirements.txt       # Python 依赖
├── docs/                  # 文档源文件
│   ├── index.md           # 首页
│   ├── glossary.md        # 术语表
│   ├── getting-started/   # 入门教程
│   ├── hiding-a-cache/    # 藏宝指南
│   └── imgs/              # 图片资源
└── archived/              # 归档文件
```

## 🛠 技术栈

- **[MkDocs](https://www.mkdocs.org/)** - 静态文档生成器
- **[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)** - Material Design 主题
- **[mkdocs-glightbox](https://blueswen.github.io/mkdocs-glightbox/)** - 图片灯箱效果

## 📝 贡献指南

欢迎提交 Pull Request！详细的贡献要求请参考 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 许可证

本项目的内容和文档可自由使用，具体许可信息请查看项目代码库。
