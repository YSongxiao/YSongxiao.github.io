<script setup>

</script>

<template>
  <div>
    This is my CV
  </div>
  <el-button @click="show">Test</el-button>
</template>

<style scoped>

</style>

<script>
export default {
  name: "MainPage",
  components: {},
  methods:{
    show: function (){
      console.log("You made it!");
    }
  }
}
</script>