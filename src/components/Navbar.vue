<template>
    <div class="container">
        <nav id="main-row" class="row align-items-center justify-content-between">
            <!-- logo -->
            <div class="col-5 h-100 align-self-end">
                <img class="img-fluid h-100 logo" src="../assets/img/logo.png" alt="">
            </div>
            <!-- links -->
            <div class="col-7 h-100 row">
               <ul>
                   <!-- home -->
                   <li>
                       <div class="link">
                            <img src="../assets/img/house_purple.png" alt="">
                            <figcaption>Home</figcaption>   
                       </div>
                   </li>
                   <!-- pages -->
                   <li>
                       <div class="link">
                            <img src="../assets/img/document_purple.png" alt="">
                            <figcaption>pages</figcaption>   
                       </div>
                   </li>
                   <!-- blog -->
                   <li>
                       <div class="link">
                            <img src="../assets/img/blog_purple.png" alt="">
                            <figcaption>blog</figcaption>   
                       </div>
                   </li>
                   <!-- shop -->
                   <li>
                       <div class="link">
                            <img src="../assets/img/cart_purple.png" alt="">
                            <figcaption>shop</figcaption>   
                       </div>
                   </li>
                   <!-- shortcodes -->
                   <li class="less-padding">
                       <div class="link">
                            <img src="../assets/img/lab_purple.png" alt="">
                            <figcaption>shortcodes</figcaption>   
                       </div>
                   </li>
                   <!-- support -->
                   <li>
                       <div class="link">
                            <img src="../assets/img/support_purple.png" alt="">
                            <figcaption>support</figcaption>   
                       </div>
                   </li>
                   <!-- contact -->
                   <li>
                       <div class="link">
                            <img src="../assets/img/contact_purple.png" alt="">
                            <figcaption>contact</figcaption>   
                       </div>
                   </li>
               </ul>
            </div>
        </nav>
    </div>
        
</template>

<script>
export default {
    name:"Navbar",   
}

</script>

<style scoped lang="scss">

    #main-row{
        height: 150px;
        ul{
            height: 100%;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            li{
                height: 100%;
                display: flex;
                align-items: center;
                padding: 0 30px;
                text-align: center;
                cursor: pointer;
                color: #56509F;
                &:hover{
                    background-color:#FE6500;
                }
                figcaption{
                    padding-top: 10px;
                    text-transform: capitalize;
                }
            }
        }
        .less-padding{
            padding: 0 10px;
        }
    }
</style>