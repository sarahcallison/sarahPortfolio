<template>
	<div class="container-fluid imgBackground vh-100">
		<div class="imgCont">
			<div @click="$router.go(-1)" class="close">
				<img
					id="closeImg"
					src="@/assets/images/closeHover.png"
					src2="@/assets/images/close.png"
				/>
			</div>
			<img class="img-fluid" :src="imageUrl" alt="Sarah Project Image" />
		</div>
	</div>
</template>

<script>
export default {
	computed: {
		imageUrl() {
			return `/gallery/${this.$route.params.img}.jpg`;
		}
	}
};
</script>

<style lang="scss" scoped>
.imgBackground {
	background-image: linear-gradient(to right, $bgLightPurple, $bgDarkPurple);

	.imgCont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
		.close {
			position: absolute;
			right: 20px;
			top: 20px;
			height: 32px;

			#closeImg {
				content: url("@/assets/images/closeHover.png");
				content: url("@/assets/images/close.png");
				width: 45px;
				cursor: pointer;

				&:hover {
					content: url("@/assets/images/closeHover.png");
				}
			}
		}
	}
}
</style>
