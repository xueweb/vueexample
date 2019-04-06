<template>
    <div id="app">
        <inputvue/>
        <checkbox/>

    </div>
</template>

<script type="text/ecmascript-6">
    import inputvue from './components/input'
    import checkbox from './components/checkbox'

    export default {
        name: 'app',
        components: {
            inputvue,
            checkbox
        }
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin: 20px;

    }
</style>
