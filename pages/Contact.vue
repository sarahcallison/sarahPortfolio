<template>
	<div>
		<Nav where="top" shadow="0px 8px 10px -10px #999" />
		<div
			style="background: linear-gradient(to left, #e6e8ff, #f7efff); position: relative; min-height: 100vh;"
		>
			<div class="container-fluid contactContainer">
				<div class="row">
					<div class="container contactTextContainer ">
						<div class="row justify-content-center">
							<div class="col-11 col-md-6 align-self-center">
								<h1>Need to launch an idea?</h1>
								<p>
									I’d to talk about your next project.
									Send me an email or connect with me on
									LinkedIn, Instagram, Behance or Dribble.
								</p>
								<GradButton
									title="hi@sarahcallison.com"
									url="mailto:hi@sarahcallison.com"
								/>
							</div>
							<div class="col-12 col-md-6 align-self-center">
								<img
									class="img-fluid contactImg"
									src="@/assets/images/purpleBurst.png"
									alt="image of bursting purple colors"
								/>
							</div>
						</div>
					</div>
				</div>
			</div>
			<Socials id="contactSocials" />
		</div>
	</div>
</template>

<script>
import GradButton from "@/components/GradButton";
import Socials from "@/components/Socials";

export default {
	head() {
		return {
			title: "Contact - Sarah Callison",
			meta: [
				{
					hid: "description",
					name: "description",
					content:
						"Need to launch an idea? I’d love to talk about your next project. Send me an email or connect with me on LinkedIn, Instagram, Behance or Dribble."
				}
			]
		};
	},
	components: { GradButton, Socials }
};
</script>

<style lang="scss" scoped>
.contactContainer {
	.contactTextContainer {
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

		.contactImg {
			margin: 80px 0;
		}
	}
}

#contactSocials {
	padding-bottom: 20px;
}

@media only screen and (min-width: 768px) {
	.contactContainer {
		height: 600px;
		.contactTextContainer {
			position: absolute;
			top: 45%; /* position the top  edge of the element at the middle of the parent */
			left: 50%; /* position the left edge of the element at the middle of the parent */

			transform: translate(-50%, -50%);

			.contactImg {
				margin: 0;
			}
		}
	}

	#contactSocials {
		position: absolute;
		bottom: 0;
		left: 0;
		right: 0;
	}
}

@media only screen and (min-width: 1200px) {
	.contactContainer {
		.contactTextContainer {
			p {
				width: 100%;
			}
		}
	}
}
</style>
