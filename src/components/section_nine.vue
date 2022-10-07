<template>
    <section id="section_nine">
        <div class="banner">
            <div class="box-info">
                <div class="info"></div>
            </div>
        </div>
    </section>
</template>

<script>
    export default{
    Name: `section_nine`,
}
</script>

<style lang="scss" scoped>
    #section_nine{
        width: 100%;
        height: 90vh;
        background-color: rgb(236, 236, 236);
        

        .banner{
            width: 100%;
            height: 100%;
            background-image: url(img/hero42x.jpg);
            background-size: cover;
            background-position: center;
            position: relative;
            .box-info{
                width: 30%;
                height: 80%;
                background-color: red;
                position: absolute;
                left: 15%;
                bottom: 50%;
                transform: translate(-1%, 50%);
                display: flex;
                justify-content: center;
                align-items: center;
                .info{
                    width: 80%;
                    height: 80%;
                    background-color: white;

                }
            }
        }
    }
</style>