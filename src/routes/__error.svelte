<script context="module">
  export function load({ error, status }) {
    return { props: { error, status } };
  }
</script>

<script>

	// Initializations & Exports:
	export let error;
	export let status;
	
</script>

<!-- #################################################################################################### -->

<!-- Error Message -->
<section>
	<span>{status}: {error.message}</span>
</section>

<!-- #################################################################################################### -->

<style>

	section {
		display: flex;
		justify-content: center;
		align-items: center;
		height: calc(100vh - 105px);
	}

</style>