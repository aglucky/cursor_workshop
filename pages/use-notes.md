# Use Case: Taking Notes

<div class="grid grid-cols-2 gap-x-4 gap-y-2 mt-3">
  <div v-click class="flex items-center space-x-1.5 p-1 rounded-md bg-gradient-to-r from-blue-500/10 to-purple-500/10 border border-blue-500/30 transform transition-all duration-300 hover:scale-102">
    <div class="flex-shrink-0 w-5 h-5 flex items-center justify-center rounded-full bg-blue-500/20 text-blue-400 text-xs font-bold">1</div>
    <p class="text-sm">Open class slideshow</p>
  </div>
  
  <div v-click class="flex items-center space-x-1.5 p-1 rounded-md bg-gradient-to-r from-blue-500/10 to-purple-500/10 border border-blue-500/30 transform transition-all duration-300 hover:scale-102">
    <div class="flex-shrink-0 w-5 h-5 flex items-center justify-center rounded-full bg-blue-500/20 text-blue-400 text-xs font-bold">2</div>
    <p class="text-sm">Screenshot slides <span class="text-blue-400">📸</span></p>
  </div>
  
  <div v-click class="flex items-center space-x-1.5 p-1 rounded-md bg-gradient-to-r from-blue-500/10 to-purple-500/10 border border-blue-500/30 transform transition-all duration-300 hover:scale-102">
    <div class="flex-shrink-0 w-5 h-5 flex items-center justify-center rounded-full bg-blue-500/20 text-blue-400 text-xs font-bold">3</div>
    <p class="text-sm">Convert to markdown <span class="text-green-400">📝</span></p>
  </div>
  
  <div v-click class="flex items-center space-x-1.5 p-1 rounded-md bg-gradient-to-r from-blue-500/10 to-purple-500/10 border border-blue-500/30 transform transition-all duration-300 hover:scale-102">
    <div class="flex-shrink-0 w-5 h-5 flex items-center justify-center rounded-full bg-blue-500/20 text-blue-400 text-xs font-bold">4</div>
    <p class="text-sm">Use <a href="https://pandoc.org/" class="text-blue-400 hover:underline">Pandoc</a> to convert to Word for cheatsheet<span class="text-purple-400">🔄</span></p>
  </div>
  
  <div v-click class="flex items-center space-x-1.5 p-1 rounded-md bg-gradient-to-r from-blue-500/10 to-purple-500/10 border border-blue-500/30 transform transition-all duration-300 hover:scale-102">
    <div class="flex-shrink-0 w-5 h-5 flex items-center justify-center rounded-full bg-blue-500/20 text-blue-400 text-xs font-bold">5</div>
    <p class="text-sm">Create Anki cards with <a href="https://github.com/kitschpatrol/yanki" class="text-blue-400 hover:underline">YANKI</a> <span class="text-amber-400">🗂️</span></p>
  </div>
  
  <div v-click class="flex items-center space-x-1.5 p-1 rounded-md bg-gradient-to-r from-blue-500/10 to-purple-500/10 border border-blue-500/30 transform transition-all duration-300 hover:scale-102">
    <div class="flex-shrink-0 w-5 h-5 flex items-center justify-center rounded-full bg-blue-500/20 text-blue-400 text-xs font-bold">6</div>
    <p class="text-sm">Automate with scripts <span class="text-green-400">⚙️</span></p>
  </div>
  
  <div v-click="7" class="col-span-2 flex items-center justify-center p-1 rounded-md bg-gradient-to-r from-yellow-500/10 to-amber-500/10 border border-yellow-500/30 transform transition-all duration-300 hover:scale-102 mt-1">
    <div class="flex-shrink-0 w-5 h-5 flex items-center justify-center rounded-full bg-yellow-500/20 text-yellow-400 text-xs font-bold">7</div>
    <p class="text-sm flex items-center ml-1.5">
      <span class="text-yellow-400 font-bold">Profit?</span>
      <span class="ml-1.5 text-yellow-400 text-base animate-bounce">💰</span>
    </p>
  </div>
</div>

::right::

<div 
  v-motion
  :initial="{ opacity: 0, y: 100 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 500, duration: 800 } }"
  class="relative mt-2 flex items-center justify-center"
>
  <div class="absolute inset-0 bg-gradient-to-r from-blue-500/30 to-purple-500/30 rounded-xl blur-xl"></div>
  <div class="relative bg-gray-900/50 backdrop-blur-sm p-3 rounded-xl border border-blue-400/30 shadow-xl max-w-[85%] mx-auto">
    <img src="/images/cheatsheet.png" alt="Example cheatsheet" class="w-9/10 rounded-lg shadow-md hover:shadow-lg transition-all duration-300 mx-auto" />
    <p class="text-xs text-gray-400 mt-1 text-center italic">Example cheatsheet I made</p>
  </div>
</div>