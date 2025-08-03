<script>
	export let size = 'max-w-2xl';
	export let padding = 'pb-12';
</script>

<div class="flex justify-center font-serif text-lg">
	<div class="mx-8 {size} w-full {padding} {$$props.class}">
		<slot></slot>
	</div>
</div>
