<script>
    import InfoCardHeader from './InfoCardHeader.vue';

    export default {
        name: "InfoListHeader",

        components: {
            InfoCardHeader
        },

        data() {
            return {
                infosHeader: [
                    {
                        "img": "./src/assets/img/footer-logo-1.png",
                        "nav_1": "HOME",
                        "nav_2": "COURSES",
                        "nav_3": "INSTRUCTORS",
                        "nav_4": "EVENTS",
                        "nav_5": "PAGES",
                        "nav_6": "ELEMENTS"
                    }
                ]
            }
        }
    }
</script>

<template>
    <div v-for="info in infosHeader">
        <InfoCardHeader :AllTheInfosHeader="info"></InfoCardHeader>
    </div>
</template>