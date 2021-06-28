<template>
	<div>
		<Nav where="top" shadow="0px 8px 10px -10px #999" />
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
					<a href="#secondNav"
						><button id="workBtn">View My Work</button></a
					>
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

		<SecondaryNav id="secondNav" @execChangeComp="onClickChild" />
		<!-- <Digital /> -->
		<component :is="dynamicComponent"></component>

		<Socials style="marginBottom: 40px;" />
		<Nav where="bottom" shadow="0px 8px 10px 6px  #999" />
	</div>
</template>

<script>
import SecondaryNav from "@/components/SecondaryNav";
import Socials from "@/components/Socials";
import GradButton from "@/components/GradButton";
import Nav from "@/components/Nav";
import Digital from "@/components/Digital";
import Print from "@/components/Print";
import Gallery from "@/components/Gallery";
export default {
	components: {
		SecondaryNav,
		Socials,
		GradButton,
		Nav,
		Digital,
		Print,
		Gallery
	},

	data() {
		return {
			comp: ""
		};
	},

	methods: {
		onClickChild(value) {
			this.comp = value; // someValue
		}
	},

	computed: {
		dynamicComponent() {
			if (this.comp == "Print") {
				return "Print";
			} else if (this.comp == "Gallery") {
				return "Gallery";
			} else {
				return "Digital";
			}
		}
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
		top: 70px;
		width: 100%;
		padding: 0 4.5%;

		#title {
			font-size: 16px;
			letter-spacing: $tracking250;
			margin-bottom: 20px;
		}

		#name {
			margin: 10px 0;
			font-family: "Made2";
			font-size: 45px;
			text-transform: uppercase;
			line-height: 40px;

			#firstName {
				letter-spacing: #{(25/1000)}em;
				margin-right: 10px;
			}
		}

		#description {
			//display: none;
		}
		#workBtn {
			margin-top: 15px;
			color: white;
			border: 2px solid white;
			text-transform: uppercase;
			background: none;
			padding: 10px;
			transition: 0.4s;

			&:hover {
				background-color: rgba(255, 255, 255, 0.2);
			}
		}
	}
}

@media only screen and (min-width: 375px) {
	.jumboContainer {
		.infoText {
			top: 120px;
      padding: 0 5%;

			#name {
				margin: 30px 0;
        font-size: 50px;
			}

			#description {
				display: block;
				width: 90%;
			}
		}
	}
}

@media only screen and (min-width: 576px) {
	.jumboContainer {
		.jumboImage {
			margin-top: -320px;
		}

    .infoText {
			width: 80%;
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
				margin: 50px 0 35px 0;
				font-size: 70px;
				line-height: 50px;
			}
			#description {
				font-size: 25px;
			}
			#workBtn {
				margin-top: 30px;
				font-size: 18px;
				padding: 15px;
			}
		}
	}
}
</style>
