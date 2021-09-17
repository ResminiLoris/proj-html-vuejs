<template>
  <section id="main-section">
    <div class="container pb-5 pt-5">
      <div class="row ">
        <!-- sx (text) -->
        <div class="col-6 p-0">
          <h2 class="text-sec pb-4">We have been educating children for over fifteen years. Our goal is to create a place that engages each child</h2>
          <span class="text-secondary">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Animi nihil, blanditiis dolorum aut vero est autem eius eos corrupti perspiciatis. Vitae inventore possimus repudiandae ipsam doloremque. Velit unde omnis excepturi?</span>
          <ul class="mt-4 ps-0">
            <li class="pb-2"><span class="text-secondary">Comprehensive reporting on individual achievements</span></li>
            <li class="pb-2"><span class="text-secondary">Educational field trips and school presentations</span></li>
            <li class="pb-2"><span class="text-secondary">Individual attention in a small-class setting</span></li>
            <li class="pb-2"><span class="text-secondary">Learning program with after-school care</span></li>
            <li class="pb-2"><span class="text-secondary">Opportunities to carry out scientific investigations</span></li>
            <li class="pb-2"><span class="text-secondary">Positive learning environment for your child</span></li>
          </ul>
        </div>
        <!-- dx (cards) -->
        <div class="col-6 p-0 row">
          <!-- card 1 -->
          <div class="col-6">
            <div class="card bg-none border-0" style="width: 18rem;">
              <div class="img-container  rounded-circle">
                  <img src="../assets/img/toy.png" class="card-img-top" alt="...">
              </div>
              <div class="card-body text-center">
                  <h3 class="text-purple">Title</h3>
                  <p class="card-text text-secondary">Lorem ipsum dolor, sit amet consectetur adipisicing.</p>
              </div>
            </div>
          </div>
          <!-- card 2 -->
          <div class="col-6">
            <div class="card bg-none border-0" style="width: 18rem;">
              <div class="img-container  rounded-circle">
                  <img src="../assets/img/meal.png" class="card-img-top" alt="...">
              </div>
              <div class="card-body text-center">
                  <h3 class="text-purple">Title</h3>
                  <p class="card-text text-secondary">Lorem ipsum dolor, sit amet consectetur adipisicing.</p>
              </div>
            </div>
          </div>
          <!-- card 3 -->
          <div class="col-6">
            <div class="card bg-none border-0" style="width: 18rem;">
              <div class="img-container  rounded-circle">
                  <img src="../assets/img/school.png" class="card-img-top" alt="...">
              </div>
              <div class="card-body text-center">
                  <h3 class="text-purple">Title</h3>
                  <p class="card-text text-secondary">Lorem ipsum dolor, sit amet consectetur adipisicing.</p>
              </div>
            </div>  
          </div>
          <!-- card 4 -->
          <div class="col-6">
            <div class="card bg-none border-0" style="width: 18rem;">
              <div class="img-container  rounded-circle">
                  <img src="../assets/img/shield.png" class="card-img-top" alt="...">
              </div>
              <div class="card-body text-center">
                  <h3 class="text-purple">Title</h3>
                  <p class="card-text text-secondary">Lorem ipsum dolor, sit amet consectetur adipisicing.</p>
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
    name:"Checklist"
}
</script>

<style scoped lang="scss">

@import "@/assets/scss/_vars.scss";

#main-section{
  background-color:#F5F5F5;
}

.text-sec{
  color: $secondary-color;
}
li{
  span::before{
    content: url('../assets/img/list-icon.png');
    vertical-align: middle;
    padding-right: 10px;
  }
}

.bg-none{
  background-color: transparent;
}

.img-container{
  background-color: #fff;
  left: 38%;
  height: 72px;
  width: 72px;
  img{
    height: 40%;
    width: 40%;
  }
}

</style>