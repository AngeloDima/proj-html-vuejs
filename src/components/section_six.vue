<template>
    <section id="section_six">
        
        <div class="container-card">

            <div class="title"><p>Latest news & promotions</p></div>
            <div class="card">
                <img src="./img/blog92x-1200x1375.jpg" alt="">
                <div class="info-card">
                    <h3>THE BEST COFFEE IN TOWN</h3>
                    <p>By admin January 7th, 2020 Categories: News</p>
                </div>
            </div>

            <div class="card">
                <img src="./img/blog72x-1200x1375.jpg" alt="">
                <div class="info-card">
                    <h3>DISCOVER OUR NEW MENU</h3>
                    <p>By admin January 7th, 2020 Categories: News</p>
                </div>
            </div>

            <div class="card">
                <img src="./img/blog82x-1200x1375.jpg" alt="">
                <div class="info-card">
                    <h3>WE NOW ACCEPT SQUARE!</h3>
                    <p>By admin January 7th, 2020 Categories: News</p>
                </div>
            </div>


        </div>
    </section>
</template>

<script>
    export default{
    Name: `section_six`
    }
</script>

<style lang="scss" scoped>

@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Telugu:wght@300&family=Oswald&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

p{
    font-family: 'Noto Serif Telugu', serif;
}
h2, h3{
    font-family: 'Oswald', sans-serif;
}








    #section_six{
        width: 100%;
        height: 110vh;
        // background-color: antiquewhite;
        display: flex;
        flex-direction: column;
        position: relative;
  
        .container-card{
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 40px;
            // background-color: red;
            position: relative;
            top: 60px;
            
            .title{
                position: absolute;
                top: 0;
                padding-top: 25px;
                font-size: 2.7rem;
                // background-color: red;
                
             }
            .card{
                width: 25%;
                height: 75%;
                //  background-color: aqua;
                display: flex;
                align-items: flex-end;
                position: relative;
                img{
                    width: 100%;
                    height: 80%;
                    position: absolute;
                    top: 0;
                }
                .info-card{
                    width: 100%;
                    height: 20%;
                    //  background-color: aquamarine;
                    display: flex;
                    align-items: center;
                    flex-direction: column;
                    gap: 15px;
                    padding-top: 25px;
                    h3{
                        font-size: 1.7rem;
                    }
                    p{
                        font-size: 0.8rem;
                    }

                }
            }
        }
    } 
</style>