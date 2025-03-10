# Strategy: AI Powered Debugging {.text-center}


```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#3b82f6', 'primaryTextColor': '#fff', 'primaryBorderColor': '#60a5fa', 'lineColor': '#60a5fa', 'secondaryColor': '#10b981', 'tertiaryColor': '#6366f1'}}}%%
flowchart LR
    classDef primary fill:#4B9BFF,stroke:none,color:#fff,stroke-width:0px
    classDef success fill:#22C55E,stroke:none,color:#fff,stroke-width:0px
    classDef warning fill:#F59E0B,stroke:none,color:#fff,stroke-width:0px
    classDef error fill:#EF4444,stroke:none,color:#fff,stroke-width:0px
    classDef diamond fill:transparent,stroke:#fff,color:#fff

    A[Encounter<br/>Issue]:::error --> 
    B[Add<br/>Context to Chat]:::primary --> 
    C[Use AI to add<br/>more detailed logging]:::warning
    
    C --> D{Test<br/>Solution}:::diamond
    D --> |Success| E[Fixed!]:::success
    D --> B

    style A font-size:14px,rx:5px,ry:5px
    style B font-size:14px,rx:5px,ry:5px
    style C font-size:14px,rx:5px,ry:5px
    style D font-size:14px
    style E font-size:14px,rx:5px,ry:5px
```

<div class="grid grid-cols-4 gap-2 mt-8">
  <div v-click class="p-2 rounded-lg border border-red-500/30 bg-red-500/10">
    <div class="text-xl text-red-400 text-center">🐛</div>
    <p class="text-center text-red-300 text-xs mt-1">Identify Issue to Solve</p>
  </div>
  
  <div v-click class="p-2 rounded-lg border border-blue-500/30 bg-blue-500/10">
    <div class="text-xl text-blue-400 text-center">🤖</div>
    <p class="text-center text-blue-300 text-xs mt-1">Add Error Logs + Context to AI</p>
  </div>

  <div v-click class="p-2 rounded-lg border border-yellow-500/30 bg-yellow-500/10">
    <div class="text-xl text-yellow-400 text-center">📝</div>
    <p class="text-center text-yellow-300 text-xs mt-1">Request AI to Add more Detailed Logs</p>
  </div>

  <div v-click class="p-2 rounded-lg border border-green-500/30 bg-green-500/10">
    <div class="text-xl text-green-400 text-center">✅</div>
    <p class="text-center text-green-300 text-xs mt-1">Verify Fix</p>
  </div>
</div>

<div v-click class="absolute bottom-4 right-4 text-xs text-gray-400 italic">
  Pro tip: Use agent mode for automated debugging cycles
</div>