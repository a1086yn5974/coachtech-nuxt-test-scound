<template>
  <div class="container">
    <h1>{{title}}</h1>
    <p>{{description}}</p>
    <nuxt-link to="/">topへ</nuxt-link>
  </div>
</template>

<script>
export default {
  data(){
    return{
      title: 'Other page',
      description: 'this is message',
    }
  },
}
</script>

<style>
.container {
  padding: 30px;
}
</style>
