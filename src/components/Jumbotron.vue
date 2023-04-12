<script>
    export default{
        name:"Jumbotron",
        data(){
            return{
                img:"https://os-system.com/blog/wp-content/uploads/2020/11/nodejs-based-applications-1024x538.png"
            }
        }
    }
</script>

<template>
    <div class="container">
        <img :src="img" alt="">
    </div>

</template>

<style>
.container{
    width: 100%;
    height: 400px;
}
img{
    width: 100%;
    height: 400px;
    object-fit: cover;

}
</style>