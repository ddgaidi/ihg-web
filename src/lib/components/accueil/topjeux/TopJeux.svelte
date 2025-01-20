<script lang="ts">
    import { language } from '$lib/stores/language';

    import jeu1 from '../../../images/jeux/snake.jpeg';
    import jeu2 from '../../../images/jeux/undercover.jpeg';
    import jeu3 from '../../../images/jeux/mysterious.jpeg';


    function handleRightClick(event: MouseEvent): void {
        event.preventDefault();
    }
</script>

<div class="flex flex-col justify-center items-center bg-[#f0f0ff] dark:bg-[#191936] pt-28 transition-all duration-300" id="topjeux-container">

    <div class="flex flex-col justify-center items-center mb-10" id="title-container">
        <h1 class="uppercase text-4xl font-black text-transparent bg-clip-text bg-gradient-to-l from-[#8558f2] to-[#00c599] transition-all duration-300" id="titre">{ $language === 'Français' ? 'jeux en vedettes' : 'featured games' }</h1>
        <h2 class="text-lg font-semibold text-black dark:text-white transition-all duration-300" id="sous-titre">{ $language === 'Français' ? 'Nous avons sélectionné pour vous les jeux les plus populaires et les plus appréciés.' : 'We have selected the most popular and most appreciated games for you.' }</h2>
    </div>

    <div class="flex justify-center items-center gap-x-10" id="topjeux-list">

        <div class="relative group" id="jeu-container">
            <img src={jeu1} alt="TwistyTails" on:contextmenu={handleRightClick} draggable="false" class="w-[300px] rounded-2xl brightness-[20%] group-hover:scale-105 group-hover:brightness-100 transition-all duration-300">
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white group-hover:hidden transition-all duration-300">
                <h3 class="uppercase text-xl font-bold" id="nom">Twisty Tails</h3>
                <h4 class="text-sm font-normal" id="date">{ $language === 'Français' ? 'Prochainement...' : 'Soon...' }</h4>
            </div>
        </div>

        <div class="relative group" id="jeu-container">
            <img src={jeu2} alt="Masques&Crocs" on:contextmenu={handleRightClick} draggable="false" class="w-[300px] rounded-2xl brightness-[20%] group-hover:scale-105 group-hover:brightness-100 transition-all duration-300">
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white group-hover:hidden transition-all duration-300">
                <h3 class="uppercase text-xl font-bold" id="nom">{ $language === 'Français' ? 'Masques & Crocs' : 'Masks and Fangs' }</h3>
                <h4 class="text-sm font-normal" id="date">{ $language === 'Français' ? 'Prochainement...' : 'Soon...' }</h4>
            </div>
        </div>

        <div class="relative group" id="jeu-container">
            <img src={jeu3} alt="Mysterious" on:contextmenu={handleRightClick} draggable="false" class="w-[300px] rounded-2xl brightness-[20%] group-hover:scale-105 group-hover:brightness-100 transition-all duration-300">
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white group-hover:hidden transition-all duration-300">
                <h3 class="uppercase text-xl font-bold" id="nom">Mysterious</h3>
                <h4 class="text-sm font-normal" id="date">{ $language === 'Français' ? 'Prochainement...' : 'Soon...' }</h4>
            </div>
        </div>

    </div>

    <a href="/jeux" class="flex justify-center items-center bg-gradient-to-l from-[#8558f2] to-[#00c599] hover:brightness-125 transition-all duration-300 mt-5 py-2 px-20 rounded-full" id="voirplus">
        <h5 class="uppercase text-xl font-black text-transparent bg-clip-text bg-gradient-to-l from-[#e0d4ff] to-[#d9fff6] transition-all duration-300">{ $language === 'Français' ? 'Voir plus' : 'View more' }</h5>
    </a>
</div>