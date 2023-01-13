<script lang="ts">
	const test = 2;
	$: test2 = test * 2;
</script>

<template>
	<h1 class="ml-12">{test2} and welcome to SvelteKit</h1>
	<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
</template>
