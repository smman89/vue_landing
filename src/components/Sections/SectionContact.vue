<template>
    <section class="contacts">
        <div>
            <base-input>
            </base-input>
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
    return {};
  }
};
</script>

<style lang="scss">
.contacts {
  background-image: url("../../../static/img/bg_contact.png");
  background-size: cover;
}
</style>

