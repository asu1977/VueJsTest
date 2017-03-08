<template>
    <div class="test">
        <span v-html="title"></span>
        <p>{{user.firstName}}</p>
        <p v-text="user.firstName"></p>
    </div>
</template>

<script>
    export default {
        name: 'test',
        data() {
            return {
                title: '<h1>Hello World</h1>',
                user: {
                    firstName: 'John',
                    lastName: 'Doe'
                }
            }
        }
    }
</script>

<style scoped>

</style>