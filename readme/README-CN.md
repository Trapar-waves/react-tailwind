# @trapar-waves/react-tailwind

![npm version](https://img.shields.io/npm/v/@trapar-waves/react-tailwind)
![npm dm](https://img.shields.io/npm/dm/@trapar-waves/react-tailwind)
![License](https://img.shields.io/github/license/Trapar-waves/react-tailwind)
![GitHub last commit](https://img.shields.io/github/last-commit/Trapar-waves/react-tailwind)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Trapar-waves/react-tailwind/release.yml)
![Renovate](https://img.shields.io/badge/renovate-enabled-blue)

---

[English](../README.md) | [日本語](./README-JP.md) | [Русский язык](./README-RU.md)

> 一个现代UI开发模板，集成了React和Tailwind CSS，以及Rsbuild、TypeScript、ESLint (Antfu config)和Iconify支持。

## ✨ 特性

- **现代UI框架:** 使用React (v19)构建组件驱动的声明式界面。
- **实用优先的样式:** 采用Tailwind CSS v4 (`tailwindcss`)和`@tailwindcss/postcss`，实现灵活快速的样式设计，同时保持一致性。
- **快速开发工作流:** 使用Rsbuild（`@rsbuild/core`和`@rsbuild/plugin-react`）实现优化构建和高效开发服务器性能。
- **图标支持:** 包含`@iconify/json`和`@iconify/tailwind4`，提供可扩展和可定制的图标。
- **类型安全:** 使用TypeScript (v5.9.x)增强代码可靠性，并在开发过程中提供强大的类型检查。
- **注重代码质量:** 包含ESLint和`@antfu/eslint-config`，用于代码 linting 和执行最佳实践。
- **Git Hooks:** 集成`husky`和`lint-staged`用于提交前检查。

## 💻 技术栈

- **框架/库:** React (v19)
- **样式:** Tailwind CSS (`tailwindcss`)
- **构建工具:** Rsbuild (`@rsbuild/core`)
- **语言:** TypeScript (v5.9.x)
- **CSS处理:** PostCSS with `@tailwindcss/postcss`
- **代码检查:** ESLint与`@antfu/eslint-config`
- **图标库:** Iconify (`@iconify/json`, `@iconify/tailwind4`)

完整依赖列表参见[package.json](../package.json)。

## 🚀 开始使用

按照以下说明在本地运行项目。

### 前提条件

确保已安装以下软件：

- Node.js (推荐 >= 18.x 版本)
- 包管理器 (npm, yarn 或 pnpm)

```bash
node -v
npm -v
```

### 安装步骤

1. 使用模板创建新项目:

   ```bash
   pnpm create trapar-waves
   ```

2. 导航到项目目录并安装依赖:

   ```bash
   pnpm install
   # or
   npm install
   # or
   yarn install
   ```

3. 启动开发服务器:

   ```bash
   pnpm dev
   ```

## 🧱 项目结构

```
├── public/           # 静态资源
├── src/              # 源代码
│   ├── App.css       # 全局样式和Tailwind导入
│   ├── App.tsx       # 主应用组件
│   └── index.tsx     # 入口点
├── rsbuild.config.ts # Rsbuild配置
├── tsconfig.json     # TypeScript配置
├── eslint.config.js  # ESLint配置
└── package.json      # 项目依赖和脚本
```

## 🤝 贡献指南

欢迎贡献，非常感谢您的支持！请按照以下步骤进行贡献：

1. Fork 本仓库
2. 创建功能分支（`git checkout -b feature/amazing-feature`）
3. 提交您的更改（`git commit -m 'Add some amazing feature'`）
4. 推送到分支（`git push origin feature/amazing-feature`）
5. 打开Pull Request

## 👤 Author

- **Rikka:** [admin@rikka.cc](mailto:admin@rikka.cc)
- **GitHub Profile:** [Muromi-Rikka](https://github.com/Muromi-Rikka)

## 🔗 Links

- **仓库:** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **主页:** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **问题:** [https://github.com/Trapar-waves/react-tailwind/issues](https://github.com/Trapar-waves/react-tailwind/issues)
