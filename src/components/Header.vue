<template>
    <header>
        <h1>Tasks Tracker</h1>
        <Button text="Add Task" />
    </header>
</template>

<script>
    import Button from"./Button"

    export default {
        name: "Header",
        components: {
            Button
        }
    }
</script>

<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
</style>