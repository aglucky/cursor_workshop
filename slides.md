---theme: seriph
title: Introduction to AI Coding - Headstart
info: |
  Best practices for AI powered coding
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
highlighter: shiki
lineNumbers: false
colorSchema: dark
css: unocss
background: https://source.unsplash.com/collection/94734566/1920x1080
fonts:
  sans: "Inter"
  mono: "Fira Code"
download: true
layout: cover
---

# Introduction to AI Tools

Best practices for AI powered coding

---
transition: slide-up
layout: default
src: ./pages/why-ai.md
class: text-center
---



---
transition: slide-up
layout: default
---

# Current Landscape: Categories

<div class="grid grid-cols-1 gap-3 mt-5">

<v-clicks>
  <div class="p-3 rounded-lg border border-blue-500 bg-blue-500/10">
    <h3 class="text-lg font-bold text-blue-400">Chat</h3>
    <p class="mt-1 text-sm">Simple chat interface that can have self contained features like code execution</p>
  </div>

  <div class="p-3 rounded-lg border border-green-500 bg-green-500/10">
    <h3 class="text-lg font-bold text-green-400">Code Editor</h3>
    <p class="mt-1 text-sm">IDE with AI features like intelligent autocomplete, integrated chat, and auto-applying changes</p>
  </div>

  <div class="p-3 rounded-lg border border-purple-500 bg-purple-500/10">
    <h3 class="text-lg font-bold text-purple-400">Agent</h3>
    <p class="mt-1 text-sm">AI systems that generate projects or interact with codebases primarily through prompts</p>
  </div>
</v-clicks>
</div>


---
transition: slide-up
layout: default
src: ./pages/landscape.md
---


---
transition: slide-up
layout: two-cols
---

# Cursor

<div class="space-y-4">
  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="text-2xl text-amber-400">⏱️</div>
    <div>
      <span class="font-bold text-amber-400">Pioneer: </span> 
      <span class="text-gray-100">One of the oldest AI code editors</span>
    </div>
  </div>

  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="text-2xl text-blue-400">🔄</div>
    <div>
      <span class="font-bold text-blue-400">VSCode Foundation: </span> 
      <span class="text-gray-100">Fork of VSCode with AI features</span>
    </div>
  </div>

  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="text-2xl text-green-400">🚀</div>
    <div>
      <span class="font-bold text-green-400">Rapid Innovation: </span> 
      <span class="text-gray-100">Releases new features quickly</span>
    </div>
  </div>

  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="text-2xl text-purple-400">🤖</div>
    <div>
      <span class="font-bold text-purple-400">Choose Your Model: </span> 
      <span class="text-gray-100">Multiple AI models + API key support</span>
    </div>
  </div>

  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="text-2xl text-yellow-400">💰</div>
    <div>
      <span class="font-bold text-yellow-400">Worth the Cost: </span> 
      <span class="text-gray-100">Only AI tool I currently pay for</span>
    </div>
  </div>

  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="text-2xl text-red-400">🧪</div>
    <div>
      <span class="font-bold text-red-400">High Hiring Bar: </span> 
      <span class="text-gray-100">Gave me my hardest take home interview last year</span>
    </div>
  </div>
</div>

::right::

<div class="flex items-center justify-center h-full">
  <div v-motion 
       :initial="{ scale: 0.8, opacity: 0 }" 
       :enter="{ scale: 1, opacity: 1, transition: { delay: 300, duration: 800 } }"
       class="text-center p-8 bg-gradient-to-br from-gray-800/50 to-blue-900/50 rounded-xl backdrop-blur-sm shadow-xl">
    <img src="https://www.cursor.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-dark.c2eae9ea.png&w=2880&q=75" 
         alt="Cursor logo" 
         class="w-36 h-auto mx-auto mb-4 drop-shadow-lg hover:scale-105 transition-transform duration-300" />
    <a href="https://cursor.sh" 
       target="_blank" 
       class="text-xl font-medium text-blue-400 hover:text-blue-300 transition-colors duration-300 flex items-center justify-center">
      cursor.sh
      <div class="i-carbon-launch ml-1"></div>
    </a>
  </div>
</div>

---
transition: slide-up
layout: default
src: ./pages/cursor.md
---



