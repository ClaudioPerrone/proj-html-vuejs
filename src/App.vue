<script>
    import PageHeader from './components/PageHeader.vue';
    import PageMain from './components/PageMain.vue';
    import PageFooter from './components/PageFooter.vue';

    export default {

        components: {
            PageHeader,
            PageMain,
            PageFooter
        }
    }

</script>

<template>
        
        <PageHeader></PageHeader>
    
        <main>
            <PageMain></PageMain>
        </main>
    
        <PageFooter></PageFooter>

</template>

<style lang="scss">
    @use './style/generics';
</style>
