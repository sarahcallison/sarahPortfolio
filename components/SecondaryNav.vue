<template>
	<!-- As a link -->
	<nav class="sNav">
		<div class="navWrapper">
			<ul>
				<li
					:class="{ active: activeBtn === 'btn1' }"
					@click="
						changeComp('Print');
						activeBtn = 'btn1';
					"
				>
					Print
				</li>
				<li
					:class="{ active: activeBtn === 'btn2' }"
					@click="
						changeComp('Digital');
						activeBtn = 'btn2';
					"
				>
					Digital
				</li>
				<li
					:class="{ active: activeBtn === 'btn3' }"
					@click="
						changeComp('Gallery');
						activeBtn = 'btn3';
					"
				>
					Gallery
				</li>
			</ul>
		</div>
	</nav>
</template>

<script>
export default {
	data() {
		return {
			activeBtn: "btn2"
		};
	},

	methods: {
		changeComp: function(str) {
			this.$emit("execChangeComp", str);
		}
	}
};
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
			justify-content: space-around;
			width: 500px;
			padding: 15px;
			margin: 0;

			.active {
				background-image: linear-gradient(
					to right,
					$gradDark,
					$gradLight
				);
				background-clip: text;
				-webkit-text-fill-color: transparent;
				-moz-text-fill-color: transparent;
			}

			li {
				list-style-type: none;
				letter-spacing: $tracking250;
				cursor: pointer;

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
}

@media only screen and (min-width: 768px) {
	.sNav {
		.navWrapper {
			li {
				font-size: 18px;
			}
		}
	}
}
</style>
