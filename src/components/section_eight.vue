<template>
    <section id="section_six">
        <div class="title">TITOLO</div>
        <div class="container-card">


            <div class="card">
                <div class="info-card"></div>
            </div>

            <div class="card">
                <div class="info-card"></div>
            </div>

            <div class="card">
                <div class="info-card"></div>
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
    #section_six{
        width: 100%;
        height: 100vh;
        background-color: antiquewhite;
        display: flex;
        flex-direction: column;
        .title{
            width: 100%;
            height: 10%;
            background-color: red;
        }
        .container-card{
            width: 100%;
            height: 90%;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 40px;
            .card{
                width: 21.4%;
                height: 70%;
                background-color: aqua;
                display: flex;
                align-items: flex-end;
                .info-card{
                    width: 100%;
                    height: 20%;
                    background-color: aquamarine;
                }
            }
        }
    } 
</style>