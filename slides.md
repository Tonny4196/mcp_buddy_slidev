---
# try also 'default' to start simple
theme: seriph
# AI tech neural network background
background: https://source.unsplash.com/1920x1080/?artificial+intelligence,neural+network,technology,data,digital
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Buddy AI中間発表
  
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

# <span class="ai-title">🤖 Buddy AI中間発表</span>

<div class="ai-subtitle">2ヶ月間プログラムの中間発表</div>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="ai-button px-4 py-2 rounded-lg cursor-pointer transition-all duration-300" hover="bg-blue-400 bg-opacity-20 transform scale-105">
    次のページはスペースキーを押してください <carbon:arrow-right class="inline ml-2"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-blue-300 transition-colors duration-300">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-blue-300 transition-colors duration-300">
    <carbon-logo-github />
  </a>
</div>

<style>
.ai-title {
  background: linear-gradient(135deg, #00A8FF, #6C5CE7);
  background-size: 200% 200%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: ai-pulse 3s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(0, 168, 255, 0.6);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-subtitle {
  color: #E2E8F0;
  text-shadow: 0 0 20px rgba(108, 92, 231, 0.6);
  font-size: 1.2rem;
  margin-top: 1rem;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-button {
  background: linear-gradient(45deg, rgba(0, 168, 255, 0.2), rgba(108, 92, 231, 0.2));
  border: 1px solid rgba(0, 168, 255, 0.5);
  color: #E2E8F0;
  backdrop-filter: blur(10px);
  box-shadow: 0 8px 32px rgba(0, 168, 255, 0.3);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

@keyframes ai-pulse {
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

# 🧠 チーム名の由来

<div class="grid grid-cols-1 gap-4">

## <span class="ai-highlight">全員がtech系に関わっている</span>
- **自分・てぃーぬ：SE**
- **たなとす：セキュリティ系**
- **しょうど：情シス**

<v-click>

## <span class="ai-highlight">Tech系にまつわる名前にしよう</span>

</v-click>

<v-click>

## <span class="ai-highlight">最初の目標達成のMTGでAIの話をめっちゃした</span>
**AI系のワードに被せよう → MCPになった**

</v-click>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #00A8FF, #6C5CE7);
  background-size: 200% 200%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: ai-pulse 4s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(0, 168, 255, 0.4);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-highlight {
  color: #00A8FF;
  text-shadow: 0 0 15px rgba(0, 168, 255, 0.6);
}

.slide-container {
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
  color: #E2E8F0;
}

h2 {
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
  color: #E2E8F0;
}

@keyframes ai-pulse {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>

---

# 🤖 チームメンバー

<div class="grid grid-cols-1 gap-6 pt-4">

<div class="ai-card bg-gradient-to-br from-slate-800/80 to-slate-900/80 p-6 rounded-xl border border-blue-400/30 backdrop-blur-sm">

## <span class="ai-member-name">🧠 とに</span>
- **職業：** <span class="ai-highlight-text">SE</span>
- **勉強内容：** <span class="ai-highlight-text">個人開発</span>
- **最近興味がある分野：** <span class="ai-highlight-text">MCP・コーディングエージェント</span>

</div>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #00A8FF, #6C5CE7);
  background-size: 200% 200%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: ai-pulse 4s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(0, 168, 255, 0.4);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-card {
  box-shadow: 0 8px 32px rgba(0, 168, 255, 0.3), inset 0 1px 0 rgba(255, 255, 255, 0.1);
  transition: all 0.3s ease;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 20px 40px rgba(0, 168, 255, 0.4), inset 0 1px 0 rgba(255, 255, 255, 0.2);
}

.ai-member-name {
  color: #00A8FF;
  text-shadow: 0 0 15px rgba(0, 168, 255, 0.8);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-highlight-text {
  color: #6C5CE7;
  font-weight: 600;
  text-shadow: 0 0 10px rgba(108, 92, 231, 0.5);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

@keyframes ai-pulse {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>

---

# 🔄 活動内容

<div class="grid grid-cols-1 gap-6">

<v-click>

<div class="ai-activity-card">

## 🧠 気になったテック系の情報共有
<div class="ai-activity-desc">チームメンバーが見つけた技術情報やトレンドを共有</div>

</div>

</v-click>

<v-click>

<div class="ai-activity-card">

## 💪 筋トレ報告
<div class="ai-activity-desc">健康維持とチームビルディングを兼ねた活動</div>
<div class="ai-note-text">*写真入れる*</div>

</div>

</v-click>

<v-click>

<div class="ai-activity-card">

## 🌅 7時朝会
<div class="ai-activity-desc">定期的なコミュニケーションとスケジュール共有</div>

</div>

</v-click>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #00A8FF, #6C5CE7);
  background-size: 200% 200%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: ai-pulse 4s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(0, 168, 255, 0.4);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-activity-card {
  padding: 1.5rem;
  border-radius: 1rem;
  border: 1px solid rgba(0, 168, 255, 0.4);
  backdrop-filter: blur(10px);
  transition: all 0.3s ease;
  margin: 0.75rem 0;
  background: linear-gradient(135deg, rgba(0, 168, 255, 0.1), rgba(108, 92, 231, 0.1));
  box-shadow: 0 8px 32px rgba(0, 168, 255, 0.2);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-activity-card:hover {
  transform: translateY(-3px) scale(1.02);
  box-shadow: 0 12px 40px rgba(0, 168, 255, 0.3);
}

.ai-activity-desc {
  color: #E2E8F0;
  font-size: 1.1rem;
  margin-top: 0.5rem;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-note-text {
  color: #6C5CE7;
  font-style: italic;
  margin-top: 0.5rem;
  text-shadow: 0 0 8px rgba(108, 92, 231, 0.5);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

h2 {
  color: #00A8FF;
  text-shadow: 0 0 15px rgba(0, 168, 255, 0.6);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

@keyframes ai-pulse {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>

---

# 🎯 成果報告

<div class="flex justify-center items-center h-full">

<div class="ai-achievement-container">

## <span class="ai-celebration-text">🎉 おめでとうございます！</span>

<div class="ai-achievement-content">
<div class="ai-achiever-name">**てぃーぬさんが**</div>
<div class="ai-certification-name">**HTML5プロフェッショナル認定試験**</div>
<div class="ai-level-badge">**レベル2に合格**</div>
</div>

<div class="ai-sparkle-effect">✨</div>

</div>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #00A8FF, #6C5CE7);
  background-size: 200% 200%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: ai-pulse 4s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(0, 168, 255, 0.4);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-achievement-container {
  background: linear-gradient(135deg, 
    rgba(0, 168, 255, 0.2) 0%, 
    rgba(108, 92, 231, 0.2) 100%);
  border: 2px solid rgba(0, 168, 255, 0.5);
  padding: 2.5rem;
  border-radius: 1.5rem;
  text-align: center;
  backdrop-filter: blur(15px);
  box-shadow: 
    0 20px 40px rgba(0, 168, 255, 0.3),
    0 0 60px rgba(108, 92, 231, 0.2),
    inset 0 1px 0 rgba(255, 255, 255, 0.1);
  position: relative;
  overflow: hidden;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-celebration-text {
  background: linear-gradient(45deg, #00A8FF, #6C5CE7);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-shadow: 0 0 30px rgba(0, 168, 255, 0.8);
  font-size: 2rem;
  animation: ai-pulse-glow 2s ease-in-out infinite;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-achievement-content {
  margin: 1.5rem 0;
  font-size: 1.3rem;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-achiever-name {
  color: #E2E8F0;
  margin: 0.5rem 0;
  text-shadow: 0 0 15px rgba(226, 232, 240, 0.8);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-certification-name {
  background: linear-gradient(45deg, #00A8FF, #6C5CE7);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  margin: 0.5rem 0;
  text-shadow: 0 0 20px rgba(0, 168, 255, 0.5);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-level-badge {
  background: linear-gradient(45deg, #6C5CE7, #00A8FF);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 1.4rem;
  margin: 0.5rem 0;
  text-shadow: 0 0 25px rgba(108, 92, 231, 0.6);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-sparkle-effect {
  position: absolute;
  top: 1rem;
  right: 1rem;
  font-size: 2rem;
  animation: ai-sparkle 3s ease-in-out infinite;
}

@keyframes ai-pulse-glow {
  0%, 100% { text-shadow: 0 0 30px rgba(0, 168, 255, 0.8); }
  50% { text-shadow: 0 0 50px rgba(0, 168, 255, 1), 0 0 80px rgba(108, 92, 231, 0.6); }
}

@keyframes ai-sparkle {
  0%, 100% { 
    transform: rotate(0deg) scale(1);
    opacity: 0.7;
  }
  50% { 
    transform: rotate(180deg) scale(1.2);
    opacity: 1;
  }
}

@keyframes ai-pulse {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>

---

# 🚀 残り1ヶ月の各自の目標

<div class="grid grid-cols-1 gap-6 pt-4">

<div class="ai-goals-container">

## <span class="ai-goals-icon">🤖</span> 今後の目標設定

<div class="ai-goals-description">
各メンバーの残り1ヶ月での目標を設定し、<br>
<span class="ai-highlight-goals">継続的な成長と学習を目指します</span>
</div>

<div class="ai-progress-bar">
  <div class="ai-progress-fill"></div>
</div>

</div>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #00A8FF, #6C5CE7);
  background-size: 200% 200%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: ai-pulse 4s ease-in-out infinite;
  text-shadow: 0 0 30px rgba(0, 168, 255, 0.4);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-goals-container {
  background: linear-gradient(135deg, 
    rgba(0, 168, 255, 0.2) 0%, 
    rgba(108, 92, 231, 0.2) 100%);
  border: 1px solid rgba(0, 168, 255, 0.4);
  padding: 2rem;
  border-radius: 1.2rem;
  backdrop-filter: blur(10px);
  box-shadow: 0 15px 35px rgba(0, 168, 255, 0.3);
  text-align: center;
  position: relative;
  overflow: hidden;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-goals-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.1), transparent);
  animation: ai-shimmer 3s infinite;
}

.ai-goals-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
  display: inline-block;
  animation: ai-bounce 2s infinite;
  color: #00A8FF;
  text-shadow: 0 0 20px rgba(0, 168, 255, 0.8);
}

.ai-goals-description {
  font-size: 1.2rem;
  color: #E2E8F0;
  line-height: 1.8;
  margin: 1.5rem 0;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-highlight-goals {
  background: linear-gradient(45deg, #00A8FF, #6C5CE7);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 600;
  text-shadow: 0 0 20px rgba(0, 168, 255, 0.5);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-progress-bar {
  width: 100%;
  height: 8px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 4px;
  overflow: hidden;
  margin-top: 2rem;
}

.ai-progress-fill {
  height: 100%;
  background: linear-gradient(90deg, #00A8FF, #6C5CE7);
  border-radius: 4px;
  width: 66%;
  animation: ai-progress-fill 2s ease-out;
}

h2 {
  color: #00A8FF;
  text-shadow: 0 0 15px rgba(0, 168, 255, 0.6);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

@keyframes ai-shimmer {
  0% { left: -100%; }
  100% { left: 100%; }
}

@keyframes ai-bounce {
  0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
  40% { transform: translateY(-10px); }
  60% { transform: translateY(-5px); }
}

@keyframes ai-progress-fill {
  0% { width: 0%; }
  100% { width: 66%; }
}

@keyframes ai-pulse {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>

---
layout: center
class: text-center
---

# <span class="ai-final-title">🤖 ありがとうございました！</span>

<div class="ai-team-name">チーム <span class="ai-mcp-highlight">MCP</span></div>

<div class="pt-12">
  <span class="ai-question-prompt px-4 py-2 rounded-lg cursor-pointer transition-all duration-300" hover="bg-blue-400 bg-opacity-20 transform scale-105">
    💭 ご質問はありますか？
  </span>
</div>

<div class="ai-floating-elements">
  <div class="ai-float-1">🤖</div>
  <div class="ai-float-2">🧠</div>
  <div class="ai-float-3">🔄</div>
  <div class="ai-float-4">🚀</div>
</div>

<style>
.ai-final-title {
  background: linear-gradient(135deg, #00A8FF, #6C5CE7);
  background-size: 200% 200%;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: ai-pulse 3s ease-in-out infinite;
  text-shadow: 0 0 40px rgba(0, 168, 255, 0.6);
  font-size: 3rem;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-team-name {
  font-size: 2rem;
  color: #E2E8F0;
  margin: 2rem 0;
  text-shadow: 0 0 20px rgba(226, 232, 240, 0.5);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-mcp-highlight {
  background: linear-gradient(45deg, #00A8FF, #6C5CE7);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: bold;
  text-shadow: 0 0 30px rgba(0, 168, 255, 0.8);
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-question-prompt {
  background: linear-gradient(45deg, rgba(0, 168, 255, 0.2), rgba(108, 92, 231, 0.2));
  border: 1px solid rgba(0, 168, 255, 0.5);
  color: #E2E8F0;
  backdrop-filter: blur(10px);
  box-shadow: 0 8px 32px rgba(0, 168, 255, 0.3);
  font-size: 1.3rem;
  font-family: 'Meiryo', 'Hiragino Sans', 'Yu Gothic UI', sans-serif;
}

.ai-floating-elements {
  position: absolute;
  width: 100%;
  height: 100%;
  pointer-events: none;
}

.ai-floating-elements div {
  position: absolute;
  font-size: 2rem;
  animation: ai-float 6s ease-in-out infinite;
  color: #00A8FF;
  text-shadow: 0 0 15px rgba(0, 168, 255, 0.8);
}

.ai-float-1 {
  top: 20%;
  left: 15%;
  animation-delay: 0s;
}

.ai-float-2 {
  top: 30%;
  right: 15%;
  animation-delay: 1.5s;
}

.ai-float-3 {
  bottom: 30%;
  left: 20%;
  animation-delay: 3s;
}

.ai-float-4 {
  bottom: 25%;
  right: 20%;
  animation-delay: 4.5s;
}

@keyframes ai-float {
  0%, 100% { 
    transform: translateY(0px) rotate(0deg);
    opacity: 0.6;
  }
  50% { 
    transform: translateY(-20px) rotate(180deg);
    opacity: 1;
  }
}

@keyframes ai-pulse {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
</style>