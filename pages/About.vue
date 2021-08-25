<template>
	<div>
		<Nav where="top" shadow="0px 8px 10px -10px #999" />
		<div
			style="background: linear-gradient(to left, #d7d7d7, #f5f5f5); position: relative; min-height: 100vh;"
		>
			<div class="container-fluid aboutContainer">
				<div class="row">
					<div class="container aboutTextContainer ">
						<div class="row justify-content-center">
							<div class="col-11 col-lg-8">
								<h1>Design doesn't feel like work</h1>
								<p>
									Design was what I did for fun to pay for 
									my degree in healthcare. After working several 
									years in that field, I decided to pursue design 
									full time. It’s still fun to me. 
									<br />
									<br />
									When faced with design problems, I work to 
									hone my skills and grow as a designer. Read 
									testimonials about my work in my 
									resume. 
								</p>
								<GradButton title="View Resume" />
							</div>
						</div>
					</div>
				</div>
			</div>

			<div class="aboutImgContainer">
				<img
					class="img-fluid aboutImg"
					src="@/assets/images/about.png"
					alt="Image of Sarah"
				/>
			</div>
			<Socials id="aboutSocials" />
		</div>
	</div>
</template>

<script>
import GradButton from "@/components/GradButton";
import Socials from "@/components/Socials";
import Nav from "@/components/Nav";

export default {
	head() {
		return {
			title: "About - Sarah Callison",
			meta: [
				{
					hid: "description",
					name: "description",
					content: "Design doesn't feel like work. When faced with design problems, I work to hone my skills and grow as a designer. Read testimonials about my work in my resume."
				}
			]
		};
	},
	props: ["GradButton", "Socials"],
	components: { GradButton, Socials, Nav }
};
</script>

<style lang="scss" scoped>
.aboutContainer {
	.aboutTextContainer {
		h1 {
			font-family: "Made";
			margin-top: 100px;
			color: $header;
			font-size: 50px;
		}
		p {
			margin: 40px 0;
			z-index: 1;
			width: 100%;
		}
	}
}

.aboutImgContainer {
	.aboutImg {
		width: 100%;
		margin-bottom: 60px;
	}
}

#aboutSocials {
	padding-bottom: 20px;
}

@media only screen and (min-width: 768px) {
	.aboutContainer {
		height: 600px;
		.aboutTextContainer {
			position: absolute;
			top: 45%; /* position the top  edge of the element at the middle of the parent */
			left: 50%; /* position the left edge of the element at the middle of the parent */

			transform: translate(-50%, -50%);

			p {
				width: 70%;
			}
		}
	}

	.aboutImgContainer {
		position: absolute;
		bottom: 0px;
		right: 0px;

		.aboutImg {
			max-width: 400px;
			margin-bottom: 0;
		}
	}

	#aboutSocials {
		position: absolute;
		bottom: 0;
		left: 0;
		right: 0;
	}
}

@media only screen and (min-width: 1200px) {
	.aboutContainer {
		.aboutTextContainer {
			p {
				width: 80%;
			}
		}
	}

	.aboutImgContainer {
		.aboutImg {
			max-width: 450px;
		}
	}
}

@media only screen and (min-width: 1400px) {
	.aboutContainer {
		.aboutTextContainer {
			p {
				width: 100%;
			}
		}
	}
}
</style>
