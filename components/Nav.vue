<template>
	<!-- As a link -->
	<nav class="sNav" :style="{ where: 0, boxShadow: shadow }">
		<div class="navWrapper">
			<ul>
				<a class="mainNavItem" href="/">SC</a>
				<nuxt-link class="nuxtLink" to="/"><li>Work</li></nuxt-link>
				<nuxt-link class="nuxtLink" to="/About"
					><li>About</li></nuxt-link
				>
				<nuxt-link class="nuxtLink" to="/Contact"
					><li>Contact</li></nuxt-link
				>
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
	z-index: 1;

	.navWrapper {
		width: 100%;
		display: flex;
		justify-content: center;

		.nuxtLink {
			color: black;
			text-decoration: none;

			&:hover {
				background-image: linear-gradient(
					to right,
					$gradDark,
					$gradLight
				);
				background-clip: text;
				-webkit-text-fill-color: transparent;
				-moz-text-fill-color: transparent;
			}
		}

		.nuxt-link-exact-active {
			background-image: linear-gradient(to right, $gradDark, $gradLight);
			background-clip: text;
			-webkit-text-fill-color: transparent;
			-moz-text-fill-color: transparent;
		}

		.mainNavItem {
			color: black;
			text-decoration: none;
			font-family: "Made2";
			font-size: 35px;
		}

		ul {
			display: flex;
			justify-content: space-around;
			align-items: center;
			width: 500px;
			margin: 0;
			padding: 0;
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
