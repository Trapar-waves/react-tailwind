# @trapar-waves/react-tailwind

![npm version](https://img.shields.io/npm/v/@trapar-waves/react-tailwind)
![npm dm](https://img.shields.io/npm/dm/@trapar-waves/react-tailwind)
![License](https://img.shields.io/github/license/Trapar-waves/react-tailwind)
![GitHub last commit](https://img.shields.io/github/last-commit/Trapar-waves/react-tailwind)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Trapar-waves/react-tailwind/release.yml)
![Renovate](https://img.shields.io/badge/renovate-enabled-blue)

![React Tailwind](../assets/readme/hero.svg)

---

[English](../README.md) | [日本語](./README-JP.md) | [Русский язык](./README-RU.md)

> 一个现代化的 UI 开发模板，集成了 React 和 Tailwind CSS，配合 Rsbuild、TypeScript、ESLint（Antfu 配置）和 Iconify 支持。

![Features](../assets/readme/headers/features.svg)

- **现代 UI 框架：** 使用 React (v19) 构建，支持组件驱动的声明式接口。
- **实用优先的样式：** 采用 Tailwind CSS v4（`tailwindcss`）和 `@tailwindcss/postcss`，实现灵活快速的样式开发，同时保持一致性。
- **快速开发工作流：** 使用 Rsbuild（`@rsbuild/core` 和 `@rsbuild/plugin-react`）进行优化构建和高效开发服务器性能。
- **图标支持：** 包含 `@iconify/json` 和 `@iconify/tailwind4`，提供可扩展和可定制的图标。
- **类型安全：** 利用 TypeScript (v5.9.x) 提高代码可靠性，并在开发过程中提供强大的类型检查。
- **代码质量：** 包含 ESLint 和 `@antfu/eslint-config` 进行代码检查和最佳实践 enforcement。
- **Git Hooks：** 集成 `husky` 和 `lint-staged` 进行提交前检查。

![Tech Stack](../assets/readme/headers/tech-stack.svg)

- **框架/库：** React (v19)
- **样式：** Tailwind CSS (`tailwindcss`)
- **构建工具：** Rsbuild (`@rsbuild/core`)
- **语言：** TypeScript (v5.9.x)
- **CSS 处理：** PostCSS 和 `@tailwindcss/postcss`
- **代码检查：** ESLint 和 `@antfu/eslint-config`
- **图标：** Iconify (`@iconify/json`, `@iconify/tailwind4`)

查看 [package.json](../package.json) 获取完整的依赖列表。

![Getting Started](../assets/readme/headers/getting-started.svg)

## 前置条件

- Node.js（推荐 >= 18.x）
- 包管理器（npm、yarn 或 pnpm）

### 安装

1. 使用模板创建新项目：

   ```bash
   pnpm create trapar-waves
   ```

2. 导航到项目目录并安装依赖：

   ```bash
   pnpm install
   ```

3. 启动开发服务器：

   ```bash
   pnpm dev
   ```

![Project Structure](../assets/readme/headers/project-structure.svg)

```
├── public/           # 静态资源
├── src/              # 源代码
│   ├── App.css       # 全局样式和 Tailwind 导入
│   ├── App.tsx       # 主应用组件
│   └── index.tsx     # 入口点
├── rsbuild.config.ts # Rsbuild 配置
├── tsconfig.json     # TypeScript 配置
├── eslint.config.js  # ESLint 配置
└── package.json      # 项目依赖和脚本
```

![Contributing](../assets/readme/headers/contributing.svg)

欢迎贡献，非常感谢！请按照以下步骤贡献：

1. Fork 仓库
2. 创建特性分支（`git checkout -b feature/amazing-feature`）
3. 提交更改（`git commit -m 'Add some amazing feature'`）
4. 推送到分支（`git push origin feature/amazing-feature`）
5. 创建 Pull Request

![License](../assets/readme/headers/license.svg)

MIT License © 2025 Trapar Waves

## 👤 作者

- **Rikka：** [admin@rikka.cc](mailto:admin@rikka.cc)
- **GitHub 主页：** [Muromi-Rikka](https://github.com/Muromi-Rikka)

## 🔗 链接

- **仓库：** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **Issues：** [https://github.com/Trapar-waves/react-tailwind/issues](https://github.com/Trapar-waves/react-tailwind/issues)
