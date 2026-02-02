<script lang="ts">
	let props = $props();
</script>

<!-- 
	Todo:
	- Make the cards responsive
	- Add a tooltip for the trend
	- Add a tooltip for the change
-->

<div
	class="flex h-80 w-full flex-col items-start justify-end bg-(--c) p-4 shadow-md outline outline-stone-900"
	style="--c: {props.colour};"
>
	<div>
		<h3 class="mb-2 text-xl font-black text-stone-900">{props.title}</h3>
		<p class="mb-2 font-mono text-2xl font-bold text-stone-900">{props.value}</p>
	</div>
</div>
