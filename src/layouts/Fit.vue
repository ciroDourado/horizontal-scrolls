<script setup>
defineProps({
	contentClasses: {
		default: () => [
			"ScreenWidth",
			"ScreenHeight",
			"MaterialBackgroundGrey100",
		]
	}
})
</script>

<template>
	<main :class="contentClasses">
		<slot/>
	</main>
</template>
