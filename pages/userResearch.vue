<template>
	<!-- userResearch Content -->
	<div class="userResearch">
		<div @click="$router.go(-1)" class="close">
			<img
				id="closeImg"
				src="@/assets/images/closeHover.png"
				src2="@/assets/images/close.png"
			/>
		</div>
		<!-- First Section -->
		<div class="container projectContainers">
			<div class="row">
				<div class="col-12 align-self-center textSection">
					<h4>UTAH VALLEY UNIVERSITY</h4>
					<h2>User Research</h2>
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
							<picture>
								<source
									media="(min-width:992px)"
									srcset="@/assets/images/map.png"
								/>
								<img
									src="@/assets/images/mapMobile.png"
									alt="Image of map"
									class="img-fluid"
								/>
							</picture>
						</div>
						<div
							class="col-12 col-md-7 col-lg-6 order-md-1 align-self-center textSection problemText"
						>
							<h2 id="problemHeader">The Problem</h2>
							<p>
								The onset of the COVID-19 pandemic forced medical providers 
								to rapidly adopt Telehealth in 2020. An expected three-year 
								timeframe for remote Telehealth implementation was completed 
								in an unprecedented three weeks. Improving the user experience 
								of remote digital healthcare became a global priority. 
							<br />
							<br />
								My senior project group was tasked with improving the Telehealth 
								experience for medical providers. We were responsible for the research phase
								of the project. I was responsible for creating the interactive infographic, writing
								the survey and interview questions, and writing the academic research report.
							</p>
							

							<h4 class="purpHeader">Deliverables</h4>
							<p class="highFidText">Interactive infographic<br>
							<a href="/academicResearch.pdf" target="blank">Academic research report</a>
							</p>
							
							<GradButton
								title="View interactive infographic"
								url="https://sarahcallison.github.io/"
								target="blank"
							/>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- Third Section -->
		<div class="container-fluid projectContainers">
			<div class="row ">
				<div class="container">
					<div class="row justify-content-md-center">
						<div class="col-12 col-md-10 align-self-center px-4 px-md-0 textSection mainText">
							<h2 class="text-center" id="solutionHeader">The Solution</h2>
							<h4 class="text-center subtitle firstHeader">
								Research
							</h4>
							
							
								<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/cover.png"
								alt="image of interactive infographic"
							/>
							<figcaption class="text-center mt-3">
								Interactive infographic of survey results
							</figcaption>
							
							<p class="text-left">
								<br />
								<br />
								We began the research phase of this project by completing a review of 
								current Telehealth research. As existing literature focuses primarily 
								on provider acceptance of the use of Telehealth in medical practice, 
								exploratory research to pinpoint user issues experienced by both the 
								provider and the patient was needed. Identifying the underlying cause 
								of these issues would serve as a guide for further research and, in 
								turn, illuminate potential solutions for improving the Telehealth 
								user experience. 
								<br />
								<br />
								After speaking with faculty advisors from the Digital Media and Public 
								and Community Health departments, we came up with these questions to 
								guide and focus research tasks: 
								<br />
								<ol>
								<li>What does a provider need to comfortably take care of patients remotely?</li>
								<li>How are current digital solutions meeting or not meeting provider needs?</li>
								<li>What gaps in patient care need to be filled?</li>	
								</ol>
								A focus on providers in the first phase of our project would serve to 
								guide future research into how issues in the provider user experience 
								impact patient outcomes. 
								</p>
								
								<img
									class="img-fluid px-0 mt-5"
									src="@/assets/images/digital/apps.png"
									alt="image of app icons"
								/>
								<figcaption class="text-center mt-3">
									Apps reviewed on Google Play and Apple Store on 9/17/2020
								</figcaption>
								
								<p>
								One of the issues that was discussed in the early stages of this research 
								is poor Internet connectivity. Developing a medical resource app that would 
								be available offline was considered. In an audit of current medical resource
								technology, 16 apps with user reviews of four stars or higher were identified, 
								seven of which are available offline. We refocused our research activities on 
								how to improve existing digital solutions. 
								<br />
								<br />
								In a review of the literature regarding design research methodologies, two 
								concepts were emphasized repeatedly by UX researchers: the importance of 
								variety in obtaining valid results and the use of research as a tool to fuel 
								the design process. Instead of designing a perfect quantitative study with a 
								large N, researching a diverse set of circumstances can save time, be cost-effective,
								and deliver useful insights. Sample size is important; however, a large sample 
								of very similar participants may produce results that are not representative of 
								the target audience as a whole. For results that are externally valid, a diverse 
								set of users and conditions should be tested.
								<br />
								<br />
								Since time is frequently a limitation, designing a perfect study may not be 
								feasible. Researchers from the Nielsen Norman Group, a premier resource in UX 
								research and design, say that it is most important to start somewhere and keep 
								learning. Research activities should be planned and executed to inform the next 
								step in the design process.
							</p>

							<h4 class="text-center subtitle">Methods</h4>
							

							<p>
								For a more accurate analysis of the Telehealth provider experience, quantitative 
								and qualitative user research methods were utilized. To first identify, and then 
								quantify provider user experience issues, we created a 10-question, multiple choice 
								survey using the Qualtrics platform. This survey was designed to be taken by providers 
								in approximately two minutes. Question topics included how digital solutions are used 
								by providers in daily practice and what issues are encountered during digital solutions 
								usage. 
								<br />
								<br />

								The survey link was sent to twenty healthcare clinics and a teletherapy organization, 
								all located within the United States&#8212;one respondent was located in Europe.
								Additionally, the survey was advertised on the personal social media channels of the 
								researchers. No incentive was offered for completion of the survey. 
								<br />
								<br />
								User interviews were utilized to gather qualitative data. The final question of the 
								survey asked providers to share their email address if they would be willing to answer 
								additional questions regarding their Telehealth user experience. The SignUp Genius 
								platform was used to schedule interview time slots. Providers were invited in an email
								to sign up for a 30-minute remote interview which would take place on Zoom. Interview 
								invitations included a digital recording release form. 
								<br />
								<br />
								Interview questions were designed to probe for the underlying cause of Telehealth user 
								experience issues without leading the interviewee to give expected answers. Providers 
								were asked to identify which user experience issue had the greatest impact on their
								ability to provide medical care. Additional questions asked providers to describe the 
								functionality of digital solutions given an ideal world. A script was used to standardize
								each interview and to avoid variations in interview questions that may have biased the 
								responses.
							</p>

							<h4 class="text-center subtitle">Results</h4>
							

							<p>
								49 clinicians in 17 different medical professions completed the survey. Of the 49 
								respondents, 58.5 percent utilize a digital solution to find information regarding 
								best practice at least once per day. 26.8 percent of the survey sample uses digital 
								solutions for this purpose multiple times per day. 
								</p>
								
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/graph2.png"
								alt="image of graph"
							/>
							<figcaption class="text-center mt-3">
								Provider use of digital solutions
							</figcaption>
								
								<p>
								The frequency in use of digital solutions as a resource for medical information was 
								not surprising. However, lack of Internet connectivity or a digital solution “not 
								working” occurred within our sample population less frequently than was expected. 
								Issues were experienced only several times per month by 43.9 percent of our sample. 
								Another 43.9 percent never experienced these issues. 
								</p>
								
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/graph4.png"
								alt="image of graph"
							/>
							<figcaption class="text-center mt-3">
								Internet connectivity issues experienced by providers
							</figcaption>	
								
								<p>
								Although these issues were experienced relatively infrequently, 61 percent of our 
								respondents indicated that their ability to provide care was impacted when their 
								Internet or digital solution was not working. 
								</p>
								
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/graph6.png"
								alt="image of graph"
							/>
							<figcaption class="text-center mt-3">
								Impact of issues on provider's ability to provide care
							</figcaption>	
								
								<p>
								Additional issues were experienced as providers navigated the UI of their digital 
								solution. 34 percent of our sample stated that their digital solution was difficult 
								to use or navigate. 
								</p>
								
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/graph3.png"
								alt="image of graph"
							/>
							<figcaption class="text-center mt-3">
								Breakdown of issues experienced by providers
							</figcaption>	
								
								<p>
								View an <a href="https://sarahcallison.github.io/" target="blank">interactive infographic</a> of the survey results. 
								<br />
								<br />
								One of the proponents of user experience research is that three to five percent of 
								participants in a usability study identify 85 percent of the usability issues. Of 
								the 49 respondents, 88 percent were willing to participate in a user experience 
								interview, however, only six providers responded to our interview invites. Interviews 
								were conducted with each of the six providers who practice in the following care areas: 
								nursing and nurse education, speech therapy, psychology, respiratory therapy, and certified 
								nurse midwifery. 
								<br />
								<br />
								Although technical issues such as Internet 
								connectivity were less frequent than expected, 
								user experience issues were noted by each 
								provider during their interview. Three of the 
								user experience problems mentioned in the 
								interviews were identified by providers as having
								a significant impact on their ability to provide 
								care: difficulty with patient onboarding to 
								Telehealth technology, searchability or navigation 
								of digital solutions, and issues with charting, 
								such as a non-intuitive user interface in the 
								charting platform. 
							</p>

							<h4 class="text-center subtitle">Next Steps</h4>
						

							<p>
								This research did not focus on the patient 
								user experience or how issues experienced by 
								providers impact patient outcomes. Research that 
								explores the patient user experience and patient 
								outcomes is essential to prioritize the significance 
								of user experience issues and to guide future 
								research and design decisions. Direct observation of 
								user behavior in a field study may be useful in 
								avoiding response biases.
								<br />
								<br />
								Four provider personas were 
								created as a tool for future researchers. After 
								exploratory research based on the patient user 
								experience is completed, patient personas should 
								be utilized to guide the design process. Proposed 
								solutions of a chatbot and/or voicebot, and voice-enabled 
								search and charting will need to be re-evaluated based 
								on the results of patient user research. 
								</p>
								
							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/personas.png"
								alt="image of persona profile"
							/>
							<figcaption class="text-center mt-3">
								Provider personas based on our sample
							</figcaption>
								
								<p>
								Once research is completed, the design process 
								should include testing of both low- and high-fidelity 
								prototypes before building the design. User testing 
								of prototypes is essential to evaluate the validity 
								of design decisions. After the design is built, the 
								final step in the design process should include user 
								testing to identify any user experience issues. 
							</p>

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
							The user experience design process should be cyclical. 
							As technology and user needs evolve, additional research 
							and user testing is needed. With a multitude of tools and 
							resources available, designers are well-equipped to keep 
							pace with the rapidly changing Telehealth industry. 
						</p>

						<h4 class="purpHeader text-center">Deliverables</h4>
						<p class="text-center highFidText">Interactive infographic<br>
							<a href="/academicResearch.pdf" target="blank">Academic research report</a>
							</p>
							
							<GradButton
								class="text-center"
								title="View infographic"
								url="https://sarahcallison.github.io/"
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
			next="/brandishApp"
			prev="/websiteRedesign"
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
.userResearch {
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
	.userResearch {
	
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
		
	}
}

@media only screen and (min-width: 768px) {
	.userResearch {
		.projectContainers {
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
	.userResearch {
		.projectContainers {
			#macImg {
				margin-top: -300px;
				margin-bottom: 100px;
			}
			
			.mainText p {
				width: 600px;
				margin: 0 auto;
				
			.highFidText {
				margin-bottom: 2rem;
				}
			}
		}
	}
}

</style>
