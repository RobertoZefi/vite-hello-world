<script>
export default{
    data(){
        return{
            message: 'La mia prima app con Vite!'
        }
    }
}
</script>

<template>
    <div class="title">
        <h1>{{ message }}</h1>
    </div>
</template>

<style>
    .title{
    border: 2px solid black;
    padding: 30px;
    border-radius: 20px;
    }
</style>