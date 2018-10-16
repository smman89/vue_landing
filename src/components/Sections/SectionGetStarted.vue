<template>
    <section>
        <div class="container">
            <h1 class="h1 h1__heading_accent">Let’s get started!</h1>
            <div class="grid">
                <div class="grid__row">
                    <step 
						v-for="(item, index) in steps" 
						:key="index" 
						:item="item"
					/>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import Step from "../UI/Step/Step";
export default {
	name: "SectionGetStarted",
	components: {
			Step
	},
  data() {
    return {
      steps: [
        {
          imgNumber: "1.svg",
          imgMain: "Register-illustration.svg",
          title: "Register now",
          desc:
            'Simply <b><a class="a__pink" href="ya.ru">Register your Business</a></b>' +
            " to join the eDining digital gift card network."
        },
        {
          imgNumber: "2.svg",
          imgMain: "enableeftpos.svg",
          title: "Link your EFTPOS",
          desc:
            "Once registered, you will receive an email to link your existing EFTPOS terminals."
        },
        {
          imgNumber: "3.svg",
          imgMain: "transact.svg",
          title: "Start transacting",
          desc:
            "Customers will present their eDining Digital Gift Card" +
            +"for you to process through your EFTPOS terminal."
        }
      ]
    };
  }
};
</script>

<style lang="scss"  scoped>
.steps {
  margin-bottom: 10vh;
}
.h1 {
  text-align: center;
  margin-top: 80px;
}
</style>
