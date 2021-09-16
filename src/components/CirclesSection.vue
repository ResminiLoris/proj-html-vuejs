<template>
    <section>
        <div class="container">
            <div class="row mt-5 mb-5">
                <!-- title -->
                <div class="col-12 text-center pt-4 pb-4 mb-5">
                    <h2 class="text-purple text-big">Welcome to Fable</h2>
                    <span class="text-secondary d-block pb-3">Fable daycare, preschool and Kindergarden</span>
                    <img src="../assets/img/header_divider.png" alt="">
                </div>
                <!-- card 1 -->
                <div class="col-3">
                    <div class="card border-0" style="width: 18rem;">
                        <div class="img-container bg-orange rounded-circle">
                            <img src="../assets/img/schoolbag_alt.png" class="card-img-top" alt="...">
                        </div>
                        <div class="card-body text-center">
                            <h3 class="text-purple">Title</h3>
                            <p class="card-text text-secondary">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                    </div>
                </div>
                <!-- card 2 -->
                <div class="col-3">
                     <div class="card border-0" style="width: 18rem;">
                        <div class="img-container bg-purple rounded-circle">
                            <img src="../assets/img/schoolbag_alt.png" class="card-img-top" alt="...">
                        </div>
                        <div class="card-body text-center">
                            <h3 class="text-purple">Title</h3>
                            <p class="card-text text-secondary">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                    </div>
                </div>
                <!-- card 3 -->
                <div class="col-3">
                     <div class="card border-0" style="width: 18rem;">
                        <div class="img-container bg-orange rounded-circle">
                            <img src="../assets/img/schoolbag_alt.png" class="card-img-top" alt="...">
                        </div>
                        <div class="card-body text-center">
                            <h3 class="text-purple">Title</h3>
                            <p class="card-text text-secondary">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                    </div>
                </div>
                <!-- card 4 -->
                <div class="col-3">
                     <div class="card border-0" style="width: 18rem;">
                        <div class="img-container bg-purple rounded-circle">
                            <img src="../assets/img/schoolbag_alt.png" class="card-img-top" alt="...">
                        </div>
                        <div class="card-body text-center">
                            <h3 class="text-purple">Title</h3>
                            <p class="card-text text-secondary">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:"CircleSection"
}
</script>

<style  lang="scss">
    .img-container{
        position: relative;
        left: 25%;
        height: 144px;
        width: 144px;
        img{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            height: 50px;
            width: 50px;
        }
    }
        .text-purple{
            color: #56509F;
        }
        .bg-orange{
            background-color: #FE6500;
        }
        .bg-purple{
            background-color: #56509F;
        }
        .text-big{
            font-size: 50px;
        }
    
</style>