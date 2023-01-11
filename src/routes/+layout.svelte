<script lang="ts">

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

	main {
		padding: 1em;
	}

</style>