---
transition: slide-up
layout: default
---

# Command K

<div class="grid grid-cols-1 gap-3 mt-6">
  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-blue-500/30 bg-blue-500/10 shadow-md">
    <div class="text-xl text-blue-400 mr-3 mt-0.5">⚡</div>
    <div>
      <h3 class="font-bold text-blue-400">Quick Access</h3>
      <p class="text-gray-200">Quick shortcut for immediate code edits</p>
    </div>
  </div>

  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-teal-500/30 bg-teal-500/10 shadow-md">
    <div class="text-xl text-teal-400 mr-3 mt-0.5">🔄</div>
    <div>
      <h3 class="font-bold text-teal-400">Universal Context</h3>
      <p class="text-gray-200">Works in editor, terminal, or for quick questions</p>
    </div>
  </div>

  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-amber-500/30 bg-amber-500/10 shadow-md">
    <div class="text-xl text-amber-400 mr-3 mt-0.5">✨</div>
    <div>
      <h3 class="font-bold text-amber-400">Lightweight Transformations</h3>
      <p class="text-gray-200">Ideal for simple edits (replace for loops with map/filter)</p>
    </div>
  </div>
</div>

<div 
  v-motion
  :initial="{ x: 100, opacity: 0 }"
  :enter="{ x: 0, opacity: 1, transition: { delay: 700, duration: 500 } }"
  class="absolute bottom-8 right-8 max-w-xs">
  <div class="flex items-center">
    <div class="flex items-center space-x-1">
      <span class="px-2 py-0.5 bg-blue-500/20 border border-blue-500/30 rounded text-xs text-blue-400 font-mono">⌘</span>
      <span class="text-blue-400 animate-pulse">+</span>
      <span class="px-2 py-0.5 bg-blue-500/20 border border-blue-500/30 rounded text-xs text-blue-400 font-mono">K</span>
    </div>
  </div>
</div>


---
transition: slide-up
layout: default
---

# AI Chat

<div class="grid grid-cols-2 gap-3 mt-4">
  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-purple-500/30 bg-purple-500/10 shadow-md">
    <div class="text-xl text-purple-400 mr-3 mt-0.5">💬</div>
    <div>
      <h3 class="font-bold text-purple-400 text-sm">Sidebar Interface</h3>
      <p class="text-gray-200 text-xs">Chat with AI in sidebar of editor</p>
    </div>
  </div>

  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-blue-500/30 bg-blue-500/10 shadow-md">
    <div class="text-xl text-blue-400 mr-3 mt-0.5">🔗</div>
    <div>
      <h3 class="font-bold text-blue-400 text-sm">Context Aware</h3>
      <p class="text-gray-200 text-xs">Reference code, files, or terminal output</p>
    </div>
  </div>

  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-indigo-500/30 bg-indigo-500/10 shadow-md">
    <div class="text-xl text-indigo-400 mr-3 mt-0.5">📂</div>
    <div>
      <h3 class="font-bold text-indigo-400 text-sm">Rich Inputs</h3>
      <p class="text-gray-200 text-xs">Include folders, docs, websites, images</p>
    </div>
  </div>

  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-green-500/30 bg-green-500/10 shadow-md">
    <div class="text-xl text-green-400 mr-3 mt-0.5">✅</div>
    <div>
      <h3 class="font-bold text-green-400 text-sm">One-Click Apply</h3>
      <p class="text-gray-200 text-xs">Apply changes with right file open</p>
    </div>
  </div>
</div>

<div v-click class="mt-4 flex justify-center w-full">
  <div class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-yellow-500/30 bg-yellow-500/10 shadow-md w-full">
    <div class="text-xl text-yellow-400 mr-3 mt-0.5">💡</div>
    <div>
      <h3 class="font-bold text-yellow-400 text-sm">Best Practice</h3>
      <p class="text-gray-200 text-xs">Ideal for targeted changes to single files or specific code areas</p>
    </div>
  </div>
</div>

