<template>
    <header>
        <h1>Houses</h1>
        <Button text="+ Create New" color="red"/>
    </header>

</template>

<script>
import Button from './Button'


export default {
    name: 'Header',
    props: {
        title: String,

    },
    components: {
        Button,
    }
}
</script>

<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: right;
        margin-bottom: 20px ;
        }
</style>