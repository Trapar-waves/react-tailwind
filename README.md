# @trapar-waves/react-tailwind

![npm version](https://img.shields.io/npm/v/@trapar-waves/react-tailwind)
![npm dm](https://img.shields.io/npm/dm/@trapar-waves/react-tailwind)
![License](https://img.shields.io/github/license/Trapar-waves/react-tailwind)
![GitHub last commit](https://img.shields.io/github/last-commit/Trapar-waves/react-tailwind)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Trapar-waves/react-tailwind/release.yml)
![Renovate](https://img.shields.io/badge/renovate-enabled-blue)

---

[中文](./readme/README-CN.md) | [日本語](./readme/README-JP.md) | [Русский язык](./readme/README-RU.md)

> A modern UI development template integrating React and Tailwind CSS, with Rsbuild, TypeScript, ESLint (Antfu config), and Iconify support.

## ✨ Features

- **Modern UI Framework:** Built using React (v19) for a component-driven, declarative interface.
- **Utility-First Styling:** Employs Tailwind CSS v4 (`tailwindcss`) along with `@tailwindcss/postcss`, enabling flexible and rapid styling while maintaining consistency.
- **Fast Development Workflow:** Uses Rsbuild (`@rsbuild/core` and `@rsbuild/plugin-react`) for optimized builds and efficient development server performance.
- **Icon Support:** Includes `@iconify/json` and `@iconify/tailwind4` for scalable and customizable iconography.
- **Type Safety:** Utilizes TypeScript (v5.9.x) to enhance code reliability and provide robust type checking during development.
- **Focus on Code Quality:** Includes ESLint with `@antfu/eslint-config` for linting and enforcing best practices in the codebase.
- **Git Hooks:** Integrated `husky` and `lint-staged` for pre-commit checks.

## GitHub Pages

Pushing a version tag matching `v*` runs [`.github/workflows/pages.yml`](./.github/workflows/pages.yml), which builds with `BASE_PATH=/<repository-name>/`, copies `dist/index.html` to `dist/404.html` for SPA routing, and deploys to GitHub Pages. In the repository **Settings → Pages**, set **Source** to **GitHub Actions** once.

Local subpath check (Unix-like shell):

```bash
BASE_PATH=/react-tailwind/ pnpm run build && pnpm preview
```

PowerShell:

```powershell
$env:BASE_PATH="/react-tailwind/"; pnpm run build; pnpm preview
```

## 💻 Tech Stack

- **Framework/Library:** React (v19)
- **Styling:** Tailwind CSS (`tailwindcss`)
- **Build Tool:** Rsbuild (`@rsbuild/core`)
- **Language:** TypeScript (v5.9.x)
- **CSS Processing:** PostCSS with `@tailwindcss/postcss`
- **Linting:** ESLint with `@antfu/eslint-config`
- **Iconography:** Iconify (`@iconify/json`, `@iconify/tailwind4`)

See the [package.json](./package.json) for a full list of dependencies.

## 🚀 Getting Started

### Prerequisites

- Node.js (>= 18.x recommended)
- Package manager (npm, yarn, or pnpm)

### Installation

1. Create a new project using the template:

   ```bash
   pnpm create trapar-waves
   ```

2. Navigate to your project directory and install dependencies:

   ```bash
   pnpm install
   ```

3. Start the development server:

   ```bash
   pnpm dev
   ```

## 📁 Project Structure

```
├── public/           # Static assets
├── src/              # Source code
│   ├── App.css       # Global styles and Tailwind imports
│   ├── App.tsx       # Main application component
│   └── index.tsx     # Entry point
├── rsbuild.config.ts # Rsbuild configuration
├── tsconfig.json     # TypeScript configuration
├── eslint.config.js  # ESLint configuration
└── package.json      # Project dependencies and scripts
```

## 🤝 Contributing

Contributions are welcome and greatly appreciated! Please follow these steps to contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

MIT License © 2025 Trapar Waves

## 👤 Author

- **Rikka:** [admin@rikka.cc](mailto:admin@rikka.cc)
- **GitHub Profile:** [Muromi-Rikka](https://github.com/Muromi-Rikka)

## 🔗 Links

- **Repository:** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **Issues:** [https://github.com/Trapar-waves/react-tailwind/issues](https://github.com/Trapar-waves/react-tailwind/issues)
