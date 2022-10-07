<template>
    <section class="flex">



        <div class="Sx">
            <div class="logo">
                <img src="./img/logo-restaurant.png" alt="">
            </div>
            <div class="info-header">
                <h1>FINE DINING EXPERIENCE</h1>
                <p>Pellentesque vitae viverra risus, sagittis.
                    Venenatis ridiculus scelerisque nisi in urna
                    nulla. Sit tempor a et nisl, ac felis.
                </p>
                <a href="#">EXPLORE THE MENU</a>
            </div>
        </div>

        <!-- ------------------------------------- -->

        <div class="Dx">
            <div class="menù"></div>
        </div>



    </section>
</template>

<script>
    export default{
    Name: `header_cli`,
}
</script>

<style lang="scss" scoped>
    .flex{
        display: flex;
    }


    .Sx{
        width: 40%;
        height: 100vh;
        background-color: rgb(0, 0, 0);
        display: flex;
        flex-direction: column;
        
        gap: 15%;
        .logo img{
            width: 250px;
            height: 60px;
            margin: 20px 20px;
            // background-color: aqua;
        }


        .info-header{
            width: 70%;
            height: 55%;
            background-color: red;
            margin: auto;
            position: relative;
            bottom: 10%;
            h1{
                color: white;
                text-align: left;
            }
            p{
                color: rgb(231, 231, 231);
                text-align: left;
            }
            a{
                color: white;
                padding: 10px 20px;
                border: 1px solid white;
                text-decoration: none;
            }
        }
    }
    
    .Dx{
        width: 60%;
        height: 100vh;
        background-image: url(img/slider52x.jpg);
        background-size: cover;
        .menù{
            width: 100%;
            height: 10%;
            background-color: rgba(0, 255, 255, 0.534);
        }
    }


</style>
.