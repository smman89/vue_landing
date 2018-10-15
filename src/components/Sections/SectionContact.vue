<template>
    <section class="contacts">
      	<div class="grid container_flex">
			<h1 class="h1 h1__heading_accent">{{ title }}</h1>
			<div class="grid__row space-between">
				<base-input :input="contactForm.buisnessName" class="col-md-5 col-xs-12"/>
				<base-input :input="contactForm.contactName" class="col-md-5 col-xs-12"/>
			</div>
			<div class="grid__row space-between">
				<base-input :input="contactForm.phone" class="col-md-5 col-xs-12"/>
				<base-input :input="contactForm.email" class="col-md-5 col-xs-12"/>
			</div>
			<div class="grid__row space-around">
				<base-input :input="contactForm.msg" class="col-md-12 col-xs-12"/>
			</div>
			<div class="grid__row flex-end">
			<button class="col-md-4 col-xs-12 btn btn-pink btn-xl">SEND</button>
			</div>
     	</div>
    </section>
</template>

<script>
import BaseInput from "../UI/BaseInput/BaseInput";
export default {
  components: {
    BaseInput
  },
  data() {
    return {
      contactForm: {
        buisnessName: { title: "Buisness Name*", val: "" },
        contactName: { title: "Contact Name*", val: "" },
        phone: { title: "Telephone*", val: "" },
        email: { title: "Email*", val: "" },
        msg: { title: "Message*", val: "" }
      },
      title: "Get in touch with us today!"
    };
  }
};
</script>

<style lang="scss" scoped>
h1 {
	text-align: center;
	margin-top: 80px;
}
.contacts {
	background-image: url("../../../static/img/bg_contact.png");
	background-size: cover;
	padding-bottom: 10vh;
}
.container_flex {
	max-width: 1000px;
}
</style>

