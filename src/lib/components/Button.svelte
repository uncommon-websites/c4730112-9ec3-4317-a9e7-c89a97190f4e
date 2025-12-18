<script lang="ts">
  import { onMount } from 'svelte';
  
  export let variant: 'primary' | 'black' | 'warm' = 'primary';
  export let className = '';
</script>

<button 
  class="
    inline-flex items-center justify-center gap-2 rounded-full px-6 py-3 text-sm font-semibold transition-all active:scale-95
    {variant === 'primary' ? 'bg-black text-white hover:bg-gray-800' : ''}
    {variant === 'black' ? 'bg-black text-white hover:bg-gray-800' : ''}
    {variant === 'warm' ? 'bg-primary-600 text-white hover:bg-primary-700 shadow-lg shadow-primary-200' : ''}
    {className}
  "
>
  <slot />
</button>
