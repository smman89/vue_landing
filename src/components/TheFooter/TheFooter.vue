<template>
    <section >
        <hr class="footer__line_color">
        <div class="container">
            <div class="footer__content">
                <div>
                  <p 
                    class="contact h5 h5__pink" 
                    v-for="(item, index) in contacts" 
                    :key="index" 
                    :item="item" 
                    v-html="item.desc" 
					>
                  </p>
                </div>
                <div class="socials" >
                  <img 
                    class="img" 
                    v-for="(item, index) in socials" 
                    :key="index" 
                    :item="item" 
                    :src="'/static/img/Brands/' + item.img"
                    >
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  data() {
    return {
      socials: [
        { title: "facebook", img: "facebook.svg" },
        { title: "linkedin", img: "linkedin.svg" },
        { title: "twitter", img: "twitter.svg" }
      ],
      contacts: [
        { title: "company", desc: "<b>eDining<b> © 2018" },
        { title: "email", desc: "info@info.com" },
        { title: "phone", desc: "5555 8888 888" }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
hr {
  border: none;
  height: 20px;
  width: 100%;
  margin: 0px;
}
.footer__content {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  margin: 30px auto;
}
.img {
  margin: 5px 20px;
}
.contact {
  display: inline-block;
}
p {
  margin: 5px 20px;
}
</style>
