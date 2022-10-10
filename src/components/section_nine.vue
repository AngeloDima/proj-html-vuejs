<template>
    <section id="section_nine">
        <div class="banner">
            <div class="box-info">
                <div class="info">

                    <h1>BRAISED <br> ABALONE</h1>
                    <div id="price">$52</div>

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

@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Telugu:wght@300&family=Oswald&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

p, a{
    font-family: 'Noto Serif Telugu', serif;
}
h1{
    font-family: 'Oswald', sans-serif;
}









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
                #price{
                    color: white;
                    position: absolute;
                    top: 105px;
                    right: 80px;
                    font-size: 1.2rem;
                }
                p{
                    font-size: 1.5rem;
                    color: white;
                    position: relative;
                    bottom: 20px;
                }
                h1{
                    color: white;
                    font-size: 3.5rem;
                    margin: 50px 0px;
                    position: relative;
                    bottom: 50px;
                }
                a{
                    text-decoration: none;
                    color: white;
                    padding: 12px 25px;
                    border: 1px solid white;
                    width: 45%;
                    position: relative;
                    bottom: 30px;
                }
                }
            }
        }
    }
</style>