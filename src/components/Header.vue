<template>
    <header>
        <h1>{{ title }}</h1>
        <Button text="Add task" color="green"/>
        <!-- <DeleteButton text = "Delete task" /> -->
    </header>
</template>

<script>
import Button from './Button'
// import DeleteButton from './DeleteButton'

 export default {
    name: "Header",
    props: ['title'],
    components: {
        Button
    },
 }
</script>

<style scoped>
    header{
        display: flex;
        justify-content: center;
        align-items: center;
        margin-bottom: 20px;
        gap: 50px;
    }
</style>