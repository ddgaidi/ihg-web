<script>
  import Navbar from '../../lib/components/navbar/Navbar.svelte';
  import Maintenance from '../../lib/components/maintenance/Maintenance.svelte';
  import Footer from "$lib/components/footer/Footer.svelte";

  import "../../app.css";
</script>

<svelte:head>
	<title>Jeux - IHG</title>
	<meta name="description" content="Infinity Horizon Games : Où chaque jeu repousse les limites !" />
	<meta content="#006633" data-react-helmet="true" name="theme-color"/>
</svelte:head>

<Navbar />
<Maintenance />
<Footer />