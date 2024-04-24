<script>
    import InfoList from './InfoListHeader.vue';

    export default {
        name: "PageHeader",

        components: {
            InfoList
        },

        props: {
            img: String,
            nav_1: String,
            nav_2: String,
            nav_3: String,
            nav_4: String,
            nav_5: String,
            nav_6: String
        }
    }
</script>

<template>
    <header>
        <InfoList></InfoList>
    </header>
    
<!--
    <header>
        <div class="ms-opacity-bg-image">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <div class="d-flex justify-content-between pt-3">
                            <div>
                                <a href=""><InfoList></InfoList></a>
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
                                <button class="ms-button-blue ms-button-white">REGISTER NOW</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>    
    </header>
-->
</template>