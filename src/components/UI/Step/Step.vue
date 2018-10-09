<template>
    <div class="col-lg step">
        <img class="step__img-number" :src="'/static/img/Steps/'+item.imgNumber"/>
        <div class="step__content">
            <img class="step__img-main" :src="'/static/img/Steps/'+item.imgMain"/>
            <h4 class="h4 h4__heading_accent">{{item.title}}</h4>
            <p v-html="item.desc" class="h6 h6__regular"></p>
        </div>
    </div>
</template>

<script>
export default {
  props: ["item"],
  computed: {
    getDescription(desc) {
      console.log(desc);
    }
  }
};
</script>


<style lang="scss">
.step {
  display: flex;

  &__img-number {
    height: auto;
    object-fit: scale-down;
    object-position: top;
    margin-right: 29px;
  }
  &__content {
  }
  &__img-main {
   
  }
}
</style>
