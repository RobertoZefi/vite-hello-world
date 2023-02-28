<script>
export default{
    data(){
        return{
            
        }
    }
}
</script>

<template>
    <div class="jumbotron">
        <img src="../assets/itachi-wallpaper-fldq4uzhzz2eubvj-fldq4uzhzz2eubvj.jpg" alt="">
        <p class="description">jumbotron</p>
    </div>
</template>

<style>
.jumbotron img{
    max-width: 100%;
    padding-top: 30px;
}

.jumbotron{
    position: relative;
}

.description{
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translateX(-50%) translateY(-50%);
    border: 2px solid white;
    border-radius: 20px;
    padding: 20px;
    font-size: 40px;
    text-transform: uppercase;
    background-color: white;
    font-weight: bold;
}
</style>