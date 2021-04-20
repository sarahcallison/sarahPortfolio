<template>
	<!-- As a link -->
	<nav class="sNav" :style="{ where: 0, boxShadow: shadow }">
		<div class="navWrapper">
			<ul>
				<a class="mainNavItem" href="/">SC</a>
				<nuxt-link to="/"><li>Work</li></nuxt-link>
				<nuxt-link to="/About"><li>About</li></nuxt-link>
				<nuxt-link to="/Contact"><li>Contact</li></nuxt-link>
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

		ul {
			display: flex;
			justify-content: space-around;
			align-items: center;
			width: 500px;
			margin: 0;
			padding: 0;
			list-style-type: none;
			text-decoration: none;

			.mainNavItem {
				color: black;
				font-family: "Made2";
				font-size: 35px;
			}

			a {
				text-decoration: none;

				li {
					color: black;
					text-decoration: none;
					letter-spacing: $tracking250;
					text-transform: uppercase;
					font-size: 14px;

					&:hover {
						text-decoration: none;

						background: linear-gradient(
							to right,
							$gradDark,
							$gradLight
						);

						background-clip: text;
						-webkit-text-fill-color: transparent;
						-moz-text-fill-color: transparent;
					}
				}
			}
		}
	}
	.nuxt-link-exact-active {
		background: linear-gradient(to right, $gradDark, $gradLight);

		background-clip: text;
		-webkit-text-fill-color: transparent;
		-moz-text-fill-color: transparent;
	}

	@supports (-ms-ime-align: auto) {
		.nuxt-link-exact-active {
			-webkit-text-fill-color: $gradDark;
			-moz-text-fill-color: $gradDark;
		}
	}

	@media not all and (min-resolution: 0.001dpcm) {
		@supports (-webkit-appearance: none) {
			.nuxt-link-exact-active {
				-webkit-text-fill-color: $gradDark;
				-moz-text-fill-color: $gradDark;
			}
		}
	}
}

@media only screen and (min-width: 768px) {
	.sNav {
		.navWrapper {
			ul {
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
}
</style>
