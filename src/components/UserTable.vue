<template>
<div>
    <table class="table">
        <thead>
            <tr>
            <th scope="col"><i>id</i></th>
            <th scope="col" style="font-weight: bold">Name</th>
            <th scope="col" style="font-weight: bold">Entry</th>
            <th scope="col" style="font-weight: bold">Exit</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th scope="row">1</th>
                <td>Mark</td>
                <td>10.00 am, 12 January, 2022</td>
                <td>7.40 pm January, 2022</td>
            </tr>
        </tbody>
    </table>
    <div class="details-btn">
            <Btn />
    </div>
</div>
</template>

<script setup>
import Btn from '@/components/DetailsButton.vue'
</script>

<style scoped>
table{
    text-align: center;
}
table tr {
    border-color: black;
}
.details-btn {
    display: flex;
    justify-content: flex-end;
}
/* table td { 
    border-left:2px solid white; 
} */
</style>
