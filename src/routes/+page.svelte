<script>
    import Header from "$lib/Header.svelte";

    import {
        Code,
        Users,
        Zap,
        ArrowRight,
        GitBranch,
        Lightbulb,
        Target,
    } from "@lucide/svelte";
</script>

<Header />

<div class="bg-purple-100 w-full pb-8">
    <div class="max-w-6xl mx-auto text-center flex flex-col pt-16">
        <h1 class="text-6xl font-bold text-gray-900 mb-6 flex flex-col">
            <span class="text-left"> Find Your Perfect </span>
            <span
                class="text-transparent text-9xl bg-clip-text bg-gradient-to-r from-violet-600 from-30% via-purple-600 via-40% to-fuchsia-600 to-75% h-38"
            >
                Open Source
            </span>
            <span class="text-right"> Contribution </span>
        </h1>
        <p class="text-xl text-gray-600 mb-12 max-w-2xl mx-auto pt-4">
            Stop wandering through endless repositories. Tell us your skills,
            and we'll match you with open-source issues you can actually solve.
        </p>

        <div class="flex flex-col sm:flex-row gap-4 justify-center mb-16">
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
        <div class="max-w-4xl mx-auto">
            <div class="grid md:grid-cols-3 gap-8 mb-12 pt-8 max-w-4xl mx-auto">
                <div
                    class="bg-white/70 backdrop-blur-sm p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow"
                >
                    <Code class="h-12 w-12 text-violet-600 mx-auto mb-4" />
                    <h3 class="text-lg font-semibold text-gray-900 mb-2">
                        Match Your Skills
                    </h3>
                    <p class="text-gray-600">
                        Select the technologies you know and we'll find issues
                        that match your expertise.
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
                        Discover active projects looking for contributors just
                        like you.
                    </p>
                </div>

                <div
                    class="bg-white/70 backdrop-blur-sm p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow"
                >
                    <Zap class="h-12 w-12 text-fuchsia-600 mx-auto mb-4" />
                    <h3 class="text-lg font-semibold text-gray-900 mb-2">
                        Make an Impact
                    </h3>
                    <p class="text-gray-600">
                        Start contributing to meaningful projects and grow your
                        developer portfolio.
                    </p>
                </div>
            </div>

            <div
                id="how-it-works"
                class="bg-white/80 backdrop-blur-sm rounded-2xl border border-gray-200 p-8 mb-12 shadow-lg max-w-4xl mx-auto"
            >
                <h2 class="text-3xl font-bold text-gray-900 mb-8">
                    How It Works
                </h2>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="text-center">
                        <div
                            class="bg-violet-200 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4"
                        >
                            <span class="text-2xl font-bold text-violet-600"
                                >1</span
                            >
                        </div>
                        <h3 class="text-lg font-semibold text-gray-900 mb-2">
                            Select Your Skills
                        </h3>
                        <p class="text-gray-600">
                            Choose from 35+ technologies including JavaScript,
                            Python, React, Docker, and more.
                        </p>
                    </div>
                    <div class="text-center">
                        <div
                            class="bg-purple-200 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4"
                        >
                            <span class="text-2xl font-bold text-purple-600"
                                >2</span
                            >
                        </div>
                        <h3 class="text-lg font-semibold text-gray-900 mb-2">
                            Get Matched
                        </h3>
                        <p class="text-gray-600">
                            Our algorithm finds GitHub and GitLab issues that
                            match your skill set and experience level.
                        </p>
                    </div>
                    <div class="text-center">
                        <div
                            class="bg-fuchsia-200 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4"
                        >
                            <span class="text-2xl font-bold text-fuchsia-600"
                                >3</span
                            >
                        </div>
                        <h3 class="text-lg font-semibold text-gray-900 mb-2">
                            Start Contributing
                        </h3>
                        <p class="text-gray-600">
                            Click through to the issue and start making your
                            first open-source contribution.
                        </p>
                    </div>
                </div>
            </div>

            <div
                id="about"
                class="bg-gradient-to-br from-purple-50 to-violet-50 rounded-2xl border border-purple-200 p-8 mb-12 shadow-lg max-w-4xl mx-auto"
            >
                <h2 class="text-3xl font-bold text-gray-900 mb-6">
                    About JumpstartOS
                </h2>
                <div class="text-left max-w-4xl mx-auto space-y-6">
                    <p class="text-gray-700 leading-relaxed">
                        JumpstartOS was born from a simple observation:
                        countless developers want to contribute to open source,
                        but finding the right issues to work on is incredibly
                        difficult. We've all been there - scrolling through
                        endless GitHub repositories, trying to find something
                        that matches our skills and interests.
                    </p>
                    <p class="text-gray-700 leading-relaxed">
                        Our mission is to bridge this gap by creating an
                        intelligent matching system that connects developers
                        with meaningful open-source opportunities. Whether
                        you're a beginner looking for your first contribution or
                        an experienced developer seeking new challenges,
                        JumpstartOS helps you find projects where you can make a
                        real impact.
                    </p>
                    <p class="text-gray-700 leading-relaxed">
                        We believe that open source is the backbone of modern
                        software development, and every contribution - no matter
                        how small - makes a difference. By making it easier to
                        get involved, we're helping to strengthen the entire
                        open-source ecosystem.
                    </p>
                </div>
            </div>

            <div class="grid md:grid-cols-2 gap-8 mb-12 max-w-4xl mx-auto">
                <div
                    class="bg-violet-50 rounded-xl p-6 border border-purple-200"
                >
                    <Target class="h-8 w-8 text-violet-600 mb-4" />
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">
                        Curated for Your Level
                    </h3>
                    <p class="text-gray-600">
                        Find issues labeled as "good first issue" for beginners,
                        or more complex challenges for experienced developers.
                        No more scrolling through irrelevant problems.
                    </p>
                </div>
                <div
                    class="bg-purple-50 rounded-xl p-6 border border-purple-200"
                >
                    <GitBranch class="h-8 w-8 text-purple-600 mb-4" />
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">
                        Multiple Platforms
                    </h3>
                    <p class="text-gray-600">
                        We search across GitHub and GitLab to find the best
                        opportunities, giving you access to thousands of active
                        open-source projects.
                    </p>
                </div>
                <div
                    class="bg-fuchsia-50 rounded-xl p-6 border border-fuchsia-200"
                >
                    <Lightbulb class="h-8 w-8 text-fuchsia-600 mb-4" />
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">
                        Learn & Grow
                    </h3>
                    <p class="text-gray-600">
                        Contributing to open source is the best way to improve
                        your coding skills, learn new technologies, and build
                        your professional network.
                    </p>
                </div>
                <div
                    class="bg-gradient-to-br from-pink-50 to-pink-100 rounded-xl p-6 border border-pink-200"
                >
                    <Users class="h-8 w-8 text-pink-600 mb-4" />
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">
                        Join the Community
                    </h3>
                    <p class="text-gray-600">
                        Connect with maintainers and other contributors. Build
                        relationships that can lead to mentorship opportunities
                        and career growth.
                    </p>
                </div>
            </div>

            <div class="bg-gradient-to-br from-violet-700 from-30% via-purple-700 via-40% to-fuchsia-700 to-75% text-white rounded-2xl p-8">
                <h2 class="text-2xl font-bold mb-6">
                    Join Thousands of Contributors
                </h2>
                <div class="grid grid-cols-2 md:grid-cols-3 gap-6">
                    <div class="text-center">
                        <div class="text-3xl font-bold text-violet-200 mb-1">
                            10,000+
                        </div>
                        <div class="text-violet-100">Issues Found</div>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl font-bold text-purple-200 mb-1">
                            35+
                        </div>
                        <div class="text-purple-100">Technologies</div>
                    </div>
                    <!-- <div class="text-center">
                        <div class="text-3xl font-bold text-fuchsia-200 mb-1">
                            2
                        </div>
                        <div class="text-fuchsia-100">Platforms</div>
                    </div> -->
                    <div class="text-center">
                        <div class="text-3xl font-bold text-pink-200 mb-1">
                            24/7
                        </div>
                        <div class="text-pink-100">Updated</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="h-32"></div>

</div>