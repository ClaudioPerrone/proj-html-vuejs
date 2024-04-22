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
    <div class="container">
        
        <PageHeader></PageHeader>
    
        <main>
            <PageMain></PageMain>
        </main>
    
        <PageFooter></PageFooter>
        
    </div>

</template>

<style lang="scss">
    @use './style/generics';
</style>
