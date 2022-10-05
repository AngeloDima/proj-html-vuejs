<template>
    <section id="section_two">


        <div class="card">
            <div class="card-img"></div>
            <div class="card-title"></div>
            <div class="card-info"></div>
            <div class="card-button"></div>
        </div>


        <div class="card">
            <div class="card-img"></div>
            <div class="card-title"></div>
            <div class="card-info"></div>
            <div class="card-button"></div>
        </div>


        <div class="card">
            <div class="card-img"></div>
            <div class="card-title"></div>
            <div class="card-info"></div>
            <div class="card-button"></div>
        </div>


    </section>
</template>

<script>
        export default{
    Name: `section_two`,
}
</script>

<style lang="scss" scoped>
    #section_two{
        width: 100%;
        height: 60vh;
        background-color: cadetblue;

        display: flex;
        justify-content: center;
        align-items: center;
        gap: 5%;

        .card{
            width: 20%;
            height: 80%;
            background-color: green;
            .card-img{
                width: 100%;
                height: 35%;
                background-color: red;
            }
            .card-title{
                width: 100%;
                height: 10%;
                background-color: rgba(255, 0, 0, 0.699);
            }
            .card-info{
                width: 100%;
                height: 35%;
                background-color: aqua;
            }
            .card-button{
                width: 100%;
                height: 20%;
                background-color: rgb(0, 182, 182)     
            }
        }
    }
</style>