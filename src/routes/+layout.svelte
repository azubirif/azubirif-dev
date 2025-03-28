<script lang="ts">
	import { base } from '$app/paths';
	import '../app.css';
	import TopBarEl from '$lib/TopBarEl.svelte'; 
	let { children } = $props();
</script>
<div class ="top-0 sticky w-full pt-2 bg-[#81A1C1] flex flex-col items-center justify-center">
	<h1 class ="text-4xl font-bold font-kadwa text-primary">zubiri</h1>
	<div class ="flex flex-row">
		<TopBarEl title ="inicio" href="{base}/"/>
		<TopBarEl title ="apuntes" href="{base}/notes"/>
	</div>
</div>
{@render children()}
<div class="fixed bottom-0 w-full py-2 px-4 bg-second">
	<div class="flex flex-row justify-between">
		<h1 class="font-bold text-white font-kadwa">Alejandro Zubiri</h1>
		<div class="flex flex-row items-center justify-center">
			<a href="https://github.com/azubirif" target="_blank" class="fa fa-github scale-150 text-white"></a>
		</div>
	</div>
</div>
