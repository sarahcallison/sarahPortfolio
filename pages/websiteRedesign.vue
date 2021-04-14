<template>
	<!-- websiteRedesign Content -->
	<div class="websiteRedesign">
		<NuxtLink to="/" class="close">
			<img
				id="closeImg"
				src="@/assets/images/closeHover.png"
				src2="@/assets/images/close.png"
			/>
		</NuxtLink>
		<!-- First Section -->
		<div class="container projectContainers" id="firstProjContainer">
			<div class="row">
				<div
					class="col-12 col-md-7 col-lg-6 align-self-center textSection"
				>
					<h4>Utah Valley University</h4>
					<h2>Website Redesign</h2>
					<div class="gradLine"></div>
					<p>
						May 2021
					</p>
				</div>
			</div>
		</div>
		<!-- Second Section -->
		<div class="container-fluid infoColor projectContainers">
			<div class="row">
				<div class="container">
					<div class="row">
						<div
							class="col-12 col-md-5 col-lg-6 order-md-2 align-self-center"
						>
							<img
								class="img-fluid"
								id="macImg"
								src="@/assets/images/digital/mac.png"
								alt="image of mac computer"
							/>
						</div>
						<div
							class="col-12 col-md-7 col-lg-6 order-md-1 align-self-center textSection"
						>
							<h2>The Problem</h2>
							<p>
								Lorem ipsum dolor sit amet, consectetur
								adipiscing elit. Nullam dapibus convallis sapien
								sed egestas. Nunc suscipit sem lorem, non
								pretium risus rutrum ut. Mauris sagittis urna
							</p>
							<GradButton title="Go To XD Adobe.com" />
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- Third Section -->
		<div class="container projectContainers">
			<div class="row">
				<div
					class="col-12 col-md-7 col-lg-6 align-self-center text-center textSection"
				>
					<h2>The Solution</h2>
					<h4>Mobile App Concept</h4>

					<p>
						Lorem ipsum dolor sit amet, consectetur adipiscing elit.
						Nullam dapibus convallis sapien sed egestas. Nunc
						suscipit sem lorem, non pretium risus rutrum ut. Mauris
						sagittis urna elit, efficitur convallis nisi feugiat
						quis. Ut lacus est, egestas vel feugiat in, vehicula
						quis tortor. Cras pretium odio nisl, eget dignissim nunc
						commodo et.
						<br />
						<br />
						Aliquam hendrerit vitae tortor id iaculis. Vestibulum
						varius quam eros, sit amet mattis nulla varius vel.
						Maecenas feugiat mi quis mattis ultricies. Morbi vitae
						lectus in erat blandit egestas. Vestibulum ante ipsum
						primis in faucibus orci luctus et ultrices posuere
						cubilia curae; Mauris ultricies blandit metus, et cursus
						urna congue ut. Mauris mollis tortor eget nisl
						scelerisque sagittis. Etiam nisl orci, malesuada et
						aliquet vel, congue sit amet ex. Curabitur tincidunt
						lacinia ligula, eu pellentesque lectus vestibulum vitae.
						Sed eu mauris eu sem viverra aliquet. Aliquam erat
						volutpat. Sed lacinia massa ornare rhoncus facilisis.
					</p>
					<GradButton title="View Project" />
				</div>
			</div>
		</div>
	</div>
</template>

<script>
import GradButton from "@/components/GradButton";
export default {
	components: {
		GradButton
	}
};
</script>

<style lang="scss" scoped>
.websiteRedesign {
	color: black;

	.close {
		position: absolute;
		right: 20px;
		top: 20px;
		height: 32px;

		#closeImg {
			content: url("@/assets/images/closeHover.png");
			content: url("@/assets/images/close.png");
			width: 45px;

			&:hover {
				content: url("@/assets/images/closeHover.png");
			}
		}
	}

	#firstProjContainer {
		padding-bottom: 200px;
	}

	.projectContainers {
		padding-top: 100px;
		padding-bottom: 100px;

		#macImg {
			margin-top: -200px;
			margin-bottom: 100px;
		}

		.textSection {
			padding-left: 50px;
			padding-right: 50px;

			h4 {
				font-size: 14px;
				letter-spacing: $tracking250;
			}

			h2 {
				font-size: 50px;
				font-family: "Made";
				color: $header;
			}

			p {
				font-size: 18px;
			}
		}

		.gradLine {
			height: 3px;
			width: 80px;
			margin: 20px 0;
			background-image: linear-gradient(to right, $gradDark, $gradLight);
		}
	}

	.infoColor {
		background-image: linear-gradient(
			to right,
			$bgLightPurple,
			$bgDarkPurple
		);
	}
}

@media only screen and (min-width: 768px) {
	.websiteRedesign {
		.projectContainers {
			#macImg {
				margin-top: 0;
				margin-bottom: 0;
			}

			.textSection {
				padding-left: 15px;
				padding-right: 15px;

				h4 {
					font-size: 16px;
					letter-spacing: $tracking250;
				}

				h2 {
					font-size: 60px;
					font-family: "Made";
					color: $header;
				}
			}
		}
	}
}

@media only screen and (min-width: 992px) {
	.websiteRedesign {
		.projectContainers {
			#macImg {
				margin-top: -200px;
				margin-bottom: 100px;
			}
		}
	}
}
</style>
