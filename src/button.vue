<template>
  <button class="g-button">hi</button>
</template>

<script>
export default {
  name: ''
}
</script>

<style lang="sass">
  .g-button {
    font-size: var(--font-size);
    height: var(--button-height);
    padding: 0 1em; /* width */
    border-radius: var(--border-radius);
    border: 1px solid var(--border-color);
    background-color: var(--button-bg);
    color: var(--color);
    &:hover {
      border-color: var(--border-color-hover);
    }
    &:active {
      background-color: var(--button-active-bg);
    }
    &:focus {
      outline: none;
    }
  }
</style>