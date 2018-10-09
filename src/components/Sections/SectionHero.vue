<template>
  <section class="hero">
    <div class="container">
      <div class="header">
          <img src="/static/img/Hero/eDining_logo_white.svg" alt="logo">
          <div>
            <button class="btn btn-pink btn-sm">REGISTER</button>
            <button class="btn btn-transparent btn-sm">LOGIN</button>
          </div>
      </div>
      <div class="row no-gutters">
        <div class="col-lg-6">
          <h1 class=" h1 h1__heading head"> Attract more customers with the eDining Digital Gift Card </h1>
          <p class="h4 h4__primary">Boost traffic and revenue by accepting the eDining Digital Gift Card from members of leading loyalty programs.</p>
          <button class="btn btn-pink btn-xl">REGISTER YOUR BUSINESS</button>
        </div>
     
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
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.hero {
  background-image: url("/static/img/Hero/header.png");
  background-size: cover;
  padding-bottom: 300px;
}

.buttons {
  display: flex;
  justify-content:flex-end;
  flex-wrap: wrap;
}
.no-gutters {
  margin-right: 0;
  margin-left: 0;

  > .col,
  > [class*="col-"] {
    padding-right: 0;
    padding-left: 0;
  }
}
.header {
  display: flex;
  justify-content:space-between;
  flex-wrap: wrap;
  align-items: center;
  padding: 40px 0px;
}
.head {
  text-align: left;
}
</style>
