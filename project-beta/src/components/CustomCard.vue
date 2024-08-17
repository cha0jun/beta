<script setup lang="ts">

const props = defineProps({
    title: {String, required: true},
    icon: {String, required: false}
})
</script>

<template>

<div class="border-radius-l padding-card display-flex-col bg-white color-black ">
<img >
    <div>
        <h6>{{ props.title }}</h6>
        <img src="./public/arrow.svg"/>
    </div>
</div>
</template>

<style scoped>
.border-radius-l {
    border-radius: 8px;
}
.padding-card {
padding: .375rem;
}

.display-flex-col {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
}

.bg-white {
    background-color: white;
}

.color-black {
    color: black;
}

</style>