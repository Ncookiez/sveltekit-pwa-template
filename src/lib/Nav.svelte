<script lang="ts">

	// Initializations:
	const links = [
		{ route: '/', name: 'Home' },
		{ route: '/about', name: 'About' }
	];

</script>

<!-- #################################################################################################### -->

<nav>

	<!-- Navigation Links -->
	<ul class="links">
		{#each links as link}
			<li><a href="{link.route}">{link.name}</a></li>
		{/each}
	</ul>

</nav>

<!-- #################################################################################################### -->

<style>

	nav {
		display: flex;
		align-items: center;
		height: 53px;
		width: 100%;
		padding: 0 32px;
		background: #263238;
		border-bottom: 2px solid rgba(34,40,49,0.3);
	}

	.links {
		display: flex;
	}
	
	.links li {
		margin: 0 2em 0 0;
		list-style: none;
	}

	.links a {
		color: inherit;
		text-decoration: none;
	}
	
</style>