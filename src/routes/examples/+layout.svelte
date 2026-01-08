<script lang="ts">
	import '../layout.css';
	let { children } = $props();
	import Sidebar from '$lib/components/Sidebar.svelte';
</script>

<div class="flex min-h-screen">
	<Sidebar />

	<main>
		{@render children()}
	</main>
</div>
