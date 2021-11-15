<template>
	<!-- websiteRedesign Content -->
	<div class="websiteRedesign">
	<!--
		<div @click="$router.go(-1)" class="close">
			<img
				id="closeImg"
				src="@/assets/images/closeHover.png"
				src2="@/assets/images/close.png"
			/>
		</div>
		-->
		<div>
		<router-link to="Digital">
			<img
				id="closeImg"
				src="@/assets/images/closeHover.png"
				src2="@/assets/images/close.png"
		</router-link>
		</div>
		<!-- First Section -->
		<div class="container projectContainers" id="firstProjContainer">
			<div class="row">
				<div class="col-12 align-self-center textSection">
					<h4>UTAH VALLEY UNIVERSITY</h4>
					<h2>Website Redesign</h2>
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
								src="@/assets/images/digital/mac.png"
								alt="image of mac computer"
							/>
						</div>
						<div
							class="col-12 col-md-7 col-lg-6 order-md-1 align-self-center  textSection"
						>
							<h2 id="problemHeader">The Problem</h2>
							<p>
								When I joined the Academic Tutoring team, the visual presence of the 
								department fit the persona of a staid academic office—sedate, respectable, 
								and unadventurous. To align the department’s appearance with its forward-thinking 
								mission, a new brand identity and an updated website were in order.
								<br />
								<br />
								My role in this project was responsible for all UX/UI aspects; I was a UX team of one.
							</p>

							<h4 class="purpHeader">Deliverables</h4>
							<p class="highFidText">High-fidelity prototype (prototype link may load slowly)</p>
							<GradButton
								title="View Prototype"
								url="https://xd.adobe.com/view/f7dd9dec-1211-468d-aee0-bd9292267f87-a28e/"
								target="blank"
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

							<p class="text-left">
								The research phase of this project progressed quickly. 
								The director provided me with a set of low-fidelity 
								wireframes to give me an idea of what he would like to 
								see on the new site. I was also given body copy which 
								determined what content would go on each page. 
								<br />
								<br />
								Before I was hired, I met 
								with a tutor from Academic Tutoring multiple times during 
								an academically-challenging semester. This helped me become 
								familiar with the user experience of a UVU student, our primary
								audience. I compiled and prioritized a list of requirements for each 
								of our user groups: students, UVU faculty and staff, and 
								the Academic Tutoring staff. 
								<br />
								<br />

								One of the key requirements was that the style of our website be 
								consistent with both Academic Tutoring’s and UVU’s brand identity. 
								As one of 60+ departments within UVU, our new identity needed to 
								represent the department in a way that was both recognizable and 
								unique, but stayed true to UVU’s design standard. A careful review 
								of UVU’s style guide provided the guidance I needed to meet the 
								university’s design constraints. Staying consistent with our brand 
								required a little more effort.  
							</p>

							<h4 class="text-center subtitle">Ideation</h4>
							

							<p>
								Since the website was my first assignment as an intern, I hadn’t 
								had time to develop a new brand identity for Academic Tutoring. It 
								was decided by the team that I would mock up a landing page in several 
								styles so we could determine which style best communicates our voice. 
								To get the ideas flowing, the director and I scoured the internet for 
								examples. Websites with an open, creative feel and sites that featured hand drawn 
								elements stood out as examples that might best match Academic Tutoring’s
								mission. 
								<br />
								<br />
								Academic Tutoring’s mission statement:
								<br />
								<br />
								<i>
								Academic Tutoring embraces the power of students helping
								students and supports all individuals—regardless of identity,
								culture, point of view, or background—as they navigate the
								challenges associated with their educational goals. With a
								focus on gateway major courses, certified student employees
								work alongside each student to foster serious academic
								exploration and inspire lifelong learning.
								</i>
								<br />
								<br />
								When I presented mock ups of the landing page in both a hand 
								drawn and a vector-based style, the team unanimously agreed 
								that the more relaxed appearance of the hand drawn style represents 
								who we are. Academic Tutoring is meant to be an inclusive, 
								creative space where students can make mistakes freely without 
								negative consequences. Using a hand-drawn style moves away from 
								the style of traditional and institutional academic websites and communicates 
								that we have an atmosphere where students have space to grow. 
								<br />
								<br />
								These design decisions should have been verified with user testing 
								but—more on that later.
							</p>

							<h4 class="text-center subtitle">Ui Design</h4>
							
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/landingPage.png"
								alt="image of the Academic Tutoring home page"
							/>
							<figcaption class="text-center mt-3">
								Academic Tutoring's new landing page
							</figcaption>

							<p>
								Each semester, Academic Tutoring hosts an event called Studypalooza. 
								The signage for this event, which was created before I joined the team, 
								features a background texture made of school-related icons. Since this 
								event garnered campus-wide attention in the past, the director requested 
								that I incorporate the icon motif in the new website.
								<br />
								<br />

								A casual script font was used in combination with hand-drawn icons and 
								accents. The Jaeggers typeface was selected over other script fonts 
								because, as the font’s creator, Inspiratype, said, “It’s made to 
								resemble hand scratches, so it looks like a natural style—like your own
								hand scratches.” The use of this typeface along with hand-drawn accents, 
								like an asterisk, resembles hand-drawn notes that a student might make 
								as they are exploring new concepts. Clear hierarchy 
								and clean designs add professionalism to this whimsical style.
								<br />
								<br />
								The “base” of each icon was outsourced to save time. Each icon was then 
								edited to maintain consistency between the icons throughout the site. 
								Sparkles were added to reflect our creative, open atmosphere.
								<br />
								<br />
								UVU’s primary color palette is forest green, black, white and metallic silver. 
								Per UVU’s style guide, a complimentary color palette of lighter greens can be 
								used with discretion in addition to the primary palette. 
								<br />
								<br />
								Since UVU uses pre-coded elements, we were somewhat constrained by what we 
								could include in the UI. Custom elements mean more work for the developer 
								and are not always approved. We edited these elements to match our style by
								adding hand drawn accents and using a lighter UVU-approved green. We also had to modify 
								some of our font selections at our developer's request and use UVU-approved fonts like Raleway that were similar 
								to the fonts we used in our brand identity. 
								</p>
								
								<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/customize.png"
								alt="image of web page"
							/>
							<figcaption class="text-center mt-3">
								Customized pre-configured elements on the Peer Tutoring page
							</figcaption>
							
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/customize2.png"
								alt="image of web page"
							/>
							<figcaption class="text-center mt-3">
								We used an original image to customize content on the Supplemental Instruction page
							</figcaption>
							
							

							<h4 class="text-center subtitle">Problem Solving</h4>
							

							<p>
								It can be difficult for a designer to view their own designs objectively. I 
								proposed user testing as a means of evaluating our designs to the director, but 
								he wanted to postpone testing until the website and other upcoming projects were 
								completed. After getting feedback from a few friends and family members, it was 
								clear that the amount of content on the subpages (Peer Tutoring or Online 
								Tutoring) made the site feel cluttered—important information was harder to find. 
								Some content was repeated on each page to maintain consistency, which resulted 
								in more clutter.
								<br />
								<br />
								Since this was my first assignment of my first design position, I was hesitant to push the
								issue. The director has a great eye for design and subscribes to high-quality 
								design content. Since he didn’t think user testing was necessary, I decided to 
								leave this issue alone.
								<br />
								<br />
								A few months later, I still felt strongly that we needed to get feedback from our users. I drafted 
								a <a target="blank" href="/usabilityTestPlan.pdf">usability test plan</a> 
								and researched several testing 
								platforms we could use. I pitched my plan to the director and this time, he was on board. 
								I contacted our developer about adding the code. The developer informed us 
								that UVU already had user testing protocols in place, but their web team was not
								able to create a test for us at that time due to a high workload. When I checked 
								with my director again after a couple of months, he said that he liked the website 
								how it was and didn’t want to complete testing at that time. 
								<br />
								<br />
								After another month or so, several team members provided feedback about the website 
								which was in line with feedback I had received previously: the site felt cluttered 
								and some of the content was geared toward mid-management level positions such as 
								faculty or staff, rather than students. I communicated their feedback to the director.
								By that time, I’d had some successes as an intern with other projects and felt more 
								confidence in my evaluation of our website. User testing was not approved, but a 
								second iteration of the site was given a green light.
							</p>

						

							<h4 class="text-center subtitle">
								Iteration
							</h4>
							

							<p>
								The second iteration is a streamlined version of the first iteration. 
								Repetitive content was removed. Content that was geared toward faculty or staff was 
								moved from the student pages to the Faculty Resources page or 
								deleted from the site. Any content which was placed above essential information about 
								our services, such as hours and locations, was removed or placed lower on the page so 
								that the most important information was the first content to be seen by the user. 
								<br />
								<br />
								I would have chosen to remove some of the heavier green elements, such as the drop-down
								tiles featured on the Supplemental Instruction page, to make the UI feel cleaner. The team
								preferred to keep these elements in the second iteration. 
								<br />
								<br />
								I was able to gather some user feedback by external means. A project for one of my classes required 
								us to perform three rounds of user testing on an app or a website. I submitted a mockup 
								similar to Academic Tutoring’s website—one with a combination of images and icons, and 
								one with only icons. Feedback from 10 UVU students between the ages of 18 - 35 indicated
								that the icons-only mockup was easier to navigate and felt more on-trend with current 
								designs. Based on that feedback, we removed all of the images from the website. 
								</p>
								
								<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/iconsOnly.png"
								alt="image of web page"
							/>
								<figcaption class="text-center mt-3">
								Icons on the landing page
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
							I learned so many valuable lessons as an intern at Academic Tutoring 
							that it is difficult to pick only a few. The most important lessons 
							I learned were these:

							<br />
							<br />

							If I’m stuck on a particular aspect of a design, it’s time for me to talk
							to the users—or review what they’ve already told me. User feedback 
							illuminates the problems with the greatest negative impact on the user 
							experience. If the fix for these problems is not readily apparent, which 
							it rarely is, feedback from users provides clues to the solution. 
							<br />
							<br />
							When my pitch for user testing wasn’t approved on multiple occasions, I 
							realized that it was my pitch that needed to change rather than the director. 
							A presentation of how user testing could improve the bottom line for Academic 
							Tutoring rather than a discussion of design principles may have been an 
							effective strategy.
							<br />
							<br />
							The last high-fidelity prototype I sent to the web developer was completed in 
							June 2021. View the <a href=https://uvu.edu/academictutoring target="blank">live 
							website</a> for Academic Tutoring. 
						</p>

						<h4 class="purpHeader text-center">Deliverables</h4>
						<p class="text-center highFidText">
							High-fidelity prototype (prototype link may load slowly)
						</p>
						<GradButton
							class="text-center"
							title="View Prototype"
							url="https://xd.adobe.com/view/f7dd9dec-1211-468d-aee0-bd9292267f87-a28e/"
							target="blank"
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
			next="/userResearch"
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
.websiteRedesign {
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
	padding-top: 75px;
	padding-bottom: 50px;
	}
	
	
#problemHeader {	
	margin-bottom: 35px;
	font-size: 45px;
	}
	
	#solutionHeader {
	font-size: 45px;
	}


	.projectContainers {
		padding-top: 100px;
		padding-bottom: 100px;

		#macImg {
			margin-top: -200px;
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
			
			a {
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
	.websiteRedesign {
	
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
	.websiteRedesign {
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
	.websiteRedesign {
		.projectContainers {
			#macImg {
				margin-top: -200px;
				margin-bottom: 100px;
			}
			
			.mainText p {
				width: 60%;
				margin: 0 auto;
			}
			
			.highFidText {
			margin-bottom: 2rem;
			}
		}
	}
}

</style>
