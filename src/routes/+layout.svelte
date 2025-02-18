<script lang="ts">
  import Nav from '$lib/Nav.svelte'
  import Footer from '$lib/Footer.svelte'
  import '../app.css'
</script>

<Nav />

<main><slot /></main>

<Footer />

<style>
  main {
    padding: 1em;
  }
</style>
