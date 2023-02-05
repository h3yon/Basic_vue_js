<template>
  <div>
    <!-- 데이터 바인딩 -->
    <h1>Hello {{ username }}</h1>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      username: 'John Doe',
      message: 'Welcome 개발자의 품격',
      arr: [],
      obj: {}
    }
  }
}
</script>
<style scoped>
/* 전체적인 css는 assets에 위치할 것 */
.text-red {
  color: red;
}
</style>
