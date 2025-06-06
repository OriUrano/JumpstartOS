<script>
    import { GitBranch, Lightbulb, Target, Users } from '@lucide/svelte';
    import Card from './Card.svelte';
</script>

<div class="grid md:grid-cols-2 gap-8 mb-12 max-w-4xl mx-auto">
    <Card
        Icon={Target}
        textColor="text-violet-600"
        borderColor="border-violet-200"
        heading="Curated for Your Level"
        text='Find issues labeled as "good first issue" for beginners,
        or more complex challenges for experienced developers.
        No more scrolling through irrelevant problems.'
    />
    <Card
        Icon={GitBranch}
        textColor="text-purple-600"
        borderColor="border-purple-200"
        heading="Multiple Platforms"
        text="We search across GitHub and GitLab to find the best
        opportunities, giving you access to thousands of active
        open-source projects."
    />
    <Card
        Icon={Lightbulb}
        textColor="text-fuchsia-600"
        borderColor="border-fuchsia-200"
        heading="Learn & Grow"
        text="Contributing to open source is the best way to improve
        your coding skills, learn new technologies, and build
        your professional network."
    />
    <Card
        Icon={Users}
        textColor="text-pink-600"
        borderColor="border-pink-200"
        heading="Join the Community"
        text="Connect with maintainers and other contributors. Build
        relationships that can lead to mentorship opportunities
        and career growth."
    />
</div>
