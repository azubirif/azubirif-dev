<script lang="ts">
	import { base } from '$app/paths';
	import '../app.css';
	import TopBarEl from '$lib/TopBarEl.svelte'; 
	let { children } = $props();
</script>
<div class ="top-0 w-full pt-2 bg-[#81A1C1] flex flex-col items-center justify-center">
	<h1 class ="text-4xl font-bold font-kadwa text-primary">zubiri</h1>
	<div class ="flex flex-row">
		<TopBarEl title ="inicio" href="/{base}"/>
		<TopBarEl title ="blog" href="/{base}/blog"/>
		<TopBarEl title ="apuntes" href="/{base}/notes"/>
	</div>
</div>
{@render children()}
