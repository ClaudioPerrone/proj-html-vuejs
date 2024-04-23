<script>
    export default {
        name: "PageHeader"
    }
</script>

<template>
    <header>
        <div class="ms-opacity-bg-image">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <div class="d-flex justify-content-between pt-3">
                            <div>
                                <a href=""><img src="../assets/img/footer-logo-1.png" alt=""></a>
                            </div>
                            <nav class="pt-3">
                                <ul class="d-flex">
                                    <li><a href="#">HOME</a></li>
                                    <li><a href="#">COURSES</a></li>
                                    <li><a href="#">INSTRUCTORS</a></li>
                                    <li><a href="#">EVENTS</a></li>
                                    <li><a href="#">PAGES</a></li>
                                    <li><a href="#">ELEMENTS</a></li>
                                </ul>
                            </nav>
                            <nav class="pt-3">    
                                <ul class="d-flex">
                                    <li><a href=""><i class="fa-solid fa-magnifying-glass"></i></a></li>
                                    <li><a href=""><i class="fa-regular fa-clipboard"></i></a></li>
                                    <li><a href=""><i class="fa-solid fa-bars"></i></a></li>
                                </ul>
                            </nav>
                    
                        </div>
                        <div class="hero text-center">
                            <h1>Contemporary Ideas</h1>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus laboriosam magnam commodi ducimus assumenda dolorem ex quos fugiat nam quod quas consectetur, perferendis, non ipsum dolor repellat veritatis. Debitis, autem!</p>
                            <div class="d-flex justify-content-center">
                                <button class="ms-button-blue"><a href="">REGISTER NOW</a></button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>    
    </header>
</template>

<style scoped lang="scss">

    @use '../style/partials/variables' as *;

    header {
        background-image: url("../assets/img/course-9-f-img.jpg");
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
        height: 700px;
/*--------------------------------

            HERO

------------------------------- */
        .hero {
            padding-top: 15%;
            color: $color-white;

            h1 {
                font-size: 70px;
            }
        }

        button {
            &.ms-button-blue {
                padding: 15px 40px;
                background-color: $color-blue;
                color: $color-white;
                border-style: none;
            }
        }

        .ms-opacity-bg-image {
            background-color: $color-alpha-3;
            height: 100%;
        }
        
        li {
            list-style: none;
            padding: 0 10px;
            
            a {
            text-decoration: none;
            color: $color-white;
        }
        }
        
        a {
            text-decoration: none;
            color: $color-white;
        }
    }


</style>