<template>
	<section class="buisness div-grey ">
		<div class="block">
			<div class="block__container">
				<div class="grid">
					<div class="grid__row">
						<div class="col-xs-12">
							<h1 class="h1 h1__heading_accent">More business, more often.</h1>
							<ul class="h4 h4__accent">
								<li>Free to join with no set up fees</li>
								<li>Simple transaction process</li>
								<li>User friendly administration portal</li>
								<li>Extend the reach of your business</li>
								<li>Extend the reach of your business</li>
							</ul>
					 	</div>
					</div>
					<div class="grid__row">
						<button class="col-md-7 col-xs-12 btn btn_pink btn_xl">REGISTER YOUR BUISNESS</button>
					</div>
				</div>
			</div>
		</div>
		<div class="block block_right">
            <div class="block__content">
                <img class="img" src="/static/img/business/mockups.png">
            </div>
		</div>	
    </section>
</template>

<style lang="scss" scoped>
.buisness {
  position: relative;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.block {
  flex-basis: 50%;
  flex-grow: 1;
  &__container {
    padding-bottom: 5vw;
    max-width: 600px;
    margin-left: auto;
  }
  &_right {
    min-width: 400px;
    align-self: stretch;
    display: flex;
  }
  &__content {
    display: flex;
    background: linear-gradient(0deg, #e62343, #b5075b);
    justify-content: center;
    align-items: center;
    align-self: stretch;
    width: 100%;
  }
}
.img {
  width: 80%;
  padding: 3vw;
  max-width: 500px;
}

@media screen and (max-width: 1000px) {
  .block__container {
    margin: 0 auto;
  }
}
</style>
