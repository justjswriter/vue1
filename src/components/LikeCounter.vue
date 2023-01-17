<script>
    export default {
      data() {
        return{
          counter: 0,
        }
      },
      methods:{
        Like(){
          this.counter++
        }
      }
    }
</script>

<template>
    <button @click="Like">{{counter}}</button>
</template>

<style scoped>

</style>