<div 
  v-motion
  :initial="{ x: 100, opacity: 0 }"
  :enter="{ x: 0, opacity: 1, transition: { delay: 700, duration: 500 } }"
  class="absolute bottom-8 right-8 max-w-xs">
  <div class="flex items-center">
    <div class="flex items-center space-x-2">
      <span class="px-2 py-1 bg-purple-500/20 border border-purple-500/30 rounded text-xs text-purple-400 flex items-center">
        <span class="i-carbon-chat-bot mr-1"></span>AI Chat
      </span>
      <div class="flex space-x-1">
        <span class="h-2 w-2 rounded-full bg-purple-400 animate-ping-slow"></span>
        <span class="h-2 w-2 rounded-full bg-purple-300 animate-ping-slower"></span>
        <span class="h-2 w-2 rounded-full bg-purple-200 animate-ping-slowest"></span>
      </div>
    </div>
  </div>
</div>


---
transition: slide-up
layout: default
---

# Agent Mode

<div class="grid grid-cols-2 gap-3 mt-4">
  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-teal-500/30 bg-teal-500/10 shadow-md">
    <div class="text-xl text-teal-400 mr-3 mt-0.5">🧠</div>
    <div>
      <h3 class="font-bold text-teal-400 text-sm">Enhanced Context</h3>
      <p class="text-gray-200 text-xs">All features of chat plus auto-context gathering</p>
    </div>
  </div>

  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-blue-500/30 bg-blue-500/10 shadow-md">
    <div class="text-xl text-blue-400 mr-3 mt-0.5">🛠️</div>
    <div>
      <h3 class="font-bold text-blue-400 text-sm">Tool Execution</h3>
      <p class="text-gray-200 text-xs">Run tools via <a href="https://www.anthropic.com/news/model-context-protocol" target="_blank">MCP</a> (terminal commands)</p>
    </div>
  </div>

  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-green-500/30 bg-green-500/10 shadow-md">
    <div class="text-xl text-green-400 mr-3 mt-0.5">🔧</div>
    <div>
      <h3 class="font-bold text-green-400 text-sm">Auto-Repair</h3>
      <p class="text-gray-200 text-xs">Auto-fixes based on lint errors or test failures</p>
    </div>
  </div>

  <div v-click class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-purple-500/30 bg-purple-500/10 shadow-md">
    <div class="text-xl text-purple-400 mr-3 mt-0.5">🔄</div>
    <div>
      <h3 class="font-bold text-purple-400 text-sm">End-to-End</h3>
      <p class="text-gray-200 text-xs">Complete features without interruption</p>
    </div>
  </div>
</div>

<div v-click class="mt-4 grid grid-cols-1 gap-2">
  <div class="flex items-start p-3 rounded-lg transition-all duration-300 hover:bg-white/5 border border-amber-500/30 bg-amber-500/10 shadow-md">
    <div class="text-xl text-amber-400 mr-3 mt-0.5">🚀</div>
    <div>
      <h3 class="font-bold text-amber-400 text-sm">YOLO Mode</h3>
      <p class="text-gray-200 text-xs flex items-center">
        Allow agent to use tools without permission
        <span class="inline-block ml-2 px-1.5 py-0.5 bg-red-500/20 border border-red-500/30 rounded text-xs text-red-400">
          Add guardrails to prevent unwanted changes
        </span>
      </p>
    </div>
  </div>
</div>

<div 
  v-motion
  :initial="{ x: 100, opacity: 0 }"
  :enter="{ x: 0, opacity: 1, transition: { delay: 700, duration: 500 } }"
  class="absolute bottom-8 right-8 max-w-xs">
  <div class="flex items-center">
    <span class="text-teal-300 text-sm mr-2">Agent Status:</span>
    <span class="px-2 py-0.5 bg-green-500/20 border border-green-500/30 rounded text-xs text-green-400 flex items-center">
      <span class="h-2 w-2 rounded-full bg-green-400 mr-1.5 animate-pulse"></span>Active
    </span>
  </div>
</div>


---
transition: slide-up
layout: default
---

# Other Features {.gradient-text .mb-8 .text-center}

