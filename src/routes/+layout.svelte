<script lang="ts">
	import '../app.css';
	import TopBarEl from '$lib/TopBarEl.svelte'; 
	let { children } = $props();
</script>
<div class ="top-0 w-full py-2 bg-red-500 flex flex-col items-center justify-center">
	<h1>Zubiri</h1>
	<div class ="flex flex-row">
		<TopBarEl title ="inicio" href="/"/>
		<TopBarEl title ="blog" href="/blog"/>
		<TopBarEl title ="apuntes" href="/notes"/>
	</div>
</div>
{@render children()}
