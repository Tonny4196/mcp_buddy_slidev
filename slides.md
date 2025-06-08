---
# Anthony Fu inspired clean theme
theme: default
# Clean light background
background: '#ffffff'
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
fonts:
  sans: ['Inter', 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', 'Segoe UI', 'Roboto', 'sans-serif']
  mono: ['JetBrains Mono', 'Consolas', 'Monaco', 'Fira Code', 'monospace']
---

# Buddy 中間発表

<div class="subtitle">2ヶ月間プログラムの中間発表</div>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="nav-button">
    次へ <carbon:arrow-right class="inline ml-2"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2 opacity-60">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none hover:opacity-100">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none hover:opacity-100">
    <carbon-logo-github />
  </a>
</div>

<style>
/* Global responsive overflow prevention */
* {
  box-sizing: border-box;
}

.slidev-layout {
  overflow-x: hidden !important;
  max-width: 100% !important;
}

h1 {
  font-size: 2.5rem;
  font-weight: 700;
  color: #1a1a1a;
  margin-bottom: 0.5rem;
  padding: 0 2rem;
  box-sizing: border-box;
}

.subtitle {
  color: #666666;
  font-size: 1.25rem;
  font-weight: 400;
  margin-top: 1rem;
}

.nav-button {
  background: #10b981;
  color: white;
  padding: 0.75rem 1.5rem;
  border-radius: 0.5rem;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.2s ease;
  border: none;
  display: inline-flex;
  align-items: center;
}

.nav-button:hover {
  background: #059669;
  transform: translateY(-1px);
}
</style>

<!--
Buddy 2ヶ月間プログラムの中間発表スライド
-->

---
layout: default
---

# チーム名の由来

<div class="space-y-4 text-left mx-auto px-4" style="max-width: 800px; width: 90%; height: 450px; box-sizing: border-box; padding-top: 1rem; overflow: hidden;">

<div class="origin-step">

## 全員がtech系に関わっている
- **とに：SE**
- **てぃーぬ：FE**
- **たなとす：セキュリティ系**
- **しょうど：情シス**

</div>

<v-click>

<div class="origin-step">

## Tech系にまつわる名前にしよう

</div>

</v-click>

<v-click>

<div class="origin-step highlight">

## 最初の目標達成のMTGでAIの話をめっちゃした
**AI系のワードに被せよう → <span class="team-name">MCP</span>になった**

</div>

</v-click>

</div>

<style>
h1 {
  color: #1a1a1a;
  font-weight: 700;
  margin-bottom: 1.5rem;
  text-align: center;
  font-size: 2.5rem;
}

h2 {
  color: #333333;
  font-weight: 600;
  font-size: 1.4rem;
  margin-bottom: 0.5rem;
}

.origin-step {
  background: #f8f9fa;
  padding: 0.8rem;
  border-radius: 0.75rem;
  border: 1px solid #e9ecef;
  margin-bottom: 0.6rem;
  height: auto;
  min-height: 70px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.origin-step.highlight {
  border-color: #10b981;
  background: #f0fdf4;
}

.team-name {
  color: #10b981;
  font-weight: 700;
  font-size: 1.2em;
}

li {
  color: #555555;
  margin: 0.2rem 0;
  font-size: 1rem;
}

strong {
  color: #1a1a1a;
  font-weight: 600;
}
</style>

---

# チームメンバー

<div class="members-container">

<div class="member-card">

## とに 🤖
- **職業：** SE
- **勉強内容：** 個人開発
- **最近興味がある分野：** MCP・コーディングエージェント

</div>

<div class="member-card">

## てぃーぬ 💻
- **職業：** FE（フロントエンドエンジニア）
- **勉強内容：** JavaScript・ディープラーニングG検定
- **最近興味がある分野：** AIを使ったコーディング

</div>

<div class="member-card">

## たなとす 🔒
- **職業：** ICS系 セキュリティ
- **勉強内容：** 脆弱性評価・サイバー攻撃対策
- **最近興味がある分野：** obsidianのAI活用

</div>

<div class="member-card">

## しょうど（しょうどうぶつ） 🖥️
- **職業：** 社内情シス
- **勉強内容：** 簿記3級
- **最近興味がある分野：** 情報セキュリティ全般・情報リテラシー

</div>

</div>

<style>
h1 {
  color: #1a1a1a;
  font-weight: 700;
  margin-bottom: 2rem;
  text-align: center;
}

.members-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.2rem;
  padding: 0.5rem 2rem;
  max-width: 900px;
  height: 450px;
  margin: 0 auto;
  box-sizing: border-box;
  overflow-y: auto;
}

.member-card {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 1rem;
  padding: 1.2rem;
  max-width: 400px;
  width: 100%;
  height: 200px;
  transition: all 0.2s ease;
  margin: 0 auto;
  box-sizing: border-box;
  overflow: hidden;
}

.member-card:hover {
  transform: translateY(-2px);
  border-color: #10b981;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
}

.member-card h2 {
  color: #1a1a1a;
  font-size: 1.75rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  text-align: center;
}

.member-card li {
  color: #555555;
  margin: 0.75rem 0;
  font-size: 1.1rem;
}

.member-card strong {
  color: #1a1a1a;
  font-weight: 600;
}
</style>

---

# 活動内容

<div class="activities-grid">

<v-click>

<div class="activity-item">

## 📚 気になったテック系の情報共有
<div class="activity-desc">チームメンバーが見つけた技術情報やトレンドを共有</div>

</div>

</v-click>

<v-click>

<div class="activity-item">

## 💪 筋トレ報告
<div class="activity-desc">健康維持とチームビルディングを兼ねた活動</div>
<div class="note-text">*写真入れる*</div>

</div>

</v-click>

<v-click>

<div class="activity-item">

## 🌅 7時朝会
<div class="activity-desc">定期的なコミュニケーションとスケジュール共有</div>

</div>

</v-click>

</div>

<style>
h1 {
  color: #1a1a1a;
  font-weight: 700;
  margin-bottom: 2rem;
  text-align: center;
}

.activities-grid {
  display: grid;
  gap: 1rem;
  padding: 0.5rem 2rem;
  max-width: 800px;
  height: 450px;
  margin: 0 auto;
  width: 90%;
  box-sizing: border-box;
  overflow-y: auto;
}

.activity-item {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 0.75rem;
  padding: 1.2rem;
  height: 120px;
  transition: all 0.2s ease;
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.activity-item:hover {
  transform: translateY(-2px);
  border-color: #10b981;
  background: #f0fdf4;
}

.activity-item h2 {
  color: #1a1a1a;
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 1rem;
}

.activity-desc {
  color: #555555;
  font-size: 1.1rem;
  line-height: 1.6;
}

.note-text {
  color: #888888;
  font-style: italic;
  margin-top: 0.75rem;
  font-size: 0.95rem;
}
</style>

---

# 成果報告

<div class="flex justify-center items-center" style="height: 450px; padding: 2rem 0;">

<div class="achievement-card">

## 🎉 おめでとうございます！

<div class="achievement-details">
<div class="achiever-name">**てぃーぬさんが**</div>
<div class="certification-name">**HTML5プロフェッショナル認定試験**</div>
<div class="level-badge">**レベル2に合格**</div>
</div>

</div>

</div>

<style>
h1 {
  color: #1a1a1a;
  font-weight: 700;
  margin-bottom: 2rem;
  text-align: center;
}

.achievement-card {
  background: #f8f9fa;
  border: 2px solid #10b981;
  border-radius: 1.5rem;
  padding: 1.5rem;
  text-align: center;
  max-width: 600px;
  width: 90%;
  height: 300px;
  position: relative;
  box-shadow: 0 10px 30px rgba(16, 185, 129, 0.1);
  margin: 0 auto;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.achievement-card h2 {
  color: #f59e0b;
  font-size: 1.8rem;
  font-weight: 700;
  margin-bottom: 1.5rem;
}

.achievement-details {
  font-size: 1.1rem;
  line-height: 1.7;
}

.achiever-name {
  color: #333333;
  margin: 1rem 0;
}

.certification-name {
  color: #1a1a1a;
  margin: 1rem 0;
  font-weight: 600;
}

.level-badge {
  color: #10b981;
  font-size: 1.3rem;
  margin: 1rem 0;
  font-weight: 700;
}

strong {
  font-weight: 600;
}
</style>

---

# 残り1ヶ月の目標

<div class="goals-section">

<div class="goals-card">

## 📋 各メンバーの個別目標

<div class="individual-goals">

<div class="goal-member">
<h3>🤖 とに</h3>
<ul>
<li>個人開発プロジェクトの継続</li>
<li>MCPとコーディングエージェントの深掘り</li>
</ul>
</div>

<div class="goal-member">
<h3>💻 てぃーぬ</h3>
<ul>
<li>9月受験に向けたディープラーニングG検定の勉強</li>
<li>プチ増量期で筋肉を1kgぐらい増やす</li>
</ul>
</div>

<div class="goal-member">
<h3>🔒 たなとす</h3>
<ul>
<li>10月に受けるかもしれないセキスペの勉強</li>
<li>6月は100km走る</li>
</ul>
</div>

<div class="goal-member">
<h3>🖥️ しょうど</h3>
<ul>
<li>簿記3級の勉強</li>
<li>体重維持</li>
</ul>
</div>

</div>

</div>

</div>

<style>
h1 {
  color: #1a1a1a;
  font-weight: 700;
  margin-bottom: 2rem;
  text-align: center;
}

.goals-section {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  height: 420px;
  padding: 1rem 2rem;
  box-sizing: border-box;
  overflow: hidden;
}

.goals-card {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 1.2rem;
  padding: 0.8rem;
  text-align: center;
  max-width: 850px;
  width: 95%;
  height: 380px;
  overflow: hidden;
  box-sizing: border-box;
  margin: 0 auto;
}

.goals-card h2 {
  color: #1a1a1a;
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 1rem;
}

.individual-goals {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0.7rem;
  margin-top: 1rem;
}

.goal-member {
  background: #f0fdf4;
  border: 1px solid #d1fae5;
  border-radius: 0.75rem;
  padding: 0.8rem;
  transition: all 0.2s ease;
}

.goal-member:hover {
  transform: translateY(-2px);
  border-color: #10b981;
  box-shadow: 0 4px 12px rgba(16, 185, 129, 0.1);
}

.goal-member h3 {
  color: #1a1a1a;
  font-size: 1.1rem;
  font-weight: 600;
  margin-bottom: 0.5rem;
  text-align: center;
}

.goal-member ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.goal-member li {
  color: #555555;
  font-size: 0.9rem;
  margin: 0.3rem 0;
  padding-left: 1rem;
  position: relative;
}

.goal-member li:before {
  content: "→";
  color: #10b981;
  font-weight: 600;
  position: absolute;
  left: 0;
}
</style>

---
layout: center
class: text-center
---

# ありがとうございました！

<div class="team-name">チーム <span class="mcp-highlight">MCP</span></div>

<div class="pt-12">
  <div class="question-prompt">
    💬 ご質問はありますか？
  </div>
</div>

<style>
h1 {
  font-size: 2.5rem;
  font-weight: 700;
  color: #1a1a1a;
  margin-bottom: 1rem;
  padding: 0 2rem;
  box-sizing: border-box;
}

.team-name {
  font-size: 2rem;
  color: #555555;
  margin: 2rem 0;
  font-weight: 500;
}

.mcp-highlight {
  color: #10b981;
  font-weight: 700;
}

.question-prompt {
  background: #f8f9fa;
  border: 1px solid #10b981;
  color: #1a1a1a;
  padding: 1rem 2rem;
  border-radius: 0.75rem;
  font-size: 1.3rem;
  font-weight: 500;
  display: inline-block;
  transition: all 0.2s ease;
}

.question-prompt:hover {
  border-color: #059669;
  background: #f0fdf4;
}
</style>