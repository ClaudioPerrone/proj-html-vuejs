<script>
    import InfoCard from './InfoCardHeader.vue';

    export default {
        name: "InfoListHeader",

        components: {
            InfoCard
        },

        data() {
            return {
                infos: [
                    {   /* HEADER */
                        "img": "./src/assets/img/footer-logo-1.png",
                        "nav_1": "HOME",
                        "nav_2": "COURSES",
                        "nav_3": "INSTRUCTORS",
                        "nav_4": "EVENTS",
                        "nav_5": "PAGES",
                        "nav_6": "ELEMENTS",
                    },
                ]
            }
        }
    }
</script>

<template>
    <div v-for="info in infos">
        <InfoCard :AllTheInfos="info"></InfoCard>
    </div>
</template>