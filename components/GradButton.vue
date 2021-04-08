<template>
	<div id="gradButton">
		<a href="#">
			{{ title }}
		</a>
	</div>
</template>

<script>
export default {
	props: ["title"]
};
</script>

<style lang="scss" scoped>
#gradButton {
	margin: 50px 0;
	a {
		text-decoration: none;
		text-transform: uppercase;
		color: $bodyGray;
		border: $btnStroke solid $bodyGray;
		padding: 10px 35px;

		&:hover {
			background-image: linear-gradient(to right, $gradDark, $gradLight);
			background-clip: text;
			-webkit-text-fill-color: transparent;
			-moz-text-fill-color: transparent;

			border: $btnStroke solid;
			border-image: linear-gradient(to right, $gradDark, $gradLight) 10;
		}
	}
}
</style>
