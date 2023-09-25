<template lang="">
  <div>
    <button @click="increment" id="counter-button">increment</button>
    <p>Count is: {{ count }}</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      this.count++
    }
  }
}
</script>
<style lang="css">
  #counter-button {
    background-color: #000;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    border-radius: 5px;
  }

  #counter-button:hover {
    background-color: #333;
    cursor: pointer;
  }
</style>