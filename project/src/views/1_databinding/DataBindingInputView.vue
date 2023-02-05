<template>
  <div>
    <input type="text" v-model="userId" />
    <button @click="myFunction()">클릭</button>
    <button @click="changeData">변경</button>
    <br />
    <input type="text" v-model.number="num1" /> +
    <input type="text" v-model.number="num2" /> =
    <span>{{ num1 + num2 }}</span>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'h3yon.go',
      num1: 0,
      num2: 0,
      num3: 0,
      num4: 0
    }
  },
  beforeCreate() {},
  created() {},
  beforeMount() {},
  mounted() {},
  beforeUpdate() {},
  updated() {},
  beforeUnmount() {},
  unmounted() {},
  methods: {
    myFunction() {
      console.log(this.userId)
    },
    changeData() {
      this.userId = 'Jeremy'
    }
  }
}
</script>
