<template>
    <section id="footer">
        <div class="box-info">
            <div class="info">
                <h2>AVADA RESTAURANT</h2>
                <p>Quam eu proin sit massa condimentum. Volutpat non pulvinar
                    aliquet nunc. Quam eu proin sit massa condimentum.
                </p>
                <div class="social">
                    <div class="card"></div>
                    <div class="card"></div>
                    <div class="card"></div>
                    <div class="card"></div>
                    <div class="card"></div>
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
    #footer{
        width: 100%;
        height: 70vh;
        background-image: url(img/footer2x.jpg);
        background-size: cover;
        background-position: bottom;
        .box-info{
            width: 40%;
            height: 100%;
            // background-color: rgba(255, 0, 0, 0.301);
            margin: auto;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            #p-finale{
                color: white;
            }
            .info{
                width: 80%;
                height: 100%;
                // background-color: rgba(255, 255, 255, 0.349);
                text-align: center;
                display: flex;
                flex-direction: column;
                justify-content: space-around;
                h2{
                    color: white;
                    margin: 0px 0px ;
                    position: relative;
                    top: 50px;
                }
                p{
                    color: white;
                    margin: 0px 0px;
                }
                .social{
                    display: flex;
                    justify-content: center;
                    gap: 15px;
                    position: relative;
                    bottom: 50px;
                    .card{
                    width: 75px;
                    height: 75px;
                    background-color: aquamarine;
                    border: 1px solid black;
                }
                }
            }
        }
    }
</style>

