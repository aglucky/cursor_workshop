# Pattern: Test Driven Development

<div class="grid grid-cols-3 gap-4 mt-6">
  <div v-click class="p-3 rounded-lg border border-red-500 bg-red-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-red-400 mr-2">✨</div>
      <h3 class="text-base font-bold text-red-400">Create Feature</h3>
    </div>
    <p class="mt-1 text-xs">Define new functionality to implement</p>
  </div>

  <div v-click class="p-3 rounded-lg border border-blue-500 bg-blue-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-blue-400 mr-2">🧪</div>
      <h3 class="text-base font-bold text-blue-400">Generate Tests</h3>
    </div>
    <p class="mt-1 text-xs">Use AI to create comprehensive test cases</p>
  </div>

  <div v-click class="p-3 rounded-lg border border-green-500 bg-green-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-green-400 mr-2">⚙️</div>
      <h3 class="text-base font-bold text-green-400">Implement</h3>
    </div>
    <p class="mt-1 text-xs">Code the feature to pass the tests</p>
  </div>
</div>

<div 
  v-motion
  :initial="{ opacity: 0, y: 50 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 700, duration: 500 } }"
  class="relative my-6 mx-auto max-w-3xl"
>
  <div class="flex items-center justify-center">
    <div class="w-16 h-16 rounded-full bg-gradient-to-br from-blue-400 to-blue-600 flex items-center justify-center shadow-lg relative z-10">
      <div class="text-4xl text-white">🔄</div>
    </div>
    <div class="h-2 bg-gradient-to-r from-blue-500 to-green-500 flex-grow mx-4 rounded-full shadow-md"></div>
    <div class="w-16 h-16 rounded-full bg-gradient-to-br from-green-400 to-green-600 flex items-center justify-center shadow-lg relative z-10">
      <div class="text-4xl text-white">✅</div>
    </div>
  </div>
</div>

<div class="grid grid-cols-3 gap-4">
  <div v-click class="p-3 rounded-lg border border-purple-500 bg-purple-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-purple-400 mr-2">🏃</div>
      <h3 class="text-base font-bold text-purple-400">Run Tests</h3>
    </div>
    <p class="mt-1 text-xs">Verify functionality automatically</p>
  </div>

  <div v-click class="p-3 rounded-lg border border-amber-500 bg-amber-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-amber-400 mr-2">🔧</div>
      <h3 class="text-base font-bold text-amber-400">Fix Issues</h3>
    </div>
    <p class="mt-1 text-xs">Resolve any failing tests with AI help</p>
  </div>

  <div v-click class="p-3 rounded-lg border border-teal-500 bg-teal-500/10 transition-all duration-300 hover:shadow-lg hover:scale-102">
    <div class="flex items-center mb-2">
      <div class="text-2xl text-teal-400 mr-2">🔌</div>
      <h3 class="text-base font-bold text-teal-400">Integration</h3>
    </div>
    <p class="mt-1 text-xs">Mix unit, integration & property tests</p>
  </div>
</div>

<div 
  v-click
  class="absolute bottom-8 right-8 max-w-xs">
  <div class="flex items-center">
    <span class="text-green-300 text-sm mr-2">Tests:</span>
    <span class="px-2 py-0.5 bg-green-500/20 border border-green-500/30 rounded text-xs text-green-400 flex items-center">
      <span class="h-2 w-2 rounded-full bg-green-400 mr-1.5 animate-pulse"></span>15 passing
    </span>
  </div>
</div>