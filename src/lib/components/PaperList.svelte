<script>
	import papersData from '$lib/papers.json';
	const papers = papersData.notes;
</script>

<div class="space-y-6">
	{#each papers as paper}
		<div
			class="rounded-xl border border-gray-200 p-6 transition hover:border-blue-500/10 hover:shadow-blue-500/10"
		>
			<h3 class="text-lg font-semibold text-gray-800">
				<a
					href={`https://openreview.net/forum?id=${paper.forum}`}
					target="_blank"
					rel="noreferrer"
					class="hover:underline"
				>
					{paper.content.title.value}
				</a>
			</h3>
			<p class="mt-2 text-sm text-gray-600">
				{paper.content.authors.value.join(', ')}
			</p>
		</div>
	{/each}
</div>
