<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.ico';

	let { children } = $props();
	
	export const botId = 'id482613900020_bot';
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}
