<template>
    <div class="wrap">
        <Header></Header>
        <main></main>
        <TabBar></TabBar>
    </div>
</template>

<script>
    import Header from 'components/layout/Header'
    import TabBar from 'components/layout/TabBar'    
    export default {
        components: {
            Header,
            TabBar
        }
    }
</script>
<style lang="stylus" scoped>
    .wrap 
        height 100%
        display flex
        flex-direction column
        main 
            display flex
            flex 1
</style>


