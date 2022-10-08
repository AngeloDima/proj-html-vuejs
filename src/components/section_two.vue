<template>
    <section id="section_two">

        <!-- -----CARD ONE---- -->
        <div class="card">
            <div class="card-img">
                <img src="./img/sushi-1.png" alt="">
            </div>
            <div class="card-title">
                <h1>
                    THE BEST TABLE IN TOWN
                </h1>
            </div>
            <div class="card-info">
                <p>
                    Sed aenean egestas ut aliquam turpis mauris,
                    molestie. Vitae tellus tempor sem id tempus
                    neque, tellus turpis turpis. Morbi tortor id gravida aliquet
                </p>
            </div>
            <div class="card-button">
                <a href="#">
                    EXPLORE THE MENU
                </a>
            </div>
        </div>

        <!-- -----CARD TWO---- -->
        <div class="card">
            <div class="card-img">
                <img src="./img/sushi-2.png" alt="">
            </div>
            <div class="card-title">
                <h1>
                    PERFECT FOR GROUPS
                </h1>
            </div>
            <div class="card-info">
                <p>
                    Quam eu proin sit massa condimentum.
                    Volutpat non pulvinar aliquet nunc. Orci
                    elementum in aliquet a gravida vivamus
                    aliquam turpis vitae.
                </p>
            </div>
            <div class="card-button">
                <a href="#">
                    MAKE A RESERVATION
                </a>
            </div>
        </div>

        <!-- -----CARD THREE---- -->
        <div class="card">
            <div class="card-img">
                <img src="./img/sushi-3.png" alt="">
            </div>
            <div class="card-title">
                <h1>
                    FRESH PRODUCE EVERYDAY
                </h1>
            </div>
            <div class="card-info">
                <p>
                    Hendrerit amet, volutpat leo non, commodo
                    maecenas scelerisque tincidunt. Morbi
                    vulputate morbi purus quisque sit sagittis orci
                    elementum gravida.
                </p>
            </div>
            <div class="card-button">
                <a href="#">
                    LEARN MORE ABOUT US
                </a>
            </div>
        </div>


    </section>
</template>

<script>
        export default{
    Name: `section_two`,
}
</script>

<style lang="scss" scoped>

@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Telugu:wght@300&family=Oswald&display=swap');


h1{
    font-family: 'Oswald', sans-serif;
}

p{
    font-family: 'Noto Serif Telugu', serif;
}




    #section_two{
        width: 100%;
        height: 60vh;
        // background-color: cadetblue;

        display: flex;
        justify-content: center;
        align-items: center;
        gap: 5%;

        .card{
            width: 20%;
            height: 80%;
            // background-color: green;
            .card-img{
                width: 100%;
                height: 30%;
                // background-color: red;
                display: flex;
                justify-content: center;
                img{
                    width:45%;
                }
            }
            .card-title{
                width: 100%;
                height: 15%;
                //  background-color: rgba(255, 0, 0, 0.699);
                display: flex;
                justify-content: center;
                position: relative;
                h1{
                    font-size: 2rem;
                    position: absolute;
                    bottom: 0;
                }
            }
            .card-info{
                width: 100%;
                height: 35%;
                //  background-color: aqua;
                display: flex;
                justify-content: center;
                align-items: center;
                p{
                    text-align: center;
                    font-size: 1.2rem;
                    
                }
            }
            .card-button{
                width: 100%;
                height: 20%;
                // background-color: rgb(0, 182, 182);
                display: flex;
                justify-content: center;  
                align-items: center; 
                a{
                    padding: 10px 30px;
                    border: 1px solid rgb(216, 216, 216);
                    text-decoration: none;
                    color: black;
                }
            }
        }
    }
</style>