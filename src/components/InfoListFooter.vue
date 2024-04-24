<script>
    import InfoCardFooter from './InfoCardFooter.vue';

    export default {
        name: "InfoListFooter",

        components: {
            InfoCardFooter
        },

        data() {
            return {
                infosFooter: [
                    {   /* HEADER */
                        "img_logo": "./src/assets/img/footer-logo-1.png",
                        "img_earth": "./src/assets/img/footer-img-1.png",
                    },
                ]
            }
        }
    }
</script>

<template>
    <div v-for="info in infosFooter">
        <InfoCardFooter :AllTheInfosFooter="info"></InfoCardFooter>
    </div>
</template>