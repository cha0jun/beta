<script setup lang="ts">
const props = defineProps({
    title: {type: String, required: true},
    content: {type: String, required: true}
})
</script>

<template>
    <h1>{{ props.title }}</h1>
    <p>{{ props.content }}</p>
</template>