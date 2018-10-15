<template>
    <div class="base-input">
        <input 
          class="base-input__field input__text" 
          type="text"
          :placeholder="input.title"
        >
    </div>
</template>
<script>
export default {
  props: ["input"]
}
</script>

<style lang="scss">
@import "../../../style/base/colors";
.base-input {
  display: flex;
  font-size: 20px;
  width: 100%;
  &__field {
    flex-basis: 100%;
    background: transparent;
    font-size: 1em;
    border: 0 solid $input_line-color;
    border-bottom-width: 2.59px;
    line-height: inherit;
    margin: 20px 2px;
    padding: 10px 2px;
  }
}
</style>

