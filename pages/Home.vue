<template>
	<div>
		<h1 class="customClass">Sarah Callison</h1>
		<p>This is her portfolio</p>
        <button type="button" class="btn btn-warning">Primary</button>
	</div>
</template>

<script>
export default {
    //use for SEO
	head() {
		return {
			title: "Home",
			meta: [
				{
					hid: "description",
					name: "description",
					content: "Sarah Callison website"
				}
			]
		};
	}
};
</script>

<style  lang="scss" scoped>
    .customClass {
        color: $green;
    }
</style>