<div class="grid grid-cols-2 gap-6 mt-8">
  <div v-click class="tip-card info">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-blue-400 mr-2">📝</div>
      <h3 class="text-lg font-bold text-blue-400">Commit Message Generation</h3>
    </div>
    <p class="text-sm text-gray-300">Messages are generated based on your code changes</p>
    <div class="mt-2 px-2 py-1 bg-blue-500/10 rounded-md text-xs text-blue-300 inline-block">
      Descriptive Git Commits 🎯
    </div>
  </div>

  <div v-click class="tip-card info green">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-green-400 mr-2">📏</div>
      <h3 class="text-lg font-bold text-green-400">Cursor Rules</h3>
    </div>
    <p class="text-sm text-gray-300">Global or project level prompt support</p>
    <div class="mt-2 px-2 py-1 bg-green-500/10 rounded-md text-xs text-green-300 inline-block">
      Compatible with formats like <a href="https://llmstxt.org/">llms.txt</a> 🤖
    </div>
  </div>

  <div v-click class="tip-card info purple">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-purple-400 mr-2">🎨</div>
      <h3 class="text-lg font-bold text-purple-400">Unlimited Slow Requests</h3>
    </div>
    <p class="text-sm text-gray-300">Includes Sonnet 3.7, GPT-4o, and more</p>
    <div class="mt-2 px-2 py-1 bg-purple-500/10 rounded-md text-xs text-purple-300 inline-block">
      Paid Plan Feature ✨
    </div>
  </div>

  <div v-click class="tip-card info amber">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-amber-400 mr-2">🔄</div>
      <h3 class="text-lg font-bold text-amber-400">Checkpoints</h3>
    </div>
    <p class="text-sm text-gray-300">Automatic chat checkpoints for progress tracking</p>
    <div class="mt-2 px-2 py-1 bg-red-500/10 rounded-md text-xs text-red-300 inline-block">
      Use with caution for critical work ⚠️ 
    </div>
  </div>
</div>

<div 
  v-motion
  :initial="{ x: 100, opacity: 0 }"
  :enter="{ x: 0, opacity: 1, transition: { delay: 700, duration: 500 } }"
  class="absolute bottom-8 right-8 max-w-xs">
  <div class="flex items-center">
    <span class="text-blue-300 text-sm mr-2">Features:</span>
    <span class="px-2 py-0.5 bg-blue-500/20 border border-blue-500/30 rounded text-xs text-blue-400 flex items-center">
      <span class="h-2 w-2 rounded-full bg-blue-400 mr-1.5 animate-pulse"></span>Premium
    </span>
  </div>
</div>

---
transition: slide-up
layout: two-cols-header
src: ./pages/use-notes.md
---


---
transition: slide-up
src: ./pages/use-ui.md
layout: two-cols-header
---

---
transition: slide-up
src: ./pages/pat-test.md
layout: default
---

---
transition: slide-up
src: ./pages/strat-bug.md
layout: default
---

# Coding Mindsets {.gradient-text .mb-8 .text-center}

<div class="grid grid-cols-2 gap-6 mt-8">
  <div v-click class="tip-card info">
    <div class="flex items-center mb-4">
      <div class="text-2xl text-blue-400 mr-2">🏗️</div>
      <h3 class="text-lg font-bold text-blue-400">Bottom Up Design</h3>
    </div>
    <ul class="space-y-3">
      <li class="flex items-center space-x-2">
        <div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400">1</div>
        <span class="text-gray-300">Determine project structure</span>
      </li>
      <li class="flex items-center space-x-2">
        <div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400">2</div>
        <span class="text-gray-300">Create project primitives</span>
      </li>
      <li class="flex items-center space-x-2">
        <div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400">3</div>
        <span class="text-gray-300">Have AI use primitives for new features</span>
      </li>
    </ul>
  </div>

  <div v-click class="tip-card info green">
    <div class="flex items-center mb-4">
      <div class="text-2xl text-green-400 mr-2">🎯</div>
      <h3 class="text-lg font-bold text-green-400">Top Down Design</h3>
    </div>
    <ul class="space-y-3">
      <li class="flex items-center space-x-2">
        <div class="w-6 h-6 rounded-full bg-green-500/20 flex items-center justify-center text-green-400">1</div>
        <span class="text-gray-300">Start with goal, split into tasks</span>
      </li>
      <li class="flex items-center space-x-2">
        <div class="w-6 h-6 rounded-full bg-green-500/20 flex items-center justify-center text-green-400">2</div>
        <span class="text-gray-300">Write todo list (optional)</span>
      </li>
      <li class="flex items-center space-x-2">
        <div class="w-6 h-6 rounded-full bg-green-500/20 flex items-center justify-center text-green-400">3</div>
        <span class="text-gray-300">Have AI complete all subtasks</span>
      </li>
    </ul>
  </div>
