<template>
	<div>
		<Nuxt />
	</div>
</template>

<script>
export default {};
</script>

<style>
.page-enter-active,
.page-leave-active {
	transition: opacity 0.5s;
}
.page-enter,
.page-leave-to {
	opacity: 0;
}

.layout-enter-active,
.layout-leave-active {
	transition: opacity 0.5s;
}
.layout-enter,
.layout-leave-to {
	opacity: 0;
}

html {
	font-family: "Typold Book 500", "Source Sans Pro", -apple-system,
		BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial,
		sans-serif;
	font-size: 16px;
	word-spacing: 1px;
	-ms-text-size-adjust: 100%;
	-webkit-text-size-adjust: 100%;
	-moz-osx-font-smoothing: grayscale;
	-webkit-font-smoothing: antialiased;
	box-sizing: border-box;
	scroll-behavior: smooth;
}

*,
*::before,
*::after {
	box-sizing: border-box;
	margin: 0;
}
</style>
