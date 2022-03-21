<script setup>
defineProps({
	contentClasses: {
		default: () => [
			"HorizontalScroll",
			"Block",
			"MaxWidthFit",
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
