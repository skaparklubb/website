<script lang="ts">
	import Header from '$lib/Header.svelte';
	import '../app.css';
	interface Props {
		children?: import('svelte').Snippet;
	}

	let { children }: Props = $props();
</script>

<div class="container">
	<Header></Header>
	{@render children?.()}
</div>
