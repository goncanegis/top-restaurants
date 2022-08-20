<template>
  <div class="container text-center">
    <NuxtLayout name="error">
      <template #header>
        <h1>Page Not Found</h1>
      </template>

      <template #redirectButton>
        <NuxtLink to="/">Go back</NuxtLink>
      </template>
    </NuxtLayout>
  </div>
</template>

<style scoped>
.container {
  margin-top: 5rem;
}
</style>
