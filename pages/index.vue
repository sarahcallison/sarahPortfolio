<template>
	<div>
		<div class="container-fluid p-0 jumboContainer">
			<div class="infoText">
				<h4 id="title">Digital Designer</h4>
				<h1 id="name">Sarah Callison</h1>
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

			<SecondaryNav />

			<div class="main">
				<h1>test</h1>
			</div>
		</div>
	</div>
</template>

<script>
import SecondaryNav from "@/components/SecondaryNav";
export default {
	components: {
		SecondaryNav
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
		}
		#name {
			margin-top: 10px;
		}
		#description {
			margin-top: 10px;
		}
		#workBtn {
			margin-top: 15px;
			color: white;
			border: 2px solid white;
			text-transform: uppercase;
			background: none;
			padding: 10px 15px;
		}
	}
}

.main {
	height: 6000px;
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
			#title {
				font-size: 16px;
			}
			#name {
				margin-top: 20px;
			}
			#description {
				margin-top: 20px;
			}
			#workBtn {
				margin-top: 30px;
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
</style>
