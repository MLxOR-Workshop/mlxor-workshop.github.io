<script>
	export let href = '';
</script>

<a {href}>
	<div
		class="my-2 cursor-pointer font-mono text-xs text-gray-600 uppercase underline underline-offset-4 transition hover:bg-gray-600 hover:text-white"
	>
		<slot></slot>
	</div>
</a>
