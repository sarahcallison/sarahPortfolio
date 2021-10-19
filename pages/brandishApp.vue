<template>
	<!-- brandishApp Content -->
	<div class="brandishApp">
		<div @click="$router.go(-1)" class="close">
			<img
				id="closeImg"
				src="@/assets/images/closeHover.png"
				src2="@/assets/images/close.png"
			/>
		</div>
		<!-- First Section -->
		<div class="container projectContainers" id="firstProjContainer">
			<div class="row">
				<div class="col-12 align-self-center textSection">
					<h4>UTAH VALLEY UNIVERSITY</h4>
					<h2>Brandish App</h2>
					<div class="gradLine"></div>
					<p>
						November 2020
					</p>
				</div>
			</div>
		</div>
		<!-- Second Section -->
		<div class="container-fluid infoColor projectContainers" id="problemContainer">
			<div class="row">
				<div class="container">
					<div class="row ">
						<div
							class="col-12 col-md-5 col-lg-6 order-md-2 align-self-center"
						>
							<img
								class="img-fluid"
								id="macImg"
								src="@/assets/images/digital/brandishApp.png"
								alt="image of brandish app on smartphone"
							/>
						</div>
						<div
							class="col-12 col-md-7 col-lg-6 order-md-1 align-self-center  textSection problemText"
						>
							<h2 id="problemHeader" class="smallerHeader">The Problem</h2>
							<p>
								With the proliferation of mobile and social media platforms, there is no longer 
								“one size fits all” for publishing digital content. Users can pick and choose how 
								they want to get content. To reach a wider audience, digital publishers must
								make their content adaptable across a variety of platforms. 
								<br />
								<br />
								In my Immersive Authoring II course, I was tasked with creating a business persona 
								and adapting this persona’s content across multiple platforms. I created Brandish, a would-be marketing 
								resource, that publishes content about how to build a brand from the ground up. 
							</p>

							<h4 class="purpHeader">Deliverables</h4>
							<p class="highFidText">High-fidelity prototype</p>
							<GradButton
								title="Go To XD Adobe.com"
								url="https://xd.adobe.com/view/2b0ab223-73b6-45af-9dfc-a08ab92c8c44-7e59/"
							/>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- Third Section -->
		<div class="container-fluid projectContainers">
			<div class="row justify-content-md-center">
				<div class="container">
					<div class="row justify-content-md-center">
						<div
							class="col-12 col-md-10 align-self-center px-4 px-md-0 textSection mainText"
						>
							<h2 class="text-center smallerHeader">The Solution</h2>
							<h4 class="text-center subtitle firstHeader">
								Research
							</h4>

							<p class="text-left">
								Early in the semester, I reviewed what marketing 
								content and apps are already available. I found 
								multiple sources that provide marketing services, 
								such as consulting from Brandology or business card 
								design from Brandly, rather than guidance on how to 
								build a brand on your own. One of the more well-known 
								brand-building platforms, HubSpot, provides some 
								marketing resources and methodologies, but focuses 
								on inbound marketing, sales, and service software. 
								<br />
								<br />
								Many digital publishers take a DIY approach to 
								marketing—at least in the initial stages of growing 
								their brand. Brandish content, specifically the Brandish 
								app, is designed to take the user through the process of 
								building a basic marketing plan—focusing on foundational 
								concepts rather than the mechanics of tracking leads and 
								sales. Once the user has the basic concepts down, other 
								Brandish platforms, such as social channels, would provide 
								an endless stream of ideas and tips to hone their marketing 
								efforts.
								<br />
								<br />
								I was stumped when it came time to pick a name for my business. 
								It seemed all the variations of the word “brand” were already 
								in use. I wanted something bold that would stand out from all 
								of the trendy or obvious choices like brandology or brandily. 
								I searched online thesauri and talked with friends and family
								about my ideas. The word “brandish” was proposed. This felt 
								like a winning combination of the word brand paired with a bold 
								marketing idea. I selected Brandish with the tagline, Show off 
								your brand, and a longer tagline for use on mediums such as a 
								podcast: Is the world ready for your brand? Don’t promote it. 
								Brandish it. 
							</p>

							<h4 class="text-center subtitle">Ideation</h4>

							<p>
								I began the ideation process by sketching, progressing to low-
								fidelity wireframes. With each iteration, I included more content 
								from my research to build a richer experience for the user.  
								<br />
								<br />

								*Images of sketches*
								<br />
								<br />
								
								When I was building my business persona, I created a negative 
								space logo in black and white. I love the simplicity of black and 
								white. This high-contrast color combination feels clean and bold. 
								The app’s color scheme matched the logo’s color scheme for the 
								reasons listed above and consistency with the Brandish brand.
								<br />
								<br />
								*Image of logo*
							</p>

							<h4 class="text-center subtitle">Ui Design</h4>

							<p>
								Prior to this project, I’d spent months working 
								on UVU websites which feature pre-configured 
								elements. I had a lot of questions about mobile 
								dimensions, so I availed myself of the resources 
								provided by InVision and Kapeli’s iOS cheat sheet. 
								I made some slight modifications to the recommendations 
								in order to create content hierarchy, but it felt 
								satisfying to base my design off what users are familiar 
								with and what has worked for high-level designers. 
								Doing a little research took a lot of the guesswork 
								out of the design.
								<br />
								<br />

								Once I had the dimensions down, I started on the 
								navigation. Traditionally, a popout menu is featured 
								in the upper right corner. I’ve frequently found this 
								menu difficult to reach while navigating on my phone. 
								I have a minor skeletal malformation called Brachydactyly 
								type D or “stub thumb.” The last phalanx or section of 
								my thumb is stunted, making my thumb shorter than average. 
								This condition is sometimes called “toe thumb.” Imagine 
								navigating an app with one of your toes! Okay, it’s not 
								that bad, but it does make reaching that corner menu harder.
								<br />
								<br />
								I decided to do some more research on mobile navigation. 
								I read an article by UX designer Kiril Karov about 
								reinventing app navigation: “One-handed Use of Tab Bar/Bottom 
								Navigation — Best Practices for Reachability.” Karov talks 
								about how a majority of users navigate using their thumb, 
								making it difficult to reach the menus located in the upper 
								corners. For an easier navigation experience, I decided to 
								use a bottom navigation menu. This app only has three menu 
								items—if additional items were needed, a menu that pops out 
								from an ellipse icon or the word “more” could be used.
								<br />
								<br />
								*image of nav*
							</p>

							<h4 class="text-center subtitle">Iteration</h4>

							<p>
								This app was designed to be simple, but some of the 
								sections featured too much information for easy 
								navigation. I hid some of the content so that the 
								user could choose to progressively disclose 
								information at their own pace. 
								<br />
								<br />
								*image of plus icons*
								<br />
								<br />
								Black and white is bold, but the app’s UI didn’t say 
								“brandish”—it felt cold and a little flat. I added 
								some pops of neon-colored gradients and a background 
								gradient to add some warmth and texture. 
								<br />
								<br />
								*Iteration images*
							</p>

							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/first.jpg"
								alt="image of mobile phone app design"
							/>
							<figcaption class="text-center mt-3">
								First Iteration
							</figcaption>

							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/second.jpg"
								alt="image of mobile phone app design"
							/>
							<figcaption class="text-center mt-3">
								Second Iteration
							</figcaption>

							<h4 class="text-center subtitle">
								Problem Solving
							</h4>

							<div class="embed-responsive embed-responsive-4by3">
								<iframe
									class="embed-responsive-item px-0 mt-5"
									src="https://www.youtube.com/embed/TdsgREfA6BQ"
									title="YouTube video player"
									frameborder="0"
									allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture allowfullscreen"
								>
								</iframe>
							</div>
							<figcaption class="text-center mt-3">
								Second Iteration
							</figcaption>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="container-fluid projectContainers infoColor" id="lessons">
			<div class="row justify-content-md-center">
				<div class="container">
					<div
						class="col-12 align-self-center px-4 px-md-0 textSection mainText"
					>
						<h4 class="text-center subtitle firstHeader">
							Lessons Learned
						</h4>

						<p class="text-left">
							It was an eye-opening experience to design the user experience 
							around a problem I experience on a daily basis. Navigating on 
							my phone wasn’t ruining my day, but it started to bug me 
							increasingly over time until I was able to put my finger 
							(or thumb) on what the issue was. I was invested in finding a 
							solution for one of my frustrating problems. I want to be as 
							invested in solving frustrating problems for other people, 
							the users, in any project that I design for. Becoming invested 
							in the problems of someone else takes empathy and hard work, 
							which is something that I plan to keep practicing. 
						</p>

						<h4 class="purpHeader text-center">Deliverables</h4>
						<p class="text-center highFidText">
							High-fidelity prototype
						</p>
						<GradButton
							class="text-center"
							title="Go To XD Adobe.com"
							url="https://xd.adobe.com/view/729e9ab2-12f3-4c6f-9d05-5ce0775a0fbd-27cd/"
						/>
					</div>
				</div>
			</div>
		</div>
		<NextNav
			:class="{
				noNav: scrollPosition < 100,
				showNav: scrollPosition > 100
			}"
			next=""
			prev="/userResearch"
		/>
	</div>
