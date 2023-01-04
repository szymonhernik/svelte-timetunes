<script>
	export let todos;
</script>

<div class="rounded-lg mx-auto w-1/2 shadow-sm flex flex-col gap-2">
	{#each todos as item, index}
		<div class="rounded-md  p-4 flex justify-between flex-row border-2 border-gray-100">
			<div class="font-medium text-sm">{item.text}</div>
			<button>❌</button>
		</div>
	{/each}
</div>
