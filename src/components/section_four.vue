<template>
    <section id="section_four">
        <div class="mini_titolo"><h1>TITOLO</h1></div>

        <div class="container_img">
            <div class="poster">
                <div class="Sx"></div>
                <div class="Dx">
                    <div class="info"></div>
                </div>
            </div>
            <div class="poster-mini">
                <div class="info-mini"></div>
            </div>
            <div class="poster-mini2">
                <div class="info-mini"></div>
            </div>
        </div>

    </section>
</template>

<script>
     export default{
     Name: `section_four`
     }
</script>

<style lang="scss" scoped>
    #section_four{
        width: 100%;
        height: 180vh;
        background-color: rgba(0, 202, 252, 0.342);

        display: flex;
        flex-direction: column;
        .mini_titolo{
            width: 100%;
            height: 5%;
            background-color: rgba(255, 0, 0, 0.432);
        }
        .container_img{
            width: 100%;
            height: 95%;
            background-color: green;

            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            .poster{
                width: 70%;
                height: 50%;
                background-color: wheat;
                display: flex;
                .Sx{
                    width: 50%;
                    height: 100%;
                    background-image: url(img/blog72x.jpg);
                    background-size: cover;
                }
                .Dx{
                    width: 50%;
                    height: 100%;
                    background-color: black;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                     
                    .info{
                        width: 80%;
                        height: 80%;
                        background-color: red;
                        color: white;
                    }
                }
            }
            .poster-mini{
                width: 33.5%;
                height: 40%;
                background-image: url(img/info52x.jpg);
                background-position: 0px -50px;
                background-size: cover;
                margin: 0px 20px;
                display: flex;
                justify-content: center;
                align-items: center;
            }

            .poster-mini2{
                width: 33.5%;
                height: 40%;
                background-image: url(img/info12x.jpg);
                background-position: 0px -50px;
                background-size: cover;
                margin: 0px 20px;
                display: flex;
                justify-content: center;
                align-items: center;
            }
            .info-mini{
                width: 80%;
                height: 80%;
                background-color: red;
            }
        }
    }
    
</style>