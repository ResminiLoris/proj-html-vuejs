<template>
  <section>
      <div class="container mb-5">
        <div class="row g-5">
            <!-- card 1 -->
            <div class="col-6">
                <div class="class-card row">
                    <div class="col-6 p-3">
                        <!-- top -->
                        <div class="mb-5">
                            <h3 class="fs-2 text-light">Little lambs</h3>
                            <span class="gray">class name</span>
                        </div>
                        <!-- bottom -->
                        <div class="text-center">
                            <div class="d-inline-block ps-3 pe-3 border-end">
                                <h3 class="text-light">3/4</h3>
                                <span class="gray">months old</span>
                            </div>
                            <div class="d-inline-block ps-3 pe-3">
                                <h3 class="text-light">9</h3>
                                <span class="gray">class size</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 p-0">
                        <img class="img-fluid" src="../assets/img/card-1.jpg" alt="">
                    </div>
                </div>
            </div>
            <!-- card 2 -->
            <div class="col-6">
                <div class="class-card row">
                    <div class="col-6 p-3">
                        <!-- top -->
                        <div class="mb-5">
                            <h3 class="fs-2 text-light">Bouncy Bears</h3>
                            <span class="gray">class name</span>
                        </div>
                        <!-- bottom -->
                        <div class="text-center">
                            <div class="d-inline-block ps-3 pe-3 border-end">
                                <h3 class="text-light">2/3</h3>
                                <span class="gray">years old</span>
                            </div>
                            <div class="d-inline-block ps-3 pe-3">
                                <h3 class="text-light">12</h3>
                                <span class="gray">class size</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 p-0">
                        <img class="img-fluid" src="../assets/img/card-2.jpg" alt="">
                    </div>
                </div>
            </div>
            <!-- card 3 -->
            <div class="col-6 mt-4">
                <div class="class-card row">
                    <div class="col-6 p-3">
                        <!-- top -->
                        <div class="mb-5">
                            <h3 class="fs-2 text-light">Tenderhearts</h3>
                            <span class="gray">class name</span>
                        </div>
                        <!-- bottom -->
                        <div class="text-center">
                            <div class="d-inline-block ps-3 pe-3 border-end">
                                <h3 class="text-light">3/4</h3>
                                <span class="gray">years old</span>
                            </div>
                            <div class="d-inline-block ps-3 pe-3">
                                <h3 class="text-light">15</h3>
                                <span class="gray">class size</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 p-0">
                        <img class="img-fluid" src="../assets/img/card-3.jpg" alt="">
                    </div>
                </div>
            </div>
            <!-- card 4 -->
            <div class="col-6 mt-4">
                <div class="class-card row">
                    <div class="col-6 p-3">
                        <!-- top -->
                        <div class="mb-5">
                            <h3 class="fs-2 text-light">Shiny Stars</h3>
                            <span class="gray">class name</span>
                        </div>
                        <!-- bottom -->
                        <div class="text-center">
                            <div class="d-inline-block ps-3 pe-3 border-end">
                                <h3 class="text-light">4/5</h3>
                                <span class="gray">years old</span>
                            </div>
                            <div class="d-inline-block ps-3 pe-3">
                                <h3 class="text-light">20</h3>
                                <span class="gray">class Size</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 p-0">
                        <img class="img-fluid" src="../assets/img/card-4.jpg" alt="">
                    </div>
                </div>
            </div>
        </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"Cards"
}
</script>

<style lang="scss">
@import "@/assets/scss/_vars.scss";

.class-card{
    background-color: $secondary-color;
    cursor: pointer;
}
.gray{
    color: #C5C2DE;
}

</style>