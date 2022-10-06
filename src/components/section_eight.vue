<template>
    <section id="section_eight">
        <div class="card"></div>
        <div class="card-up"></div>
        <div class="card"></div>
    </section>
</template>

<script>
    export default{
    Name: `section_eight`
    }
</script>

<style lang="scss" scoped>
    #section_eight{
        width: 100%;
        height: 100vh;
        background-color: aqua;
        display: flex;
        justify-content: center;
        align-items: center;
        .card{
            width: 23.5%;
            height: 70%;
            background-color: red
        }
        .card-up{
            width: 23.4%;
            height: 70%;
            background-color: rgb(0, 192, 0);
            position: relative;
            bottom: 5%;
        }
    }
</style>