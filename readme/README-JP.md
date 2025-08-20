# @trapar-waves/react-tailwind

![npm version](https://img.shields.io/npm/v/@trapar-waves/react-tailwind)
![npm dm](https://img.shields.io/npm/dm/@trapar-waves/react-tailwind)
![License](https://img.shields.io/github/license/Trapar-waves/react-tailwind)
![GitHub last commit](https://img.shields.io/github/last-commit/Trapar-waves/react-tailwind)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Trapar-waves/react-tailwind/release.yml)
![Renovate](https://img.shields.io/badge/renovate-enabled-blue)

---

[English](../README.md) | [中文](./README-CN.md) | [Русский язык](./README-RU.md)

> ReactとTailwind CSSを統合したモダンなUI開発テンプレート。Rsbuild、TypeScript、ESLint (Antfu config)、Iconifyをサポート。

## ✨ 特徴

- **モダンUIフレームワーク:** コンポーネント駆動の宣言型インターフェースのためにReact (v19)を使用して構築されています。
- **ユーティリティファーストのスタイリング:** Tailwind CSS v4 (`tailwindcss`)と`@tailwindcss/postcss`を採用し、一貫性を維持しながら柔軟で迅速なスタイリングを可能にします。
- **高速開発ワークフロー:** Rsbuild（`@rsbuild/core`と`@rsbuild/plugin-react`）を使用して最適化されたビルドと効率的な開発サーバーパフォーマンスを実現します。
- **アイコンサポート:** `@iconify/json`と`@iconify/tailwind4`を含み、スケーラブルでカスタマイズ可能なアイコンを提供します。
- **型安全性:** TypeScript (v5.9.x)を使用してコードの信頼性を向上させ、開発中に堅牢な型チェックを提供します。
- **コード品質への焦点:** ESLintと`@antfu/eslint-config`を含み、コードベースのリンティングとベストプラクティスの適用を実現します。
- **Git フック:** `husky`と`lint-staged`を統合し、コミット前のチェックを実施します。

## 💻 技術スタック

- **フレームワーク/ライブラリ:** React (v19)
- **スタイリング:** Tailwind CSS (`tailwindcss`)
- **ビルドツール:** Rsbuild (`@rsbuild/core`)
- **言語:** TypeScript (v5.9.x)
- **CSS処理:** PostCSS with `@tailwindcss/postcss`
- **リンティング:** `@antfu/eslint-config`を備えたESLint
- **アイコン:** Iconify (`@iconify/json`, `@iconify/tailwind4`)

依存関係の完全なリストについては[package.json](../package.json)を参照してください。

## 🚀 始め方

以下の手順に従ってプロジェクトをローカルで実行してください。

### 前提条件

以下がインストールされていることを確認してください：

- Node.js (推奨バージョン >= 18.x)
- パッケージマネージャー (npm, yarn または pnpm)

```bash
node -v
npm -v
```

### インストール

1. テンプレートを使用して新しいプロジェクトを作成:

   ```bash
   pnpm create trapar-waves
   ```

2. プロジェクトディレクトリに移動し、依存関係をインストール:

   ```bash
   pnpm install
   # or
   npm install
   # or
   yarn install
   ```

3. 開発サーバーを起動:

   ```bash
   pnpm dev
   ```

## 🧱 プロジェクト構造

```
├── public/           # 静的アセット
├── src/              # ソースコード
│   ├── App.css       # グローバルスタイルとTailwindのインポート
│   ├── App.tsx       # メインアプリケーションコンポーネント
│   └── index.tsx     # エントリーポイント
├── rsbuild.config.ts # Rsbuild設定
├── tsconfig.json     # TypeScript設定
├── eslint.config.js  # ESLint設定
└── package.json      # プロジェクトの依存関係とスクリプト
```

## 🤝 コントリビューション

貢献は歓迎され、非常に高く評価されています！貢献するには以下の手順に従ってください：

1. リポジトリをフォークする
2. 機能ブランチを作成する（`git checkout -b feature/amazing-feature`）
3. 変更をコミットする（`git commit -m 'Add some amazing feature'`）
4. ブランチにプッシュする（`git push origin feature/amazing-feature`）
5. Pull Requestを開く

## 👤 Author

- **Rikka:** [admin@rikka.cc](mailto:admin@rikka.cc)
- **GitHub Profile:** [Muromi-Rikka](https://github.com/Muromi-Rikka)

## 🔗 Links

- **リポジトリ:** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **ホームページ:** [https://github.com/Trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind)
- **イシュー:** [https://github.com/Trapar-waves/react-tailwind/issues](https://github.com/Trapar-waves/react-tailwind/issues)
