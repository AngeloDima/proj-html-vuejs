<template>
    <section id="section_three">
        <div class="Sx"></div>
        <div class="Dx">
            <div class="info"></div>
        </div>
    </section>
</template>

<script>
    export default{
    Name: `section_seven`,
}
</script>

<style lang="scss" scoped>
    #section_three{
        width: 100%;
        height: 90vh;
        background-color: rgb(236, 236, 236);
        display: flex;

        .Sx{
            width: 61%;
            height: 100%;
            background-image: url(img/slider32x.jpg);
            background-size: cover;
            background-position: top;
        }

        .Dx{
            width: 39%;
            height: 100%;
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
            .info{
                width: 80%;
                height: 80%;
                background-color: rgba(255, 0, 0, 0.616);
                
            }
        }
    }
</style>