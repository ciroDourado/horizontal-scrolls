<script setup>
defineProps({
	contentClasses: {
		default: () => [
			"HorizontalScrollTitle",
			"Height32",
			"Width128",
			"Block",
			"BackgroundTransparent"
		]
	}
})
</script>

<template>
	<section :class="contentClasses">
		<slot/>
	</section>
</template>
