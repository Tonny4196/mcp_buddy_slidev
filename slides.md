---
# Anthony Fu inspired clean theme
theme: default
# Clean gradient background
background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%)
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
  color: #f8fafc;
  margin-bottom: 0.5rem;
}

.subtitle {
  color: #94a3b8;
  font-size: 1.25rem;
  font-weight: 400;
  margin-top: 1rem;
}

.nav-button {
  background: #3b82f6;
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
  background: #2563eb;
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

<div class="space-y-8 text-left max-w-4xl mx-auto">

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
  color: #f8fafc;
  font-weight: 700;
  margin-bottom: 2rem;
  text-align: center;
}

h2 {
  color: #e2e8f0;
  font-weight: 600;
  font-size: 1.5rem;
  margin-bottom: 1rem;
}

.origin-step {
  background: rgba(30, 41, 59, 0.5);
  padding: 2rem;
  border-radius: 0.75rem;
  border: 1px solid rgba(71, 85, 105, 0.3);
}

.origin-step.highlight {
  border-color: #3b82f6;
  background: rgba(59, 130, 246, 0.1);
}

.team-name {
  color: #3b82f6;
  font-weight: 700;
  font-size: 1.2em;
}

li {
  color: #cbd5e1;
  margin: 0.5rem 0;
}

strong {
  color: #f1f5f9;
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
.members-container {
  display: flex;
  justify-content: center;
  padding-top: 2rem;
}

.member-card {
  background: rgba(30, 41, 59, 0.6);
  border: 1px solid rgba(71, 85, 105, 0.4);
  border-radius: 1rem;
  padding: 2.5rem;
  max-width: 28rem;
  transition: all 0.2s ease;
}

.member-card:hover {
  transform: translateY(-2px);
  border-color: #3b82f6;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
}

.member-card h2 {
  color: #f8fafc;
  font-size: 1.75rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  text-align: center;
}

.member-card li {
  color: #cbd5e1;
  margin: 0.75rem 0;
  font-size: 1.1rem;
}

.member-card strong {
  color: #f1f5f9;
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
.activities-grid {
  display: grid;
  gap: 1.5rem;
  padding-top: 2rem;
  max-width: 4xl;
  margin: 0 auto;
}

.activity-item {
  background: rgba(30, 41, 59, 0.5);
  border: 1px solid rgba(71, 85, 105, 0.3);
  border-radius: 0.75rem;
  padding: 2rem;
  transition: all 0.2s ease;
  position: relative;
}

.activity-item:hover {
  transform: translateY(-2px);
  border-color: #3b82f6;
  background: rgba(30, 41, 59, 0.7);
}

.activity-item h2 {
  color: #f8fafc;
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 1rem;
}

.activity-desc {
  color: #cbd5e1;
  font-size: 1.1rem;
  line-height: 1.6;
}

.note-text {
  color: #94a3b8;
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
.achievement-card {
  background: rgba(30, 41, 59, 0.6);
  border: 2px solid #3b82f6;
  border-radius: 1.5rem;
  padding: 3rem;
  text-align: center;
  max-width: 32rem;
  position: relative;
  box-shadow: 0 10px 30px rgba(59, 130, 246, 0.2);
}

.achievement-card h2 {
  color: #fbbf24;
  font-size: 2rem;
  font-weight: 700;
  margin-bottom: 2rem;
}

.achievement-details {
  font-size: 1.2rem;
  line-height: 1.8;
}

.achiever-name {
  color: #e2e8f0;
  margin: 1rem 0;
}

.certification-name {
  color: #3b82f6;
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
.goals-section {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  padding-top: 2rem;
}

.goals-card {
  background: rgba(30, 41, 59, 0.6);
  border: 1px solid rgba(71, 85, 105, 0.4);
  border-radius: 1.2rem;
  padding: 3rem;
  text-align: center;
  max-width: 36rem;
}

.goals-card h2 {
  color: #f8fafc;
  font-size: 2rem;
  font-weight: 600;
  margin-bottom: 2rem;
}

.goals-description {
  font-size: 1.25rem;
  color: #cbd5e1;
  line-height: 1.8;
  margin-bottom: 2rem;
}

.highlight {
  color: #3b82f6;
  font-weight: 600;
}

.progress-indicator {
  margin-top: 2rem;
}

.progress-bar {
  width: 100%;
  height: 8px;
  background: rgba(71, 85, 105, 0.3);
  border-radius: 4px;
  overflow: hidden;
  margin-bottom: 0.75rem;
}

.progress-fill {
  height: 100%;
  background: #3b82f6;
  border-radius: 4px;
  width: 66%;
  transition: width 0.5s ease;
}

.progress-text {
  color: #94a3b8;
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
  color: #f8fafc;
  margin-bottom: 1rem;
}

.team-name {
  font-size: 2rem;
  color: #cbd5e1;
  margin: 2rem 0;
  font-weight: 500;
}

.mcp-highlight {
  color: #3b82f6;
  font-weight: 700;
}

.question-prompt {
  background: rgba(30, 41, 59, 0.6);
  border: 1px solid #3b82f6;
  color: #e2e8f0;
  padding: 1rem 2rem;
  border-radius: 0.75rem;
  font-size: 1.3rem;
  font-weight: 500;
  display: inline-block;
  transition: all 0.2s ease;
}

.question-prompt:hover {
  border-color: #60a5fa;
  background: rgba(30, 41, 59, 0.8);
}
</style>