---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection
background: https://source.unsplash.com/1920x1080/?technology,programming
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Buddy 中間発表
  
  2ヶ月間プログラムの中間発表資料
  
  詳細は [Sli.dev](https://sli.dev) をご覧ください
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# Buddy 中間発表

2ヶ月間プログラムの中間発表

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
Buddy 2ヶ月間プログラムの中間発表スライド
-->

---
transition: fade-out
---

# チーム名の由来

<div class="grid grid-cols-1 gap-4">

## 全員がtech系に関わっている
- **自分・てぃーぬ：SE**
- **たなとす：セキュリティ系**
- **しょうど：情シス**

<v-click>

## Tech系にまつわる名前にしよう

</v-click>

<v-click>

## 最初の目標達成のMTGでAIの話をめっちゃした
**AI系のワードに被せよう → MCPになった**

</v-click>

</div>

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

# チームメンバー

<div class="grid grid-cols-1 gap-6 pt-4">

<div class="bg-blue-50 p-6 rounded-lg">

## とに
- **職業：** SE
- **勉強内容：** 個人開発
- **最近興味がある分野：** MCP・コーディングエージェント

</div>

</div>

---

# 活動内容

<div class="grid grid-cols-1 gap-6">

<v-click>

## 📚 気になったテック系の情報共有
チームメンバーが見つけた技術情報やトレンドを共有

</v-click>

<v-click>

## 💪 筋トレ報告
健康維持とチームビルディングを兼ねた活動
*写真入れる*

</v-click>

<v-click>

## 🌅 7時朝会
定期的なコミュニケーションとスケジュール共有

</v-click>

</div>

---

# 成果報告

<div class="flex justify-center items-center h-full">

<div class="bg-gradient-to-r from-green-400 to-blue-500 text-white p-8 rounded-xl text-center">

## 🎉 おめでとうございます！

**てぃーぬさんが**  
**HTML5プロフェッショナル認定試験**  
**レベル2に合格**

</div>

</div>

---

# 残り1ヶ月の各自の目標

<div class="grid grid-cols-1 gap-6 pt-4">

<div class="bg-gradient-to-r from-purple-400 to-pink-400 text-white p-6 rounded-lg">

## 📋 今後の目標設定

各メンバーの残り1ヶ月での目標を設定し、  
継続的な成長と学習を目指します

</div>

</div>

---
layout: center
class: text-center
---

# ありがとうございました！

チーム MCP

<div class="pt-12">
  <span class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    ご質問はありますか？
  </span>
</div>