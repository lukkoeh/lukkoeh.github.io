<script>
    function openInNewTab(url) {
        window.open(url, '_blank', 'noopener,noreferrer');
    }
</script>

<div class="flex w-screen h-screen justify-center items-start bg-slate-900">
    <div class="w-11/12 md:w-2/3 lg:w-1/3 bg-slate-800 mt-10 md:mt-20 lg:mt-40 flex flex-col items-center rounded-3xl p-6 md:p-8 lg:p-10 gap-6 md:gap-8 lg:gap-10">
        <img src="lukas.jpg" alt="Lukas" class="w-1/2 md:w-1/3 rounded-full"/>
        <h1 class="text-white text-3xl md:text-4xl lg:text-5xl font-bold text-center">Lukas Köhler</h1>
        <h2 class="text-white text-lg md:text-xl font-thin text-center">Artificial Intelligence Engineer</h2>
        <button 
            on:click={() => openInNewTab('https://www.linkedin.com/in/lukkoeh/')}
            class="bg-blue-500 hover:bg-blue-600 text-white w-full px-4 py-2 rounded-lg transition-colors">
            Linkedin
        </button>
        <button 
            on:click={() => openInNewTab('https://github.com/lukkoeh')}
            class="bg-gray-900 hover:bg-gray-800 text-white w-full px-4 py-2 rounded-lg transition-colors">
            GitHub
        </button>
        <button 
            on:click={() => openInNewTab('mailto:lukas@lukkoeh.io')}
            class="bg-gray-700 hover:bg-gray-600 text-white w-full px-4 py-2 rounded-lg transition-colors">
            E-Mail
        </button>
    </div>
</div>

<style>
	/* styles go here */
</style>