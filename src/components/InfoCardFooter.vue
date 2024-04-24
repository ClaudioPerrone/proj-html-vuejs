<script>
    export default {
        name: 'InfoCardFooter',

        props: {
            AllTheInfosFooter: Object
        }
    }
</script>

<template>
    <footer class="pt-5">
        <div class="container py-5">
            <div class="row pt-5">
                <div class="col-3">
                    <ul>
                        <img class="pb-5" :src=AllTheInfosFooter.img_logo>
                        <!-- <img class="pb-5" src="../assets/img/logo-light.png"> -->
                        <li><p>Providing Life Changing Experience Through Education. Class That Fit Your Busy Life. Closer to Home</p></li>
                        <p class="pb-1"><i class="fa-solid fa-phone pe-4"></i>1-677-124-44227</p>
                        <p><i class="fa-regular fa-clock pe-4"></i>Mon - Sat 8.00 - 18.00</p>
                    </ul>
                </div>
                <div class="col-3">
                    <ul>
                        <li class="pb-5">
                            <h2>Popular Courses</h2>
                        </li>
                        <li class="pb-3">
                            <h4>Business English</h4>
                            <h5>Preston Marshall</h5>
                        </li>
                        <li class="pb-3">
                            <h4>Social Computing</h4>
                            <h5>David Sanders</h5>
                        </li>
                        <li class="pb-3">
                            <h4>Learn Spanish</h4>
                            <h5>Jennie King</h5>
                        </li>
                    </ul>
                </div>
                <div class="col-3">
                    <div>
                        <ul>
                            <li class="pb-5"><h2>Support</h2></li>
                            <li><p>User dashboard</p></li>
                            <li><p>Contact Us</p></li>
                            <li><p>FAQ</p></li>
                            <li><p>Course Offer</p></li>
                            <li><p>Events</p></li>
                        </ul>
                    </div>
                </div>
                <div class="col-3">
                    <h2 class="pb-5">Flexible Learning</h2>
                    <img :src=AllTheInfosFooter.img_earth>
                    <!-- <img src="../assets/img/footer-img-1.png" alt=""> -->
                </div>
            </div>
        </div>
        <div class="line container d-flex justify-content-center"></div>
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex justify-content-between p-5">
                    <div>
                        <p>Copyrights 2017 @Mikado Themes</p>
                    </div>
                    <div class="d-flex justify-content-between align-items-center">
                        <p class="pe-4">CALL +44 300 303 0266</p>
                        <p class="pe-4">FOLLOW US</p>
                        <i class="fa-brands fa-twitter pe-3 pb-3"></i>
                        <i class="fa-brands fa-instagram pe-3 pb-3"></i>
                        <i class="fa-brands fa-facebook-f pe-3 pb-3"></i>
                    </div>
                </div>
            </div>
        </div>  
    </footer>
</template>

<style scoped lang="scss">

    @use '../style/partials/variables' as *;

    footer {
        background-color: $color-black;
        color: $color-grey-1;

        .line {
            border: 1px solid $color-grey-2;
            height: 1px;
            width: 65%;
        }
    
        li {
            list-style: none;
        }

        .col-12 {
            color: $color-grey-2;
        }

        .col-3 {
            img {
                width: 80%;
            }
        }
    }
</style>