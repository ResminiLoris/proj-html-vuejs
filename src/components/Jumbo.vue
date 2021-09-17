<template>
  <section class="jumbo container-fluid pt-4">
      <!-- sx side (text) -->
        <div class="container">
            <div class="text">
                <span class="orange">Friendly Atmosphere</span>
                <h2 class="title secondary-clr">Welcoming Place</h2>
                <span class="secondary-clr d-block">For Every Child</span>
                <div class="btn-orange fs-5">Buy this theme now</div>
            </div>
        </div>
        <!-- dx side (images) -->
        <div class="images">
            <img class="image-1 h-100" src="../assets/img/slider_slide2_img1.png" alt="">
            <img class="image-2 h-100" src="../assets/img/slider_slide2_img2.png" alt="">
        </div>
  </section>
</template>

<script>
export default {
    name: "Jumbo"
}
</script>

<style lang="scss">
@import "@/assets/scss/_vars.scss";

    .jumbo{
        height: 600px;
        background-image: linear-gradient(to top,#E8E6E7 0, #E8E6E7 20%, white 30%, #DDEDFA 80% );
        .text{
            display: inline-block;
            font-size: 50px;
            position: absolute;
            top: 35%;
                .orange{
                    color: $main-color;
                }
                .secondary-clr{
                    color: $secondary-color;
                }
                .title{
                    font-size: 60px;
                }
                .btn-orange{
                    color: white;
                    display: inline-block;
                    padding: 10px 20px;
                    background-color: $main-color;
                    cursor: pointer;
                    &:active{
                        background-color: $secondary-color;
                    }
                }
        }

        .images{
            position: absolute;
            right: 0;
            width: 50%;
            .image-2{
                    position: absolute;
                    right: 100px;
                    z-index: 1;
                }

                .image-1{
                    position: relative;
                    z-index: 2;
                }
        }

    }
    
</style>