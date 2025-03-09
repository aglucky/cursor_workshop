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

<div class="mt-10" />


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