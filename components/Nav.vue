<template>
	<!-- As a link -->
	<nav class="sNav" :style="{ where: 0, boxShadow: shadow }">
		<div class="navWrapper">
			<ul>
				<a class="mainNavItem" href="#">SC</a>
				<a href="#"><li>Work</li></a>
				<a href="#"><li>About</li></a>
				<a href="#"><li>Contact</li></a>
			</ul>
		</div>
	</nav>
</template>

<script>
export default {
	props: {
		where: {
			type: String,
			default: ""
		},
		shadow: {
			type: String,
			default: ""
		}
	}
};
</script>

<style lang="scss" scoped>
.sNav {
	position: absolute;
	background-color: white;
	opacity: $navOpacity;
	width: 100%;
	display: flex;
	align-items: center;
	box-shadow: 0px 1px 10px -10px #999;
	padding: 5px 0;

	.navWrapper {
		width: 100%;
		display: flex;
		justify-content: center;
		a {
			text-decoration: none;
			color: black;
		}

		.mainNavItem {
			text-decoration: none;
			color: black;
			font-family: "Made2";
			font-size: 35px;
		}

		ul {
			display: flex;
			justify-content: space-evenly;
			align-items: center;
			width: 500px;
			margin: 0;
			padding: 0;
		}

		@supports not (-ms-ime-align: auto) {
			ul {
				justify-content: space-between;
			}
		}

		a {
			li {
				list-style-type: none;
				letter-spacing: $tracking250;
				text-transform: uppercase;
				font-size: 14px;
			}
		}
	}
}

@media only screen and (min-width: 768px) {
	.sNav {
		.navWrapper {
			.mainNavItem {
				font-size: 40px;
			}
			a {
				li {
					font-size: 16px;
				}
			}
		}
	}
}
</style>
