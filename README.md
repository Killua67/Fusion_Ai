# Fusion AI

一个集成多个 AI 聊天界面的桌面应用程序。

## 项目简介

Fusion AI 是一个基于 Electron 开发的跨平台桌面应用，旨在为用户提供一个统一的 AI 聊天平台，让用户可以在同一个界面中使用多个 AI 服务。

## 功能特点

- 多 AI 平台集成
- 统一的聊天界面
- 跨平台支持（macOS、Windows、Linux）
- 简洁现代的用户界面

## 安装说明

### 环境要求

- Node.js >= 14.0.0
- Yarn 包管理器

### 安装 Yarn

1. 使用 npm 安装 Yarn（需要先安装 Node.js）：
```bash
npm install -g yarn
```

2. 验证安装：
```bash
yarn --version
```

如果你使用其他操作系统，也可以参考 [Yarn 官方安装指南](https://classic.yarnpkg.com/en/docs/install)。

### 安装步骤

1. 克隆项目
```bash
git clone ..../Fusion_Ai.git
cd Fusion_Ai
```

2. 安装依赖
```bash
yarn install
```

3. 启动开发环境
```bash
yarn start
```

4. 打包应用
```bash
yarn build
```

## 使用说明

1. 启动应用后，您可以在主界面看到所有支持的 AI 平台
2. 选择想要使用的 AI 服务
3. 开始聊天交互

## 开发相关

- 使用 Electron 框架开发
- 采用现代化的 UI 设计
- 支持自定义主题

## 贡献指南

欢迎提交 Issue 和 Pull Request 来帮助改进这个项目。

## 许可证

MIT License 

## 软件界面展示

![Fusion AI 界面截图](img.png)

软件支持多种 AI 模型:
- ChatGPT
- Claude
- Gemini
- Grok 
