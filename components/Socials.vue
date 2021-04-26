<template>
	<div class="container socialContainer">
		<div class="row justify-content-center my-4">
			<div class="col-12 col-md-6 col-lg-5">
				<div class="d-flex justify-content-around">
					<a href="https://behance.net/sarahcallison">
						<img
							src="@/assets/images/socialIcons/behance.png"
							alt="behance icon contact"
							class="socialImages"
						/>
					</a>
					<a
						href="https://www.linkedin.com/in/sarah-callison-06227420a"
					>
						<img
							src="@/assets/images/socialIcons/linkedIn.png"
							alt="linkedin icon contact"
							class="socialImages"
						/>
					</a>
					<a href="https://instagram.com/ispyadesigner">
						<img
							src="@/assets/images/socialIcons/instagram.png"
							alt="instagram icon contact"
							class="socialImages"
						/>
					</a>
					<a href="https://dribbble.com/sarahcal">
						<img
							src="@/assets/images/socialIcons/dribble.png"
							alt="behance icon contact"
							class="socialImages"
						/>
					</a>
				</div>
			</div>
		</div>
		<div class="row justify-content-center mt-4">
			<div class="col-12 col-md-6 col-lg-8 text-center names">
				&copy; Sarah Callison {{ new Date().getFullYear() }} | Code By
				<a
					id="webLink"
					target="_blank"
					href="http://www.tysonelfors.com"
					>Tyson Elfors</a
				>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.socialContainer {
	.socialImages {
		width: 60px;
		transition: transform 0.4s;

		&:hover {
			transform: translateY(-10px);
		}
	}

	.names {
		text-transform: uppercase;
		letter-spacing: $tracking250;
	}

	#webLink {
		color: black;
	}
}
</style>
