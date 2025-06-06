<script>
    import { ArrowRight } from '@lucide/svelte';
</script>

<h1 class="text-6xl font-bold text-gray-900 mb-6 flex flex-col">
    <span class="text-left"> Find Your Perfect </span>
    <span
        class="text-transparent text-9xl bg-clip-text bg-gradient-to-r from-violet-600 from-30% via-purple-600 via-40% to-fuchsia-600 to-75% h-38"
    >
        Open Source
    </span>
    <span class="text-right relative bottom-6"> Contribution </span>
</h1>
<p class="text-xl text-gray-600 mb-12 max-w-2xl mx-auto pt-4">
    Stop wandering through endless repositories. Tell us your skills, and we'll
    match you with open-source issues you can actually solve.
</p>

<div class="flex flex-col sm:flex-row gap-4 justify-center mb-18">
    <button
        class="bg-purple-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-purple-700 transition-colors shadow-lg flex items-center justify-center"
    >
        Get Started Now
        <ArrowRight class="ml-2 h-5 w-5" />
    </button>
    <button
        class="border-2 border-purple-600 text-purple-600 px-8 py-3 rounded-lg font-semibold hover:bg-purple-50 transition-colors"
    >
        Sign In
    </button>
</div>
