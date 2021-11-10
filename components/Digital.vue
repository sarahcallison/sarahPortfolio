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
					<h2>Website Redesign</h2>
					<div class="gradLine"></div>
					<p>
						A new brand identity and an updated website 
						for UVU’s Academic Tutoring department
					</p>
					<NuxtLink
						style="cursor: auto; textDecoration: none;"
						to="/websiteRedesign"
					>
						<GradButton title="View Project" />
					</NuxtLink>
				</div>
				<div class="col-12 col-md-5 col-lg-6 align-self-center">
					<img
						class="img-fluid"
						src="@/assets/images/lavenderMac-updated.png"
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
							<h4>Utah Valley University</h4>
							<h2>User Research</h2>
							<div class="gradLine ml-md-auto"></div>
							<p id=rightText>
								Data analysis and next steps for improving the
								Telehealth user experience
							</p>
							<NuxtLink
								style="cursor: auto; textDecoration: none;"
								to="/userResearch"
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
									srcset="@/assets/images/mac-updated.png"
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
				<div
					class="col-12 col-md-7 col-lg-6 align-self-center textSection"
				>
					<h4>Mobile App Concept</h4>
					<h2>Brandish App</h2>
					<div class="gradLine"></div>
					<p>
						High-fidelity prototype of an app that 
						teaches users how to market their brand
					</p>
					<NuxtLink
						style="cursor: auto; textDecoration: none;"
						to="/brandishApp"
					>
						<GradButton title="View Project" />
					</NuxtLink>
				</div>
				<div class="col-12 col-md-5 col-lg-6 align-self-center">
					<img
						class="img-fluid"
						src="@/assets/images/brandishApp.png"
						alt="image of brandish app on smartphone"
					/>
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
				font-size: 15px;
				letter-spacing: $tracking250;
				text-transform: uppercase;
			}

			h2 {
				font-size: 50px;
				font-family: "Made";
				color: $header;
			}

			p {
				font-size: 16px;
			}
		}
		
		#rightText {
			display: inline;
			float: right;
			margin-bottom: 3rem;
			margin-left: 15%;
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

@media only screen and (min-width: 320px) {
	.main {
		.projectContainers {
			#rightText {
			display: inline;
			float: right;
			margin-bottom: 3rem;
			margin-left: 0;
			}
		}
	}
}

@media only screen and (min-width: 768px) {
	.main {
		.projectContainers {
			.textSection {
				padding-left: 15px;
				padding-right: 15px;

				h4 {
					font-size: 15px;
					letter-spacing: $tracking250;
				}

				h2 {
					font-size: 50px;
					font-family: "Made";
					color: $header;
				}
			}
		}
	}
}

@media only screen and (min-width: 992px) {
	.main {
		.projectContainers {
			.textSection {
					
				p {
					width: 65%;
				}
			}
		}
	}
}

@media only screen and (min-width: 1200px) {
	.main {
		.projectContainers {
			.textSection {
					
				p {
					width: 70%;
				}
				
				#rightText {
					display: inline;
					float: right;
					margin-bottom: 3rem;
					margin-left: 22%;
				}
				
				#right {
					padding-left: 10%;
				}
			}
		}
	}
}

</style>
