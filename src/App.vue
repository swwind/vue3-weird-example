<template>
  <router-link to="/test/114514">Click me!</router-link>
  <router-view v-slot="{ Component }">
    <suspense>
      <template #default>
        <component :is="Component"/>
      </template>
      <template #fallback>
        <div>Loading...</div>
      </template>
    </suspense>
  </router-view>
</template>
