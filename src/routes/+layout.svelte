<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href="%sveltekit.assets%/favicon.svg" />
</svelte:head>

{@render children()}
