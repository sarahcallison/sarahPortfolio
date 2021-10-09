<template>
	<div id="gradButton">
		<a :href="url" :target="target">
			{{ title }}
		</a>
	</div>
</template>

<script>
export default {
	props: {
		title: String,
		url: String
	}
};
</script>

<style lang="scss" scoped>
#gradButton {
	margin: 50px 0;
	cursor: pointer;
	a {
		text-decoration: none;
		text-transform: uppercase;
		color: $bodyGray;
		border: $btnStroke solid $bodyGray;
		padding: 10px 5%;

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

@media only screen and (min-width: 768px) {
	#gradButton {
		font-size: 16px;
	}
}
</style>
