<script>
	export let name = 'John Doe';
	export let affiliation = 'Software Engineer';
	export let image = '';
	export let link = '';
</script>

<a href={link} target="_blank" rel="noreferrer" class="inline-block">
	<div class="flex cursor-pointer flex-col items-center justify-center px-4 py-4">
		<div
			class="h-32 w-32 rounded-full border border-gray-300 bg-cover bg-center"
			style="background-image: url({image})"
		></div>
		<div
			class="mt-2 mb-2 max-w-32 border-gray-300 text-center text-xl underline decoration-gray-300 underline-offset-6 transition hover:decoration-gray-500"
		>
			{name}
		</div>
		<div class="max-w-32 text-center text-base text-gray-600">{affiliation}</div>
	</div>
</a>
