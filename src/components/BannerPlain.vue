<template>
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
</template>

<script>
export default {
    name:"BannerPlain"
}
</script>

<style scoped lang="scss">
  .banner{
    background-color: #56509F;
    height: 150px;
    .btn-transparent{
      color: white;
      font-size: 18px;
      border: 1px solid white;
      text-align: center;
      padding: 10px;
      cursor: pointer;
    }
  }
</style>