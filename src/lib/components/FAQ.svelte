<script lang="ts">
  export let question: string;
  export let answer: string;
  
  let isOpen = false;
  
  function toggle() {
    isOpen = !isOpen;
  }
</script>

<div class="border-b border-gray-200">
  <button 
    on:click={toggle}
    class="w-full py-6 flex items-center justify-between text-left hover:opacity-70 transition-opacity"
  >
    <span class="text-lg md:text-xl font-semibold pr-8">{question}</span>
    <span class="text-2xl font-light transition-transform duration-300 flex-shrink-0" class:rotate-45={isOpen}>+</span>
  </button>
  
  {#if isOpen}
    <div class="pb-6 text-gray-600 leading-relaxed">
      {@html answer}
    </div>
  {/if}
</div>
