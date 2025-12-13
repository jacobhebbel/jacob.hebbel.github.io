<script>
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<a href="/">home</a>
	<a href="/about">about</a>
</svelte:head>

{@render children()}
