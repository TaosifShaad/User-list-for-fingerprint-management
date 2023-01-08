<template>
    <div class='total-card'>
        <img class="user-img" src="@/assets/photo-1633332755192-727a05c4013d.jfif" alt="">
            <UserTable></UserTable>
    </div>
</template>

<script setup>
import UserTable from '@/components/UserTable.vue'
</script>

<style scoped>
.user-img {
    width: 155px;
    border-radius: 50%;
}

.total-card {
    background: #ecf0f3;
    display: grid;
    /* grid-template-columns: repeat(auto-fill, 293px); */
    grid-template-columns: 1fr 3fr;
    max-width: 650px;
    margin: auto;
    padding: 34px;
    column-gap: 20px;
    box-shadow: 14px 14px 20px #cbced1, -14px -14px 20px white;
    border-radius: 15px;
}

/* .content {
    display: flex;
    gap: 43px;
    align-items: baseline;
} */


</style>