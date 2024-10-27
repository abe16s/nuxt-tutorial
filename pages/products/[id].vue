<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minus ullam enim neque atque maiores vel beatae animi vitae consequuntur. Nulla aliquid optio repellendus modi est odio iste vero, quibusdam minus?</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    definePageMeta({
        layout: "products"
    })
</script>

<style scoped>

</style>