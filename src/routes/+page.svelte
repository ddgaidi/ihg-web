<script>
  import Navbar from '../lib/components/navbar/Navbar.svelte';
  import TopJeux from '../lib/components/accueil/topjeux/TopJeux.svelte';
  import Presentation from "$lib/components/accueil/presentation/Presentation.svelte";
  import Footer from "$lib/components/footer/Footer.svelte";
  import "../app.css";
</script>

<svelte:head>
	<title>Accueil - IHG</title>
	<meta name="description" content="Infinity Horizon Games : Où chaque jeu repousse les limites !" />
	<meta content="#006633" data-react-helmet="true" name="theme-color"/>
</svelte:head>

<Navbar />
<TopJeux />
<Presentation />
<Footer />