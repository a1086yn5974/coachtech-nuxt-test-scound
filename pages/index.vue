<template>
  <div class="container">
     <div class="students">
        <h1>生徒一覧</h1>
        <nuxt-link to="/students/">生徒の情報を見る</nuxt-link>
     </div>
     <div class="administrator">
        <h1>管理者</h1>
        <nuxt-link to="/management">管理画面を見る</nuxt-link>
     </div>
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.students{
  margin-right: 40px;
}

.administrator{
  margin-left: 40px;
}
</style>