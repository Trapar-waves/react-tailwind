# @trapar-waves/react-tailwind

![npm version](https://img.shields.io/npm/v/@trapar-waves/react-tailwind)
![npm dm](https://img.shields.io/npm/dm/@trapar-waves/react-tailwind)
![License](https://img.shields.io/github/license/Trapar-waves/react-tailwind)
![GitHub last commit](https://img.shields.io/github/last-commit/Trapar-waves/react-tailwind)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Trapar-waves/react-tailwind/release.yml)
![Renovate](https://img.shields.io/badge/renovate-enabled-blue)

---

[English](../README.md) | [中文](./README-CN.md) | [日本語](./README-JP.md)

> Современный шаблон разработки UI, интегрирующий React и Tailwind CSS, с поддержкой Rsbuild, TypeScript, ESLint (конфигурация Antfu) и Iconify.

## ✨ Возможности

- **Современный UI фреймворк:** Построен на React (v19) для компонентно-ориентированного декларативного интерфейса.
- **Утилитарный подход к стилям:** Использует Tailwind CSS v4 (`tailwindcss`) вместе с `@tailwindcss/postcss`, обеспечивая гибкую и быструю разработку стилей с сохранением一致性.
- **Быстрый рабочий процесс разработки:** Использует Rsbuild (`@rsbuild/core` и `@rsbuild/plugin-react`) для оптимизированных сборок и эффективной работы сервера разработки.
- **Поддержка иконок:** Включает `@iconify/json` и `@iconify/tailwind4` для масштабируемых и настраиваемых иконок.
- **Типобезопасность:** Использует TypeScript (v5.9.x) для повышения надежности кода и обеспечения строгой проверки типов во время разработки.
- **Фокус на качестве кода:** Включает ESLint с `@antfu/eslint-config` для линтинга и применения лучших практик.
- **Git Hooks:** Интегрированы `husky` и `lint-staged` для проверок перед коммитом.

## 💻 Технический стек

- **Фреймворк/библиотека:** React (v19)
- **Стилизация:** Tailwind CSS (`tailwindcss`)
- **Инструмент сборки:** Rsbuild (`@rsbuild/core`)
- **Язык:** TypeScript (v5.9.x)
- **Обработка CSS:** PostCSS и `@tailwindcss/postcss`
- **Линтинг:** ESLint и `@antfu/eslint-config`
- **Иконки:** Iconify (`@iconify/json`, `@iconify/tailwind4`)

Полный список зависимостей смотрите в [package.json](../package.json).

## 🚀 Начало работы

### Предварительные требования

- Node.js (рекомендуется >= 18.x)
- Менеджер пакетов (npm, yarn или pnpm)

### Установка

1. Создайте новый проект с помощью шаблона:

   ```bash
   pnpm create trapar-waves
   ```

2. Перейдите в директорию проекта и установите зависимости:

   ```bash
   pnpm install
   ```

3. Запустите сервер разработки:

   ```bash
   pnpm dev
   ```

## 📁 Структура проекта

```
├── public/           # Статические ресурсы
├── src/              # Исходный код
│   ├── App.css       # Глобальные стили и импорты Tailwind
│   ├── App.tsx       # Основной компонент приложения
│   └── index.tsx     # Точка входа
├── rsbuild.config.ts # Конфигурация Rsbuild
├── tsconfig.json     # Конфигурация TypeScript
├── eslint.config.js  # Конфигурация ESLint
└── package.json      # Зависимости и скрипты проекта
```

## 🤝 Участие в разработке

Участие приветствуется и высоко ценится! Пожалуйста, следуйте этим шагам для вклада:

1. Fork репозиторий
2. Создайте ветку для новой функции (`git checkout -b feature/amazing-feature`)
3. Зафиксируйте изменения (`git commit -m 'Add some amazing feature'`)
4. Отправьте изменения в ветку (`git push origin feature/amazing-feature`)
5. Откройте Pull Request

## 📄 Лицензия

MIT License © 2025 Trapar Waves

## 👤 Автор

- **Rikka:** [admin@rikka.cc](mailto:admin@rikka.cc)
- **Профиль GitHub:** [Muromi-Rikka](https://github.com/Muromi-Rikka)

## 🔗 Ссылки

- **Репозиторий:** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **Issues:** [https://github.com/Trapar-waves/react-tailwind/issues](https://github.com/Trapar-waves/react-tailwind/issues)
