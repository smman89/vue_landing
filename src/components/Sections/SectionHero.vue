<template>
	<section class="hero">
		<div class="grid">
			<div class="grid__row space-between">
			<img class="col-md-3 col-xs-12 logo" src="/static/img/Hero/eDining_logo_white.svg" alt="logo">
			<div class="col-md-5 col-xs-12"></div>
				<button class="col-md-2 col-xs-12 btn btn-pink btn-sm">REGISTER</button>
				<button class="col-md-2 col-xs-12 btn btn-transparent btn-sm">LOGIN</button>
			</div>
		</div>
		<div class="grid">
		<div class="grid__row">
			<div class="col-lg-6 col-xs-12">
				<h1 class="h1 h1__heading head">{{ title }}</h1>
				<p class="h4 h4__primary">{{ desc }}</p>
			</div>
		</div>
			<div class="grid__row">
				<button class="col-md-4 col-xs-12 btn btn-pink btn-xl">REGISTER YOUR BUSINESS</button>
			</div>
		</div>
	</section>
</template>

<script>
export default {
  name: "SectionHero",
  components: {},
  data() {
    return {
      title: "Attract more customers with the eDining Digital Gift Card",
      desc:
        "Boost traffic and revenue by accepting the eDining Digital Gift" +
        "Card from members of leading loyalty programs."
    };
  }
};
</script>

<style lang="scss">
.hero {
  background-image: url("/static/img/Hero/header.png");
  background-size: cover;
  padding-bottom: 300px;
  padding-top: 40px;
}
.h1 {
  text-align: left;
}
.btn-sm {
  align-self: center;
}
</style>
