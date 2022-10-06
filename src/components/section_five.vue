<template>
    <section id="section_three">
        <div class="banner"></div>
    </section>
</template>

<script>
    export default{
    Name: `section_five`,
}
</script>

<style lang="scss" scoped>
    #section_three{
        width: 100%;
        height: 60vh;
        background-color: rgb(236, 236, 236);
        display: flex;

        .banner{
            width: 100%;
            height: 100%;
            background-image: url(img/page52x.jpg);
            background-size: cover;
           
        }
    }
</style>