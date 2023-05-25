<script>
    import "../app.css";
</script>

<svelte:head>
    <meta property="og:title" content="Site Title" />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="http://my.site.com" />
    <meta property="og:image" content="stats.png" />
    <meta name="twitter:card" content="summary_large_image">
    <meta property="og:description" content="Embrace progress, shed complexity, and thrive in the ecosystem— join the movement and drop Minecraft legacy version support to ignite innovation." />
    <meta name="theme-color" content="#2b2d31">
</svelte:head>

<div class="flex">
    <div class="flex flex-col justify-start items-center w-full">
        <slot/>
    </div>
</div>
