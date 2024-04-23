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
                    <div class="d-flex justify-content-between">
                        <div>
                            <a href=""><img src="../assets/img/footer-logo-1.png" alt=""></a>
                        </div>
                        <nav>
                            <ul class="d-flex">
                                <li><a href="#">HOME</a></li>
                                <li><a href="#">COURSES</a></li>
                                <li><a href="#">INSTRUCTORS</a></li>
                                <li><a href="#">EVENTS</a></li>
                                <li><a href="#">PAGES</a></li>
                                <li><a href="#">ELEMENTS</a></li>
                            </ul>
                        </nav>
                        <nav>
                            <ul class="d-flex justify-content-between">
                                <li><a href=""><i class="fa-solid fa-magnifying-glass"></i></a></li>
                                <li><a href=""><i class="fa-regular fa-clipboard"></i></a></li>
                                <li><a href=""><i class="fa-solid fa-bars"></i></a></li>
                            </ul>
                        </nav>
                
                    </div>
                    <hero class="text-center">
                        <h1>Contemporary Ideas</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus laboriosam magnam commodi ducimus assumenda dolorem ex quos fugiat nam quod quas consectetur, perferendis, non ipsum dolor repellat veritatis. Debitis, autem!</p>
                        <div class="d-flex justify-content-center">
                            <button class="button"><a href="">REGISTER NOW</a></button>
                        </div>
                    </hero>
                </div>
            </div>
        </div>    
</header>


</template>

<style scoped lang="scss">

    @use '../style/partials/variables' as *;

    header {
        background-image: url("../assets/img/course-9-f-img.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        height: 500px;

        .ms-opacity-bg-image {
            background-color: rgba($color: #000000, $alpha: 0.2);
            height: 100%;
        }
        
        li {
            list-style: none;
            padding: 0 10px;
            
            a {
            text-decoration: none;
            color: $color-txt-white-alpha-1;
        }
        }
        
        a {
            text-decoration: none;
        }
    }


</style>