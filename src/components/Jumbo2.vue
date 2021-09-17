<template>
  <section class="jumbo-2">
    <div class="container h-100">
      <div class="row justify-content-center align-items-center h-100">
        <div class="col-12 row justify-content-center pt-5">
          <!-- virgolette -->
          <div class="circle mt-5 mb-5">
            <img class="quote" src="../assets/img/quote.png" alt="">
          </div>
        </div>
        <!-- testo -->
        <div class="text-center">
          <h2 class="text-light fs-1 fw-lighter">I have to say that i have 2 children ages 5 and 2 and have used various daycare's in Kindergardebs and this is by far the very best i have ever used</h2>
        </div>
        <!-- linea separazione -->
        <hr class="quote-line">
        <!-- autore -->
        <div class="text-center pb-5">
          <span class="text-light">Cecil j.Kirk</span>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
    name:"Jumbo2"
}
</script>

<style scoped lang="scss">
  .jumbo-2{
    height: 700px;
    background-image: url("../assets/img/jumbo-2.jpg");
    background-repeat: no-repeat;
    background-position-y: center;
    .circle{
      position: relative;
      border: 2px solid white;
      height: 100px;
      width: 100px;
      border-radius: 50%;
      .quote{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
      }
    }
    .quote-line{
      height: 2px;
      color: #fff;
      width: 10%;
      opacity: 100;
    }
  }
</style>