<template>
    <div>
        <h2>THis is from first component</h2>
        <h3>{{ props.message }}</h3>
        <button>trigger function from parent</button>
    </div>
</template>

<script setup>
const props = defineProps(['message'])

</script>

<style scoped>

</style>