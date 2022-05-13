<script>
	import Header from '../components/Header.svelte';
	import { onMount } from 'svelte';
	let h2;

	onMount(() => {
		console.dir(h2);
	});
</script>
