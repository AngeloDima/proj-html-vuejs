<template>
    <section id="section_eight">


        <div class="card">
            <div class="info-card">


                <div class="cattegorie">
                    <h2>HORS D'OEUVRES</h2>
                </div>

                <div class="name-dessert">
                    <h3>AHI SALMON NIGIRI</h3>
                    <h5>$48</h5>
                </div>

                <div class="description-dessert">
                    <p>Eget vulputate vitae quis rutrum blandit
                        sed. Quam nulla sit lacinia.
                    </p>
                </div>

                <!-- ----- -->


                <div class="name-dessert">
                    <h3>UMI MASU SALAD</h3>
                    <h5>$21</h5>
                </div>

                <div class="description-dessert">
                    <p>Mollis ornare sit sapien, sodales. Cursus
                        duis proin semper quisque.
                    </p>
                </div>


                <!-- ------ -->


                <div class="name-dessert">
                    <h3>TEMAKI WITH CRAB</h3>
                    <h5>$32</h5>
                </div>

                <div class="description-dessert">
                    <p>Ac vel, risus ornare senectus placerat duis
                        amet dictumst tellus.
                    </p>
                </div>

                <!-- ----- -->


                <div class="name-dessert">
                    <h3>CALIFORNIA ROLLS</h3>
                    <h5>$22</h5>
                </div>

                <div class="description-dessert">
                    <p>Ac vel, risus ornare senectus placerat duis
                        amet dictumst tellus.
                    </p>
                </div>

            </div>
        </div>



        <div class="card-up">
            <div class="effect"></div>
            <img src="./img/misc22x.jpg" alt="">
            <div class="info-up">


                <div class="cattegorie">
                    <h2>MAIN COURSE</h2>
                </div>

                <div class="name-dessert">
                    <h3>BRAISED ABALONE</h3>
                    <h5>$52</h5>
                </div>

                <div class="description-dessert">
                    <p>Mollis ornare sit sapien, soales. Cursus 
                       duis proin semper quisque.
                    </p>
                </div>

                <!-- ----- -->


                <div class="name-dessert">
                    <h3>TWICE COOKED PORK</h3>
                    <h5>$21</h5>
                </div>

                <div class="description-dessert">
                    <p>Ac vel, risus ornare senectus placerat dduis
                        amet dictumst tellus
                    </p>
                </div>


                <!-- ------ -->


                <div class="name-dessert">
                    <h3>KUNG PAO CHICKEN</h3>
                    <h5>$32</h5>
                </div>

                <div class="description-dessert">
                    <p>Quis duis sit dictum aliquam a velit enim.
                        Tellus in sit augue aliquam.
                    </p>
                </div>


                <!-- ----- -->


                <div class="name-dessert">
                    <h3>CHAR SIU & SUSHIS</h3>
                    <h5>$48</h5>
                </div>

                <div class="description-dessert">
                    <p>Feugiat rhoncus ipsum tristique purus
                        diam, et dolor molestie.
                    </p>
                </div>



            </div>
        </div>



        <div class="card">
            <div class="info-card">
                
                <div class="cattegorie">
                    <h2>DESSERTS</h2>
                </div>

                <div class="name-dessert">
                    <h3>CHOCOLATE BALL CAKE</h3>
                    <h5>$13</h5>
                </div>

                <div class="description-dessert">
                    <p>In pellentesque in felis massa vehicula. In
                    sed euismod ut.
                    </p>
                </div>

                <!-- ----- -->

                <div class="name-dessert">
                    <h3>LIME PIE WITH CRUST</h3>
                    <h5>$14</h5>
                </div>

                <div class="description-dessert">
                    <p>Mollis orare sit sapien, sodales. Cursus
                        duis proin semper quisque.
                    </p>
                </div>


                <!-- ------ -->


                <div class="name-dessert">
                    <h3>RASBERRY PEAR CAKE</h3>
                    <h5>$18</h5>
                </div>

                <div class="description-dessert">
                    <p>Eget vulputate vitae quis rutrum blandit
                        sed. Quam nulla sit.
                    </p>
                </div>

                <!-- ----- -->


                <div class="name-dessert">
                    <h3>CAFE AU LAIT</h3>
                    <h5>$6</h5>
                </div>

                <div class="description-dessert">
                    <p>Eget vulputate vutae quis rutrum blandit
                        sed. Quam nulla sit.
                    </p>
                </div>

            </div>


        </div>
    </section>
</template>

<script>
    export default{
    Name: `section_eight`
    }
</script>

<style lang="scss" scoped>







    #section_eight{
        width: 100%;
        height: 120vh;
        // background-color: aqua;
        display: flex;
        justify-content: center;
        align-items: center;
        .card{
            width: 23.5%;
            height: 60%;
            background-color: rgb(229 229 229);
            display: flex;
            justify-content: center;
            align-items: center;
            .info-card{
                width: 70%;
                // height: 90%;
                // background-color: white;
                .cattegorie{
                    width: 100%;
                    // background-color: blue;
                    margin: 20px 0px;
                }
                .name-dessert{
                    width: 100%;
                    //  background-color: aqua;
                    margin: 45px 0px 20px 0px;
                    position: relative;
                    h5{
                        position: absolute;
                        right: 0;
                        top: 5px;
                    }
                }
                .description-dessert{
                    width: 100%;
                    color: rgb(87, 87, 87);
                    // background-color: aquamarine;
                }
            }
        }
        .card-up{
            width: 23.4%;
            height: 60%;
            // background-color: rgb(0, 192, 0);
            position: relative;
            bottom: 5%;
            img{
                height: 100%;
                width: 100%;
                
            }
            .effect{
                width: 100%;
                height: 100%;
                background-color: rgba(0, 0, 0, 0.349);
                position: absolute;
                bottom: 0;
                box-shadow: 0px 290px 70px -40px inset rgb(0, 0, 0);;
            }
            .info-up{
                width: 70%;
                // height: 80%;
                //  background-color: aliceblue;
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
                
                .cattegorie{
                    width: 100%;
                    // background-color: blue;
                    margin: 20px 0px;
                    color: white;
                }
                .name-dessert{
                    width: 100%;
                //  background-color: aqua;
                    margin: 45px 0px 20px 0px;
                    color: white;
                    position: relative;
                    h5{
                        position: absolute;
                        right: 0;
                        top: 5px;
                    }
                }
                .description-dessert{
                    width: 100%;
                    color: rgba(255, 255, 255, 0.671);
                    // background-color: aquamarine;
                }
            }
        }
    }
</style>