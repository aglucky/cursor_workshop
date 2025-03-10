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
src: cursor.md
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
      <p class="text-gray-200">Ideal for simple edits (map/filter vs. for loops)</p>
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
      <p class="text-gray-200 text-xs">Run tools via <a href="https://www.anthropic.com/news/model-context-protocol" target="_blank" class="text-blue-300 underline hover:text-blue-200">MCP</a> (terminal commands)</p>
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
        Automatic tool execution 
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

# Other Features

<div class="grid grid-cols-2 gap-4 mt-6">
  <div v-click class="p-4 rounded-lg border border-blue-500 bg-blue-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-blue-400 mr-2">📝</div>
      <h3 class="text-lg font-bold text-blue-400">Commit Message Generation</h3>
    </div>
    <p class="mt-1 text-sm">Smart commit messages generated based on your code changes</p>
  </div>

  <div v-click class="p-4 rounded-lg border border-green-500 bg-green-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-green-400 mr-2">📏</div>
      <h3 class="text-lg font-bold text-green-400">Cursor Rules</h3>
    </div>
    <p class="mt-1 text-sm">Project/global prompts for consistent behavior (e.g., use uv for Python)</p>
    <p class="mt-1 text-xs text-gray-400">Works with <a href="https://llmstxt.org/" class="text-green-300 hover:underline">llms.txt</a> files for documentation</p>
  </div>

  <div v-click class="p-4 rounded-lg border border-purple-500 bg-purple-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-purple-400 mr-2">🎨</div>
      <h3 class="text-lg font-bold text-purple-400">Unlimited Slow Requests w/ Paid Plan</h3>
    </div>
    <p class="mt-1 text-sm">Use premium models like Sonnet 3.7 or GPT-4o as much as you want with slow requests</p>
  </div>

  <div v-click class="p-4 rounded-lg border border-amber-500 bg-amber-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-amber-400 mr-2">🔄</div>
      <h3 class="text-lg font-bold text-amber-400">Checkpoints</h3>
    </div>
    <p class="mt-1 text-sm">Automatic chat checkpoints for progress tracking</p>
    <p class="mt-1 text-xs text-red-400">Don't rely too much on this for critical work!</p>
  </div>
</div>


---
transition: slide-up
layout: two-cols
src: ./pages/use-notes.md
---

---
transition: slide-up
layout: two-cols
src: ./pages/use-ui.md
---

---
transition: slide-up
layout: default
src: ./pages/pat-test.md
---


---
transition: slide-up
layout: default
src: ./pages/strat-bug.md
---


---
transition: slide-up
layout: two-cols-header
---

# Coding Mindsets

<div class="grid grid-cols-2 gap-4 mt-6">
  <div v-click class="p-4 rounded-lg border border-blue-500 bg-blue-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-blue-400 mr-2">🏗️</div>
      <h3 class="text-lg font-bold text-blue-400">Bottom Up Design</h3>
    </div>
    <ul class="mt-2 space-y-2 text-sm">
      <li class="flex items-start">
        <span class="text-blue-400 mr-2">1.</span>
        <span>Determine project structure</span>
      </li>
      <li class="flex items-start">
        <span class="text-blue-400 mr-2">2.</span>
        <span>Create project primitives (data sources)</span>
      </li>
      <li class="flex items-start">
        <span class="text-blue-400 mr-2">3.</span>
        <span>Have AI use primitives for features</span>
      </li>
    </ul>
  </div>

  <div v-click class="p-4 rounded-lg border border-green-500 bg-green-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-green-400 mr-2">🎯</div>
      <h3 class="text-lg font-bold text-green-400">Top Down Design</h3>
    </div>
    <ul class="mt-2 space-y-2 text-sm">
      <li class="flex items-start">
        <span class="text-green-400 mr-2">1.</span>
        <span>Start with goal, split into tasks/subtasks</span>
      </li>
      <li class="flex items-start">
        <span class="text-green-400 mr-2">2.</span>
        <span>Write todo list (optional)</span>
      </li>
      <li class="flex items-start">
        <span class="text-green-400 mr-2">3.</span>
        <span>Have AI complete all subtasks</span>
      </li>
    </ul>
  </div>
</div>

<div class="grid grid-cols-2 gap-4 mt-4">
  <div v-click class="p-3 rounded-lg border border-blue-500/50 bg-blue-500/5 transition-all duration-300">
    <div class="flex items-center">
      <div class="text-xl text-blue-400 mr-2">💡</div>
      <h4 class="font-medium text-blue-400">Example: Backend First</h4>
    </div>
    <p class="mt-1 text-sm text-gray-300">Start with Nextjs + server actions, then build UI on top</p>
  </div>

  <div v-click class="p-3 rounded-lg border border-green-500/50 bg-green-500/5 transition-all duration-300">
    <div class="flex items-center">
      <div class="text-xl text-green-400 mr-2">💡</div>
      <h4 class="font-medium text-green-400">Example: UI First</h4>
    </div>
    <p class="mt-1 text-sm text-gray-300">Design the UI/UX flow, then implement backend to support it</p>
  </div>
</div>


---
transition: slide-up
---

# Tips for more efficient generation {.text-center}

- Update README with project structure (AI can help)
- Keep requests small and focused
- Remove incorrect code that might influence output
- Write detailed prompts for complex tasks
- Stick to popular libraries/frameworks


---
transition: slide-up
layout: two-cols-header
---

# Things to watch out for {.text-center}

::left::

## ⚠️ Unrelated Breaking Changes
*Use comprehensive tests to verify functionality*

## ⏳ Easy to Make Irreversible Changes
*Leverage git to fall back on past working state*

::right::

## 🛑 Placeholder Code Covertly Added
*Thoroughly validate before production use*

## 🧠 AI Struggles to build complex features
*Build core logic, let AI handle extensions*


---
transition: slide-up
layout: two-cols-header
---
# Closing Thoughts {.text-center}

::left::
### 🧠 Solidify Fundamentals  
*Build strong programming foundations to better leverage AI*

### 💡 Strategic Investments  
*Choose AI tools that align with your development workflow*

::right::

### 🚀 Push Boundaries  
*Explore new possibilities and expand your coding horizons*


<div class="mt-4 text-center">
  <span class="text-2xl font-bold text-blue-400 animate-bounce">Happy Coding! 🚀</span>
</div>

---
layout: end
---

# Questions?
