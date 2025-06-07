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
h1 {
  font-size: 3.5rem;
  font-weight: 700;
  color: #1a1a1a;
  margin-bottom: 0.5rem;
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

<div class="space-y-6 text-left max-w-5xl mx-auto px-8">

<div class="origin-step">

## 全員がtech系に関わっている
- **自分・てぃーぬ：SE**
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
  margin-bottom: 2rem;
  text-align: center;
}

h2 {
  color: #333333;
  font-weight: 600;
  font-size: 1.5rem;
  margin-bottom: 1rem;
}

.origin-step {
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 0.75rem;
  border: 1px solid #e9ecef;
  margin-bottom: 1.2rem;
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
  margin: 0.5rem 0;
}

strong {
  color: #1a1a1a;
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

</div>

<style>
h1 {
  color: #1a1a1a;
  font-weight: 700;
  margin-bottom: 2rem;
  text-align: center;
}

.members-container {
  display: flex;
  justify-content: center;
  padding-top: 2rem;
  padding-left: 2rem;
  padding-right: 2rem;
}

.member-card {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 1rem;
  padding: 2.5rem;
  max-width: 36rem;
  width: 100%;
  transition: all 0.2s ease;
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
  gap: 1.2rem;
  padding: 2rem 2rem 0 2rem;
  max-width: 60rem;
  margin: 0 auto;
}

.activity-item {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 0.75rem;
  padding: 1.5rem;
  transition: all 0.2s ease;
  position: relative;
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

<div class="flex justify-center items-center h-full">

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
  padding: 2.5rem;
  text-align: center;
  max-width: 40rem;
  width: 90%;
  position: relative;
  box-shadow: 0 10px 30px rgba(16, 185, 129, 0.1);
  margin: 0 auto;
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

## 📋 今後の目標設定

<div class="goals-description">
各メンバーの残り1ヶ月での目標を設定し、<br>
<span class="highlight">継続的な成長と学習を目指します</span>
</div>

<div class="progress-indicator">
  <div class="progress-bar">
    <div class="progress-fill"></div>
  </div>
  <span class="progress-text">2/3 完了</span>
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
  align-items: center;
  height: 100%;
  padding: 2rem;
}

.goals-card {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 1.2rem;
  padding: 2.5rem;
  text-align: center;
  max-width: 42rem;
  width: 90%;
}

.goals-card h2 {
  color: #1a1a1a;
  font-size: 1.8rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
}

.goals-description {
  font-size: 1.15rem;
  color: #555555;
  line-height: 1.7;
  margin-bottom: 1.5rem;
}

.highlight {
  color: #10b981;
  font-weight: 600;
}

.progress-indicator {
  margin-top: 2rem;
}

.progress-bar {
  width: 100%;
  height: 8px;
  background: #e5e7eb;
  border-radius: 4px;
  overflow: hidden;
  margin-bottom: 0.75rem;
}

.progress-fill {
  height: 100%;
  background: #10b981;
  border-radius: 4px;
  width: 66%;
  transition: width 0.5s ease;
}

.progress-text {
  color: #888888;
  font-size: 0.9rem;
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
  font-size: 3.5rem;
  font-weight: 700;
  color: #1a1a1a;
  margin-bottom: 1rem;
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