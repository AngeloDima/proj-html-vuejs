<template>
    <section class="flex">



        <div class="Sx">
            <div class="logo"></div>
            <div class="info-header"></div>
        </div>

        <!-- ------------------------------------- -->

        <div class="Dx">
            <div class="menù"></div>
        </div>



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
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 15%;
        .logo{
            width: 100%;
            height: 10%;
            background-color: aqua;
        }
        .info-header{
            width: 80%;
            height: 55%;
            background-color: red;



        }
    }
    
    .Dx{
        width: 60%;
        height: 100vh;
        background-image: url(img/slider52x.jpg);
        background-size: cover;
        .menù{
            width: 100%;
            height: 10%;
            background-color: rgba(0, 255, 255, 0.534);
        }
    }


</style>