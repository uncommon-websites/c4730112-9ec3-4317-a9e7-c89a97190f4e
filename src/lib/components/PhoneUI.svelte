<div class="relative bg-black rounded-[3rem] p-3 w-full h-full shadow-2xl ring-1 ring-gray-900/5">
  <!-- Power Button -->
  <div class="absolute -right-[2px] top-24 w-[2px] h-12 bg-gray-800 rounded-r-md"></div>
  <!-- Volume Buttons -->
  <div class="absolute -left-[2px] top-24 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>
  <div class="absolute -left-[2px] top-36 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>

  <!-- Screen -->
  <div class="bg-white w-full h-full rounded-[2.5rem] overflow-hidden relative flex flex-col">
    <!-- Status Bar / Notch Area -->
    <div class="h-12 w-full flex justify-center items-start pt-2 absolute top-0 left-0 z-20">
      <div class="w-28 h-7 bg-black rounded-full flex items-center justify-center gap-2 px-3">
        <!-- Dynamic Island Content Simulation -->
        <div class="w-full h-full flex items-center justify-between opacity-0">
           <!-- Hidden content just to keep size -->
        </div>
      </div>
    </div>

    <!-- App Content -->
    <div class="flex-1 overflow-y-auto pt-12 px-6 pb-6 text-xs font-medium select-none scrollbar-hide">
      <!-- Header -->
      <div class="flex justify-between items-baseline mb-6 mt-2">
        <h2 class="text-3xl font-bold tracking-tight">Sleep Twin</h2>
        <div class="text-gray-400 text-[10px] uppercase tracking-wide text-right leading-tight font-semibold">
          7 Day<br>Streak
        </div>
      </div>

      <!-- Sleep Twin Character -->
      <div class="mb-8 bg-gradient-to-br from-primary-50 to-primary-100 rounded-3xl p-6 flex flex-col items-center">
        <div class="text-6xl mb-3">😊</div>
        <div class="text-sm font-semibold text-gray-800">Thriving</div>
        <div class="text-[10px] text-gray-500 mt-1">Keep up the momentum!</div>
      </div>

      <!-- Today's Tasks -->
      <div class="mb-6">
        <h3 class="text-[10px] uppercase tracking-wide text-gray-400 font-bold mb-3">Today's Protocol</h3>
        <div class="space-y-3">
          <!-- Task 1 -->
          <div class="flex items-center gap-3">
            <span class="text-black border-[1.5px] border-black rounded-full w-5 h-5 flex items-center justify-center text-[10px] font-bold">✓</span>
            <span class="text-sm font-medium line-through text-gray-400">No caffeine after 2pm</span>
          </div>

          <!-- Task 2 -->
          <div class="flex items-center gap-3">
            <span class="text-black border-[1.5px] border-black rounded-full w-5 h-5 flex items-center justify-center text-[10px] font-bold">✓</span>
            <span class="text-sm font-medium line-through text-gray-400">15min evening walk</span>
          </div>

          <!-- Task 3 -->
          <div class="flex items-center gap-3 justify-between">
            <div class="flex items-center gap-3">
              <span class="border-[1.5px] border-gray-300 rounded-full w-5 h-5"></span>
              <span class="text-sm font-medium">Phone away by 10pm</span>
            </div>
            <span class="text-[10px] text-primary-600 font-bold">22:00</span>
          </div>
        </div>
      </div>

      <!-- Weekly Progress -->
      <div class="mb-6">
        <h3 class="text-[10px] uppercase tracking-wide text-gray-400 font-bold mb-3">This Week</h3>
        <div class="flex justify-between items-end h-20">
          <div class="flex flex-col items-center gap-1">
            <div class="w-6 bg-primary-500 rounded-t" style="height: 75%"></div>
            <span class="text-[9px] text-gray-400">M</span>
          </div>
          <div class="flex flex-col items-center gap-1">
            <div class="w-6 bg-primary-500 rounded-t" style="height: 85%"></div>
            <span class="text-[9px] text-gray-400">T</span>
          </div>
          <div class="flex flex-col items-center gap-1">
            <div class="w-6 bg-primary-500 rounded-t" style="height: 90%"></div>
            <span class="text-[9px] text-gray-400">W</span>
          </div>
          <div class="flex flex-col items-center gap-1">
            <div class="w-6 bg-primary-500 rounded-t" style="height: 80%"></div>
            <span class="text-[9px] text-gray-400">T</span>
          </div>
          <div class="flex flex-col items-center gap-1">
            <div class="w-6 bg-primary-500 rounded-t" style="height: 95%"></div>
            <span class="text-[9px] text-gray-400">F</span>
          </div>
          <div class="flex flex-col items-center gap-1">
            <div class="w-6 bg-primary-500 rounded-t" style="height: 88%"></div>
            <span class="text-[9px] text-gray-400">S</span>
          </div>
          <div class="flex flex-col items-center gap-1">
            <div class="w-6 bg-primary-400 rounded-t" style="height: 100%"></div>
            <span class="text-[9px] text-black font-bold">S</span>
          </div>
        </div>
      </div>

      <!-- Community Challenge -->
      <div class="bg-gray-50 rounded-2xl p-4">
        <div class="flex items-center gap-2 mb-2">
          <span class="text-sm">🏆</span>
          <span class="text-[10px] uppercase tracking-wide text-gray-500 font-bold">Daily Challenge</span>
        </div>
        <p class="text-xs font-medium text-gray-800">No screens 30min before bed</p>
        <p class="text-[10px] text-gray-500 mt-1">347 members participating</p>
      </div>
    </div>
    
    <!-- Home Indicator -->
    <div class="absolute bottom-1 left-1/2 -translate-x-1/2 w-32 h-1 bg-black rounded-full opacity-20"></div>
  </div>
</div>

