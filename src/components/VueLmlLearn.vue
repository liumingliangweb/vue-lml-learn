<template>
  <div class="learn">{{propData}}</div>
</template>
<script>
export default {
  name: 'vue-lml-learn',
  props: {
    propData: {
      type: String,
      default: '我是默认值'
    }
  },
  data() {
    return {

    }
  },
  methods: {

  }
}
</script>
<style scoped>
.learn {
  color: aqua;
}
</style>