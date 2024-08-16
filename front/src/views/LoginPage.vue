<template>
  <div class="login">
    <el-card style="max-width: 30rem">
    <template #header>
      <div class="card-header">
        <span>登 录</span>
      </div>
    </template>
    <p v-for="o in 4" :key="o" class="text item">{{ 'List item ' + o }}</p>
    <template #footer>Footer content</template>
  </el-card>
  </div>
</template>


<style scoped>
.login {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.card-header {
  font-size: 1.5rem;
  font-weight: bold;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>