</div>

<div class="grid grid-cols-2 gap-6 mt-6">
  <div v-click class="feature-item">
    <div class="flex items-center">
      <div class="text-xl text-blue-400 mr-2">💡</div>
      <h4 class="font-medium text-blue-400">Example: Backend First</h4>
    </div>
    <p class="mt-2 text-sm text-gray-300">Start with Nextjs + server actions, then build UI on top</p>
  </div>

  <div v-click class="feature-item green">
    <div class="flex items-center">
      <div class="text-xl text-green-400 mr-2">💡</div>
      <h4 class="font-medium text-green-400">Example: UI First</h4>
    </div>
    <p class="mt-2 text-sm text-gray-300">Design the UI/UX flow, then implement backend to support it</p>
  </div>
</div>

<div class="absolute bottom-5 right-5 text-sm text-gray-400 animate-float">
  Choose the approach that fits your project best! 🎨
</div>


---
transition: slide-up
layout: default
---

# Tips for More Efficient Generation {.gradient-text .mb-8}

<div class="grid grid-cols-2 gap-6 mt-8">
  <div v-click class="tip-card info">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-blue-400 mr-2">📝</div>
      <h3 class="text-lg font-bold text-blue-400">Make a README</h3>
    </div>
    <p class="text-sm text-gray-300">Use AI to generate README.md with project structure, technologies, etc.</p>
  </div>

  <div v-click class="tip-card info">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-blue-400 mr-2">🎯</div>
      <h3 class="text-lg font-bold text-blue-400">Focus & Clarity</h3>
    </div>
    <p class="text-sm text-gray-300">Keep individual requests small and focused</p>
  </div>

  <div v-click class="tip-card warning">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-yellow-400 mr-2">🧹</div>
      <h3 class="text-lg font-bold text-yellow-400">Clean Slate</h3>
    </div>
    <p class="text-sm text-gray-300">Remove incorrect code as it may influence output</p>
  </div>

  <div v-click class="tip-card info">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-yellow-400 mr-2">✍️</div>
      <h3 class="text-lg font-bold text-yellow-400">Detailed Instructions</h3>
    </div>
    <p class="text-sm text-gray-300">Add more details in prompts for complex tasks</p>
  </div>

  <div v-click class="tip-card info">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-blue-400 mr-2">📋</div>
      <h3 class="text-lg font-bold text-blue-400">Prompt Management</h3>
    </div>
    <p class="text-sm text-gray-300">Use a clipboard manager like<a href="https://www.raycast.com/" target="_blank" class="ml-1 text-blue-400 hover:text-blue-300">Raycast</a></p>
  </div>

  <div v-click class="tip-card info">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-blue-400 mr-2">😎</div>
      <h3 class="text-lg font-bold text-blue-400">Popularity Rules</h3>
    </div>
    <p class="text-sm text-gray-300">Popular libraries/frameworks tend to have best results</p>
  </div>

</div>

<div class="absolute bottom-5 right-5 text-sm text-gray-400 animate-float">
  You'll learn what works for you over time 🚀
</div>



---
transition: slide-up
layout: two-cols-header
---

# Things to Watch Out For {.gradient-text .mb-8 .text-center}

<div class="grid grid-cols-2 gap-6 mt-8">
  <div v-click class="tip-card warning">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-yellow-400 mr-2">⚠️</div>
      <h3 class="text-lg font-bold text-yellow-400">Unrelated Breaking Changes</h3>
    </div>
    <p class="text-sm text-gray-300">Write tests to verify functionality and catch regressions</p>
  </div>

  <div v-click class="tip-card warning">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-yellow-400 mr-2">⏳</div>
      <h3 class="text-lg font-bold text-yellow-400">Irreversible Modifications</h3>
    </div>
    <p class="text-sm text-gray-300">Use version control (git) as a safety net for your code</p>
  </div>

  <div v-click class="tip-card warning">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-yellow-400 mr-2">🛑</div>
      <h3 class="text-lg font-bold text-yellow-400">Hidden Placeholder Code</h3>
    </div>
    <p class="text-sm text-gray-300">Always validate AI-generated code before pushing to production</p>
  </div>

  <div v-click class="tip-card warning">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-yellow-400 mr-2">🧠</div>
      <h3 class="text-lg font-bold text-yellow-400">Complex Feature Limits</h3>
    </div>
    <p class="text-sm text-gray-300">Build core logic yourself, let AI handle the repetitive work</p>
  </div>
