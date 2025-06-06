<script>
    import { GitBranch, Github } from "@lucide/svelte";
</script>

<header
    class="bg-white/70 backdrop-blur-sm border-b border-gray-200 sticky top-0 z-50"
>
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between items-center h-16">
            <div class="flex items-center space-x-2">
                <GitBranch strokeWidth={2} class="h-8 w-8 text-purple-600" />
                <span class="text-xl font-bold text-gray-900">JumpstartOS</span>
            </div>
            <nav class="flex items-center space-x-6">
                <a
                    href="#"
                    class="text-gray-600 hover:text-gray-900 transition-colors"
                >
                    How it works
                </a>
                <a
                    href="#"
                    class="text-gray-600 hover:text-gray-900 transition-colors"
                >
                    About
                </a>
                <a
                    href="#"
                    class="flex items-center space-x-2 bg-gray-900 text-white px-4 py-2 rounded-lg hover:bg-gray-800 transition-colors"
                >
                    <Github strokeWidth={3} class="h-4 w-4" />
                    <span>Sign in with GitHub</span>
                </a>
            </nav>
        </div>
    </div>
</header>
