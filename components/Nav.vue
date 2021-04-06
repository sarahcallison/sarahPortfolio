<template>
	<!-- As a link -->
	<nav class="sNav">
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
export default {};
</script>

<style lang="scss" scoped>
.sNav {
	position: absolute;
	top: 0;
	background-color: white;
	opacity: 0.8;
	width: 100%;
	display: flex;
	align-items: center;
	box-shadow: 0px 1px 10px #999;

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
