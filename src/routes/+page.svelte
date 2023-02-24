<script lang="ts">
	import code from './+page.svelte?raw';
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<code>
	<pre>{code}</pre>
</code>

<style>
	pre {
		width: fit-content;
		padding: 12px;
		background-color: black;
		color: white;
		border-radius: 4px
	}
</style>
