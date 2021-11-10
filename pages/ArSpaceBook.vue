<template>
	<!-- websiteRedesign Content -->
	<div class="arSpaceBook">
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
					<h2>AR Space Book</h2>
					<div class="gradLine"></div>
					<p>
						May 2021
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
								src="@/assets/images/digital/arSpaceBookHeader.png"
								alt="image of floating astronaut"
							/>
						</div>
						<div
							class="col-12 col-md-7 col-lg-6 order-md-1 align-self-center  textSection problemText"
						>
							<h2 id="problemHeader">The Problem</h2>
							<p>
								How can we combine the digital and physical world to 
								create a deeper layer of engagement? Augmented reality 
								(AR) is one answer. In my Immersive Authoring II course, 
								my group was tasked with enhancing 
								a print book which features at least eight AR features. 
								We worked in teams of two English students and two 
								Digital Media students to write, design, and print a 
								book on a topic of our choice. I was responsible for 
								creating the AR features and the cover designs. 
								
							<br />
							<br />
							</p>

							<h4 class="purpHeader">Deliverables</h4>
							<p class="highFidText">Printed book</p>
							<GradButton
								title="View PDF of Book"
								url="/printPages.pdf"
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
							<h2 class="text-center" id="solutionHeader">The Solution</h2>
							<h4 class="text-center subtitle firstHeader">
								Research
							</h4>
							
								<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/print/book.jpg"
								alt="image of printed book"
							/>
							<figcaption class="text-center mt-3">
								A telescope view of the night sky with a parallax effect
							</figcaption>

							<p class="text-left">
								
								Our topic needed to be something that the 
								English students could write persuasively 
								about. Since the Perseverance rover was scheduled to 
								be launched during the course of our project, 
								we considered the question of whether a 
								manned mission to Mars would be feasible in 
								light of concerns about the health of the 
								astronauts. The English students would argue 
								that these missions should be pursued due to 
								advances in medical and nutritional science. 
								The Digital Media students would create 
								graphics and AR features that enable our 
								users to experience what it might be like 
								to be on a long-term mission in space. 

								<br />
								<br />
								I researched dozens of NASA articles/videos 
								and made note of elements that surprised me 
								or seemed significant to me. As I reviewed 
								NASA’s content, I asked myself, how could 
								this cool fact be translated into an AR experience? 
							</p>


							<h4 class="text-center subtitle">Ideation</h4>
							

							<p>
								Our professor asked us to make a list of 
								possible AR features. This turned out to 
								be a great way to brainstorm. To meet 
								project requirements, our book was to 
								include four unique features (up to two of the same type of feature) 
								and at least several complex features&#8212;an 
								original infographic, for example. After 
								reviewing the capabilities of ZapWorks, 
								our designated AR-building platform, 
								Abby and I talked through our lists and 
								picked these features:
								<br />
								<br />
								
								<ul>
								<li>Face tracking with a 3D model of an astronaut helmet</li>
								<li>360 image of the surface of Mars</li>
								<li>A sampling of space shuttle flight decks and launches in 360</li>
								<li>An original animation about nutrition in space</li>
								<li>An original interactive infographic about some of the common problems astronauts encounter in space</li>
								<li>An original animated timeline about the food and nutrition history of space travel</li>
								<li>A 3D model of the Perseverance rover</li>
								<li>A telescope view of the night sky with a parallax effect (original feature created in ZapWorks)</li>
							</ul>
							
							
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/print/parallax.png"
								alt="image of night sky through telescope"
							/>
							<figcaption class="text-center mt-3">
								A telescope view of the night sky with a parallax effect
							</figcaption>
							</p>
							
							<p>
							Whenever I don’t know where to start, I start 
							sketching. It took several iterations to 
							incorporate all of the key points from my NASA 
							research, but then I was ready to find assets 
							for my components of the project.
							</p>
							
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/print/infographicSketch.jpg"
								alt="image of sketches"
							/>
							<figcaption class="text-center mt-3">
								A sketch of the interactive infographic feature
							</figcaption>
							

							<h4 class="text-center subtitle">Ui Design</h4>
						

							<p>
								Our goal was to enable the reader to experience
								what long-term space travel might be like. So we 
								chose a minimalistic style for the book design and let the beautiful 
								images from NASA speak for themselves. 
							</p>
							
								<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/print/rocket.png"
								alt="image of rocket launch"
							/>
							<figcaption class="text-center mt-3">
								One of NASA's image assets
							</figcaption>
								
							<p>
								One of the key concepts in the book’s copy is 
								that a manned mission to Mars, though many 
								years from becoming a reality, should be 
								pursued. Since the idea of a manned mission to 
								Mars remains somewhat surreal, I incorporated 
								surreal elements in the front and back cover 
								designs. 
							</p>
							
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/print/front.jpeg"
								alt="image of front book cover"
							/>
							<figcaption class="text-center mt-3">
								The front cover
							</figcaption>
							
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/print/back.jpeg"
								alt="image of back book cover"
							/>
							<figcaption class="text-center mt-3">
								The back cover
							</figcaption>
							
							<h4 class="text-center subtitle">
								Problem Solving
							</h4>
						

							<p>
								The biggest obstacle we faced was the timeline. 
								The final draft of the copy was due only a few 
								days before the print deadline. We had an early 
								version of the copy which included about half 
								of the required content. We had all of the main 
								ideas, but didn’t have the final version until 
								the day it was due.
								<br />
								<br />
								I intended to prepare as much of the AR content 
								as I could before receiving the final draft. 
								Originally, I planned to create the ZapWorks 
								projects, download the zap codes (like a QR code) 
								to include in the print design, and upload the AR 
								content after the book was sent to print. In 
								reviewing ZapWorks, I learned that the platform 
								provides three tools, or project types, to build 
								AR experiences: Designer, Studio, and UniversalAR. 
								The ability to switch project types in ZapWorks 
								has been deprecated so changing the project type 
								invalidates the zap code. 
								</p>
								
								<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/print/zapCode.png"
								alt="image of zap code"
							/>
							<figcaption class="text-center mt-3">
								The instructions we included at the beginning of the book
							</figcaption>
							
								<p>
								This meant that I didn’t have very much time to 
								figure out if the features I planned would work 
								with the project type we selected for each ZapCode. 
								As a work around, I created dummy content to upload 
								to test the project types, which made for more work, 
								but ensured the success of our AR features. 
								<br />
								<br />
								Since ZapWorks was a new platform to both me and my 
								partner, most of the time I spent creating the AR 
								features was invested in testing the experience on 
								both Android and iOS devices. 
								<br />
								<br />
								<br />
								<br />
							</p>

							


							
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
							
							Perhaps the most meaningful AR interaction is 
							featured in the interactive infographic about 
							issues that astronauts experience in space. When 
							the user taps on the plus icon over the astronaut’s 
							heart, popup text explains how astronauts are at-risk 
							for experiencing psychological and cognitive 
							difficulties from being isolated in space. As this text
							appears, the astronaut image desaturates and fades in 
							opacity. Next, an explanation about how astronauts can 
							combat these issues appears, and the astronaut image 
							resaturates and increases to 100% opacity. This 
							interaction was especially meaningful due to the COVID 
							lockdowns and gathering restrictions. 
							</p>
							
							<div class="centerImg">
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/print/astronaut.png"
								alt="image of zap code"
							/>
							<figcaption class="text-center mt-3">
								The astronaut feature in the interactive infographic
							</figcaption>
							</div>

							<p class="text-left">
							To put it simply, I’ve learned to start early and test 
							often, and that a finished product is most satisfying 
							when it adds meaning for the user.
						</p>

						<h4 class="purpHeader text-center">Deliverables</h4>
						<p class="text-center highFidText">
							Printed book
						</p>
						<GradButton
							class="text-center"
							title="View PDF of book"
							url="/printPages.pdf"
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
			next="/GraphicDesign"
			prev=""
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
.arSpaceBook {
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

	.centerImg {
		position:relative;
		height:100%;
		width:100%;
		text-align: center;
	}
	
	#firstProjContainer {	
		padding-bottom: 100px;
	}
	
	#solutionHeader {
		font-size: 45px;
	}
	
	#lessons {
		padding-top: 30px;
	}
	
	#problemContainer {
		padding-top: 0;
		padding-bottom: 0;
	}
	
	.problemText {
		padding-top: 75px;
		padding-bottom: 50px;
	}
	
	
	#problemHeader {	
		margin-bottom: 35px;
		font-size: 45px;
		}


	.projectContainers {
		padding-top: 100px;
		padding-bottom: 100px;

		#macImg {
			margin-top: -200px;
			margin-bottom: 100px;
		}
		
		.smallerHeader {
			font-size: 45px;
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
				margin: 40px 0;
			}

			h2 {
				font-size: 50px;
				font-family: "Made";
				color: $header;
			}

			p {
				font-size: 16px;
			}

			figcaption {
				color: $bodyGray;
				padding-bottom: 40px;
				font-size: 14px;
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
	.arSpaceBook {
	
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
				margin-top: -200px;
				margin-bottom: 100;
			}
			}
		
	}
}

@media only screen and (min-width: 768px) {
	.arSpaceBook {
		.projectContainers {
			#macImg {
				margin-top: 0;
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
	.arSpaceBook {
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
