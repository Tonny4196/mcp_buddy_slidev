---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection
background: https://source.unsplash.com/1920x1080/?nature,water
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## MCP Buddy Slidev プレゼンテーション
  
  MCP Buddyプロジェクトのドキュメンテーションとプレゼンテーション。
  
  詳細は [Sli.dev](https://sli.dev) をご覧ください
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# MCP Buddy

プレゼンテーション作成とドキュメント

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    次のページはスペースキーを押してください <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
各スライドの最後のコメントブロックはスライドノートとして扱われます。プレゼンターモードでスライドと一緒に表示・編集できます。[詳細はドキュメントを参照](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Slidevとは？

Slidevは開発者向けに設計されたスライド作成・プレゼンテーションツールで、以下の機能を備えています

- 📝 **テキストベース** - Markdownでコンテンツに集中し、後でスタイルを設定
- 🎨 **テーマ対応** - テーマをnpmパッケージで共有・利用可能
- 🧑‍💻 **開発者フレンドリー** - コードハイライト、自動補完付きライブコーディング
- 🤹 **インタラクティブ** - Vueコンポーネントの埋め込みで表現力を向上
- 🎥 **録画機能** - 内蔵の録画機能とカメラビュー
- 📤 **ポータブル** - PDF、PNG、またはホスト可能なSPAとしてエクスポート
- 🛠 **ハック可能** - Webページで可能なあらゆることが実現可能

<br>
<br>

詳細は [Why Slidev?](https://sli.dev/guide/why) をお読みください

<!--
Markdownで `style` タグを使用して現在のページのスタイルを上書きできます。
詳細: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# はじめに

Slidevには [**Node.js >=14.0**](https://nodejs.org/) が必要です

npmを使用:

```bash
$ npm install -g @slidev/cli
$ slidev
```

yarnを使用:

```bash
$ yarn global add @slidev/cli
$ slidev
```

`slides.md` を編集して <http://localhost:3030> を開くと変更を確認できます。

---

# このプロジェクトの使用方法

開発サーバーを起動:

```bash
npm run dev
```

本番用にビルド:

```bash
npm run build
```

PDFにエクスポート:

```bash
npm run export
```

Slidevの詳細は[ドキュメント](https://ja.sli.dev/)をご覧ください。

---

# ありがとうございました！

ご質問はありますか？