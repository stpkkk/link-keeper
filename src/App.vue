<template>
	<the-header title="Links Keeper"></the-header>
	<the-resources></the-resources>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue'
import TheResources from './components/stored-resources/TheResources.vue'

export default {
	components: { TheHeader, TheResources },
}
</script>

<style scoped></style>
