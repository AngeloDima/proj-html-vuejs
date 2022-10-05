<template>
    <section class="flex">
        <div class="Sx"></div>
        <div class="Dx"></div>
    </section>
</template>

<script>
    export default{
    Name: `header_cli`,
}
</script>

<style lang="scss" scoped>
    .flex{
        display: flex;
    }


    .Sx{
        width: 40%;
        height: 100vh;
        background-color: rgb(0, 0, 0);
    }
    
    .Dx{
        width: 60%;
        height: 100vh;
        background-image: url(img/slider52x.jpg);
        background-size: cover;
    }


</style>