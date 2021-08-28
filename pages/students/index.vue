<template>
  <div class="student">
      <div class="title">
        <h1>生徒一覧</h1>
      </div>
      <div class="detail">
        <ul>
          <li><NuxtLink :to="{path: 'users/生徒A'}">生徒A</NuxtLink></li>
          <li><NuxtLink :to="{path: 'users/生徒B'}">生徒B</NuxtLink></li>
          <li><NuxtLink :to="{path: 'users/生徒C'}">生徒C</NuxtLink></li>
        </ul>
      </div>
      <NuxtLink to="/">戻る</NuxtLink>
  </div>
</template>


<style>
.student {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

</style>