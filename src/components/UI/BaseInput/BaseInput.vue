<template>
    <div class="base-input">
        <input 
        class="base-input__field" 
        type="text"
        placeholder="Привет"
        >
    </div>
</template>

<style lang="scss">
@import "../../../style/base/colors";
.base-input {
  display: flex;
  font-size: 20px;
  &__field {
    background: transparent;
    font-size: 1em;
    color: $input_text-color;
    border: 0 solid $input_line-color;
    border-bottom-width: 2.59px;
    line-height: inherit;
    margin: 20px 2px;
    padding: 10px 2px;
  }
}
</style>

