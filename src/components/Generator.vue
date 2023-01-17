<script >
    export default{
      data(){
        return{
          arr: []
        }
      },
      methods:{
        generator(){
          this.arr.push(Math.random()*100)
        }
      }
    }
</script>

<template>
    <div>
      <button @click="generator()">Generate</button>
      <ul>
        <li v-for="num in arr">{{num}}</li>
      </ul>
    </div>
</template>
