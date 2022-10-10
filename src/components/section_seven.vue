<template>
    <section id="section_three">
        <div class="Sx"></div>
        <div class="Dx">
            <div class="info">
                <p>ENJOY YOUR MEAL AT HOME</p>
                <h1>TAKEOUT NOW AVAILABLE</h1>
                <p>Pellentesque vitae viverra risus, sagittis.
                    Venenatis ridiculus scelerisque nisi in urna
                    nulla non arci moris tortor.
                </p>
                <a href="#">VIEW TAKEOUT MENU</a>
            </div>
        </div>
    </section>
</template>

<script>
    export default{
    Name: `section_seven`,
}
</script>

<style lang="scss" scoped>

@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+Telugu:wght@300&family=Oswald&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

p, a{
    font-family: 'Noto Serif Telugu', serif;
}
h2, h1{
    font-family: 'Oswald', sans-serif;
}







    #section_three{
        width: 100%;
        height: 90vh;
        background-color: rgb(236, 236, 236);
        display: flex;

        .Sx{
            width: 61%;
            height: 100%;
            background-image: url(img/slider72x-scaled.jpg);
            background-size: cover;
            background-position: top;
        }

        .Dx{
            width: 39%;
            height: 100%;
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
            .info{
                width: 50%;
                height: 80%;
                //  background-color: rgba(255, 0, 0, 0.616);


                display: flex;
                justify-content: center;
                
                flex-direction: column;
                gap: 50px;
                p:first-child{
                    font-size: 0.9rem;
                    color: white;
                }
                p:nth-child(3){
                    color: white;
                    font-size: 1.1rem;
                }
                h1{
                    color: white;
                    font-size: 2.8rem;
                }
                a{
                    text-decoration: none;
                    color: white;
                    padding: 12px 25px;
                    border: 1px solid white;
                    width: 62%;
                }
            }
        }
    }
</style>