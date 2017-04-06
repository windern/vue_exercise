<template>
    <div id="secondcomponent">
        <h1>I am another page</h1>
        <a> written by {{ author }} </a>
        <p> 感谢 <a href="https://github.com/windern">windern</a>大神的技术指导</p>
    </div>
</template>
<script>
    export default {
        name : 'secondcomponent',
        data () {
            return {
                author:'windern',
                articles:[]
            }
        }
    }
</script>
<style lang="scss">
</style>
