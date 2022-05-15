<script>

	// Imports:
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
	import '../app.css';
	
</script>

<!-- #################################################################################################### -->

<!-- Navbar -->
<Nav />

<!-- App Content -->
<main><slot /></main>

<!-- Footer -->
<Footer />

<!-- #################################################################################################### -->

<style>

	/* CSS Goes Here */

</style>