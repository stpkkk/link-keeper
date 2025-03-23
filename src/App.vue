<template>
	<the-header title="Links Keeper"></the-header>
	<stored-resources :resources="storedResources"></stored-resources>
</template>

<script>
import StoredResources from './components/stored-resources/StoredResources.vue'
import TheHeader from './components/layouts/TheHeader.vue'

export default {
	components: { StoredResources, TheHeader },
	data() {
		return {
			storedResources: [
				{
					id: 'official-guide',
					title: 'Official Guide',
					description: 'Official Vue.js documentation.',
					link: 'https://vuejs.org',
				},
				{
					id: 'google',
					title: 'Google',
					description: 'Learn to Google',
					link: 'https://google.com',
				},
			],
		}
	},
}
</script>

<style scoped></style>
