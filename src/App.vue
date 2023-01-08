<script setup>
import UserCard from "@/components/UserCard.vue";
</script>

<template>
  <div class="user-card">
    <UserCard></UserCard>
    <UserCard></UserCard>
    <UserCard></UserCard>
    <UserCard></UserCard>
  </div>
</template>

<style scoped>
.user-card {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(669px, 1fr));
  row-gap: 60px;
}
</style>
