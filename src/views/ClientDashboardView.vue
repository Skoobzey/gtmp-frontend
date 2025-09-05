<template>
  <div
    class="flex justify-center absolute top-1/2 left-1/2 mr-[-%50] -translate-x-1/2 -translate-y-1/2"
  >
    <div class="w-[400px] h-auto bg-surface-800 rounded-md pb-8">
      <div class="text-center my-8">
        <div class="font-bold text-2xl">Welcome to GTMP</div>
      </div>

      <div class="px-6">
        <RouterLink to="/player/login/dashboard/legacy-login">
          <Button label="Login" icon="pi pi-user" class="w-full" />
        </RouterLink>
      </div>
      <div class="px-6 mt-8">
        <RouterLink to="/player/login/dashboard/legacy-register">
          <Button label="Register Account" icon="pi pi-user-plus" class="w-full" />
        </RouterLink>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import { RouterLink } from "vue-router";
import Button from "primevue/button";
</script>

<style>
body {
  background-color: rgba(0, 0, 0, 0.1) !important;
}
</style>
