<template>
  <div>
    <!-- 문자열 처리 -->
    <div>{{ htmlString }}</div>
    <!-- HTML 태그 처리 -->
    <div v-html="htmlString"></div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      htmlString: '<p style="color:red">빨간색 문자</p>'
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
