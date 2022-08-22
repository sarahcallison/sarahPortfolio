<template>
	<!-- galleryMain Content -->
	<div class="galleryMain">
		<!-- First Section -->
		<div class="container galleryContainers" id="content-desktop">
			
			<!-- Illustrations -->
			<div class="row mt-5" id="illustrations">
				<div class="col-12 align-self-center textSection">
					<h2>Illustrations</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'mightyFicusThumbnail'
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/mightyFicusThumbnail.jpg"
							alt="image of illustration"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'physicsThumbnail'
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/physicsThumbnail.jpg"
							alt="image of illustration"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'valentines'
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/valentines.jpg"
							alt="image of illustration"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						url="@/assets/images/gallery/x.jpg"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'x'
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/x.jpg"
							alt="image of illustration"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						url="@/assets/images/gallery/protegeThumbnail.jp"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'protegeThumbnail'
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/protegeThumbnail.jpg"
							alt="image of illustration"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						url="@/assets/images/gallery/physicsThumbnail.jpg"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'lineAndShape'
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/lineAndShape.jpg"
							alt="image of illustration"
						/>
					</NuxtLink>
				</div>
			</div>
			
			<div class="row mb-5">
				<div class="col-12 align-self-center textSection">
					
					
			<!-- Motion Graphics -->
			<div class="row my-5">
				<div class="col-12 align-self-center textSection">
					<h2>Motion Graphics</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<a
						class="toImageNuxtLink"
						href="/gallery/interactiveDemo/index.html"
						target="blank"
					>
						<img
							class="img-fluid"
							src="~/assets/images/gallery/interactiveInfographicThumbnail.jpg"
							alt="image of original audrey hepburn website"
						/>
					</a>
					<p class="text-center  mt-3 px-1">
						Interactive infographic made in Hype
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/MoT1BNYbiR0`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/taglineVid.jpg"
							alt="image of girl studying"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Tagline animation created for UVU Academic Tutoring
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/e_RzIbMlBio`
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/compilation.jpg"
							alt="image of animated hot air balloon"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Compilation of short animations for UVU Academic Tutoring
					</p>
				</div>
			</div>
			<!-- Audio and Video -->
			<div class="row my-5">
				<div class="col-12 align-self-center textSection">
					<h2>Audio & Video</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/QZ3lzG6Ly-4`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/deeganOnFire.jpg"
							alt="image of Brian Deegan"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Video created in Photoshop - original footage &copy;
						Brian Deegan
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
				
				<a target="_blank"
						class="toImageNuxtLink"
						href="https://anchor.fm/brandishyourbrand"
					>
						<img
							class="img-fluid"
							src="~/assets/images/gallery/podcast.jpg"
							alt="image of audio equalizer"
						/>
					</a>
					<!--<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://anchor.fm/brandishyourbrand`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/podcast.jpg"
							alt="image of equalizer"
						/>
					</NuxtLink>
					-->
					<p class="text-center px-1 mt-3">
						Original podcast hosted on Anchor
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/TIEkFZpKKCg`
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/veggie.jpg"
							alt="image of lettuce in space"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Video edited in Premier Pro - original footage &copy;
						NASA
					</p>
				</div>
			</div>

			
		</div>
		
		<div class="container galleryContainers" id="content-mobile">
		
		

			<!-- Motion Graphics -->
			<div class="row my-5">
				<div class="col-12 align-self-center textSection">
					<h2>Motion Graphics</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<a
						class="toImageNuxtLink"
						href="/gallery/interactiveDemo/index.html"
						target="blank"
					>
						<img
							class="img-fluid"
							src="~/assets/images/gallery/interactiveInfographicThumbnail.jpg"
							alt="image of original audrey hepburn website"
						/>
					</a>
					<p class="text-center  mt-3 px-1">
						Interactive infographic made in Hype
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/MoT1BNYbiR0`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/taglineVid.jpg"
							alt="image of girl studying"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Tagline animation created for UVU Academic Tutoring
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/e_RzIbMlBio`
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/compilation.jpg"
							alt="image of animated hot air balloon"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Compilation of short animations for UVU Academic Tutoring
					</p>
				</div>
			</div>
			<!-- Audio and Video -->
			<div class="row my-5">
				<div class="col-12 align-self-center textSection">
					<h2>Audio & Video</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/QZ3lzG6Ly-4`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/deeganOnFire.jpg"
							alt="image of Brian Deegan"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Video created in Photoshop - original footage &copy;
						Brian Deegan
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
				
				<a target="_blank"
						class="toImageNuxtLink"
						href="https://anchor.fm/brandishyourbrand"
					>
						<img
							class="img-fluid"
							src="~/assets/images/gallery/podcast.jpg"
							alt="image of audio equalizer"
						/>
					</a>
					<!--<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://anchor.fm/brandishyourbrand`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/podcast.jpg"
							alt="image of equalizer"
						/>
					</NuxtLink>
					-->
					<p class="text-center px-1 mt-3">
						Original podcast hosted on Anchor
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/TIEkFZpKKCg`
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/veggie.jpg"
							alt="image of lettuce in space"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Video edited in Premier Pro - original footage &copy;
						NASA
					</p>
				</div>
			</div>

			<!-- Illustrations -->
			<div class="row mt-5">
				<div class="col-12 align-self-center textSection">
					<h2>Illustrations</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
				
						<img
							class="img-fluid"
							src="@/assets/images/gallery/valentines.jpg"
							alt="image of illustration"
						/>
					
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					
						<img
							class="img-fluid"
							src="@/assets/images/gallery/physicsThumbnail.jpg"
							alt="image of illustration"
						/>
				
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					
						<img
							class="img-fluid "
							src="@/assets/images/gallery/mightyFicusThumbnail.jpg"
							alt="image of illustration"
						/>
				
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					
						<img
							class="img-fluid"
							src="@/assets/images/gallery/x.jpg"
							alt="image of illustration"
						/>
			
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					
						<img
							class="img-fluid"
							src="@/assets/images/gallery/protegeThumbnail.jpg"
							alt="image of illustration"
						/>
			
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					
						<img
							class="img-fluid "
							src="@/assets/images/gallery/lineAndShape.jpg"
							alt="image of illustration"
						/>

				</div>
			</div>
		</div>
		
	</div>
</template>

<script>
import GradButton from "@/components/GradButton";
export default {
	components: {
		GradButton
	},
	data() {
		return {
			active: "digital"
		};
	}
};
</script>

<style lang="scss" scoped>
.galleryMain {
	color: black;
	
	#illustrations {
	
		margin-bottom: 50px;
	
	}

	.galleryContainers {
		padding-top: 100px;
		padding-bottom: 100px;

		.textSection {
			padding-left: 50px;
			padding-right: 50px;

			h4 {
				font-size: 15px;
				letter-spacing: $tracking250;
			}

			h2 {
				font-size: 50px;
				font-family: "Made";
				color: $header;
			}
		}

		p {
			font-size: 18px;
			color: $bodyGray;
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
	
	
			#content-desktop {display: none;}
			#content-mobile {display: block;}
	
		
}


@media only screen and (min-width: 768px) {
	.galleryMain {
	
			#content-desktop {display: block;}
			#content-mobile {display: none;}
	
		.galleryContainers {
			.textSection {
				padding-left: 15px;
				padding-right: 15px;

				h4 {
					font-size: 15px;
					letter-spacing: $tracking250;
				}

				h2 {
					font-size: 50px;
					font-family: "Made";
					color: $header;
				}
			}
		}
	}
}
</style>
