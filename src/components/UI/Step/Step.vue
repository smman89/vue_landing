<template>
	<div class="col-lg-4 step">
		<img class="step__img-number" :src="'/static/img/Steps/'+item.imgNumber"/>
		<div>
			<img :src="'/static/img/Steps/'+item.imgMain"/>
			<h4 class="h4 h4__heading_accent">{{ item.title }}</h4>
			<p class="h6 h6__regular" v-html="item.desc" ></p>
		</div>
	</div>
</template>

<script>
export default {
  props: ["item"]
};
</script>

<style lang="scss">
.step {
  display: flex;
  &__img-number {
    object-fit: none;
    object-position: top;
    margin-right: 29px;
  }
}
</style>
