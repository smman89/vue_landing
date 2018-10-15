<template>
	<section class="buisness div-grey ">
		<div class="block_left">
			<div class="cont">
				<h1 class="h1 h1__heading_accent">More business, more often.</h1>
				<ul class="h4 h4__accent">
					<li>Free to join with no set up fees</li>
					<li>Simple transaction process</li>
					<li>User friendly administration portal</li>
					<li>Extend the reach of your business</li>
					<li>Extend the reach of your business</li>
				</ul>
				<button class="btn btn-pink btn-xl">REGISTER YOUR BUISNESS</button>
			</div>
		</div>
		<div class="right">
            <div class="block_right">
                <img class="img1" src="/static/img/business/mockups.png">
            </div>
		</div>	
    </section>
</template>

<style lang="scss" scoped>
.buisness {
  position: relative;
  display: flex;
  justify-content: flex-start;
  flex-wrap: wrap;
}
.block_left {
  flex-basis: 50%;
  flex-grow: 1;
  padding-bottom: 20px;
}

.block_right {
  display: flex;
  background: linear-gradient(0deg, #e62343, #b5075b);
  justify-content: center;
  align-items: center;
}
.right {
  flex-basis: 50%;
  flex-grow: 1;
  min-width: 768px;
}

.img1 {
  width: 50%;
  margin: 20px 0;
}
.cont {
  width: 600px;
  margin: 0 auto;
}
</style>
