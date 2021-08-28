<template>
  <div class="student_id">
    <div>
      <h1>{{ id }}</h1>
    </div>
    <div>
      <span><NuxtLink to="/students/">生徒一覧に戻る</NuxtLink></span><span>|</span><span><NuxtLink to="/">トップページへ</NuxtLink></span>
    </div>
    
  </div>
</template>


<script>
export default {
  data() {
    return {
      id: this.$route.params.id
    }
  }
}
</script>

<style>
.student_id {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
