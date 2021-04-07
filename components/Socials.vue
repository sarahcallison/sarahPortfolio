<template>
	<div class="container socialContainer my-5">
		<div class="row justify-content-center my-4">
			<div class="col-12 col-md-6 col-lg-5">
				<div class="d-flex justify-content-around">
					<a href="#">
						<img
							src="@/assets/images/socialIcons/behance.png"
							alt="behance icon contact"
							class="socialImages"
						/>
					</a>
					<a href="#">
						<img
							src="@/assets/images/socialIcons/linkedIn.png"
							alt="behance icon contact"
							class="socialImages"
						/>
					</a>
					<a href="#">
						<img
							src="@/assets/images/socialIcons/instagram.png"
							alt="behance icon contact"
							class="socialImages"
						/>
					</a>
					<a href="#">
						<img
							src="@/assets/images/socialIcons/dribble.png"
							alt="behance icon contact"
							class="socialImages"
						/>
					</a>
				</div>
			</div>
		</div>
		<div class="row justify-content-center my-4">
			<div class="col-12 col-md-6 col-lg-5 text-center names">
				&copy; Sarah Callison | Code By Tyson Elfors
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
	}

	.names {
		text-transform: uppercase;
	}
}
</style>
