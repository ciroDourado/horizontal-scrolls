<script setup>
defineProps({
	contentClasses: {
		default: () => [
			"HorizontalScrolls",
			"Block",
			"MarginLeftAuto",
			"MarginRightAuto",
			"MaxHeight672",
			"OverflowYScroll",
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
