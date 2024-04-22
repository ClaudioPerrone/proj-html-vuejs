<script>
    export default {
        name: "PageHeader"
    }
</script>

<template>
    <header>
        <div class="d-flex justify-content-between">
            <div>
                logo
            </div>
            <div>
                <ul class="d-flex">
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">COURSES</a></li>
                    <li><a href="#">INSTRUCTORS</a></li>
                    <li><a href="#">EVENTS</a></li>
                    <li><a href="#">PAGES</a></li>
                    <li><a href="#">ELEMENTS</a></li>
                </ul>
            </div>
            <div>
                <ul class="d-flex justify-content-between">
                    <li><a href=""><i class="fa-solid fa-magnifying-glass"></i></a></li>
                    <li><a href=""><i class="fa-regular fa-clipboard"></i></a></li>
                    <li><a href=""><i class="fa-solid fa-bars"></i></a></li>
                </ul>
            </div>
    
        </div>

        <hero class="d-flex justify-content-center">
            hero img
            
        </hero>
</header>


</template>

<style scoped lang="scss">

    @use '../style/partials/variables' as *;

    li {
        list-style: none;
        padding: 0 10px;
        
        a {
            text-decoration: none;
            color: $color-txt-white-alpha-1;
        }
    }

</style>