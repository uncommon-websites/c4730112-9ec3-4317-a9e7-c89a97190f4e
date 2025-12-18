<script lang="ts">
  import Button from './Button.svelte';
</script>

<header class="w-full max-w-[1200px] mx-auto px-6 py-6 flex items-center justify-between sticky top-0 bg-white/80 backdrop-blur-md z-50">
  <a href="/" class="flex items-center gap-3 hover:opacity-80 transition-opacity">
    <svg width="32" height="32" viewBox="0 0 128 128" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M43.2996 50.542C59.9857 42.5617 73.0444 29.0193 80.5411 12.0914C75.7045 7.01301 69.417 3.38559 62.6458 1.20914L59.0184 0C58.7766 0.483656 58.5348 1.20917 58.5348 1.69282C52.7309 18.1371 40.8813 31.4376 24.9207 38.9343C13.7966 44.2545 5.57448 53.9276 1.70523 65.5353L0.496094 69.1628C0.979749 69.4046 1.70524 69.6464 2.1889 69.6464C6.78363 71.3392 11.3784 73.5156 15.7313 76.1758C21.7769 65.2935 31.45 56.104 43.2996 50.542Z" fill="currentColor"/>
      <path d="M113.428 51.5093C104.481 65.0516 92.1476 75.9339 76.9125 83.1887C64.5793 88.9926 55.148 99.8749 50.7951 112.934L49.5859 117.045C54.1807 121.156 59.7427 124.299 65.7884 126.234L69.4158 127.443C69.6576 126.96 69.8995 126.234 69.8995 125.75C75.7033 109.306 87.5529 96.0056 103.514 88.509C114.638 83.1888 123.102 73.5156 126.729 61.9079L127.938 58.2805C122.86 56.8295 118.023 54.4112 113.428 51.5093Z" fill="currentColor"/>
      <path d="M39.9154 104.47C45.9611 89.9599 57.0852 78.1103 71.353 71.3392C84.4117 65.0516 95.294 55.3785 102.791 43.529C97.2286 38.2088 92.6338 32.163 89.2482 24.9082C80.3006 41.3525 66.2746 54.653 49.1049 62.8752C39.1899 67.4699 31.2096 75.4503 26.373 85.1234C31.6933 90.2018 36.0462 96.4892 39.4318 103.502C39.4318 103.502 39.6736 103.986 39.9154 104.47Z" fill="currentColor"/>
    </svg>
    <span class="font-bold text-xl tracking-tight">StrideSleep</span>
  </a>
  
  <nav class="hidden md:flex items-center gap-8 text-sm font-medium">
    <a href="/#how-it-works" class="hover:text-primary-600 transition-colors">How It Works</a>
    <a href="/#early-access" class="hover:text-primary-600 transition-colors">Early Access</a>
    <a href="/#faq" class="hover:text-primary-600 transition-colors">FAQ</a>
  </nav>

  <Button>
    <span>Join Waitlist</span>
  </Button>
</header>
