# Meco Portfolio (Astro)

## セットアップ

```bash
npm install
npm run dev
```

`http://localhost:4321` で確認できます。

## 構成

- `src/components/Hero.astro` — 自己紹介 + フロー図(サイン要素)
- `src/components/Skills.astro` — スキル(実務レベル/学習中)
- `src/components/Works.astro` — Webサイト実績 3件
- `src/components/LP.astro` — LP実績 2件
- `src/components/Banners.astro` — バナー実績 10件(画像未設定のプレースホルダー)
- `src/components/DX.astro` — 業務改善・自動化のケーススタディ 3件
- `src/components/Contact.astro` — GitHub・お問い合わせ

## デザインコンセプト

- 配色: ペーパーグレー(#E7E6DE)+ 真鍮アクセント(#A8763E)+ 深緑(#3F5D50)
- 書体: 見出し=Zen Old Mincho、本文=Noto Sans JP、ラベル=IBM Plex Mono
- レイアウト: 決算書・伝票のような罫線区切り+番号付きの構成

## 次にやること

1. `Works.astro` / `LP.astro` の各項目に実際のサイト名・URL・説明文を入力
2. `Banners.astro` の各枠に実際のバナー画像を差し込む(`.banner-thumb` を `<img>` に置き換え)
3. `Contact.astro` のメールアドレス・GitHubリンクを実際のものに変更
4. Vercel / Netlify などにデプロイ

## デプロイ(Vercelの場合)

```bash
npm i -g vercel
vercel
```

または GitHub リポジトリに push して Vercel と連携すれば自動デプロイされます。
