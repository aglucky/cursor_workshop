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
  sans: 'Inter'
  mono: 'Fira Code'
layout: cover
---

# Introduction to AI Coding

Best practices for AI powered coding


<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: slide-up
layout: default
class: text-center
---

# Why Use AI Coding Tools?

<div class="grid grid-cols-2 gap-4 mt-6">

<div class="space-y-4 text-left">

<div class="flex items-start space-x-2">
  <div class="text-blue-500 text-xl">💻</div>
  <div>
    <div class="font-bold">Faster Development</div>
    <div class="text-sm opacity-75">Spend less time writing code</div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-purple-500 text-xl">🎨</div>
  <div>
    <div class="font-bold">UI/UX Generation</div>
    <div class="text-sm opacity-75">Create interfaces with natural language</div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-green-500 text-xl">📄</div>
  <div>
    <div class="font-bold">Documentation & Tests</div>
    <div class="text-sm opacity-75">Automatically generate comprehensive docs</div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-yellow-500 text-xl">🔍</div>
  <div>
    <div class="font-bold">Documentation Search</div>
    <div class="text-sm opacity-75">Auto search through developer resources</div>
  </div>
</div>

</div>

<div class="space-y-4 text-left">

<div class="flex items-start space-x-2">
  <div class="text-red-500 text-xl">📱</div>
  <div>
    <div class="font-bold">Code-Free Apps</div>
    <div class="text-sm opacity-75">Generate apps without coding with <a href="https://madewithclaude.com/" target="_blank" class="text-blue-400">Claude Artifacts</a></div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-teal-500 text-xl">📊</div>
  <div>
    <div class="font-bold">Create Presentations</div>
    <div class="text-sm opacity-75">Build slides like this one with <a href="https://sli.dev" target="_blank" class="text-blue-400">Sli.dev</a></div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-indigo-500 text-xl">📝</div>
  <div>
    <div class="font-bold">Class Notes</div>
    <div class="text-sm opacity-75">Take notes with <a href="https://www.markdownguide.org" target="_blank" class="text-blue-400">Markdown</a> or <a href="https://github.com/James-Yu/latex-workshop/wiki/Install" target="_blank" class="text-blue-400">LaTeX</a></div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-orange-500 text-xl">💡</div>
  <div>
    <div class="font-bold">Vibe Coding</div>
    <div class="text-sm opacity-75">Just write prompts and see where it takes you</div>
  </div>
</div>

</div>

</div>
::right::

<div class="space-y-4">

<div class="flex items-start space-x-2">
  <div class="text-red-500 text-xl">📱</div>
  <div>
    <div class="font-bold">Code-Free Apps</div>
    <div class="text-sm opacity-75">Generate apps without coding with <a href="https://madewithclaude.com/" target="_blank" class="text-blue-400">Claude Artifacts</a></div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-teal-500 text-xl">📊</div>
  <div>
    <div class="font-bold">Create Presentations</div>
    <div class="text-sm opacity-75">Build slides like this one with <a href="https://sli.dev" target="_blank" class="text-blue-400">Sli.dev</a></div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-indigo-500 text-xl">📝</div>
  <div>
    <div class="font-bold">Class Notes</div>
    <div class="text-sm opacity-75">Take notes with <a href="https://www.markdownguide.org" target="_blank" class="text-blue-400">Markdown</a> or <a href="https://github.com/James-Yu/latex-workshop/wiki/Install" target="_blank" class="text-blue-400">LaTeX</a></div>
  </div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-orange-500 text-xl">💡</div>
  <div>
    <div class="font-bold">Vibe Coding</div>
    <div class="text-sm opacity-75">Just write prompts and see where it takes you</div>
  </div>
</div>

</div>

---
transition: slide-up
layout: default
---

# Current Landscape: Categories

Three main categories of AI tools

<div class="grid grid-cols-1 gap-3 mt-5">

<div class="p-3 rounded-lg border border-blue-500 bg-blue-500/10">
  <h3 class="text-lg font-bold text-blue-400">Chat</h3>
  <p class="mt-1 text-sm">Simple chat interface with optional code execution capabilities directly in the chat environment</p>
</div>

<div class="p-3 rounded-lg border border-green-500 bg-green-500/10">
  <h3 class="text-lg font-bold text-green-400">Code Editor</h3>
  <p class="mt-1 text-sm">Enhanced IDE features including intelligent autocomplete, integrated chat, and automated code modifications</p>
</div>

