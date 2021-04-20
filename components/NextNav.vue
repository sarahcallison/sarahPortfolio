<template>
	<!-- As a link -->
	<nav class="nextNav">
		<div class="navWrapper">
			<ul>
				<div class="nuxtLink" @click="scrollToTop">
					<button type="button">
						Top
					</button>
				</div>
				<NuxtLink class="nuxtLink rightAligned" :to="prev"
					><button
						type="button"
						:class="prev == '' ? 'disabled' : 'notDis'"
					>
						Previous
					</button></NuxtLink
				>
				<li class="nuxtLink">|</li>
				<NuxtLink class="nuxtLink" :to="next"
					><button
						type="button"
						:class="next == '' ? 'disabled' : 'notDis'"
					>
						Next
					</button></NuxtLink
				>
			</ul>
		</div>
	</nav>
</template>

<script>
export default {
	data() {
		return {};
	},
	props: {
		prev: String,
		next: String
	},

	methods: {
		scrollToTop() {
			window.scroll({
				top: 0,
				left: 0,
				behavior: "smooth"
			});
		}
	}
};
</script>

<style lang="scss" scoped>
.nextNav {
	position: absolute;
	background-color: white;
	opacity: $navOpacity;
	width: 100%;
	display: flex;
	align-items: center;
	-webkit-box-shadow: 0px -4px 10px rgba(0, 0, 0, 0.15);
	-moz-box-shadow: 0px -4px 10px rgba(0, 0, 0, 0.15);
	box-shadow: 0px -4px 10px rgba(0, 0, 0, 0.15);
	padding: 5px 0;
	z-index: 1;

	.navWrapper {
		width: 100%;
		display: flex;
		justify-content: center;
		padding: 20px;

		.nuxtLink {
			color: black;
			list-style-type: none;
			text-decoration: none;
			margin: 0 10px;
			cursor: pointer;
		}

		.rightAligned {
			margin-left: auto;
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

			.disabled {
				color: lightgray;
				cursor: default;
				pointer-events: none;
			}
		}

		button {
			border: none;
			background: none;
			letter-spacing: $tracking250;
			text-transform: uppercase;
			font-size: 14px;

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
	}
}

@media only screen and (min-width: 768px) {
	.nextNav {
		.navWrapper {
			.mainNavItem {
				font-size: 40px;
			}
			li {
				font-size: 16px;
			}
		}
	}
}
</style>
