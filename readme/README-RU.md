# @trapar-waves/react-tailwind

![npm version](https://img.shields.io/npm/v/@trapar-waves/react-tailwind)
![npm dm](https://img.shields.io/npm/dm/@trapar-waves/react-tailwind)
![License](https://img.shields.io/github/license/Trapar-waves/react-tailwind)
![GitHub last commit](https://img.shields.io/github/last-commit/Trapar-waves/react-tailwind)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Trapar-waves/react-tailwind/release.yml)
![Renovate](https://img.shields.io/badge/renovate-enabled-blue)

---

[English](../README.md) | [中文](./README-CN.md) | [日本語](./README-JP.md)

> Современный шаблон разработки пользовательского интерфейса, интегрирующий React и Tailwind CSS, с поддержкой Rsbuild, TypeScript, ESLint (конфигурация Antfu) и Iconify.

## ✨ Особенности

- **Современный UI-фреймворк:** Строится с использованием React (v19) для компонентно-ориентированного декларативного интерфейса.
- **Стилизация с упором на утилиты:** Использует Tailwind CSS v4 (`tailwindcss`) вместе с `@tailwindcss/postcss`, обеспечивая гибкую и быструю стилизацию при сохранении согласованности.
- **Быстрый рабочий процесс разработки:** Использует Rsbuild (`@rsbuild/core` и `@rsbuild/plugin-react`) для оптимизированных сборок и эффективной производительности сервера разработки.
- **Поддержка иконок:** Включает `@iconify/json` и `@iconify/tailwind4` для масштабируемой и настраиваемой иконографии.
- **Типовая безопасность:** Использует TypeScript (v5.9.x) для повышения надежности кода и обеспечения надежной проверки типов во время разработки.
- **Фокус на качестве кода:** Включает ESLint с `@antfu/eslint-config` для линтинга и обеспечения лучших практик в кодовой базе.
- **Git Hooks:** Интеграция `husky` и `lint-staged` для предварительных проверок коммитов.

## 💻 Технологический стек

- **Фреймворк/Библиотека:** React (v19)
- **Стилизация:** Tailwind CSS (`tailwindcss`)
- **Инструмент сборки:** Rsbuild (`@rsbuild/core`)
- **Язык:** TypeScript (v5.9.x)
- **Обработка CSS:** PostCSS with `@tailwindcss/postcss`
- **Линтинг:** ESLint с `@antfu/eslint-config`
- **Иконки:** Iconify (`@iconify/json`, `@iconify/tailwind4`)

Полный список зависимостей см. в [package.json](../package.json).

## 🚀 Начало работы

Следуйте этим инструкциям, чтобы запустить проект локально.

### Предварительные требования

Убедитесь, что у вас установлены следующие компоненты:

- Node.js (рекомендуется версия >= 18.x)
- Пакетный менеджер (npm, yarn или pnpm)

```bash
node -v
npm -v
```

### Установка

1. Создайте новый проект с помощью шаблона:

   ```bash
   pnpm create trapar-waves
   ```

2. Перейдите в каталог вашего проекта и установите зависимости:

   ```bash
   pnpm install
   # or
   npm install
   # or
   yarn install
   ```

3. Запустите сервер разработки:

   ```bash
   pnpm dev
   ```

## 🧱 Структура проекта

```
├── public/           # Статические ресурсы
├── src/              # Исходный код
│   ├── App.css       # Глобальные стили и импорт Tailwind
│   ├── App.tsx       # Основной компонент приложения
│   └── index.tsx     # Точка входа
├── rsbuild.config.ts # Конфигурация Rsbuild
├── tsconfig.json     # Конфигурация TypeScript
├── eslint.config.js  # Конфигурация ESLint
└── package.json      # Зависимости и скрипты проекта
```

## 🤝 Участие в разработке

Вклад в проект приветствуется и очень ценится! Чтобы внести вклад, следуйте этим шагам:

1. Сделайте форк репозитория
2. Создайте ветку с функцией (`git checkout -b feature/amazing-feature`)
3. Зафиксируйте свои изменения (`git commit -m 'Add some amazing feature'`)
4. Отправьте изменения в ветку (`git push origin feature/amazing-feature`)
5. Откройте Pull Request

## 👤 Author

- **Rikka:** [admin@rikka.cc](mailto:admin@rikka.cc)
- **GitHub Profile:** [Muromi-Rikka](https://github.com/Muromi-Rikka)

## 🔗 Links

- **Репозиторий:** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **Домашняя страница:** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **Проблемы:** [https://github.com/Trapar-waves/react-tailwind/issues](https://github.com/Trapar-waves/react-tailwind/issues)