<div class="p-3 rounded-lg border border-purple-500 bg-purple-500/10">
  <h3 class="text-lg font-bold text-purple-400">Agent</h3>
  <p class="mt-1 text-sm">AI systems that generate complete projects or interact with codebases exclusively through natural language prompts</p>
</div>

</div>


---
transition: slide-up
layout: default
---

# Popular AI Tools

<div class="mt-4">

```mermaid {scale: 0.8, theme: 'dark'}
flowchart 
  chat[Chat]
  ide[Code Editor]
  agent[Agent]

  %% Tools
  gpt[ChatGPT]:::chatTool
  claude[Claude]:::chatTool
  
  windsurf[Windsurf]:::ideTool
  cursor[Cursor]:::ideTool
  
  claudeCode[Claude Code]:::agentTool
  bolt[Bolt.new]:::agentTool
  replit[Replit AI]:::multiTool
  v0[v0.dev]:::multiTool
  
  %% Connections
  chat --> gpt & claude
  ide --> windsurf & cursor
  agent --> claudeCode & bolt
  
  %% Cross-category tools
  replit --- ide
  replit --- agent

  v0 --- chat
  v0 --- agent
  
  
  
  %% Custom styling
  classDef categoryClass fill:#2c3e50,stroke:#3498db,stroke-width:2px,color:#fff,rounded,font-weight:bold,padding:10px
  classDef chatTool fill:#1a202c,stroke:#3b82f6,stroke-width:1px,color:#93c5fd
  classDef ideTool fill:#1a202c,stroke:#10b981,stroke-width:1px,color:#6ee7b7
  classDef agentTool fill:#1a202c,stroke:#8b5cf6,stroke-width:1px,color:#c4b5fd
  classDef multiTool fill:#1a202c,stroke:#f59e0b,stroke-width:1px,color:#fcd34d,font-style:italic
  
  %% Add clickable links to each tool - correct syntax for tooltips
  click gpt "https://chat.openai.com" "Visit ChatGPT" _blank
  click claude "https://claude.ai" "Visit Claude" _blank
  click windsurf "https://codeium.com/windsurf" "Visit Windsurf" _blank
  click cursor "https://cursor.sh" "Visit Cursor" _blank
  click claudeCode "https://claude.ai/code" "Visit Claude Code" _blank
  click bolt "https://bolt.new" "Visit Bolt.new" _blank
  click replit "https://replit.com/ai" "Visit Replit AI" _blank
  click v0 "https://v0.dev" "Visit v0.dev" _blank
```

</div>

<div class="mt-6 space-y-2">

<div class="flex items-start space-x-2">
  <div class="text-yellow-500 text-xl">🔄</div>
  <div>Many tools cross categories or offer features from multiple categories</div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-blue-500 text-xl">📈</div>
  <div>The AI coding landscape is rapidly evolving with new tools emerging constantly</div>
</div>

<div class="flex items-start space-x-2">
  <div class="text-green-500 text-xl">💵</div>
  <div>Tools are generally becoming more accessible and affordable over time</div>
</div>

</div>

---
transition: slide-up
layout: two-cols
---

# Cursor

<div class="space-y-2 mt-2">

- ⏱️ **Pioneer**: One of the oldest AI code editors
- 🔄 **VSCode Foundation**: Fork of VSCode with AI features
- 🚀 **Rapid Innovation**: Releases new features quickly

- 🤖 **Choose Your Model**: Multiple AI models + API key support
- 💰 **Worth the Cost**: Only AI tool I currently pay for
- 🧪 **High Hiring Bar**: Gave me my hardest take home interview last year

</div>
::right::

<div class="flex items-center justify-center h-full">
  <div class="text-center">
    <img src="https://www.cursor.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-dark.c2eae9ea.png&w=2880&q=75" alt="Cursor logo" class="w-36 h-auto" />
    <a href="https://cursor.sh" target="_blank" class="text-lg text-blue-400">cursor.sh</a>
  </div>
</div>

---
transition: slide-up

---

# Tab AI {.text-center}

<div class="space-y-2 mt-4">

- Suggests code changes as you type (press tab to accept)
- Edits multiple lines simultaneously
- Auto-imports libraries when needed
- Recommends cursor movements automatically
- Best turned off when taking notes

</div>

---
transition: slide-up

---

# Command K {.text-center}

<div class="space-y-2 mt-4">

- Quick shortcut for immediate code edits
- Works in editor, terminal, or for quick questions
- Ideal for simple edits (map/filter vs. for loops)

