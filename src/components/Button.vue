<template>
    <a name="" id="" class="btn btn-primary" href="#" role="button">{{text}}</a>
</template>

<script>
    export default {
        name: "Button",
        props: {
            text: String
        }
    }
</script>

<style scoped>
    .btn {
        margin: 12px;
        background-color: red;
        border:0
    }
</style>