<template>
  <section>
      <div class="container mb-5">
          <div class="row justify-content-center">
              <!-- card 1 -->
              <div class="col-4">
                    <div class="card border-0 mb-5 w-100" style="width: 18rem;">
                        <span class="text-secondary pb-3">October 03, 2014</span>
                        <img src="../assets/img/news-1.jpg" class="card-img-top" alt="...">
                        <div class="card-body p-0 pt-4">
                            <h3 class="text-sec mb-2">Drawing and Painting Lessons</h3>
                            <p class="text-secondary pb-4 border-bottom">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui id blanditiis minima delectus. Tenetur eum ipsa impedit cumque officia ut dolores distinctio voluptatibus a facere. Aliquid fuga quos obcaecati tempora!</p>
                            <span class="author text-secondary me-4"> Anna Brown</span>
                            <span class="type text-secondary me-4">Events, Fun</span>
                        </div>
                    </div>
              </div>
              <!-- card 2 -->
              <div class="col-4">
                  <div class="card border-0 mb-5 w-100" style="width: 18rem;">
                        <span class="text-secondary pb-3">October 03, 2014</span>
                        <img src="../assets/img/news-2.jpg" class="card-img-top" alt="...">
                        <div class="card-body p-0 pt-4">
                            <h3 class="text-sec mb-2">Fall Parents Meeting Day</h3>
                            <p class="text-secondary pb-4 border-bottom">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui id blanditiis minima delectus. Tenetur eum ipsa impedit cumque officia ut dolores distinctio voluptatibus a facere. Aliquid fuga quos obcaecati tempora!</p>
                            <span class="author text-secondary me-4"> Anna Brown</span>
                            <span class="type text-secondary me-4">Dance, Education</span>
                        </div>
                    </div>
              </div>
              <!-- card 3 -->
              <div class="col-4">
                  <div class="card border-0 mb-5 w-100" style="width: 18rem;">
                        <span class="text-secondary pb-3">October 03, 2014</span>
                        <img src="../assets/img/news-3.jpg" class="card-img-top" alt="...">
                        <div class="card-body p-0 pt-4">
                            <h3 class="text-sec mb-2">Birthday in Kindergarden</h3>
                            <p class="text-secondary pb-4 border-bottom">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui id blanditiis minima delectus. Tenetur eum ipsa impedit cumque officia ut dolores distinctio voluptatibus a facere. Aliquid fuga quos obcaecati tempora!</p>
                            <span class="author text-secondary me-4"> Anna Brown</span>
                            <span class="type text-secondary me-4">Games, General</span>
                        </div>
                    </div>
              </div>
              <!-- bottone -->
              <div class="button text-light text-uppercase fw-bold"><span>go to blog</span></div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"News"
}
</script>

<style scoped lang="scss">
@import "@/assets/scss/_vars.scss";


.author::before{
    content: url("../assets/img/author.png");
    padding-right: 10px;

}
.type::before{
    content: url("../assets/img/category.png");
    padding-right: 10px;
}
.button{
    display: inline-block;
    background-color: $main-color;
    padding: 10px 20px;
    width:initial;
    cursor: pointer;
    span::after{
    content: url("../assets/img/slider_next.png");
    vertical-align: middle;
    }
}

</style>