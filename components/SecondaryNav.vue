<template>
	<!-- As a link -->
	<nav class="sNav">
		<div class="navWrapper">
			<ul>
				<li>Digital</li>
				<li>Print</li>
				<li>Gallery</li>
			</ul>
		</div>
	</nav>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.sNav {
	position: sticky;
	top: 0;
	z-index: 1;
	color: black;
	background-color: white;
	width: 100%;
	display: flex;
	align-items: center;
	box-shadow: 0px 8px 10px -10px #999;

	.navWrapper {
		width: 100%;
		display: flex;
		justify-content: center;

		ul {
			display: flex;
			justify-content: space-evenly;
			width: 500px;
			padding: 15px;
			margin: 0;
		}
		li {
			list-style-type: none;
		}
	}
}
</style>
