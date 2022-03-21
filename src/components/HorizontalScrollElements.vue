<script setup>
defineProps({
	contentClasses: {
		default: () => [
			"HorizontalScrollElements",
			"Flex",
			"FlexRow",
			"CrossAxisStart",
			"MaxWidth800",
			"OverflowXScroll",
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
