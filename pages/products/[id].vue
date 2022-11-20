<template>
<p>Product details for {{ id }}</p>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid atque consequatur deleniti deserunt doloribus ea earum exercitationem, expedita illo, impedit laborum nihil provident rerum sed tempora? Debitis eveniet ipsa molestias!</p>
</template>

<script setup>
const { id } = useRoute().params

definePageMeta({
  layout: 'products'
})
</script>

<style lang="scss" scoped>

</style>
