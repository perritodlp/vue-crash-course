<template>
    <div>
        <div v-bind:key="todo.id" v-for="todo in todos">
            <h3>{{todo.title}}</h3>
        </div>

    </div>
</template>

<script>
export default {
    name: "Todos", // Component name
    props: ["todos"] // 
}
</script>

<style scoped>

</style>