</template>

<script>
import GradButton from "@/components/GradButton";
import NextNav from "@/components/NextNav";

export default {
	components: {
		GradButton,
		NextNav
	},

	data() {
		return {
			scrollPosition: null
		};
	},

	mounted() {
		window.addEventListener("scroll", this.updateScroll);
	},
	methods: {
		updateScroll() {
			this.scrollPosition = window.scrollY;
		}
	},
	destroy() {
		window.removeEventListener("scroll", this.updateScroll);
	}
};
</script>

<style lang="scss" scoped>
.brandishApp {
	color: black;

	.noNav {
	}

	.showNav {
		position: fixed;
		bottom: 0;
		opacity: 0.99;

		animation: fadeIn 1s;
		-webkit-animation: fadeIn 1s;
		-moz-animation: fadeIn 1s;
		-o-animation: fadeIn 1s;
		-ms-animation: fadeIn 1s;
	}

	@keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-moz-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-webkit-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-o-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-ms-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	.close {
		position: absolute;
		right: 20px;
		top: 20px;
		height: 32px;
		cursor: pointer;

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
		padding-bottom: 100px;
	}
	
	#lessons {
		padding-top: 30px;
	}
	
	#problemContainer {
				padding-top: 0;
				padding-bottom: 0;
			}
			
	.problemText {
		padding-top: 50px;
		padding-bottom: 50px;
	}

	.projectContainers {
		padding-top: 100px;
		padding-bottom: 100px;

		#macImg {
			margin-top: -260px;
			margin-bottom: 100px;
		}

		.textSection {
			h4 {
				font-size: 14px;
				letter-spacing: $tracking250;
			}
			.subtitle {
				text-transform: uppercase;
				margin: 60px 0 30px 0;
				font-size: 20px;
			}

			.firstHeader {
				margin: 40px 0 30px 0;
			}

			h2 {
				font-size: 50px;
				font-family: "Made";
				color: $header;
			}
			
			#problemHeader {
				margin-bottom: 35px;
			}
			
			.smallerHeader {
				font-size: 45px;
			}

			p {
				font-size: 16px;
			}

			figcaption {
				color: $bodyGray;
				padding-bottom: 40px;
			}
			
			.embed-responsive embed-responsive-4by3 {
				padding-top: 30px;
			}

			.purpHeader {
				font-size: 18px;
				background-image: linear-gradient(
					to right,
					$gradDark,
					$gradLight
				);
				background-clip: text;
				-webkit-text-fill-color: transparent;
				-moz-text-fill-color: transparent;
				text-transform: uppercase;
				margin-top: 25px;
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

@media only screen and (min-width: 320px) {
	.brandishApp {
	
			#firstProjContainer {
				padding-bottom: 200px;
			}
			
			#problemContainer {
				padding-top: 100px;
				padding-bottom: 100px;
			}
			
			.problemText {
				padding-top: 0px;
				padding-bottom: 0px;
			}
			
			.projectContainers {
			#macImg {
				margin-top: -250px;
				margin-bottom: 100;
			}
			}
		
	}
}


@media only screen and (min-width: 768px) {
	.brandishApp {
	
			p {
				font-size: 16px;
			}
			
		.projectContainers {
			#macImg {
				margin-top: -400px;
				margin-bottom: 0;
			}
			

			.textSection {
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
	.brandishApp {
		.projectContainers {
			#macImg {
				margin-top: -300px;
				margin-bottom: 100px;
			}
			
		.mainText p {
				width: 600px;
				margin: 0 auto;
			}
			
		.highFidText {
				margin-bottom: 2rem;
			}
			
		
		}
	}
}
</style>
