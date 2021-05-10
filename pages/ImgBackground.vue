<template>
	<div class="container-fluid imgBackground">
		<div class="imgCont">
			<div @click="$router.go(-1)" class="close">
				<img
					id="closeImg"
					src="@/assets/images/closeHover.png"
					src2="@/assets/images/close.png"
				/>
			</div>
			<img
				v-if="this.$route.params.img"
				class="img-fluid mainImg"
				:src="imageUrl"
				alt="Sarah Project Image"
			/>

			<iframe
				class="mainImg"
				v-if="this.$route.params.vid"
				width="750"
				height="500"
				:src="videoUrl"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
				allowfullscreen
			></iframe>
		</div>
	</div>
</template>

<script>
export default {
	data() {
		return {};
	},

	computed: {
		imageUrl() {
			return `/gallery/${this.$route.params.img}.jpg`;
		},

		videoUrl() {
			return this.$route.params.vid;
		}
	}
};
</script>

<style lang="scss" scoped>
.imgBackground {
	background-image: linear-gradient(to right, $bgLightPurple, $bgDarkPurple);
	height: 100vh;

	.imgCont {
		background-image: linear-gradient(
			to right,
			$bgLightPurple,
			$bgDarkPurple
		);
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;

		.mainImg {
			max-height: 100vh;
			padding: 20px 0;
		}

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
