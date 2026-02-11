# iter-ly

セブ島ツアーのランディングページ

https://www.iter-ly.com

## 技術スタック

- [Astro](https://astro.build/) v5
- [Tailwind CSS](https://tailwindcss.com/) v4
- [astro-icon](https://github.com/natemoo-re/astro-icon) + Lucide Icons
- GitHub Pages (デプロイ)

## 開発環境の構築

### 必要なもの

- Node.js v22 以上

### セットアップ

```bash
npm install
```

### 開発サーバーの起動

```bash
npm run dev
```

http://localhost:4321 で開発サーバーが起動します。

### コマンド一覧

| コマンド | 説明 |
|:--|:--|
| `npm run dev` | 開発サーバーを起動 |
| `npm run build` | 本番用ビルド (`./dist/`) |
| `npm run preview` | ビルド結果をローカルでプレビュー |
| `npm run lint` | ESLint + Prettier のチェック |
| `npm run lint:fix` | ESLint + Prettier の自動修正 |
| `npm run format` | Prettier でフォーマット |

## ディレクトリ構成

```
src/
├── components/
│   ├── parts/       # 再利用可能な UI パーツ
│   └── sections/    # ページセクション
├── layouts/
├── pages/
│   ├── index.astro        # トップページ
│   └── dev/
│       └── components.astro  # コンポーネントプレビュー
└── styles/
```
