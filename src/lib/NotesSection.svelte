<script>
    export let title;
</script>

<h1 class="text-2xl underline">{title}</h1>
<div class="mx-2 my-4 grid sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 items-center justify-center gap-5">
    <slot/>
</div>
<div class="w-9/12 h-1 bg-black rounded-2xl"></div>