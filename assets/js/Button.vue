<template>
    <button>Hello</button>
</template>
<script>
    export default {
        name: 'MyButton',
        data() {
            return {
                checked: false,
                title: 'Check me'
            }
        },
        methods: {
            check() {
                this.checked = !this.checked;
            }
        }
    }
</script>