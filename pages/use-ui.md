# Use Case: Design UI Components

<div class="space-y-4 pr-4">
  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="flex-shrink-0 w-8 h-8 flex items-center justify-center rounded-full bg-blue-500/20 text-blue-400 text-xl">📚</div>
    <div>
      <span class="font-bold text-blue-400">Import Docs: </span> 
      <span class="text-gray-100">Upload UI library docs into Cursor (e.g., Shadcn)</span>
    </div>
  </div>

  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="flex-shrink-0 w-8 h-8 flex items-center justify-center rounded-full bg-purple-500/20 text-purple-400 text-xl">⚙️</div>
    <div>
      <span class="font-bold text-purple-400">Set Rules: </span> 
      <span class="text-gray-100">Add design preferences as cursor rules</span>
    </div>
  </div>

  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="flex-shrink-0 w-8 h-8 flex items-center justify-center rounded-full bg-green-500/20 text-green-400 text-xl">🧩</div>
    <div>
      <span class="font-bold text-green-400">Generate: </span> 
      <span class="text-gray-100">Create UI components with docs as context</span>
    </div>
  </div>

  <div v-click class="flex items-center space-x-2 transition-all duration-300 hover:translate-x-1">
    <div class="flex-shrink-0 w-8 h-8 flex items-center justify-center rounded-full bg-amber-500/20 text-amber-400 text-xl">🔄</div>
    <div>
      <span class="font-bold text-amber-400">Iterate: </span> 
      <span class="text-gray-100">Refine based on feedback and regenerate</span>
    </div>
  </div>
</div>

::right::

<div 
  v-motion
  :initial="{ opacity: 0, scale: 0.8 }"
  :enter="{ opacity: 1, scale: 1, transition: { delay: 500, duration: 800 } }"
  class="relative flex items-center justify-center h-full"
>
  <div class="absolute inset-0 bg-gradient-to-br from-blue-500/30 to-purple-500/30 rounded-xl blur-xl"></div>
  <div class="relative bg-gray-900/50 backdrop-blur-sm p-5 rounded-xl border border-blue-400/30 shadow-xl max-w-[90%] mx-auto">
    <pre class="text-xs font-mono text-left p-3 bg-gray-800/70 rounded-lg border border-gray-700/50 shadow-inner">
<span class="text-blue-300">// Example UI Component Generation</span>
<span class="text-purple-300">function</span> <span class="text-green-300">Button</span>({
  <span class="text-amber-300">variant</span> = <span class="text-blue-300">'primary'</span>,
  <span class="text-amber-300">size</span> = <span class="text-blue-300">'md'</span>,
  <span class="text-amber-300">children</span>,
  ...<span class="text-amber-300">props</span>
}) {
  <span class="text-purple-300">return</span> (
    &lt;<span class="text-blue-300">button</span>
      <span class="text-green-300">className</span>={cn(
        <span class="text-blue-300">'rounded-md font-medium transition-colors'</span>,
        <span class="text-green-300">variants</span>[<span class="text-amber-300">variant</span>],
        <span class="text-green-300">sizes</span>[<span class="text-amber-300">size</span>]
      )}
      {...<span class="text-amber-300">props</span>}
    &gt;
      {<span class="text-amber-300">children</span>}
    &lt;/<span class="text-blue-300">button</span>&gt;
  )
}</pre>
    <div class="mt-4 flex justify-center gap-2">
      <div class="px-4 py-2 bg-blue-500 rounded-md text-white text-sm font-medium shadow-md hover:bg-blue-600 transition-colors cursor-pointer">Primary</div>
      <div class="px-4 py-2 bg-gray-700 rounded-md text-white text-sm font-medium shadow-md hover:bg-gray-600 transition-colors cursor-pointer">Secondary</div>
      <div class="px-4 py-2 bg-transparent border border-gray-500 rounded-md text-gray-200 text-sm font-medium shadow-md hover:bg-gray-800/50 transition-colors cursor-pointer">Outline</div>
    </div>
  </div>
</div>
