<template>
    <div id="main-banner">
        <h1>Make Your Banner estou editando pelo tab na nuvem</h1>
    </div>

</template>

<script>
export default {
    name: "Banner",
    
}
</script>

<style scoped>
 #main-banner {
    background-image: url('/public/img/burger.jpg');
    background-position: 0 -250px;
    background-size: cover;
    background-repeat: no-repeat;
    height: 500px;
    display: flex;
    align-items: center;
    justify-items: flex-start;
 }

 h1 {
    color: #fff;
    text-align: center;
    font-size: 5vh;
    background-color: #222;
    padding: 20px 40px;
    border-radius: 5px;
    
 }

</style>