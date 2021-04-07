<template>
	<div>
		<div class="container-fluid jumboContainer">
      <div class="row">
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
      </div>
		</div>

		<SecondaryNav />

    <!-- Main Content -->
    <!-- First Section -->
    <div class="container-fluid main">
      <div class="row">
        <div class="container infoHolder">
          <div class="row">
            <div class="col-12 col-md-6 align-self-center textSection">
              <h4>Utah Valley University</h4>
              <h2>Website Redesign</h2>
              <span>-</span>
              <p>Data analysis and next steps for improving the Telehealth user experience.</p>
            </div>
            <div class="col-12 col-md-6">
              <img class="img-fluid" src="@/assets/images/macGrid.png" alt="image of mac computer">
            </div>
          </div>
        </div>

        <div class="container-fluid infoHolder infoColor">
          <div class="container">
            <div class="row">
              <div class="col-12 col-md-6 order-2 align-self-center textSection text-md-right">
                <h4>Utah Valley University</h4>
                <h2>User Research</h2>
                <span>-</span>
                <p>Data analysis and next steps for improving the Telehealth user experience.</p>
              </div>
              <div class="col-12 col-md-6 order-1">
                <img class="img-fluid" src="@/assets/images/macGrid.png" alt="image of mac computer">
              </div>
            </div>
          </div>
        </div>
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
	color: black;
  height: 3000px;

  .infoHolder{
    padding: 60px 0;

    .textSection{
      padding-left: 50px;
      padding-right: 50px;      
    }
  }

  .infoColor{
    background-color: yellow;
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

  .main {
    .infoHolder{
      .textSection{
        padding-left: 15px;
        padding-right: 15px;      
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
