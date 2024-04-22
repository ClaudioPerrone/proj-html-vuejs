<script>
    export default {
        name: "PageFooter"
    }
</script>

<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-3">
                    <ul>
                        <li>iAcademy</li>
                        <li><p>Providing Life Changing Experience Through Education. Class That Fit Your Busy Life. Closer to Home</p></li>

                    </ul>
                </div>
                <div class="col-3">
                    <ul>
                        <li>
                            <h2>Popular Courses</h2>
                        </li>
                        <li>
                            <h3>Business English</h3>
                            <h3>Preston Marshall</h3>
                        </li>
                        <li>
                            <h3>Social Computing</h3>
                            <h3>David Sanders</h3>
                        </li>
                        <li>
                            <h3>Learn Spanish</h3>
                            <h3>Jennie King</h3>
                        </li>
                    </ul>
                </div>
                <div class="col-3">
                    <div>
                        <ul>
                            <li><h2>Support</h2></li>
                            <li><p>User dashboard</p></li>
                            <li><p>Contact Us</p></li>
                            <li><p>FAQ</p></li>
                            <li><p>Course Offer</p></li>
                            <li><p>Events</p></li>
                        </ul>
                    </div>
                </div>
                <div class="col-3">
                    <h2>Flexible Learning</h2>
                    img world
                </div>
            </div>
        </div>    
        <div class="line d-flex justify-content-center"></div>
        <div class="d-flex justify-content-between">
            <div>
                <p>Copyrights 2017 @Mikado Themes</p>
            </div>
            <div class="d-flex justify-content-between">
                <p>CALL +44 300 303 '266'</p>
                <p>FOLLOW US</p>
                <div class="d-flex justify-content-between">
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-instagram"></i>
                    <i class="fa-brands fa-facebook-f"></i>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped lang="scss">

    @use '../style/partials/variables' as *;

    .line {
        border: 1px solid black;
        height: 1px;
        width: 50%;
    }

    li {
        list-style: none;
    }

</style>