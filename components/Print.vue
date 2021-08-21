<template>
	<!-- Main Content -->
	<div class="main">
		<!-- First Section -->
		<div class="container projectContainers">
			<div class="row">
				<div
					class="col-12 col-md-7 col-lg-6 align-self-center textSection"
				>
					<h4>Utah Valley University</h4>
					<h2>AR Space Book</h2>
					<div class="gradLine"></div>
					<p>
						Data analysis and next steps for improving the
						Telehealth user experience.
					</p>
					<NuxtLink
						style="cursor: auto; textDecoration: none;"
						to="/ArSpaceBook"
					>
						<GradButton title="View Project" />
					</NuxtLink>
				</div>
				<div class="col-12 col-md-5 col-lg-6 align-self-center">
					<img
						class="img-fluid"
						src="@/assets/images/macGrid.png"
						alt="image of mac computer"
					/>
				</div>
			</div>
		</div>
		<!-- Second Section -->
		<div class="container-fluid infoColor projectContainers">
			<div class="row">
				<div class="container">
					<div class="row">
						<div
							class="col-12 col-md-7 col-lg-6 order-md-2 align-self-center textSection text-md-right"
						>
							<h4>Silicon Slopes Magazine</h4>
							<h2>Graphic Design</h2>
							<div class="gradLine ml-md-auto"></div>
							<p>
								Data analysis and next steps for improving the
								Telehealth user experience.
							</p>
							<NuxtLink
								style="cursor: auto; textDecoration: none;"
								to="/GraphicDesign"
							>
								<GradButton title="View Project" />
							</NuxtLink>
						</div>
						<div
							class="col-12 col-md-5 col-lg-6 order-md-1 align-self-center"
						>
							<picture>
								<source
									media="(min-width:768px)"
									srcset="@/assets/images/map.png"
								/>
								<img
									src="@/assets/images/mapMobile.png"
									alt="Image of map"
									class="img-fluid"
								/>
							</picture>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- Third Section -->
		<div class="container projectContainers">
			<div class="row">
				<div class="col-12 align-self-center textSection">
					<h2>Invitations & Cards</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: { img: `/print/showerCard` }
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/print/showerCard.jpg"
							alt="image of invitations and cards"
						/>
					</NuxtLink>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: { img: `/print/showerCard` }
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/print/showerCard.jpg"
							alt="image of invitations and cards"
						/>
					</NuxtLink>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: { img: `/print/showerCard` }
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/print/showerCard.jpg"
							alt="image of invitations and cards"
						/>
					</NuxtLink>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: { img: `/print/showerCard` }
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/print/showerCard.jpg"
							alt="image of invitations and cards"
						/>
					</NuxtLink>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: { img: `/print/showerCard` }
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/print/showerCard.jpg"
							alt="image of invitations and cards"
						/>
					</NuxtLink>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: { img: `/print/showerCard` }
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/print/showerCard.jpg"
							alt="image of invitations and cards"
						/>
					</NuxtLink>
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
.main {
	color: black;

	.projectContainers {
		padding-top: 100px;
		padding-bottom: 100px;

		.textSection {
			padding-left: 50px;
			padding-right: 50px;

			h4 {
				font-size: 14px;
				letter-spacing: $tracking250;
				text-transform: uppercase;
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
	.main {
		.projectContainers {
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
</style>
