<script>
    import { Code, Users, Zap } from '@lucide/svelte';
</script>

<div class="grid md:grid-cols-3 gap-8 mb-18 pt-8 max-w-4xl mx-auto">
    <div
        class="bg-white/70 backdrop-blur-sm p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow"
    >
        <Code class="h-12 w-12 text-violet-600 mx-auto mb-4" />
        <h3 class="text-lg font-semibold text-gray-900 mb-2">
            Match Your Skills
        </h3>
        <p class="text-gray-600">
            Select the technologies you know and we'll find issues that match
            your expertise.
        </p>
    </div>

    <div
        class="bg-white/70 backdrop-blur-sm p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow"
    >
        <Users class="h-12 w-12 text-purple-600 mx-auto mb-4" />
        <h3 class="text-lg font-semibold text-gray-900 mb-2">
            Connect with Projects
        </h3>
        <p class="text-gray-600">
            Discover active projects looking for contributors just like you.
        </p>
    </div>

    <div
        class="bg-white/70 backdrop-blur-sm p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow"
    >
        <Zap class="h-12 w-12 text-fuchsia-600 mx-auto mb-4" />
        <h3 class="text-lg font-semibold text-gray-900 mb-2">Make an Impact</h3>
        <p class="text-gray-600">
            Start contributing to meaningful projects and grow your developer
            portfolio.
        </p>
    </div>
</div>
