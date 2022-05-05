<template>
    <div class="prod-card"></div>
</template>


<script>
export default {
    name: 'ProductCard'
}
</script>
<style lang="scss" scoped>
@import "../style/vars";

.prod-card {
	flex-basis: 25%;
	padding: 20px;
	background-color: white;
	border: 2px solid lighten($primary, 70%);

	h3 {
		color: $primary;
	}

	img {
		display: block;
	}
}
</style>