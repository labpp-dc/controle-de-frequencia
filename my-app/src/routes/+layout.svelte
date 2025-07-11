<script lang="ts">
	import '../app.css';
	import Nav from './Components/Nav.svelte';

	let { children } = $props();
</script>

{@render children()}

<Nav/>