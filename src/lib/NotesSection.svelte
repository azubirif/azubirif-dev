<script>
    export let title;
</script>

<div class="w-11/12 h-1 bg-black rounded-2xl"></div>
<h1 class="text-2xl">{title}</h1>
<div class="mx-2 my-4 grid sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 items-center justify-center gap-5">
    <slot/>
</div>