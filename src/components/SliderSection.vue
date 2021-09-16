<template>
  <section class="pt-5 pb-5">
      <div class="container">
          <div class="row">
                <div class="col-6">
                    <!-- buttoni -->
                    <div class="mb-5">
                        <div class="btn">Overview</div>
                        <div class="btn btn-orange">Our mission</div>
                    </div>
                    <!-- text-section -->
                    <div class="pb-5">
                        <h2 class="text-purple">Our philosophy is learning through play as we offer a stimulating environment for children.</h2>
                    </div>
                    <!-- full day sessions -->
                    <div class="row pb-5">
                        <div class="col-3">
                            <div class="circle">
                                <img class="icon-center" src="../assets/img/clock_alt.png" alt="">
                            </div>
                        </div>
                        <div class="col-9">
                            <h3 class="text-purple">Full day sessions</h3>
                            <span class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias vitae doloribus quibusdam dolorum neque aperiam cupiditate beatae consequatur tenetur libero?</span>
                        </div>
                    </div>
                    <!-- varied classes -->
                    <div class="row pb-5">
                        <div class="col-3">
                            <div class="circle">
                                <img class="icon-center" src="../assets/img/clock_alt.png" alt="">
                            </div>
                        </div>
                        <div class="col-9">
                            <h3 class="text-purple">Full day sessions</h3>
                            <span class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias vitae doloribus quibusdam dolorum neque aperiam cupiditate beatae consequatur tenetur libero?</span>
                        </div>
                    </div>
                </div>
                <!-- carosello -->
              <div class="col-6 row align-items-center ms-2">
                  <div class="col-12">
                        <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                <img src="../assets/img/gallery_08-690x506.jpg" class="d-block w-100" alt="...">
                                </div>
                                <div class="carousel-item">
                                <img src="../assets/img/gallery_07-690x506.jpg" class="d-block w-100" alt="...">
                                </div>
                                <div class="carousel-item">
                                <img src="../assets/img/gallery_01.jpg" class="d-block w-100" alt="...">
                                </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
                                <span class="carousel-control-prev-icon bg-orange" aria-hidden="true"></span>
                                <span class="visually-hidden">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
                                <span class="carousel-control-next-icon bg-orange" aria-hidden="true"></span>
                                <span class="visually-hidden">Next</span>
                            </button>
                        </div>
                  </div>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"SliderSection"
}
</script>

<style scoped lang="scss">
    section{
        background-color: #E8E6E7;
    }
    .btn{
        margin-right: 20px;
        padding: 10px 20px;
        cursor: pointer;
        display: inline-block;
        padding: 10px 20px;
        border-bottom: 1px solid gray;
    }
   .circle{
       background-color: #FE6500;
       height: 100px;
       width: 100px;
       border-radius: 50%;
       position: relative;
       .icon-center{
           position: absolute;
           top: 50%;
           left: 50%;
           transform: translate(-50%,-50%);
       }
   }
   .text-purle{
       color: #56509F;
   }
   
   
</style>