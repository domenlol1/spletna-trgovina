<template>
<div class="banner">
</div>
<div class="skupno">
<div class="left">
    <p>filtri</p>
</div>
<div class="mid"></div>
<div class="mid"></div>
<div class="mid"></div>
</div>
</template>

<script>
export default {
    
}
</script>

<style>
.left {
background-color: antiquewhite;
width: 300px;
height: 500px;
border-right: 1px solid rgb(120, 120, 124);
}
.mid {
    display: flex;
    justify-content: center;
    height: 300px;
    width: 300px;
    background-color: rgb(124, 124, 141);
    margin-bottom: 10px;
    align-items: center;
    border-radius: 1%;
    border: 0;
    transition: 0.1s;
}
.mid:hover{
    box-shadow: 0 0 5px rgb(39, 39, 39);
    -moz-box-shadow: 0 0 5px rgb(39, 39, 39);
    -webkit-box-shadow: 0 0 5px rgb(39, 39, 39);
    border-color: black;
    border: 1px solid black;
}
.skupno {
    display: flex;
    margin-top: 80px;
    gap: 20px;
}
.banner {
    width: 1000px;
    height: 300px;
    background-image:url("../assets/banner.jpg");
    background-size: cover;
    margin: auto;
    margin-top: 10px;
}
</style>