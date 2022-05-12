<template>
    <header>
        <h1>Tastk Tracker</h1>
        <Button text="Add Task"/>
    </header>
</template>
<script>
import Button from "./Button.vue"
export default {
    name:"Header",
    props: {
        title:String,
        showAddTask:Boolean,
    },
    components: {
        Button
    }
}
</script>
<style scoped>
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
</style>