<template>
    <div>
        <h1>Hello World</h1>
        <div id="msg">
            <span class="welcomeMsg">{{message}}</span>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'MyPage',
        data() {
            return {
                message: 'Welcome to the Vue world.'
            }
        }
    }
</script>

<style scoped>
</style>
