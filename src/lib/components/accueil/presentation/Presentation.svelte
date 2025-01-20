<script lang="ts">
    import { language } from '$lib/stores/language';
</script>

<div class="flex flex-col justify-center items-center bg-[#f0f0ff] dark:bg-[#191936] py-14 transition-all duration-300" id="presentation-container">

    <div class="flex flex-col justify-center items-center mb-5" id="title-container">
        <h1 class="uppercase text-4xl font-black text-transparent bg-clip-text bg-gradient-to-l from-[#8558f2] to-[#00c599] transition-all duration-300" id="titre">{ $language === 'Français' ? 'Notre histoire' : 'Our story' }</h1>
        <h2 class="text-lg font-semibold text-black dark:text-white transition-all duration-300" id="sous-titre">{ $language === 'Français' ? 'Nous souhaitons nous présenter et partager avec vous notre parcours, nos valeurs, ainsi que les expériences qui ont façonné notre projet.' : 'We would like to introduce ourselves and share with you our journey, our values, as well as the experiences that have shaped our project.' }</h2>
    </div>

    <div class="flex justify-center items-center mx-[300px]" id="bio-container">
        <p class="text-md text-justify text-black dark:text-white transition-all duration-300">{ $language === 'Français' ? 'Infinity Horizon Games a été fondé par deux amis, Djamel Dyne GAÏDI et Yassine ACHOUR. Tous deux en BTS Cybersécurité, Informatique et Réseaux Électronique (CIEL), ils partageaient la volonté de créer un projet commun. Leur passion pour l’univers du jeu vidéo les a conduits à fonder leur propre entreprise. Conscients que le chemin serait semé d’embûches et qu’il leur faudrait beaucoup de persévérance, ils étaient néanmoins animés par une détermination sans faille.' : 'Infinity Horizon Games was founded by two friends, Djamel Dyne GAÏDI and Yassine ACHOUR. Both in BTS Cybersecurity, Computer Science and Electronic Networks (CIEL), they shared the desire to create a common project. Their passion for the world of video games led them to found their own company. Aware that the path would be strewn with pitfalls and that they would need a lot of perseverance, they were nevertheless driven by unwavering determination.' }</p>
    </div>


</div>