</div>

---
transition: slide-up

---

# AI Chat {.text-center}

<div class="space-y-2 mt-4">

- Chat with AI in sidebar of editor
- Reference code, files, or terminal output for context
- Include folders, codebase, docs, websites, or images
- Apply changes with one click (with right file open)
- Best for changes to single files or specific areas

</div>

---
transition: slide-up

---

# Agent Mode {.text-center}


<div class="space-y-2 mt-4">

- All features of chat plus auto-context gathering
- Run tools via <a href="https://www.anthropic.com/news/model-context-protocol" target="_blank" class="text-blue-400">MCP</a> (terminal commands)
- Auto-fixes based on lint errors or test failures
- Complete features end-to-end without interruption
- YOLO mode for automatic tool execution
  - Add guardrails to prevent unwanted changes

</div>

---
transition: slide-up
---

# Other Features {.text-center}

<div class="space-y-2 mt-4">

- Auto-generated commit messages
- Cursor Rules: Project/global prompts (e.g., use uv for Python)
  - Works with llms.txt files for documentation
- Modified UI with more space for features
- Automatic checkpoints in chat (use with caution)

</div>

---
layout: two-cols
transition: slide-up
---

# Use: Taking Notes

1. Open class slideshow
2. Screenshot important slides  
3. Use Cursor to convert to markdown
4. Convert to Word with Pandoc
5. Script to automate process
6. 🤑 **Profit?**

::right::

![Example cheatsheet](/images/cheatsheet.png){class="w-3/4"}
*Example cheatsheet*{class="text-sm text-gray-400 mt-2"}

---
transition: slide-up

---

# Use: Generate UI {.text-center}

<div class="space-y-2 mt-4">

1. Upload UI library docs into Cursor (e.g., Shadcn)
2. Add design preferences as cursor rules (optional)
3. Generate UI components with docs as context
4. Refine based on feedback and regenerate as needed

</div>

---
transition: slide-up

---

# Pattern: Test Driven Development {.text-center}

<div class="text-6xl floating-element absolute right-20 top-20">🧪</div>

<div class="space-y-2 mt-4">

1. Create new feature
2. Generate tests with AI
3. Implement another feature
4. Run tests to verify functionality
5. Fix issues if tests fail, otherwise continue
6. Use integration + unit/property tests

</div>

---
transition: slide-up

---

# Strategy: AI Powered Debugging {.text-center}

<div class="space-y-2 mt-4">

1. Identify code error
2. Provide context to AI with request to fix + add logging
3. If unresolved, add new error logs as context
4. Optionally use agent mode for automated fixing loop

</div>

---
transition: slide-up
layout: two-cols
---

# Bottom Up Design



1. Determine structure you want project to be (Nextjs app that uses server actions)
1. Start by creating project primitives (ex. data sources)
1. Have AI use your primitives to create project features

::right::

# Top Down Design


1. Start with project global
1. Have AI split goal into subtasks
1. Split those subtasks into subtasks
1. Write to a file as a todo list (optional)
1. Have AI do all subtasks to create project


---
transition: slide-up

---

# Tips for more efficient generation {.text-center}

<div class="space-y-2 mt-4">

- Update README with project structure (AI can help)
- Keep requests small and focused
- Remove incorrect code that might influence output
- Write detailed prompts for complex tasks
- Stick to popular libraries/frameworks

</div>

---
transition: slide-up
layout: two-cols-header
---

# Things to watch out for {.text-center}

::left::

## ⚠️ Silent Breakage  
*Use comprehensive tests to verify functionality*

## ⏳ Irreversible Changes  
*Leverage git for robust version control*

::right::

## 🛑 Placeholder Code  
*Thoroughly validate before production use*

## 🧠 Complexity Limits  
*Build core logic, let AI handle extensions*


---
transition: slide-up
layout: two-cols-header
---
# Closing Thoughts {.text-center}

<div class="mt-2">

::left::
### 🧠 Solidify Fundamentals  
*Build strong programming foundations to better leverage AI*

### 💡 Strategic Investments  
*Choose AI tools that align with your development workflow*

::right::

### 🚀 Push Boundaries  
*Explore new possibilities and expand your coding horizons*

</div>

<div class="mt-4 text-center">
  <span class="text-2xl font-bold text-blue-400 animate-bounce">Happy Coding! 🚀</span>
</div>

---
layout: end
---

# Questions?
