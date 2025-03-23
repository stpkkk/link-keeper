<template>
	<ul>
		<resource-item
			v-for="res in resources"
			:key="res.id"
			:title="res.title"
			:description="res.description"
			:link="res.link"
		></resource-item>
	</ul>
</template>

<script>
import ResourceItem from './ResourceItem.vue'

export default {
	props: ['resources'],
	components: { ResourceItem },
}
</script>

<style scoped>
ul {
	list-style: none;
	margin: auto;
	max-width: 40rem;
}
</style>
