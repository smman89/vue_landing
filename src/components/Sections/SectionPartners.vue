<template>
	<section>
		<div class="container">
			<h1 class="h1 h1__heading_accent head">{{ title }}</h1>
			<h3 class="h3 h3__leading" v-html="desc"></h3>
			<div class="partners__imgs">
				<div v-for="(item, index) in partners" :key="index" :item="item">
					<img :src="'/static/img/partners/'+item.img" alt="">
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
  data() {
    return {
      partners: [
        { title: "suncorp", img: "Suncorp.svg" },
        { title: "AAMI", img: "AAMI.svg" },
        { title: "GIO", img: "RACQ.png" },
        { title: "RACQ", img: "RACQ.png" }
      ],
      title: "Our leading partners",
      desc:
        "eDining Digital Gift Cards are offered exclusively <br>" +
        "through some of Australia’s leading loyalty programs."
    };
  }
};
</script>

<style lang="scss" scoped>
.h1 {
  	text-align: center;
	margin-top: 80px;
}
.partners__imgs {
	display: flex;
	justify-content: space-between;
	flex-wrap: wrap;
	margin: 70px 0px;
}
img {
  	max-height: 50px;
}
</style>
