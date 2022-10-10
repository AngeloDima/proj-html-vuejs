<template>
    <section id="footer">
        <div class="box-info">
            <div class="info">



                <div class="logo">
                    <img src="./img/logo-restaurant.png" alt="">
                </div>
                
                <p>Quam eu proin sit massa condimentum. Volutpat non pulvinar
                    aliquet nunc. Quam eu proin sit massa condimentum.
                </p>
                <div class="social">
                    <div class="card">
                        <img src="./img/kisspng-social-media-facebook-computer-icons-clip-art-5ae37dc8073215.6257922815248583120295.png" alt="">
                    </div>
                    <div class="card">
                        <img src="./img/kisspng-computer-icons-clip-art-twitter-logo-vector-5b5693f7ca66a0.2797760715324006318291.png" alt="">
                    </div>
                    <div class="card">
                         <img src="./img/yt.png" alt=""> 
                    </div>
                    <div class="card">
                        <img src="./img/kisspng-computer-icons-logo-instagram-icon-5b3ece732d3ba5.8310488215308427391853.png" alt="">
                    </div>
                    <div class="card">
                        <img src="./img/kisspng-computer-icons-linkedin-logo-linkedin-white-5b4847a134e5e6.8998596715314635852167.png" alt="">
                    </div>
                </div>
            </div>
            <p id="p-finale">
                Copyright 2012 - 2019 Avada All Rights Reserved Powered by WordPress ThemeFusion
            </p>
        </div>
    </section>
</template>


<script>
    export default{
    Name: `footer_cli`,
}
</script>

<style lang="scss" scoped>

@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Telugu:wght@300&family=Oswald&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

p{
    font-family: 'Noto Serif Telugu', serif;
}
h2, h3, h1{
    font-family: 'Oswald', sans-serif;
}







    #footer{
        width: 100%;
        height: 80vh;
        background-image: url(img/footer2x.jpg);
        background-size: cover;
        background-position: bottom;
        .box-info{
            width: 40%;
            height: 100%;
            //  background-color: rgba(255, 0, 0, 0.301);
            margin: auto;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            #p-finale{
                color: white;
                margin-bottom: 15px;
            }
            .info{
                width: 80%;
                height: 100%;
                // background-color: rgba(255, 255, 255, 0.349);
                text-align: center;
                display: flex;
                flex-direction: column;
                justify-content: space-around;

                .logo{
                    position: relative;
                    top: 80px;
                }
                h2{
                    color: white;
                    margin: 0px 0px ;
                    position: relative;
                    top: 50px;
                }
                p{
                    color: white;
                    margin: 0px 0px;
                    font-size: 1.2rem;
                }
                .social{
                    display: flex;
                    justify-content: center;
                    gap: 15px;
                    position: relative;
                    bottom: 120px;
                    .card{
                    width: 75px;
                    height: 75px;
                    background-color: white;
                    
                    border-radius: 50px;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    
                    img{
                        width: 40%;
                        height: 40%;
                    }
                    }
                }
             }
        }
    }   
</style>

