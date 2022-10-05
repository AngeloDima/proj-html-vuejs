<template>
    <section id="section_two">
        <div class="Sx"></div>
        <div class="Dx"></div>
    </section>
</template>

<script>
    export default{
    Name: `section_one`,
}
</script>

<style lang="scss" scoped>
    #section_two{
        width: 100%;
        height: 100vh;
        background-color: rgb(236, 236, 236);
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 5%;

        .Sx{
            width: 30%;
            height: 80%;
            background-color: red;
        }

        .Dx{
            width: 35%;
            height: 80%;
            background-color: rgba(255, 0, 0, 0.582);
        }
    }
</style>