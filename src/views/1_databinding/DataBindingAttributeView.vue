<template>
  <div>
    <input type="text" name="" id="" v-bind:value="userId" readonly />
    <input type="text" name="" id="" :value="userId" readonly />
    <!-- v-bind는 생략가능 -->
    <br /><br />
    <img :src="imgSrc" style="width: 100px; height: auto" />
    <br /><br />
    <input type="search" name="" id="" v-model="txt1" />
    <button :disabled="txt1 === ''">조회</button>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      userId: 'margirlim',
      imgSrc:
        'https://helpx.adobe.com/content/dam/help/en/photoshop/using/quick-actions/remove-background-before-qa1.png',
      txt1: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>

<style scoped></style>
