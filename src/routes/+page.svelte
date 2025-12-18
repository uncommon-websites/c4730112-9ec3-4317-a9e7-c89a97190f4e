<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import Button from '$lib/components/Button.svelte';
  import MoonIcon from '$lib/components/icons/MoonIcon.svelte';
  import BedIcon from '$lib/components/icons/BedIcon.svelte';
  import ChartIcon from '$lib/components/icons/ChartIcon.svelte';
  import UsersIcon from '$lib/components/icons/UsersIcon.svelte';
  import CheckShieldIcon from '$lib/components/icons/CheckShieldIcon.svelte';
  import PhoneUI from '$lib/components/PhoneUI.svelte';
  import FAQ from '$lib/components/FAQ.svelte';
</script>

<svelte:head>
  <title>StrideSleep - Turn Sleep Intentions Into Action</title>
  <meta name="description" content="StrideSleep transforms sleep intentions into verified actions through sensor-based accountability and adaptive behavioral coaching. Wake up energized, not regretful." />
</svelte:head>

<div class="min-h-screen bg-white text-black font-sans selection:bg-primary-100">
  <Header />

  <main class="flex flex-col items-center w-full">
    <!-- Hero Section -->
    <section id="hero" class="flex flex-col items-center text-center pt-10 pb-12 px-4 max-w-5xl mx-auto relative">
      <!-- Subtle gradient background -->
      <div class="absolute inset-0 -z-10 bg-gradient-to-b from-primary-50/30 via-white to-white"></div>
      <h1 class="text-4xl md:text-6xl lg:text-7xl font-bold tracking-tight leading-[1.1] mb-8">
        Tired of scrolling past your bedtime—again?
      </h1>
      
      <p class="text-lg md:text-xl text-gray-600 mb-8 max-w-3xl leading-relaxed">
        StrideSleep turns good sleep intentions into disciplined action. Wake up energized, not regretful.
      </p>

      <div class="mb-12">
        <Button>
          <span class="text-base">Join Waitlist</span>
        </Button>
      </div>

      <!-- Key Benefits -->
      <div class="flex flex-wrap justify-center gap-6 md:gap-8 text-sm text-gray-600 max-w-3xl">
        <div class="flex items-center gap-2">
          <ChartIcon className="w-5 h-5 text-primary-600" />
          <span>Incremental, game-like improvement</span>
        </div>
        <div class="flex items-center gap-2">
          <CheckShieldIcon className="w-5 h-5 text-primary-600" />
          <span>Built-in accountability</span>
        </div>
        <div class="flex items-center gap-2">
          <UsersIcon className="w-5 h-5 text-primary-600" />
          <span>Community support</span>
        </div>
      </div>
    </section>

    <!-- Hero Image -->
    <section class="w-full max-w-6xl mx-auto px-4 mb-20">
      <div class="rounded-3xl overflow-hidden shadow-2xl">
        <img 
          src="/generated/image-person-in-bed-looking-at-smartphone-late-1766099726774-0.webp" 
          alt="Person struggling with late-night phone use"
          class="w-full h-auto"
        />
      </div>
    </section>

    <!-- Phone Showcase -->
    <section class="w-full max-w-[1000px] px-4 mb-24 relative flex justify-center">
      <!-- Background glow with warm tones -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-primary-100/30 rounded-full blur-3xl -z-10"></div>
      
      <!-- Phone Container -->
      <div class="relative w-[300px] md:w-[340px] h-[680px] md:h-[720px] transition-transform hover:scale-[1.02] duration-500">
        <PhoneUI />
      </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="max-w-4xl mx-auto px-6 pb-20">
      <h2 class="text-3xl md:text-5xl font-bold tracking-tight text-center mb-16">
        How StrideSleep works
      </h2>
      
      <p class="text-lg md:text-xl text-gray-600 text-center mb-20 leading-relaxed">
        A behavioral system that turns sleep advice into action, especially when willpower fades.
      </p>

      <div class="space-y-20">
        <!-- Feature 1 -->
        <div class="space-y-6 text-center">
          <div class="inline-flex items-center justify-center w-16 h-16 bg-primary-100 rounded-2xl">
            <ChartIcon className="w-8 h-8 text-primary-700" />
          </div>
          <h3 class="text-2xl md:text-3xl font-bold">Incremental Improvement</h3>
          <p class="text-lg text-gray-600 leading-relaxed max-w-2xl mx-auto">
            Your Sleep Coach gives you 1–3 personalized tasks at a time—no overwhelm, no guesswork. Master them and level up.
          </p>
        </div>

        <!-- Feature 2 -->
        <div class="space-y-6 text-center">
          <div class="inline-flex items-center justify-center w-16 h-16 bg-primary-100 rounded-2xl">
            <MoonIcon className="w-8 h-8 text-primary-700" />
          </div>
          <h3 class="text-2xl md:text-3xl font-bold">The Sleep Twin</h3>
          <p class="text-lg text-gray-600 leading-relaxed max-w-2xl mx-auto">
            A visual reflection of your consistency and mood. It thrives when you follow through and suffers when you don't.
          </p>
        </div>

        <!-- Feature 3 -->
        <div class="space-y-6 text-center">
          <div class="inline-flex items-center justify-center w-16 h-16 bg-primary-100 rounded-2xl">
            <CheckShieldIcon className="w-8 h-8 text-primary-700" />
          </div>
          <h3 class="text-2xl md:text-3xl font-bold">Incorruptible Accountability</h3>
          <p class="text-lg text-gray-600 leading-relaxed max-w-2xl mx-auto">
            Verified check-ins, partner mode and built-in consequences keep you on track when motivation drops.
          </p>
        </div>

        <!-- Feature 4 -->
        <div class="space-y-6 text-center">
          <div class="inline-flex items-center justify-center w-16 h-16 bg-primary-100 rounded-2xl">
            <UsersIcon className="w-8 h-8 text-primary-700" />
          </div>
          <h3 class="text-2xl md:text-3xl font-bold">A Community That Gets It</h3>
          <p class="text-lg text-gray-600 leading-relaxed max-w-2xl mx-auto">
            Daily challenges, shared successes, and real-time support—because momentum loves company.
          </p>
        </div>
      </div>

      <!-- Community Image -->
      <div class="mt-20 rounded-3xl overflow-hidden shadow-xl">
        <img 
          src="/generated/image-group-of-diverse-people-in-casual-settin-1766099741370-2.webp" 
          alt="Community members supporting each other"
          class="w-full h-auto"
        />
      </div>
    </section>

    <!-- Early Access Section -->
    <section id="early-access" class="max-w-5xl mx-auto px-6 py-20">
      <h2 class="text-3xl md:text-4xl font-bold tracking-tight text-center mb-16">
        Be the first to know when we launch
      </h2>

      <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
        <!-- Waitlist Card -->
        <div class="bg-gray-50 rounded-3xl p-8 flex flex-col">
          <h3 class="text-xl font-bold mb-4">Join the Waiting List</h3>
          <ul class="space-y-3 mb-8 flex-grow text-gray-700">
            <li class="flex items-start gap-2">
              <span class="text-primary-600 mt-1">✓</span>
              <span>Early access notification</span>
            </li>
            <li class="flex items-start gap-2">
              <span class="text-primary-600 mt-1">✓</span>
              <span>Email updates on progress</span>
            </li>
            <li class="flex items-start gap-2">
              <span class="text-primary-600 mt-1">✓</span>
              <span>No commitment required</span>
            </li>
          </ul>
          <Button>Join Waitlist</Button>
        </div>

        <!-- Founding Community Card -->
        <div class="bg-gradient-to-br from-primary-50 to-primary-100 rounded-3xl p-8 flex flex-col border-2 border-primary-200">
          <h3 class="text-xl font-bold mb-4">Join the Founding Community</h3>
          <ul class="space-y-3 mb-8 flex-grow text-gray-800">
            <li class="flex items-start gap-2">
              <span class="text-primary-700 mt-1">✓</span>
              <span><strong>50% off forever</strong></span>
            </li>
            <li class="flex items-start gap-2">
              <span class="text-primary-700 mt-1">✓</span>
              <span>Vote on features we build</span>
            </li>
            <li class="flex items-start gap-2">
              <span class="text-primary-700 mt-1">✓</span>
              <span>Priority to all updates</span>
            </li>
            <li class="flex items-start gap-2">
              <span class="text-primary-700 mt-1">✓</span>
              <span>Weekly sleep challenges</span>
            </li>
            <li class="flex items-start gap-2">
              <span class="text-primary-700 mt-1">✓</span>
              <span>Direct line to founders</span>
            </li>
          </ul>
          <Button>Join Community</Button>
        </div>
      </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="max-w-3xl mx-auto px-6 py-20">
      <h2 class="text-3xl md:text-4xl font-bold tracking-tight text-center mb-12">
        FAQ
      </h2>

      <div class="space-y-0">
        <FAQ 
          question="Who's behind StrideSleep?" 
          answer="StrideSleep is built by Epistemic GmbH, founded by Jakob Müller in Switzerland. Jakob built Epistemic to solve execution gaps in personal development, with a focus on verified accountability systems that address why people fail despite knowing what to do."
        />
        <FAQ 
          question="When does it launch?" 
          answer="We're targeting a 2025 launch. Join the waitlist or founding community to be notified as soon as we're ready."
        />
        <FAQ 
          question="iOS or Android?" 
          answer="We're launching on both iOS and Android to make StrideSleep accessible to as many people as possible."
        />
        <FAQ 
          question="Is this another subscription I'll forget about?" 
          answer="StrideSleep is designed to create lasting behavioral change, not just passive tracking. Our accountability system and community support are built to keep you engaged and seeing results."
        />
        <FAQ 
          question="How is this different from other sleep apps?" 
          answer="Most sleep apps are passive trackers or relaxation tools. StrideSleep is an action layer—we focus on the execution gap, not the information gap. With verified accountability, adaptive coaching, and community support, we help you actually do what you know works."
        />
        <FAQ 
          question="What if I miss a night?" 
          answer="Life happens. Our Momentum System is designed to be forgiving—it's not about rigid streaks, but consistent progress over time. Your Sleep Twin reflects this balanced approach."
        />
        <FAQ 
          question="Do I need any special devices?" 
          answer="StrideSleep works with your existing devices. We integrate with popular wearables and can use your phone's sensors for verification. No expensive hardware required."
        />
        <FAQ 
          question="How can I contribute?" 
          answer="Join the Founding Community to vote on features, share feedback, and help shape StrideSleep's development. We're building this with our users, not just for them."
        />
        <FAQ 
          question="What happens in the community?" 
          answer="The Founding Community gets access to Discord for real-time support, daily challenges, shared success stories, and direct communication with the founders. It's a space for people serious about improving their sleep."
        />
      </div>
    </section>

    <!-- Footer -->
    <footer class="w-full py-12 flex flex-col items-center gap-6 text-center border-t border-gray-100 mt-auto">
      <div class="flex items-center gap-3">
        <svg width="24" height="24" viewBox="0 0 128 128" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M43.2996 50.542C59.9857 42.5617 73.0444 29.0193 80.5411 12.0914C75.7045 7.01301 69.417 3.38559 62.6458 1.20914L59.0184 0C58.7766 0.483656 58.5348 1.20917 58.5348 1.69282C52.7309 18.1371 40.8813 31.4376 24.9207 38.9343C13.7966 44.2545 5.57448 53.9276 1.70523 65.5353L0.496094 69.1628C0.979749 69.4046 1.70524 69.6464 2.1889 69.6464C6.78363 71.3392 11.3784 73.5156 15.7313 76.1758C21.7769 65.2935 31.45 56.104 43.2996 50.542Z" fill="currentColor"/>
          <path d="M113.428 51.5093C104.481 65.0516 92.1476 75.9339 76.9125 83.1887C64.5793 88.9926 55.148 99.8749 50.7951 112.934L49.5859 117.045C54.1807 121.156 59.7427 124.299 65.7884 126.234L69.4158 127.443C69.6576 126.96 69.8995 126.234 69.8995 125.75C75.7033 109.306 87.5529 96.0056 103.514 88.509C114.638 83.1888 123.102 73.5156 126.729 61.9079L127.938 58.2805C122.86 56.8295 118.023 54.4112 113.428 51.5093Z" fill="currentColor"/>
          <path d="M39.9154 104.47C45.9611 89.9599 57.0852 78.1103 71.353 71.3392C84.4117 65.0516 95.294 55.3785 102.791 43.529C97.2286 38.2088 92.6338 32.163 89.2482 24.9082C80.3006 41.3525 66.2746 54.653 49.1049 62.8752C39.1899 67.4699 31.2096 75.4503 26.373 85.1234C31.6933 90.2018 36.0462 96.4892 39.4318 103.502C39.4318 103.502 39.6736 103.986 39.9154 104.47Z" fill="currentColor"/>
        </svg>
        <span class="font-bold text-lg tracking-tight">StrideSleep</span>
      </div>
      <div class="flex flex-wrap justify-center gap-4 text-xs text-gray-400 font-medium">
        <a href="/terms-and-conditions" class="hover:text-black transition-colors">Terms & Conditions</a>
        <span>•</span>
        <a href="/privacy-policy" class="hover:text-black transition-colors">Privacy Policy</a>
        <span>•</span>
        <a href="/imprint" class="hover:text-black transition-colors">Imprint</a>
        <span>•</span>
        <a href="mailto:contact@stridesleep.com" class="hover:text-black transition-colors">Contact</a>
      </div>
      <div class="text-[10px] text-gray-300">
        © 2025 Epistemic GmbH. All rights reserved.
      </div>
      <div class="text-[10px] text-gray-300">
        Made in Münchenstein, Switzerland
      </div>
    </footer>
  </main>
</div>


