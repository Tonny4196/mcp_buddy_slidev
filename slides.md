---
# try also 'default' to start simple
theme: seriph
# futuristic tech background
background: https://source.unsplash.com/1920x1080/?cyberpunk,neon,technology,future
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
  sans: ['Meiryo', 'Hiragino Sans', 'Yu Gothic UI', 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue', 'sans-serif']
  mono: ['Consolas', 'Monaco', 'Cascadia Code', 'Segoe UI Mono', 'Roboto Mono', 'Oxygen Mono', 'Ubuntu Monospace', 'Source Code Pro', 'Fira Mono', 'Droid Sans Mono', 'Courier New', 'monospace']
---

# <span class="futuristic-title">🚀 Buddy 中間発表</span>

<div class="subtitle-glow">2ヶ月間プログラムの中間発表</div>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="futuristic-button px-4 py-2 rounded-lg cursor-pointer transition-all duration-300" hover="bg-cyan-400 bg-opacity-20 transform scale-105">
    次のページはスペースキーを押してください <carbon:arrow-right class="inline ml-2"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-cyan-300 transition-colors duration-300">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-cyan-300 transition-colors duration-300">
    <carbon-logo-github />
  </a>
</div>

<style>
.futuristic-title {
  background: linear-gradient(135deg, #00f5ff, #ff006e, #8338ec, #3a86ff);
  background-size: 400% 400%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradient-shift 3s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(0, 245, 255, 0.5);
}

.subtitle-glow {
  color: #e0e7ff;
  text-shadow: 0 0 20px rgba(99, 102, 241, 0.8);
  font-size: 1.2rem;
  margin-top: 1rem;
}

.futuristic-button {
  background: linear-gradient(45deg, rgba(6, 182, 212, 0.2), rgba(139, 92, 246, 0.2));
  border: 1px solid rgba(6, 182, 212, 0.5);
  color: #e0e7ff;
  backdrop-filter: blur(10px);
  box-shadow: 0 8px 32px rgba(6, 182, 212, 0.3);
}

@keyframes gradient-shift {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>

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
  background: linear-gradient(135deg, #00f5ff, #ff006e, #8338ec, #3a86ff);
  background-size: 400% 400%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  animation: gradient-shift 4s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(0, 245, 255, 0.3);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.slide-container {
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

@keyframes gradient-shift {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>

---

# 👥 チームメンバー

<div class="grid grid-cols-1 gap-6 pt-4">

<div class="futuristic-card bg-gradient-to-br from-slate-800/80 to-slate-900/80 p-6 rounded-xl border border-cyan-400/30 backdrop-blur-sm">

## <span class="member-name">🤖 とに</span>
- **職業：** <span class="highlight-text">SE</span>
- **勉強内容：** <span class="highlight-text">個人開発</span>
- **最近興味がある分野：** <span class="highlight-text">MCP・コーディングエージェント</span>

</div>

</div>

<style>
.futuristic-card {
  box-shadow: 0 8px 32px rgba(6, 182, 212, 0.3), inset 0 1px 0 rgba(255, 255, 255, 0.1);
  transition: all 0.3s ease;
}

.futuristic-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 20px 40px rgba(6, 182, 212, 0.4), inset 0 1px 0 rgba(255, 255, 255, 0.2);
}

.member-name {
  color: #00f5ff;
  text-shadow: 0 0 15px rgba(0, 245, 255, 0.8);
}

.highlight-text {
  color: #8b5cf6;
  font-weight: 600;
  text-shadow: 0 0 10px rgba(139, 92, 246, 0.5);
}
</style>

---

# ⚡ 活動内容

<div class="grid grid-cols-1 gap-6">

<v-click>

<div class="activity-card tech-card">

## 📚 気になったテック系の情報共有
<div class="activity-desc">チームメンバーが見つけた技術情報やトレンドを共有</div>

</div>

</v-click>

<v-click>

<div class="activity-card fitness-card">

## 💪 筋トレ報告
<div class="activity-desc">健康維持とチームビルディングを兼ねた活動</div>
<div class="note-text">*写真入れる*</div>

</div>

</v-click>

<v-click>

<div class="activity-card meeting-card">

## 🌅 7時朝会
<div class="activity-desc">定期的なコミュニケーションとスケジュール共有</div>

</div>

</v-click>

</div>

<style>
.activity-card {
  padding: 1.5rem;
  border-radius: 1rem;
  border: 1px solid;
  backdrop-filter: blur(10px);
  transition: all 0.3s ease;
  margin: 0.75rem 0;
}

.activity-card:hover {
  transform: translateY(-3px) scale(1.02);
}

.tech-card {
  background: linear-gradient(135deg, rgba(6, 182, 212, 0.1), rgba(139, 92, 246, 0.1));
  border-color: rgba(6, 182, 212, 0.4);
  box-shadow: 0 8px 32px rgba(6, 182, 212, 0.2);
}

.fitness-card {
  background: linear-gradient(135deg, rgba(34, 197, 94, 0.1), rgba(251, 146, 60, 0.1));
  border-color: rgba(34, 197, 94, 0.4);
  box-shadow: 0 8px 32px rgba(34, 197, 94, 0.2);
}

.meeting-card {
  background: linear-gradient(135deg, rgba(251, 191, 36, 0.1), rgba(245, 101, 101, 0.1));
  border-color: rgba(251, 191, 36, 0.4);
  box-shadow: 0 8px 32px rgba(251, 191, 36, 0.2);
}

.activity-desc {
  color: #e2e8f0;
  font-size: 1.1rem;
  margin-top: 0.5rem;
}

.note-text {
  color: #94a3b8;
  font-style: italic;
  margin-top: 0.5rem;
}
</style>

---

# 🏆 成果報告

<div class="flex justify-center items-center h-full">

<div class="achievement-container">

## <span class="celebration-text">🎉 おめでとうございます！</span>

<div class="achievement-content">
<div class="achiever-name">**てぃーぬさんが**</div>
<div class="certification-name">**HTML5プロフェッショナル認定試験**</div>
<div class="level-badge">**レベル2に合格**</div>
</div>

<div class="sparkle-effect">✨</div>

</div>

</div>

<style>
.achievement-container {
  background: linear-gradient(135deg, 
    rgba(34, 197, 94, 0.2) 0%, 
    rgba(59, 130, 246, 0.2) 50%, 
    rgba(147, 51, 234, 0.2) 100%);
  border: 2px solid;
  border-image: linear-gradient(135deg, #22c55e, #3b82f6, #9333ea) 1;
  padding: 2.5rem;
  border-radius: 1.5rem;
  text-center;
  backdrop-filter: blur(15px);
  box-shadow: 
    0 20px 40px rgba(34, 197, 94, 0.3),
    0 0 60px rgba(59, 130, 246, 0.2),
    inset 0 1px 0 rgba(255, 255, 255, 0.1);
  position: relative;
  overflow: hidden;
}

.celebration-text {
  background: linear-gradient(45deg, #fbbf24, #f59e0b, #d97706);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-shadow: 0 0 30px rgba(251, 191, 36, 0.8);
  font-size: 2rem;
  animation: pulse-glow 2s ease-in-out infinite;
}

.achievement-content {
  margin: 1.5rem 0;
  font-size: 1.3rem;
}

.achiever-name {
  color: #e0e7ff;
  margin: 0.5rem 0;
  text-shadow: 0 0 15px rgba(224, 231, 255, 0.8);
}

.certification-name {
  background: linear-gradient(45deg, #22c55e, #3b82f6);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  margin: 0.5rem 0;
  text-shadow: 0 0 20px rgba(34, 197, 94, 0.5);
}

.level-badge {
  background: linear-gradient(45deg, #8b5cf6, #ec4899);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 1.4rem;
  margin: 0.5rem 0;
  text-shadow: 0 0 25px rgba(139, 92, 246, 0.6);
}

.sparkle-effect {
  position: absolute;
  top: 1rem;
  right: 1rem;
  font-size: 2rem;
  animation: sparkle 3s ease-in-out infinite;
}

@keyframes pulse-glow {
  0%, 100% { text-shadow: 0 0 30px rgba(251, 191, 36, 0.8); }
  50% { text-shadow: 0 0 50px rgba(251, 191, 36, 1), 0 0 80px rgba(251, 191, 36, 0.6); }
}

@keyframes sparkle {
  0%, 100% { 
    transform: rotate(0deg) scale(1);
    opacity: 0.7;
  }
  50% { 
    transform: rotate(180deg) scale(1.2);
    opacity: 1;
  }
}
</style>

---

# 🎯 残り1ヶ月の各自の目標

<div class="grid grid-cols-1 gap-6 pt-4">

<div class="goals-container">

## <span class="goals-icon">📋</span> 今後の目標設定

<div class="goals-description">
各メンバーの残り1ヶ月での目標を設定し、<br>
<span class="highlight-goals">継続的な成長と学習を目指します</span>
</div>

<div class="progress-bar">
  <div class="progress-fill"></div>
</div>

</div>

</div>

<style>
.goals-container {
  background: linear-gradient(135deg, 
    rgba(147, 51, 234, 0.2) 0%, 
    rgba(236, 72, 153, 0.2) 50%,
    rgba(251, 113, 133, 0.2) 100%);
  border: 1px solid rgba(147, 51, 234, 0.4);
  padding: 2rem;
  border-radius: 1.2rem;
  backdrop-filter: blur(10px);
  box-shadow: 0 15px 35px rgba(147, 51, 234, 0.3);
  text-align: center;
  position: relative;
  overflow: hidden;
}

.goals-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.1), transparent);
  animation: shimmer 3s infinite;
}

.goals-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
  display: inline-block;
  animation: bounce 2s infinite;
}

.goals-description {
  font-size: 1.2rem;
  color: #e2e8f0;
  line-height: 1.8;
  margin: 1.5rem 0;
}

.highlight-goals {
  background: linear-gradient(45deg, #f472b6, #a855f7);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 600;
  text-shadow: 0 0 20px rgba(244, 114, 182, 0.5);
}

.progress-bar {
  width: 100%;
  height: 8px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 4px;
  overflow: hidden;
  margin-top: 2rem;
}

.progress-fill {
  height: 100%;
  background: linear-gradient(90deg, #9333ea, #ec4899, #f472b6);
  border-radius: 4px;
  width: 66%;
  animation: progress-fill 2s ease-out;
}

@keyframes shimmer {
  0% { left: -100%; }
  100% { left: 100%; }
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
  40% { transform: translateY(-10px); }
  60% { transform: translateY(-5px); }
}

@keyframes progress-fill {
  0% { width: 0%; }
  100% { width: 66%; }
}
</style>

---
layout: center
class: text-center
---

# <span class="final-title">🚀 ありがとうございました！</span>

<div class="team-name">チーム <span class="mcp-highlight">MCP</span></div>

<div class="pt-12">
  <span class="question-prompt px-4 py-2 rounded-lg cursor-pointer transition-all duration-300" hover="bg-cyan-400 bg-opacity-20 transform scale-105">
    💬 ご質問はありますか？
  </span>
</div>

<div class="floating-elements">
  <div class="float-1">🤖</div>
  <div class="float-2">⚡</div>
  <div class="float-3">🎯</div>
  <div class="float-4">🌟</div>
</div>

<style>
.final-title {
  background: linear-gradient(135deg, #00f5ff, #ff006e, #8338ec, #3a86ff);
  background-size: 400% 400%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradient-shift 3s ease-in-out infinite;
  text-shadow: 0 0 40px rgba(0, 245, 255, 0.6);
  font-size: 3rem;
}

.team-name {
  font-size: 2rem;
  color: #e2e8f0;
  margin: 2rem 0;
  text-shadow: 0 0 20px rgba(226, 232, 240, 0.5);
}

.mcp-highlight {
  background: linear-gradient(45deg, #22c55e, #3b82f6, #8b5cf6);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: bold;
  text-shadow: 0 0 30px rgba(34, 197, 94, 0.8);
}

.question-prompt {
  background: linear-gradient(45deg, rgba(6, 182, 212, 0.2), rgba(139, 92, 246, 0.2));
  border: 1px solid rgba(6, 182, 212, 0.5);
  color: #e0e7ff;
  backdrop-filter: blur(10px);
  box-shadow: 0 8px 32px rgba(6, 182, 212, 0.3);
  font-size: 1.3rem;
}

.floating-elements {
  position: absolute;
  width: 100%;
  height: 100%;
  pointer-events: none;
}

.floating-elements div {
  position: absolute;
  font-size: 2rem;
  animation: float 6s ease-in-out infinite;
}

.float-1 {
  top: 20%;
  left: 15%;
  animation-delay: 0s;
}

.float-2 {
  top: 30%;
  right: 15%;
  animation-delay: 1.5s;
}

.float-3 {
  bottom: 30%;
  left: 20%;
  animation-delay: 3s;
}

.float-4 {
  bottom: 25%;
  right: 20%;
  animation-delay: 4.5s;
}

@keyframes float {
  0%, 100% { 
    transform: translateY(0px) rotate(0deg);
    opacity: 0.6;
  }
  50% { 
    transform: translateY(-20px) rotate(180deg);
    opacity: 1;
  }
}

@keyframes gradient-shift {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>