<template>
	<!-- As a link -->
	<nav class="sNav" :style="{where : 0}">
		<div class="navWrapper">
			<ul>
				<a href="#">SC</a>
				<li>Work</li>
				<li>About</li>
				<li>Contact</li>
			</ul>
		</div>
	</nav>
</template>

<script>
export default {
	props: {
		where: {
			type: String,
			default: ''
		}
	}
};
</script>

<style lang="scss" scoped>
.sNav {
	position: absolute;
	background-color: white;
	opacity: 0.6;
	width: 100%;
	display: flex;
	align-items: center;
	box-shadow: 0px 1px 10px -10px #999;

	.navWrapper {
		width: 100%;
		display: flex;
		justify-content: center;

		a {
			color: red;
		}

		ul {
			display: flex;
			justify-content: space-evenly;
			width: 500px;
			padding: 20px;
			margin: 0;
		}
		li {
			list-style-type: none;
		}
	}
}
</style>
