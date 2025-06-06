<script>
    import Header from "$lib/Header.svelte";
    import CardGrid from "$lib/CardGrid.svelte";
    import Intro from "$lib/Intro.svelte";
    import HowItWorks from "$lib/HowItWorks.svelte";
    import HeroCards from "$lib/HeroCards.svelte";
    import About from "$lib/About.svelte";
    import Stats from "$lib/Stats.svelte";
</script>

<Header />

<div class="bg-purple-100 w-full pb-8">
    <div class="max-w-6xl mx-auto text-center flex flex-col pt-16">
        <Intro />
        <div class="max-w-4xl mx-auto">
            <HeroCards />
            <HowItWorks />
            <About />
            <CardGrid />
            <Stats />
        </div>
    </div>
    <div class="h-32"></div>
</div>
