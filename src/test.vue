<template>
  <div class="test" v-bind="$attrs" v-on="$listeners">
    hello
  </div>
</template>

<script>
export default {
  name: 'Test',
  props: {},
  data() {
    return {}
  }
}
</script>

<style lang="less"></style>
