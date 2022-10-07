<template>
    <section id="footer">
        <div class="box-info">
            <div class="info"></div>
        </div>
    </section>
</template>


<script>
    export default{
    Name: `footer_cli`,
}
</script>

<style lang="scss" scoped>
    #footer{
        width: 100%;
        height: 70vh;
        background-image: url(img/footer2x.jpg);
        background-size: cover;
        background-position: bottom;
        .box-info{
            width: 40%;
            height: 100%;
            background-color: rgba(255, 0, 0, 0.301);
            margin: auto;
            display: flex;
            justify-content: center;
            align-items: center;
            .info{
                width: 100%;
                height: 60%;
                background-color: rgba(255, 255, 255, 0.349);
            }
        }
    }
</style>

