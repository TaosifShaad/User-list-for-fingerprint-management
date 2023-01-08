<template>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" rel="stylesheet"/>
    <a href="#" class="btn">
        <span>See More</span>
    </a>
</template>

<script setup>

</script>

<style scoped>
.btn {
    background-color: turquoise;
    border-radius: 10px;
    color: white;
    padding: 5px 10px;
    position: relative;
    overflow: hidden;
    height: 38px;
    width: 90px;
    display: inline-block;
    transition: all .3s;
}

.btn span {
    position: relative;
    left: 0;
    transition: all .3s;
}

.btn::after {
    font-family: "Font Awesome 6 Free";
    font-weight: 900;
    content: "\f101";
    position: absolute;
    transform: translatex(-50%);
    right: -40px;
    transition: all .3s;
    font-size: 20px;
}

.btn:hover {
    background-color: #00ffb3;
}

.btn:hover span {
    left: -80px;
}

.btn:hover::after {
    right: 22px;
}

a {
    text-decoration: none;
}
</style>