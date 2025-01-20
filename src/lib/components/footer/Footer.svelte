<script lang="ts">
    import { language } from '$lib/stores/language';
    import ihg from '$lib/images/icon/ihg.png';
</script>

<div class="flex absolute w-screen bg-[#454599] dark:bg-[#0c0c1c] py-5 transition-all duration-300 items-center" id="footer-container">
    <div class="flex absolute ml-[150px]" id="icon-container">
        <img src={ihg} alt="Icône IHG" class="w-[100px]" id="ihg-icon">
    </div>

    <div class="flex flex-col justify-center items-center mx-auto gap-y-2" id="text-container">
        <h1 class="text-xl font-bold uppercase text-transparent bg-clip-text bg-gradient-to-l from-[#8558f2] to-[#00c599]">Infinity Horizon Games : Où chaque jeu repousse les limites !</h1>
        <h2 class="text-lg font-semibold text-white">Fais avec ❤️ par <a target="_blank" class="font-bold text-[#ff6410] underline hover:no-underline" href="https://github.com/ddgaidi/">DML</a></h2>
    </div>
</div>