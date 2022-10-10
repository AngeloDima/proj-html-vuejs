<template>
    <section id="section_nine">
        <div class="banner">
            <div class="box-info">
                <div class="info">

                    <h1>THE BEST TABLE IN TOWN</h1>

                    <p>Pretium accumsan porttitor viverra leo
                        gravida mollis imperdiet. Fringilla nibh
                        pharetra sociis leo amet.
                    </p>

                    <a href="#">VIEW IN THE MENU</a>

                </div>
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
                background-color: black;
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
                    // background-color: white;
                    display: flex;
                justify-content: center;
                
                flex-direction: column;
                gap: 50px;
                p{
                    font-size: 0.9rem;
                    color: white;
                }
                h1{
                    color: white;
                    font-size: 2.8rem;
                    margin: 100px 0px;
                }
                a{
                    text-decoration: none;
                    color: white;
                    padding: 12px 25px;
                    border: 1px solid white;
                    width: 45%;
                }
                }
            }
        }
    }
</style>