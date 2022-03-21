<script setup>
defineProps({
	contentClasses: {
		default: () => [
			"HorizontalScrollElement",
			"Height128",
			"Width128",
			"FlexNeverShrink",
			"MaterialBackgroundGrey300"
		]
	}
})
</script>

<template>
	<section :class="contentClasses">
		<slot/>
	</section>
</template>
