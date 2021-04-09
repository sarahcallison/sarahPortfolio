<template>
	<div>
		<div class="container-fluid jumboContainer">
			<div class="row">
				<div class="infoText">
					<h4 id="title">Digital Designer</h4>
					<h1 id="name">
						<span id="firstName">Sarah</span> Callison
					</h1>
					<p id="description">
						Launching creative solutions. If you can think it, I'll
						design it. Clean, user-centered design.
					</p>
					<button id="workBtn">View My Work</button>
				</div>
				<picture>
					<source
						media="(min-width:768px)"
						srcset="@/assets/images/heroHeaderDesktop.jpg"
					/>
					<img
						src="@/assets/images/heroHeaderMobile.jpg"
						alt="Image of Sarah"
						class="img-fluid jumboImage"
					/>
				</picture>
			</div>
		</div>

		<SecondaryNav />

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
							Data analysis and next steps for improving the
							Telehealth user experience.
						</p>
						<GradButton title="View Project" />
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
								<h4>Utah Valley University</h4>
								<h2>User Research</h2>
								<div class="gradLine ml-md-auto"></div>
								<p>
									Data analysis and next steps for improving
									the Telehealth user experience.
								</p>
								<GradButton title="View Project" />
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
					<div
						class="col-12 col-md-7 col-lg-6 align-self-center textSection"
					>
						<h4>Mobile App Concept</h4>
						<h2>Brandish App</h2>
						<div class="gradLine"></div>
						<p>
							Data analysis and next steps for improving the
							Telehealth user experience.
						</p>
						<GradButton title="View Project" />
					</div>
					<div class="col-12 col-md-5 col-lg-6 align-self-center">
						<img
							class="img-fluid"
							src="@/assets/images/brandishApp.png"
							alt="image of mac computer"
						/>
					</div>
				</div>
			</div>
		</div>

		<Socials style="marginBottom: 40px;" />
		<Nav where="bottom" shadow="0px 8px 10px 6px  #999" />
	</div>
</template>

<script>
import SecondaryNav from "@/components/SecondaryNav";
import Socials from "@/components/Socials";
import GradButton from "@/components/GradButton";
import Nav from "@/components/Nav";
export default {
	components: {
		SecondaryNav,
		Socials,
		GradButton,
		Nav
	}
};
</script>

<style lang="scss" scoped>
.jumboContainer {
	color: white;
	.jumboImage {
		margin-top: -100px;
	}
	.infoText {
		position: absolute;
		top: 120px;
		left: 10%;
		width: 70%;

		#title {
			font-size: 16px;
			letter-spacing: $tracking250;
		}

		#name {
			margin-top: 10px;
			font-family: "Made2";
			font-size: 50px;
			text-transform: uppercase;
			line-height: 40px;

			#firstName {
				letter-spacing: #{(25/1000)}em;
				margin-right: 10px;
			}
		}

		#description {
			margin-top: 10px;
			letter-spacing: #{(35/1000)}em;
			width: 80%;
		}
		#workBtn {
			margin-top: 15px;
			color: white;
			border: 2px solid white;
			text-transform: uppercase;
			background: none;
			padding: 15px;
			transition: 0.4s;

			&:hover {
				background-color: rgba(255, 255, 255, 0.2);
			}
		}
	}
}

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

@media only screen and (min-width: 576px) {
	.jumboContainer {
		.jumboImage {
			margin-top: -320px;
		}
	}
}

@media only screen and (min-width: 650px) {
	.jumboContainer {
		.jumboImage {
			margin-top: -400px;
		}
	}
}

@media only screen and (min-width: 768px) {
	.jumboContainer {
		.jumboImage {
			margin-top: 0;
		}

		.infoText {
			width: 45%;
			top: calc(15vw);
			left: auto;
			right: 0;
			padding: 0 10px;
		}
	}

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

@media only screen and (min-width: 992px) {
	.jumboContainer {
		.infoText {
			top: calc(20vw);
		}
	}
}

@media only screen and (min-width: 1200px) {
	.jumboContainer {
		.infoText {
			top: calc(18vw);
			#title {
				font-size: 25px;
			}
			#name {
				margin-top: 50px;
				font-size: 70px;
				line-height: 50px;
			}
			#description {
				margin-top: 50px;
				font-size: 25px;
			}
			#workBtn {
				margin-top: 30px;
				font-size: 18px;
			}
		}
	}
}
</style>