</div>

<div v-click class="mt-8 flex justify-center">
  <div class="icon-btn">
    <span class="mr-2"> 👮‍♂️</span>
    Remember, you're responsible for your code!
  </div>
</div>

<div class="absolute bottom-5 right-5 text-sm text-gray-400 animate-float">
  Prevention is better than cure! 🛡️
</div>


---
transition: slide-up
layout: two-cols-header
---
# Closing Thoughts {.gradient-text .mb-8 .text-center}

<div class="grid grid-cols-3 gap-6 mt-12">
  <div v-click class="tip-card info">
    <div class="flex items-center mb-3">
      <div class="text-3xl text-blue-400 mr-3">🧠</div>
      <h3 class="text-xl font-bold text-blue-400">Be An Engineer</h3>
    </div>
    <p class="text-sm text-gray-300 italic leading-relaxed">
      Use AI as a tool to make you more productive, not as a crutch to do less work.
    </p>
  </div>

  <div v-click class="tip-card info purple">
    <div class="flex items-center mb-3">
      <div class="text-3xl text-purple-400 mr-3">💡</div>
      <h3 class="text-xl font-bold text-purple-400">Pick Tools Wisely</h3>
    </div>
    <p class="text-sm text-gray-300 italic leading-relaxed">
      Don't try to optimize productivity too much, you'll waste more time than you save
    </p>
  </div>

  <div v-click class="tip-card info green">
    <div class="flex items-center mb-3">
      <div class="text-3xl text-green-400 mr-3">🚀</div>
      <h3 class="text-xl font-bold text-green-400">Experiment</h3>
    </div>
    <p class="text-sm text-gray-300 italic leading-relaxed">
      It's easier than ever to build/deploy projects. A few hours of tinkering can go a long way
    </p>
  </div>
</div>

<div v-click class="mt-12 flex justify-center items-center space-x-4">
  <div class="px-6 py-3 bg-gradient-to-r from-blue-500/20 to-purple-500/20 rounded-full border border-blue-500/30 backdrop-blur-sm">
    <span class="text-2xl font-bold bg-gradient-to-r from-blue-400 to-purple-400 bg-clip-text text-transparent animate-pulse">
      Happy Coding! 🚀
    </span>
  </div>
</div>

<div 
  v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1, transition: { delay: 1000, duration: 500 } }"
  class="absolute bottom-8 right-8 text-sm text-gray-400 animate-float">
  The future of coding is here! ✨
</div>


---
transition: slide-up
layout: default
---

# Questions? {.gradient-text .text-6xl .mb-12}

<div class="mt-16 flex flex-col items-center justify-center space-y-8">
  <div class="text-8xl animate-bounce">🤔</div>
  <div class="text-2xl text-gray-400 font-light">Feel free to ask anything!</div>
  
  <div class="mt-8 grid grid-cols-3 gap-4">
    <div class="px-4 py-2 rounded-full bg-blue-500/10 border border-blue-500/30 text-blue-400 text-sm">
      Clarifications
    </div>
    <div class="px-4 py-2 rounded-full bg-purple-500/10 border border-purple-500/30 text-purple-400 text-sm">
      Best Practices
    </div>
    <div class="px-4 py-2 rounded-full bg-green-500/10 border border-green-500/30 text-green-400 text-sm">
      Next Steps
    </div>
  </div>
</div>

<div 
  v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1, transition: { delay: 1000, duration: 500 } }"
  class="absolute bottom-8 right-8 text-sm text-gray-400 animate-float">
 Ask me anything! 💪
</div>

---
layout: end
---

# Thank You!
