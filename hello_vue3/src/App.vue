<template>
    <!-- html结构 --> 
    <div class="app">
       <h1>你好啊 这是我第一个Vue3项目</h1>
       <Person/>
    </div>
</template>

<script lang="ts">
    import Person from './components/Person.vue'
   // JS或者TS

   //export暴露
   export default {
       name:"App",//组件名  
       components:{Person} // 注册组件
   }
</script>

<style>
   /* 样式 */
   .app {
       background-color: #ddd;
       box-shadow: 0 0 10px;
       border-radius: 10px;
       padding:20px; 
   }
</style>
   