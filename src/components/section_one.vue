<template>
    <section id="section_two">
        <div class="Sx">
            <div class="info-up">
                <p><strong>HAC TELLUS, FELIS RISUS AT</strong> mattis mattis. Eget euismod
                semper eget tortor, donec amet, blandit. Tristique facilisi faucibus
                elementum feugiat in nam in feugiat. Ipsum odio etiam duis facilisis amet vulputate.
                </p>
            </div>
            <div class="info-midle">
                <h2>
                    FOOD IS OUR COMMON
                    GROUND, A UNIVERSAL
                    EXPERIENCE.
                </h2>
            </div>
            <div class="info-bottom">
                <p>
                    Tristique tempus condimentum diam donec. Condimentum
                    ullamcorper sit elemtum henrerit mi nulla in cosequat, ut.
                    Metus, nullam scelerisque netus viverra dui.
                </p>
                <img src="./img/signature-200x172.jpg" alt="">
            </div>
        </div>
        <div class="Dx">
            <p>CALIFORNIA ROLLS - $22</p>
        </div>
    </section>
</template>

<script>
    export default{
    Name: `section_one`,
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Telugu:wght@300&family=Oswald&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

p{
    font-family: 'Noto Serif Telugu', serif;
}
h2{
    font-family: 'Oswald', sans-serif;
}

    #section_two{
        width: 100%;
        height: 100vh;
        background-color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 5%;

        .Sx{
            width: 30%;
            height: 80%;
            // background-color: red;
            display: flex;
            flex-direction: column;
            gap: 45px;
            position: relative;
            .info-up{
                width: 100%;
                // height: 20%;
                // background-color: aqua;
                p{
                    font-size: 1.15rem;
                }
            }
            .info-midle{
                width: 100%;
                // height: 40%;
                // background-color: rgb(0, 255, 128);
                h2{
                    font-size: 4rem;
                }
            }
            .info-bottom{
                width: 100%;
                // height: 20%;
                // background-color: aqua;
                
                p{
                    font-size: 1.15rem;
                }
                img{
                    position: absolute;
                    bottom: 0;
                }
            }
        }

        .Dx{
            width: 35%;
            height: 80%;
            background-image: url(./img/info22x.jpg);
            background-size: cover;
            background-position: center;
            display: flex;
            justify-content: center;
            align-items: flex-end;
            
            p{
                color: white;
                position: relative;
                bottom: 15px;
            }
        }
    }
</style>