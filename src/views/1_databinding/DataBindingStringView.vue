<template>
  <div>
    <h1>Hello {{ username }}</h1>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      username: 'Myeong Han Park',
      message: 'Welcome margirlim',
      arr: [],
      obj: {}
    }
  }
}
</script>
<style scoped>
.text-red {
  color: red;
}
</style>
