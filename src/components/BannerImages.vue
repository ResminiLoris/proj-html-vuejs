<template>
    <section>
        <div class=" banner container-fluid p-0 m-0 row">
            <!-- images -->
            <div class="banner-images col-12 p-0 m-0 row">
                <div class="image col-3 p-0">
                    <img class="img-fluid" src="../assets/img/banner1.jpg" alt="">
                </div>
                <div class="image col-3 p-0">
                    <img class="img-fluid" src="../assets/img/banner2.jpg" alt="">
                </div>
                <div class="image col-3 p-0">
                    <img class="img-fluid h-100" src="../assets/img/banner3.jpg" alt="">
                </div>
                <div class="image col-3 p-0">
                    <img class="img-fluid" src="../assets/img/banner4.jpg" alt="">
                </div>
            </div>
            <!-- banner -->
            <div class="col-12 row row-text p-0 m-0 pt-5 pb-5">
                <div class="banner">
                    <div class="container h-100">
                    <div class="row h-100">
                        <div class="col-10 row align-items-center">
                        <h1 class="text-light">How to Enroll Your Child to a Class</h1>
                        </div>
                        <div class="col-2 row align-items-center">
                        <div class="btn-transparent">Learn More</div>
                        </div>
                    </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:"BannerImages"
}
</script>

<style scoped lang="scss">
    .banner{
        .banner-images{
            height: 70%;
            .image{
                height: 100%;
            }
        }
        .row-text{
            background-image: url('../assets/img/pattern.png');
        }
    }
    .btn-transparent{
        color: white;
        font-size: 18px;
        border: 1px solid white;
        text-align: center;
        padding: 10px;
        cursor: pointer;
    }
</style>