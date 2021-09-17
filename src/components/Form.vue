<template>
    <div class="container mt-5 mb-5">
        <div class="row justify-content-center">
            <!-- campi form -->
            <div class="col-6">
                <input type="text" class="form-control mb-4 pt-2 pb-2" id="exampleFormControlInput1" placeholder="Your Name*">
                <input type="email" class="form-control mb-4 pt-2 pb-2" id="exampleFormControlInput1" placeholder="Your E-Mail*">
                <input type="text" class="form-control mb-4 pt-2 pb-2" id="exampleFormControlInput1" placeholder="Subject*">
            </div>
            <!-- your message -->
            <div class="col-6">
                <div class="mb-3">
                    <textarea class="form-control" id="exampleFormControlTextarea1" rows="7" placeholder="Your Message*"></textarea>
                </div>
            </div>
            <div class="btn-orange fs-5">Send Message</div>
        </div>
    </div>
</template>

<script>
export default {
    name:"Form"
}
</script>

<style scoped lang="scss">
@import "@/assets/scss/_vars.scss";

    .btn-orange{
        color: white;
        display: inline-block;
        padding: 10px 20px;
        background-color: $main-color;
        cursor: pointer;
        width: initial;
        &:active{
            background-color: $secondary-color;
        }
    }
</style>