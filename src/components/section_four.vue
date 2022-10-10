<template>
    <section id="section_four">
        <div class="mini_titolo">
            <h1>What critics are sayng about us</h1>
        </div>

        <div class="container_img">
            <div class="poster">
                <div class="Sx"></div>
                <div class="Dx">
                    <div class="info">
                        <p>MEGGY STEWART</p>
                        <h1>NEW YORK TIMES</h1>
                        <div class="stelline"></div>
                        <p>Non areu mauris tortor ultrices mollis tellus
                            eusmod fermentum. Habitant amet tincidunt
                            id sapien accumsan sed at.
                        </p>
                        <p>
                            Mmalesuada ullamcorper amet. Pretium
                            pretium dignissim nisi.
                        </p>
                        <a href="#">READ FULL ARTICLE</a>
                    </div>
                </div>
            </div>


            <div class="poster-mini">
                
                <div class="info-mini">
                    <p>MARY MAXEY</p>
                        <h1>THE GUARDIAN</h1>
                        <div class="stelline"></div>
                        <p>
                            Non arcu mauris tortor ultrices mollis
                            tellus euismod fermentum. Habitant amet
                            tincidunt id sapien accumsan sed.
                        </p>
                        <a href="#">READ FULL ARTICLE</a>   
                </div>
                <div class="effect"></div>
                
            </div>



            <div class="poster-mini2">
                <div class="info-mini">
                    <p>PATRICK MONROE</p>
                        <h1>GLOBE AND MAIL</h1>
                        <div class="stelline"></div>
                        <p>
                            Vivamus magna justo, lacinia eget
                            consectetur sed, convallis at tellus. Nulla
                            porttitor accumsan tincidunt.
                        </p>
                        <a href="#">READ FULL ARTICLE</a>
                </div>
                <div class="effect"></div>
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
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Telugu:wght@300&family=Oswald&display=swap');

h1{
    font-family: 'Noto Serif Telugu', serif;
}
p{
    font-family: 'Noto Serif Telugu', serif;
}


.effect{
                width: 100%;
                height: 100%;
                background-color: rgba(0, 0, 0, 0.349);
                position: absolute;
                bottom: 0;
                box-shadow: 0px 290px 70px -40px inset rgb(0, 0, 0);;
            }





    #section_four{
        width: 100%;
        height: 180vh;
        // background-color: rgba(0, 202, 252, 0.342);

        display: flex;
        flex-direction: column;
        .mini_titolo{
            width: 100%;
            height: 5%;
            // background-color: rgba(255, 0, 0, 0.432);
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container_img{
            width: 100%;
            height: 95%;
            // background-color: green;

            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            .poster{
                width: 70%;
                height: 50%;
                // background-color: wheat;
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
                        width: 60%;
                        height: 80%;
                        // background-color: red;
                        display: flex;
                        flex-direction: column;
                        justify-content: center;
                        gap: 50px;
                        p:first-child{
                            font-size: 0.9rem;
                            color: white;
                        }
                        h1{
                            color: white;
                            font-size: 2.8rem;
                            font-family: 'Oswald', sans-serif;
                        }
                        .stelline{
                            width: 100px;
                            height: 30px;
                            background-color: aliceblue;
                        }
                        p:nth-child(4){
                            color: rgb(255, 255, 255);
                            font-size: 1.1rem;
                        }
                        p:nth-child(5){
                            color: rgb(255, 255, 255);
                            font-size: 1.1rem;
                        }
                        a{
                            text-decoration: none;
                            color: white;
                            padding: 12px 25px;
                            border: 1px solid white;
                            width: 59%;
                            
                        }
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
                position: relative;
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
                position: relative;
            }
            .info-mini, .info-mini2{
                width: 60%;
                height: 80%;
                // background-color: red;
                display: flex;
                justify-content: center;
                flex-direction: column;
                gap: 40px;
                z-index: 100;
                p:first-child{
                    font-size: 0.9rem;
                    color: white;
                }
                p:nth-child(4){
                    color: white;
                    font-size: 1.1rem;
                }
                h1{
                    color: white;
                    font-size: 2.8rem;
                    font-family: 'Oswald', sans-serif;
                }
                .stelline{
                     width: 100px;
                     height: 30px;
                    background-color: aliceblue;
                }
                a{
                    text-decoration: none;
                    color: white;
                    padding: 12px 25px;
                    border: 1px solid white;
                    width: 59%;
                }
            }
        }
    }
    
</style>