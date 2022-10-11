<template>
    <section class="flex">



        <div class="Sx">
            <div class="logo">
                <img src="./img/logo-restaurant.png" alt="">
            </div>
            <div class="info-header">
                <p>THE BEST TABLE IN TOWN</p>
                <h1>FINE DINING <br> EXPERIENCE</h1>
                <p>Pellentesque vitae viverra risus, sagittis.
                    Venenatis ridiculus scelerisque nisi in urna
                    nulla. Sit tempor a et nisl, ac felis.
                </p>
                <a href="#">EXPLORE THE MENU</a>
                
            </div>
            <div class="sbarra"></div>
        </div>

        <!-- ------------------------------------- -->

        <div class="Dx">
            <div class="menù">
                <ul>
                    <li><a href="">Home</a></li>
                    <li><a href="">Culinary History</a></li>
                    <li><a href="">Our Team</a></li>
                    <li><a href="">Our Menù</a></li>
                    <li><a href="">Takeout</a></li>
                    <li><a href="">Bulletin</a></li>
                    <li><a href="">Reservations</a></li>
                    <font-awesome-icon icon="fa-duotone fa-cart-shopping" />
                </ul>
            </div>
        </div>



    </section>
</template>

<script>
    export default{
    Name: `header_cli`,
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Telugu:wght@300&family=Oswald&display=swap');

*{
    
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }

.sbarra{
    width: 60px;
    height: 2px;
    background-color: rgba(255, 255, 255, 0.521);
    position: relative;
    bottom: 723px;
    left: 50px;
      
}

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
            position: relative;
            left: 40px;
            top: 10px;
            // background-color: aqua;
        }


        .info-header{
            width: 60%;
            height: 55%;
            // background-color: red;
            margin: auto;
            position: relative;
            bottom: 10%;
            h1{
                color: rgb(255, 255, 255);
                text-align: left;
                font-size: 5rem;
                font-family: 'Oswald', sans-serif;
            }
            p{
                color: rgb(231, 231, 231);
                text-align: left;
                font-size: 1.2rem;
                margin: 35px 70px 20px 0px;
                font-family: 'Noto Serif Telugu', serif;
                
            }
            a{
                color: white;
                padding: 10px 55px;
                border: 1px solid white;
                text-decoration: none;
                position: absolute;
                bottom: 0px;
                font-family: 'Oswald', sans-serif;
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
            // background-color: rgba(0, 255, 255, 0.534);
            display: flex;
            justify-content: center;
            align-items: center;
            
            ul{
                display: flex;
                list-style: none;    
                 
                li{
                    margin: 0px 30px;
                    a{
                        text-decoration: none;
                        color: rgba(255, 255, 255, 0.897);
                        font-family: 'Oswald', sans-serif;
                         
                    }
                }
            }
        }
    }


</style>
.