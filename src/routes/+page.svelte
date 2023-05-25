<svelte:head>
    <title>Drop Legacy Support</title>
</svelte:head>


<div class="flex flex-col items-center justify-evenly gap-24 min-h-[100vh]">
    <div class="text-center flex-col flex gap-2 pt-10 md:pt-20 px-4">
        <h1 class="text-white font-bold text-[40px] underline">Drop Legacy Support</h1>
        <h2 class="text-[#4a4f5b] text-2xl text-center md:break-words">Embrace progress, shed complexity, and thrive in the ecosystem—<br class="hidden md:inline">join the movement and drop legacy version support to ignite innovation.</h2>
    </div>

    <div class="place-items-center items-start grid grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-4">
        <div class="block max-w-sm p-6 rounded-lg shadow bg-[#29282b] h-[100%]">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">✨ New features</h5>
            <p class="font-normal text-gray-700 dark:text-gray-400">
                By dropping support, you can use new features that Minecraft and the API offers. Notable additions include <b>Boss Bars</b>, <b>titles</b>, <b>Display Entities</b>, <b>hex colors</b> and much more.
                <br><br>By supporting archaic versions, you increase the complexity of your plugin. Not only are you forced to code different outcomes among different versions, but you will have to use significantly more NMS, which requires individual support for every patch.
                <br><br>1.8 is over 7 years old. Backwards compatibility for <b>12 major versions</b> is extremely painful.
            </p>
        </div>
        <div class="block max-w-sm p-6 rounded-lg shadow bg-[#29282b] h-[100%]">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">♻ The ecosystem</h5>
            <p class="font-normal text-gray-700 dark:text-gray-400">Many APIs and integrations have already dropped support for older versions. Notable examples include the <a class="underline decoration-dotted" href="https://github.com/minecraft-dev/MinecraftDev/issues/591#issuecomment-475997683" target="_blank">IntelliJ Minecraft plugin</a>, <a href="https://www.spigotmc.org/resources/coreprotect.8631/" target="_blank" class="underline decoration-dotted">CoreProtect</a> and <a href="https://www.spigotmc.org/resources/official-mcmmo-original-author-returns.64348/" target="_blank" class="underline decoration-dotted">mcMMO</a>.
                <br><br>You can take advantage of the plugin development ecosystem with compatibility guarantees and interoperability with facilitating plugins, frameworks and integrations.
                <br><br>Due to the reduced community activity and limited features of older versions, the developer support network is not nearly as wide as that of newer versions.
            </p>
        </div>
        <div class="block max-w-sm p-6 rounded-lg shadow bg-[#29282b] h-[100%]">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">🤐 The stigma</h5>
            <p class="font-normal text-gray-700 dark:text-gray-400">The 1.8 community is the loud minority. Many instil fear into developers through unfairly trashing and falsely reviewing plugins who don't support these ancient versions.
                <br><br>Do not be discouraged. Many users will thank you and welcome the new features and time you can dedicate to the non-dinosaurs.
                <br><br>The truth is that the 1.8 community is not as large as it used to be. As of 2023, <b>1.8.8 accounts for only 5.6% of total servers</b>.
            </p>
            <a href="https://bstats.org/global/bukkit#minecraftVersion" target="_blank" class="mt-5 inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                See stats
                <svg aria-hidden="true" class="w-4 h-4 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
            </a>
        </div>
    </div>

    <h2 class="text-[#4a4f5b] text-[30px] text-center font-semibold mt-[-70px]">Don't be part of the problem.</h2>
    <p class="text-[#3C414B] text-[15px] text-center pb-12 mx-4 md:mx-0">Not affiliated with Mojang AB. Sponsored by <a href="https://learnspigot.com" target="_blank" class="underline decoration-dotted">LearnSpigot</a> ❤</p>
</div>

<style>
    @media (min-width: 768px) {
        .break-words {
            overflow-wrap: break-word;
            word-break: break-word;
        }
    }


</style>