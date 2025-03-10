# Tab AI

<div class="grid grid-cols-2 gap-2 mt-4">
  <div v-click class="flex items-start p-2 rounded-lg transition-all duration-300 hover:bg-white/5 border border-indigo-500/30 bg-indigo-500/10">
    <div class="text-xl text-indigo-400 mr-2">⌨️</div>
    <div>
      <h3 class="font-bold text-indigo-400 text-sm">Smart Suggestions</h3>
      <p class="text-gray-200 text-xs">Suggests code changes as you type</p>
    </div>
  </div>

  <div v-click class="flex items-start p-2 rounded-lg transition-all duration-300 hover:bg-white/5 border border-blue-500/30 bg-blue-500/10">
    <div class="text-xl text-blue-400 mr-2">✏️</div>
    <div>
      <h3 class="font-bold text-blue-400 text-sm">Multi-Line Editing</h3>
      <p class="text-gray-200 text-xs">Edits multiple lines simultaneously</p>
    </div>
  </div>

  <div v-click class="flex items-start p-2 rounded-lg transition-all duration-300 hover:bg-white/5 border border-green-500/30 bg-green-500/10">
    <div class="text-xl text-green-400 mr-2">📦</div>
    <div>
      <h3 class="font-bold text-green-400 text-sm">Smart Imports</h3>
      <p class="text-gray-200 text-xs">Auto-imports libraries when needed</p>
    </div>
  </div>

  <div v-click class="flex items-start p-2 rounded-lg transition-all duration-300 hover:bg-white/5 border border-amber-500/30 bg-amber-500/10">
    <div class="text-xl text-amber-400 mr-2">🔍</div>
    <div>
      <h3 class="font-bold text-amber-400 text-sm">Cursor Navigation</h3>
      <p class="text-gray-200 text-xs">Recommends cursor movements</p>
    </div>
  </div>
</div>

<div v-click class="flex items-start p-2 rounded-lg transition-all duration-300 hover:bg-white/5 border border-red-500/30 bg-red-500/10">
  <div class="text-xl text-red-400 mr-2">🔔</div>
  <div>
    <h3 class="font-bold text-red-400 text-sm">Pro tip</h3>
    <p class="text-gray-200 text-xs">Turn off Tab AI when taking notes to avoid distracting/ unwanted completions</p>
  </div>
</div>

<div 
  v-motion
  :initial="{ x: 100, opacity: 0 }"
  :enter="{ x: 0, opacity: 1, transition: { delay: 700, duration: 500 } }"
  class="absolute bottom-8 right-8 max-w-xs">
  <div class="flex items-center">
    <div class="flex items-center space-x-1">
      <span class="px-2 py-0.5 bg-indigo-500/20 border border-indigo-500/30 rounded text-xs text-indigo-400 font-mono">Tab</span>
      <span class="text-indigo-400 animate-pulse">→</span>
      <span class="px-2 py-0.5 bg-indigo-500/20 border border-indigo-500/30 rounded text-xs text-indigo-400 font-mono">Tab</span>
      <span class="text-indigo-400 animate-pulse">→</span>
      <span class="px-2 py-0.5 bg-indigo-500/20 border border-indigo-500/30 rounded text-xs text-indigo-400 font-mono">Tab</span>
    </div>
  </div>
</div>