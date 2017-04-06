<template>
    <div id="firstcomponent">
        <h1>I am title11</h1>
        <a> writed by {{ author }}</a>
    </div>
</template>
<script>
    export default {
        name: 'firstcomponent',
        data () {
            return {
                author: "windern"
            }
        }
    }
</script>
<style lang="scss">
</style>
