<template>
	<div>
		<Nav where="top" shadow="0px 8px 10px -10px #999" />
		<Nuxt />
	</div>
</template>

<script>
import Nav from "@/components/Nav";
export default {
	components: {
		Nav
	}
};
</script>

<style>
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
