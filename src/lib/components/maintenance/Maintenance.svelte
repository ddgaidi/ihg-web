<script lang="ts">
    import { language } from '$lib/stores/language';
</script>

<div class="flex flex-col items-center justify-center h-screen -mb-[104px] z-0 bg-[#f0f0ff] dark:bg-[#191936] transition-all duration-300" id="maintenance-container">
    <h1 class="uppercase text-4xl font-black text-transparent bg-clip-text bg-gradient-to-l from-[#8558f2] to-[#00c599] transition-all duration-300" id="titre">{ $language === 'Français' ? 'Maintenance en cours...' : 'Maintenance in progress...' }</h1>
    <h2 class="text-2xl font-semibold text-black dark:text-white transition-all duration-300" id="sous-titre">{ $language === 'Français' ? 'Nous revenons au plus vite !' : 'We\'ll be back as soon as possible !' }</h2>
</div>